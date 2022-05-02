# Bertha3

Bertha3 is a design of a split-flap display.

## Parts

Parts designed in Solidworks, and printed using the Ender3

## Parts used

[Stepper motor](https://www.adafruit.com/product/858)

## Code structure

The split flap is made up of a 2D array of split flaps called ```Bits```. The ```BitArray``` class controls all of the bits from 
one place. This is where you would print anything to the screen, or do any animations.
Create a new ```BitArray``` object, and call the functions inside to change what is displayed on the screen.

```display_layered_strings()``` is the highest level function for printing to the screen, printing an array of strings in any formatting you would like (see the docstring for more info)

Many different functions have been created to make writing to the screen as easy as possible.