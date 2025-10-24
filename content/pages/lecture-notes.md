---
content_type: page
description: This section provides the schedule of lecture topics for the course,
  lecture notes, and supporting files, and links to related resources.
draft: false
learning_resource_types:
- Lecture Notes
ocw_type: CourseSection
title: Lecture Notes
uid: 5816426e-e626-2b91-ed6f-aec27f48aba8
---
This course makes use of Athena, MIT's UNIX-based computing environment. OCW does not provide access to this environment.

{{< tableopen >}}{{< theadopen >}}{{< tropen >}}{{< thopen >}}
LEC #
{{< thclose >}}{{< thopen >}}
TOPICS
{{< thclose >}}{{< thopen >}}
LECTURE NOTES
{{< thclose >}}{{< thopen >}}
NOTES, SUPPORTING FILES, AND LINKS
{{< thclose >}}{{< trclose >}}{{< theadclose >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen >}}
1–2
{{< tdclose >}}{{< tdopen >}}
Introduction: Problem formulation, algorithm development, algorithm implementation, and algorithm verification. Structure and documentation
{{< tdclose >}}{{< tdopen >}}

Lec #1 ({{% resource_link "fa9e8a67-8960-5170-a380-0ad057c1a4e9" "PDF" %}})

Lec #2 ({{% resource_link "1f0edda9-a651-dfca-4ec1-0f8c04503b4c" "PDF" %}})

{{< tdclose >}}{{< tdopen >}}

### Lec #1

Class introduction; overview of languages; program development.

### Lec #2

Discussion of aspects of computers and their operation. An example is given of program development for a simple case of computing the area of a figure.

Links that are in the notes for this lecture:

