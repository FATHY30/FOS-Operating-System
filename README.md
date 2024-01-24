# FOS-Operating-System

## Configuration

To set up your project, follow these steps after download and extract `fos_cygwin.rar` and open it by vs code:

1. Place `fos_cygwin` directly in `C:/`.
2. Click on `RunVSCode.bat`.
3. Press Ctrl+Shift+P, select "Run Tasks" and choose either "Run FOS" or "Run FOS-qemu".

## Running FOS on Linux

To run FOS on Linux, download `fos_cygwin.rar` and navigate to the `fos_linux` directory for configuration options.

## Features

- Implemented command prompt functions for user interaction.
- Developed system calls: OS procedures that execute privileged instructions.
- Built a dynamic memory allocator with first-fit and best-fit allocation strategies.
- Created a kernel heap with initialization, allocation, deallocation, and address translation functions.
- Implemented a fault handler to manage invalid memory accesses, including page fault handling and environment workspace list management.
- Designed a user heap with initialization, allocation, and deallocation functions.
- Enhanced the fault handler with FIFO and approximate LRU replacement algorithms.
- Developed a BSD scheduler with process priority control, initialization, scheduling, and clock interrupt handling functions.
