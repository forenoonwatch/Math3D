# Math3D

## Description

A simple 3D math library created for personal use in rendering and physics engine projects.

## Background

Written in April of 2016 to work in conjunction with my game engines, and as one of my first attempts at making a publishable library.

## Building

Using GCC and GNU Make, run `make` in the library's directory. Run `make -f Makefile-Tester` in order to build the test code

## Usage

Link the library file `libmath3d.a` with your project and make `Math3D/include` available as an include path.

Add the following to the top of your source file to be able to use the classes.
```cpp
#include <math3d/math3d.hpp>
```

## Features

- Vector2
- Vector3
- Vector4
- Quaternion
- Matrix4x4

## Future work

- Add generic support for more underlying numerical type than just float
- Add/improve support for SIMD optimization
