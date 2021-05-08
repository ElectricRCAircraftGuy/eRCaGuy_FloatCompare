# eRCaGuy_FloatCompare
A C and C++ floating point comparison library with auto-scaling epsilon.

By Gabriel Staples  
www.ElectricRCAircraftGuy.com  
www.GabrielStaples.com  


# Status

Work-in-progress (WIP)--NOT functional yet.


# Description

A floating point comparison library which properly scales `epsilon` so that it never falls out as floating point error, even for really large or really small floating point values being compared. 

This library allows you to easily and _correctly_ do "equals" (`==`), "not equals" (`!=`), "greater than" (`>`), "greater than or equal to" (`>=`), "less than" (`<`), and "less than or equal to" (`<=`) comparisons between two floating point numbers. 

See also: 
1. [my work as a starting point] https://github.com/ElectricRCAircraftGuy/eRCaGuy_hello_world/blob/master/c/utilities.h#L44
1. [my ans] https://stackoverflow.com/questions/17333/what-is-the-most-effective-way-for-float-and-double-comparison/65015333#65015333


# Folders

1. **c**: a C version of this library
    1. also compiles fine in C++, and works on Arduino
1. **cpp11**: a C++11 version of this library
    1. also works on Arduino
1. **cpp17**: a C++17 version of this library???--is this even necessary? Am I using any important C++17 features?
    1. Last I checked, `Serial.println(__cplusplus);` (see [here](https://gcc.gnu.org/onlinedocs/cpp/Standard-Predefined-Macros.html) for info on gcc/clang's `__cplusplus` macro) on an ATmega328-based Arduino Pro Mini prints `201103`, which means that Arduino compiler is still C++2011, and therefore this C++17 code will _not_ work on that Arduino at least.


# Example Usage

Examples are contained inside an `examples` folder in each folder above. Refer to those. 

Here is the basic usage:

1. C library:

    ```c
    todo
    ```
1. C++11 library:

    ```cpp
    todo
    ```
1. C++17 library:

    ```cpp
    todo
    ```

# Building/using this code

TODO


# TODO

1. Be sure to write Google Test tests for everything too, and explain how to build/compile it here in the README! 
1. Also write a few basic Arduino tests in the Arduino C++11 example.
1. Link to/from my hello_world repo.
1. Add MIT license.
1. Add fancy collapsible/expandable ToC
