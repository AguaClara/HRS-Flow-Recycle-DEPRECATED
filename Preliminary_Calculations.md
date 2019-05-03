```python
import aguaclara
from aguaclara.research.stock_qc import Variable_C_Stock
from aguaclara.core.units import unit_registry as u
from aguaclara.core import utility as ut

# givens
c_lab_stock = 70.28*u.g/u.L # lab stock concentration
V_stock = 5*u.L # coagulant stock volume
v_up = 1*u.mm/u.s # desired upflow velocity
area_sed = (14*u.mm*340*u.mm).to(u.m**2) # cross sectional area of the sed tank

# calculating required system flow rate
Q_sys_calc = (area_sed * v_up).to(u.mL/u.s)

myReactor = Variable_C_Stock(Q_sys=Q_sys_calc, C_sys=1.4*u.mg/u.L, Q_stock = .01*u.mL/u.s)
c_stock = myReactor.C_stock()

lab_stock_volume = (c_stock * V_stock / c_lab_stock).to(u.mL)

print("The required volume of lab stock coagulant is", ut.round_sf(lab_stock_volume, 4))


# other calcs for Kanha
A_tube_settler = 490.8*u.mm**2 # cross sectional area tube settler
Q_tube_settler = (A_tube_settler*v_up).to(u.mL/u.s) # flow rate required per tube settler
```
