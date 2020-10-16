# Loops and conditions exercises

## Capital letters

File name: `capital_letters.py`

Write a program that prompts user to enter some text and prints the number of CAPITAL LETTERS on the screen. E.g:

    Enter text: Data Science is SUPER!
    7

## Password

File name: `password.py`

Write a program that prompts the user to enter a password, and then prints exactly one of the following messages: ‘_The password is secure._’ or ‘_The password is insecure!_’. A secure password must meet the following conditions:

* have at least one lowercase letter,
* have at least one capital letter,
* have at least one digit.

Examples:

    Enter the password: Katar7yna
    The password is secure.
    Enter the password: catastrophe01
    The password is insecure!

## Right triangle

File name: `triangle1.py`

You should write a program that will ask the user for an integer (the size of the triangle) and then print a right-angled triangle (with a right angle in the lower left corner) composed of `*` characters of the given size. E.g:

    Enter the size of the triangle: 4
    *
    **
    ***
    ****

## Isosceles triangle

File name: `triangle2.py`

Write a program that will ask the user for an integer (the size of the triangle) and then print an isosceles triangle composed of `*` characters of the given size. E.g:

    Enter the size of the triangle: 3
      *
     ***
    *****

Tip: You can print the correct number of spaces at the beginning of each line to align characters properly.

## Approximations of _π_

File name: `pi_approximations.py`

Write a program that calculates 10 000 consecutive approximations of _π_ according to the Wallis formula:

           ∞     4 n²
    π = 2  ∏   ————————
          n=1  4 n² - 1

The above formula is exact for the infinite product. In successive approximations, the value of _n_ varies from 1 to some number _N_. Successive approximations are the calculated values for the increasing upper limit _N_.

Every hundredth approximation (for _N_ ∈ 100, 200, 300...) should be displayed on the screen:

    3.133787490628162
    3.137677900950937
    3.138980103882128
    3.1396322219293986
    ...
    3.14151168992377
    3.1415125160309456
    3.1415133254501364
    3.1415141186819566
