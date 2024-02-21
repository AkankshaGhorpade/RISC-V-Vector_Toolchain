# RISC-V-Vector_Toolchain

To build a Cross Compilation toolchain from scratch for RISC-V Vector extension.

HOST Architecture: x86

TARGET Architecture: RISC-V

The steps involved in building are as follows:

- **Configure the build environment:** This involves setting up your host machine and creating the directories that will hold the cross-compilation toolchain and target image.

- **Create the target image's filesystem hierarchy:** This involves creating the basic directory structure for your target image, including directories for things like /bin, /etc, and /usr.

- **Build the cross compiler:** This is a compiler that can be used to compile code for a different architecture than the one you are running on. You will need a cross compiler to build the kernel and other software for your target image.

- **Build the C library:** The C library is a collection of essential functions that are used by many programs. You will need to build a C library for your target image before you can build other software.

- **Build the target image:** This involves compiling the kernel and other software for your target image, and then packaging it all up into a bootable image.

- **Install the target image on your target machine:** This can be done on a physical machine or a virtual machine.
