# Interactive Tutorial 1: Markdown

## Working with Markdown

Press `Ctrl + Shift + M` to open a formatted preview on the right.

## Basic Text

Write two sentences about yourself, each in a different paragraph.

I am from Buffalo, NY.

I am majoring in Earth and Atmospheric Sciences at Cornell University, and I am a member of the High
Rate Sedimentation - Plate Settlers subteam.

## Headers

Make a 3rd level header with your name:

# Leena Sen

## Emphasis

Write 4 of your favorite words using each type of emphasis:

*flocculation*
**sedimentation**
***coagulation***
~~filtration~~


## Lists

Make an ordered list of 3 things you hope to achieve this semester, and elaborate on them with sub items. Then, make an unordered list of 3 classes that you're taking this semester:

1. Clean the sedimentation tank in the grad elaborate
  i. We need to do research regarding how the sedimentation tank in the graduate students' lab functions in order to clean the tank effectively and without damaging any of the components. We also need to replace the tubes (flocculator PVC flex tubing).
2. Install a new ProCoDa box and incorporate turbidimeters, as well as connect the desktop computer to our setup
  ii. We need to move turbidimeters from the sedimentation tank in the lab to the grad lab and make sure it functions with our setup.
3. Develop a system with plate settlers in the sedimentation tank
  iii. Our hopes are  to incorporate maybe 7-10 plates within the sedimentation tank and have a more reliable flocculation process.

- Structural Geology
- Field Geophysics
- Volcanology

## Links

Write a sentence describing your major, and insert a link to your major's department website:

[I am majoring in Earth and Atmospheric Sciences and concentrating in Geological or Planetary Sciences. This department holds courses that range from environmental geosciences to courses in mathematical geosciences. The major is in CALS, College of Engineering, and the College of Arts and Sciences.] (https://www.eas.cornell.edu/eas)

## Images

Insert the Cornell seal image with:
  1. A relative file path(`/images/Cornell_University_seal.png`)
  2. A URL (https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.svg.png)

![https://upload.wikimedia.org/wikipedia/commons/4/47/Cornell_University_seal.svg]('images/Cornell_University_seal.png')

## Code Formatting

Put the name of this file in an in-line (single backtick) code format.

`/images/Cornell_University_seal.png`

Put the following text in a Python-formatted code block:

```
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```
```Python
def foo():
  print("Particles of a feather...")
  print ("...floc together!")
```

## Tables

Create a table listing your 3 favorite animals, books, and places on campus. Use a different alignment for each column.

|Animals|Books|Places|
|---|:---:|---:|
|Dogs|Jane Eyre|Snee Hall|
|Sloths|The Alchemist|WSH|
|Hippos|Welcome to Nightvale|The Johnson Museum|


## Blockquotes

Write your favorite quote. It must be attributed to Albert Einstein.
> Imagination is more important than knowledge - Albert Einstein

## Horizontal Rules

Add a horizontal rule:
---

## LaTeX Formatting

Copy the equation towards the end of the [Markdown tutorial](https://github.com/AguaClara/aguaclara_tutorial/wiki/Markdown#latex-formatting) and paste it here:

$$ a^2 + b^2 = c^2 $$
