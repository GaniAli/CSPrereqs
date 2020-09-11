# CSPrereqs

A short list of topics that are good to know for a programmer.

## Math

### Analysis

At least complexity analysis (big O notation) requires it.

### Finite fields

While not really necessary, makes life easier when it comes to understanding certain algorithms.

### Linear algebra

Doing something with a lot of numbers.

### Probability

Probabilistic algorithms.

### A lot of other topics

For a lot of problems

## Low level

### Boolean arithmetics and logic circuits

Is math, but really just needed for understanding hardware.

### Basic circuits

Connecting a lightbulb to a power source.

### Transistors

A circuit element that has three terminals, where one terminal can act as a controller of current through the other pair of terminals.

Not really necessary to understand that transistors are not just boolean devices and have complicated I-V curves.

### Logic gates

How to make them from transistors (idealised)

### Digital circuits

Combine gates to achieve some functionality, like adding two numbers.
 
### Registers

Temporary storage of immediate results or parameters for instructions.

### CPU

How does an ALU work? 

What is computer clock?

How does a CPU execute instructions using data from registers?

How do we store or read data from RAM? 

How much downtime does a CPU have and what could we do with it (multithreading)? 

### GPU

What's all the hype about parallelism about? 

Why does shader coding suck?

How does it calculate so many pixel values so fast? Could we abuse it?

### RAM

What is flash? 

What is random access?

Why is it faster to use RAM than an SSD?

Why is RAM so slow and registers are not?

### Cache

Why does accessing same data multiple times gets faster?

Why does alternating between different data cause a slow-down?

What are cache missed?

### SSD

What is it used for? 

How is it addressed?

How does an OS store data on SSD or HDD?

What are filesystems, partitions?

How does dual booting work with regards to partitions?

### Heat

Do transistors like it more when it is cool?

How do we cool cpu?

What happens if we let CPU run at 90 degrees forever?

### Motherboard

What does it offer? 

What connectors are there?

What is a bus?

## High Level

### Automata 

Machine as a language parser, e.g., a vending machine.

### Executing a program

Loading instructions to RAM.

Using RAM for storage.

### Machine instructions (Assembly)

Simplistic set of instructions for reading/writing to memory, arithmetics, `goto`, `label`s, etc.

How to write a counter to 100 in assembly?

How does it transalte to machine instructions?

Machine instructions as hex numbers written in binary form.

### Binaries vs source code

How is assembly compiled into binaries.

How is C compiled into assembly.

How is JavaScript interpreted.

### Interrupts vs. Pooling

### OS as a task scheduler (multithreading)

### Linux filesystem

Root, home partitions. 

Swap file or partition. 

`/usr` folder.

Where do library headers go?

Where do binaries go?

### Ubuntu

Installing it, using live USB, partitioning schemes, dual booting windows.

### How to use terminal on Ubuntu

What are built-in instructions?

How to list files in a directory?

How to navigate directories?

How to move/copy/remove files/directories? 

How to pipe commands?

How to remove all images from a directory?

How to mass rename files?

What is sudo? What is a root user?

How to add user to sudoers group?

How to give a user ownership of a file/directory?

How to change file permissions?

How to edit file with vi(m) or nano?

What is `PATH`, how to edit `PATH` using `bash_profile`?

What is a tty? How to switch to a new tty?

What is regex? How to use grep?

What is inode? 

How to keep system up to date?

How to manage packages?

How to install a package from a third-party repository?

How to build a package from sources? What are makefiles?

How to view system logs?

How to compile C++?

### C++

### Algorithms
