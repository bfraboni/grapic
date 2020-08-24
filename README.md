# GrAPiC 

http://licence-info.univ-lyon1.fr/grapic


## Introduction

GrAPiC is a small, easy-to-use framework to add graphical functionalities to your C/C++ code. 
Its main goal is to provide easy graphical functions to be used in introduction courses of algorithm and programming in C/C++. 
It is based on SDL2 but to use it you need to know only few very simples functions. 
The Grapic archive comes with the needed SDL part, you do not have to install SDL. Just unzip and enjoy ! 



## Building

- Clone this repository into a local one
- Initialize git submodules using `git submodule update --init --recursive`
- Create a build directory
- From the build directory:

    - Run `cmake ..`. To specify a build type (Debug or Release), append to the command `-DCMAKE_BUILD_TYPE=<build_type>`.
    By default, a Code::Blocks workspace is generated in the build directory. To change it, specify your generator (ie. Visual Studio) using the `-G` option.
    [More info here](https://cmake.org/cmake/help/latest/manual/cmake-generators.7.html)
    
    - Run `make <your_executable_name>` to build your executable. `make help` is available to list all targets
    

