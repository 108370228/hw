# Specification
The goal of this homework is to write a program that can receive three arguments: object type, width (radius), length, and calculate its area. Your program needs to support 3 shape types: circle, triangle, rectangle.

## Input
Your program needs to accept 2 or 3 arguments. The 1st argument is object type, the 2nd is width (or radius for circle), the 3rd is length. The 3rd argument is not necessary if the input object is "circle".

Usage:
```
a.out [type] [w] [l]
```

Examples:
```
a.out triangle 3 4
a.out circle 5
```


## Output
Print the area size of input shape directly. Example:
```
> a.out triangle 3 4
> 6
```
```
> a.out circle 1
> 3.1415926
```

# Requirements

We have provided a template. Create a “shapes.h” file and define 4 classes with area() function. The 4 class you need to write are:
Base class: Shape
Derived class: Circle, Triangle, Rectangle

In the template we already provide class Shape and Rectangle. You need to complete Circle and Triangle.

## Compile Your Code

We include a Makefile. Just type “make” in your command-line window.


## Test your code
Run the commands on Linux
```
kt@ntut:~/oop/hw1$ make
kt@ntut:~/oop/hw1$ ./a.out rectangle 2 4.5
kt@ntut:~/oop/hw1$ 9
```