[What is big-endian?](http://www.webopedia.com/TERM/B/big_endian.html)

[Green's Theorem](http://mathworld.wolfram.com/GreensTheorem.html)

[The IEEE standard for floating point arithmetic](http://www.dsc.ufcg.edu.br/~cnum/modulos/Modulo2/IEEE754_2008.pdf)

Minor links for those interested:

[Velocity Engine](https://velocity.apache.org/engine/1.7/)

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
3–7
{{< tdclose >}}{{< tdopen >}}
FORTRAN: "Formula Translation". Program creation, compilation and linking, variables and parameters, flow control, subroutines and functions. Structure and documentation. Use of libraries, internal and external communication, and interaction with other languages. FORTRAN: implementation issues: compilation errors, segmentation violations, Not-a-Number (NaN), Input/Output (IOSTAT) errors, Runtime errors. Transportable code, standard extensions. FORTRAN 90 differences and similarities to FORTRAN 77
{{< tdclose >}}{{< tdopen >}}

Lec #3 ({{% resource_link "f0e0c82a-be71-570a-17ce-43aa514a63db" "PDF" %}})

Lec #4 ({{% resource_link "41323518-f446-9148-18e9-c79b40fad1f6" "PDF" %}})

Lec #5 ({{% resource_link "a40a2364-4f72-5f34-95b5-878ad196e4f5" "PDF" %}})

Lec #6 ({{% resource_link "5ea7de2d-b20c-86df-928b-8250fe4f83dc" "PDF" %}})

Lec #7 ({{% resource_link "0b6b7007-996e-1952-0a44-e93a418b1e68" "PDF" %}})

{{< tdclose >}}{{< tdopen >}}

### Lec #3

Started FORTRAN (Formula Translation). Went through the basic elements that make up this language. An on-line version of a FORTRAN 77 manual can be found [here](http://physik.uibk.ac.at/hephy/praktikum/fortran_manual.pdf). In reading these notes, you should think about operations you want to do and what command or commands do you use to do that. The list on FORTRAN intrinsic functions can be found [here](https://gcc.gnu.org/onlinedocs/gcc-3.4.6/g77/Table-of-Intrinsic-Functions.html).

Other links to look at:

[The FORTRAN Programming Language](https://ourcodingclub.github.io/tutorials/fortran-intro/)

[Wikipedia Definition of FORTRAN](http://en.wikipedia.org/wiki/Fortran)

### Lec #4

Continued with showing the elements of the FORTRAN and more detail on the typically encountered features of the language. Topics covered: subroutines and functions; intrinsic functions; constants and variables; input output with open/close, read/write, formats; character strings.

The links in this lecture were to FORTRAN and intrinsic functions, which are given above. The programs poly\_area.f ({{% resource_link "3c22a7c4-6b70-2279-8f1c-77357bb498fd" "F" %}}) and vars.f ({{% resource_link "667eacfc-4c16-f882-0e50-917d90f9755b" "F" %}}) are also used. (To download programs, right click on link and "save link target as". With one-button mouse use \<ctrl>\<click> on link). On Athena to use these programs:

ssh –X linerva.mit.edu     
%add fortran     
%f77 poly\_area.f –o poly\_area     
% poly\_area

To use the f90 compiler on Athena, use add sunsoft.

Other sources of information:

[O'Reilly series of books on programming](https://www.oreilly.com/search/?q=programming&type=*&rows=10) 

[FORTRAN Resources](https://fortran-lang.org/learn/) - useful link with lots of information on FORTRAN in its various forms

### Lec #5

Continued with FORTRAN. Character strings, control statements if and do; other commands such as include, common, parameter. More programs will be developed in class including simple output and computing root-mean-square scatter of randomly generated numbers.

### Lec #6

Finish up FORTRAN. Compile, linking and runtime errors and miscellaneous topics. Practice with using the language.

### Lec #7

Examines the changes that were made in FORTRAN90 with the introductions on more modern concepts in programming languages.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
8–11
{{< tdclose >}}{{< tdopen >}}

C for scientific uses. Representation of data through arrays, pointers, and data structures. Function calls, argument passing and scoping rules, IO, profiling, system calls, and signals

C++ objects. Encapsulation and inheritance, polymorphic operators

{{< tdclose >}}{{< tdopen >}}

Lec #8 ({{% resource_link "d2d19d35-a493-2953-566b-cd406d6347f0" "PDF" %}})

Lec #9 ({{% resource_link "11c4e674-0ce4-4f97-13d7-40f70fe7f5f3" "PDF" %}})

Lec #10 ({{% resource_link "ab71f485-954a-946a-9183-ac6918df4b9e" "PDF" %}})

Lec #11 ({{% resource_link "86cfd8e9-18ea-3b34-14b0-5336b3462f2f" "PDF" %}})

{{< tdclose >}}{{< tdopen >}}

### Lec #8

Start of C-language programming. History, variables and executable statements.

Basic C Lecture

Basic C: C and FORTRAN 77 Syntax

Basic C: New Features

Lec #08 Exercises.

### Lec #9

Continuation of C. Covering Examined C-pointer; file Input/Output and the routines for formatted reads and write; compiling C routines; the C preprocessor cpp; structures in C; memory management.

Lec09\_pnt.c ({{% resource_link "daa898d1-3641-45ba-152b-2af9e2d226de" "C" %}}) is demonstration of pointers

### Lec #10

Finish structures and memory management in C. Start of C++. Inheritance and overloading in C++.

C and C++ routines used in class launch.c ({{% resource_link "4aea5a9e-83cf-e30e-030a-883fd1107ba6" "C" %}})

Ball.h ({{% resource_link "cc64c27f-893c-444c-5bde-595a347a63b6" "H" %}}) and launch.cc ({{% resource_link "6c826d7e-c469-90da-58bd-92eac3c3cc5c" "CC" %}})

C++ zip files:

ustring.zip ({{% resource_link "0708c942-c7e9-4356-63f5-287995f91d4d" "ZIP" %}}) (The ZIP file contains: 2 .h files, 1 .cc file, and 1 .txt file.)     
launch.zip ({{% resource_link "441b39e3-f9f2-b583-a110-d862597c3863" "ZIP" %}}) (The ZIP file contains: 1 .cc file, 1 .h file, and 1 .txt file.)     
coord.zip ({{% resource_link "a89199d9-8823-8638-d9ba-99927ffae0bf" "ZIP" %}}) (The ZIP file contains: 1 .cc file, 1 .h file, and 1 .txt file.)

### Lec #11

Finish up of C++ looking at classes, inheritance and overloading. We will look more carefully at the code linked in Lec #10. Homework number 3 has been set.

Example pieces of code for C and comparison to FORTRAN:

C basics ({{% resource_link "c26ed81c-4bc2-36f3-8646-870114b6d864" "PDF" %}}), area.c ({{% resource_link "c78699e8-6b16-5f4c-bf1e-d3222d6e19bc" "C" %}}), hello.c ({{% resource_link "b7745047-8d54-b510-5c92-3adb9cb542ea" "C" %}})     
C FORTRAN compare ({{% resource_link "07558a03-d25d-50ff-1d57-a6def9a9dc48" "PDF" %}})     
C pointers ({{% resource_link "05f8ac66-a0b8-53aa-6ace-1080fa72db8c" "PDF" %}})

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
12–13
{{< tdclose >}}{{< tdopen >}}

Mathematica. What it is and what it can do; structure of Mathematica; symbols, exact numbers, and machine numbers; lists, vectors, and matrices

Working with Mathematica: numerical calculations, symbolic calculations, and graphics. Importing and exporting information

{{< tdclose >}}{{< tdopen >}}

Lec #12 ({{% resource_link "1db38343-5b1f-3a37-7429-99088a836f7d" "PDF" %}})

Lec #13 ({{% resource_link "7d5277ce-de21-11d5-8cb8-94b1803f3fff" "PDF" %}})

{{< tdclose >}}{{< tdopen >}}

### Lec #12

Start of Mathematica. These lectures are accompanied by a Mathematica Notebook that shows example of concepts presented in the notes.

Lec 12 NB ({{% resource_link "3c14d2a4-2174-0a89-389d-70a8fb044a10" "NB" %}})

Introductory screen casts from Wolfram:

[Introduction](http://url.wolfram.com/oHLP0k/)

[Making Models](https://www.wolfram.com/broadcast/video.php?c=135&v=514)

[Use of the demonstrations site](https://demonstrations.wolfram.com/about.html)

[Featured Demonstrations](http://demonstrations.wolfram.com/index.html)

### Lec #13

Continuation of Mathematica. These lectures are accompanied by a Mathematica notebook that shows example of concepts presented in the notes.

Lec 13 NB ({{% resource_link "18cf33a9-d60c-8078-8348-5417aa422bfa" "NB" %}})

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
14–17
{{< tdclose >}}{{< tdopen >}}

MATLAB®. "Matrix Laboratory". MATLAB syntax, workspace, variables. Script M-files, IO, control flow, debugging, and profiling tools. Object-oriented programming

MATLAB applications, polynomials, interpolation, integration, differentiation, ODE. Graphics, 2-D, 3-D, Graphical User Interface (GUI)

{{< tdclose >}}{{< tdopen >}}

Lec #14 ({{% resource_link "d274a468-ea21-6c74-4412-91439a7ae019" "PDF" %}})

Lec #15 ({{% resource_link "0d4e1bce-e5bb-fd36-fa5f-e0711a6f3c06" "PDF" %}})

Lec #16 ({{% resource_link "4714963e-4e9e-38a8-2b87-9ce29f9f6381" "PDF" %}})

Lec #17 ({{% resource_link "44478622-e6e7-57e2-de5b-ecce3e525989" "PDF" %}})

{{< tdclose >}}{{< tdopen >}}

### Lec #14

MATLAB: introductory lecture on MATLAB introducing system, variable types, control and functions. The following MATLAB M-files are used in the lecture:

Lec01\_01.m ({{% resource_link "335a4fe5-e73b-3751-fd0d-e060b850ed2d" "M" %}})     
Lec01\_02.m ({{% resource_link "1e799675-7de6-6d6c-d945-c59ab7f934ae" "M" %}})

### Lec #15

MATLAB: path command, variables, file IO and dialog boxes. The following M-files are used:

Lec02\_01\_file.m ({{% resource_link "1101fa9b-327b-5bb4-7f42-1ccd933b40c5" "M" %}})     
Lec02\_02\_db.m ({{% resource_link "1608366b-2b0a-d288-e4ca-48af7ede3120" "M" %}})     
Lec03\_01\_file.m ({{% resource_link "d50cb2cb-6d29-c293-a6b8-6a6b109a4115" "M" %}})

The data for these M-files can be found in MatData. A tar file with the data is TSeries.tar ({{% resource_link "cd668549-0d67-1d7c-c220-725bbc297e7c" "TAR" %}}) (The TAR file contains: 10 .dat1 files, 10 .dat2 files, and 10 .dat3 files.)

### Lec #16

MATLAB: graphics handles and animation of figures. The following M-files are used in class:

Lec03\_movie.m ({{% resource_link "74301e45-7cd2-9a17-4e0d-0a5626c36176" "M" %}})     
MATLAB/per\_func.m ({{% resource_link "063307ed-7709-10fc-9803-8569307ebccd" "M" %}})

### Lec #17

MATLAB: final class on GUI construction and use. The following M-files are used (along with the data from MatData: a tar file with the data is TSeries.tar ({{% resource_link "cd668549-0d67-1d7c-c220-725bbc297e7c" "TAR" %}}) (The TAR file contains: 10 .dat1 files, 10 .dat2 files, and 10 .dat3 files.)

Basic GUI layout:

GPSanal.m ({{% resource_link "389afab6-84de-8a20-847b-ccaa333e1dfe" "M" %}})     
gpsguio.m ({{% resource_link "501337ca-81fb-5c55-3424-4ce13e5be4f2" "M" %}})

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
18–19
{{< tdclose >}}{{< tdopen >}}
Python scripting language program
{{< tdclose >}}{{< tdopen >}}

Lec #18 ({{% resource_link "2894ec98-89a5-d368-214a-9333b654714e" "PDF" %}})

Lec #19 ({{% resource_link "f826ae44-8931-a059-34c1-0e02348127c2" "PDF" %}})

{{< tdclose >}}{{< tdopen >}}

### Lec #18

Python I: Python Language Basics

[Python Programming Language—Official Website](http://www.python.org/)     
[Python v2.7.3 documentation](http://docs.python.org/index.html)     
[The Python Tutorial](http://docs.python.org/tutorial/)

### Lec #19

Python II: Python Advanced Usage

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
20
{{< tdclose >}}{{< tdopen >}}
Advanced graphics in MATLAB, 3-D representation and exportable animations
{{< tdclose >}}{{< tdopen >}}
Lec #20 ({{% resource_link "a6178c92-4163-f6e3-8cd3-45871c14334b" "PDF" %}})
{{< tdclose >}}{{< tdopen >}}

### Lec #20

3-D graphics in MATLAB.

Examples are:

Lec20\_3D.m ({{% resource_link "c65c5abb-d184-3a2f-1e4e-9ecb1b2d21c7" "M" %}}) 

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
21
{{< tdclose >}}{{< tdopen >}}
Ordinary differential equation (ODE) solutions used MATLAB and Mathematica
{{< tdclose >}}{{< tdopen >}}
Lec #21 ({{% resource_link "c0aef797-00a1-0a5e-7982-1c93dd163d86" "PDF" %}})
{{< tdclose >}}{{< tdopen >}}

### Lec #21

Solution to differential equations in Mathematica and MATLAB.

Mathematic notebook: 12.010.Lec18\_NDsolve.nb ({{% resource_link "468a074f-6f34-5346-0eac-101cd5e1c5bf" "NB" %}})

MATLAB solutions are:

Lec21\_ODE.m ({{% resource_link "09d06a67-2a23-16fc-ec6a-c2ee6995adbb" "M" %}})   
Lec21\_animate.m ({{% resource_link "1a17c14e-b138-5d06-8e09-e57b530c2035" "M" %}})   
Lec21\_hit.m ({{% resource_link "9a0a17f2-c399-3fc0-9196-a1311197a246" "M" %}})   
Lec21\_bacc.m ({{% resource_link "f588a9e1-e036-832b-69a2-bc6a5fce1f78" "M" %}})

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
22–24
{{< tdclose >}}{{< tdopen >}}

Advanced Topics: Parallel computing with large memory and large numbers of CPUs

Advanced topics: Parallel MATLAB

Discussion of final projects

**Order of the presentations will be decided in the last class**

{{< tdclose >}}{{< tdopen >}}
 
{{< tdclose >}}{{< tdopen >}}

### Lec #22

Introduction of class project. Graphics formats and issues about vector and pixel based graphics.

[GMT graphics package](http://gmt.soest.hawaii.edu/) for mapping applications

### Lec #23

Class projects: graphics processor unit (GPU) processing. Statistics and random number generators. M-file randtest.m ({{% resource_link "867d8adf-9e58-cfce-3efc-a2dc008c0203" "M" %}}) is implementation of an LCG random number generator.

### Lec #24

Graphics: review of common graphics program. Graphics with spreadsheets, Kaleidagraph, Generic Mapping Tool (GMT). Numerical methods: introduction to numerical methods

Statistical analysis tools including generation random variables and correlated random numbers

The order of the class presentations will be decided in this class and posted after the class.

[Cuda Zone](http://www.nvidia.com/object/cuda_get.html)

[MATLAB Implementation](http://www.accelereyes.com/)

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
 
{{< tdclose >}}{{< tdopen >}}
Final Project Presentations
{{< tdclose >}}{{< tdopen >}}
 
{{< tdclose >}}{{< tdopen >}}
 
{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}