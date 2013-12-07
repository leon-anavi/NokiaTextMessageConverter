NokiaTextMessageConverter
=========================

C++ application which takes a string and converts it to the button push sequence on NOKIA 1100 phone keypad. For example: HELLO -> 44 33 555 555 666

Build Instructions
==================

        $ g++ main.cpp -o conv

Usage
=====

        $./conv "Hello World"
        44 33 555 555 666 0 9 666 777 555 3

