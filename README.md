<<<<<<< HEAD
# Pintos Project
Welcome to the Pintos Project! This project is an educational operating system framework designed for teaching OS concepts. It provides a simple, well-documented environment for students to implement and experiment with various OS components.

## Table of Contents
-   Project Overview
-   Directory Structure
-   Getting Started
    -   Prerequisites
    -   Building the Project
-   Running the OS
-   Testing
-   Contributing
-   License

## Project Overview
Pintos is a simple instructional operating system framework for the 80x86 architecture. It is primarily used in academic settings to help students understand and implement fundamental OS concepts such as threads, user programs, virtual memory, and file systems.

## Directory Structure
Here's an overview of the main directories and their purposes within the Pintos project:

src/
├── examples/
│   ├── lib/
│   │   └── user/
│   ├── Makefile
│   └── .gitignore
├── filesys/
│   ├── Makefile
│   └── .gitignore
├── threads/
│   ├── Makefile
│   └── .gitignore
├── userprog/
│   ├── Makefile
│   ├── Make.vars
│   ├── syscall.c
│   ├── process.c
│   └── .gitignore
├── vm/
│   ├── Makefile
│   ├── Make.vars
│   └── .gitignore
├── utils/
│   ├── Makefile
│   └── .gitignore
├── tests/
│   ├── userprog/
│   │   ├── Make.tests
│   │   └── lib/
│   └── filesys/
│       ├── base/
│       │   ├── Make.tests
│       │   └── .gitignore
│       └── extended/
│           ├── Make.tests
│           └── sample.txt
├── Makefile
├── Makefile.build
├── Make.config
└── LICENSE

======= 
# Pintos
Labs for undergraduate OS class (600.318) at Johns Hopkins. [Pintos](http://pintos-os.org) 
is a teaching operating system for x86, challenging but not overwhelming, small
but realistic enough to understand OS in depth (it can run x86 machine and simulators 
including QEMU, Bochs and VMWare Player!). The main source code, documentation and assignments 
are developed by Ben Pfaff and others from Stanford (refer to its [LICENSE](src/LICENSE)).

The course instructor ([Ryan Huang](mailto:huang@cs.jhu.edu)) made some changes to the original
Pintos labs to tailor for his class. The upstream for this branch comes from 
[https://github.com/ryanphuang/PintosM](https://github.com/ryanphuang/PintosM). For students in the class, please
download the release version for this branch at https://github.com/jhu-cs318/pintos.git
>>>>>>> 601f1a7 (Initial commit)
