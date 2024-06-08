# Hey! I'm Filing Here

Oscar Cooper Stern, UID:305919060

In this lab, I successfully implemented a 1 MiB filesystem using ext2 structures that initalizes 2 directories
a symlink and a regular file. It is able to be mounted and used as a filesystem.

## Building

Use 'make' to compile the c code into an executable.

## Running

Use './ ext2 - create' to create cs111 -base.img

From there using 'fsck.ext2 cs111 -base.img' ensures everything works properly
use mkdir 'directoryName' to create a directory you want the filesystem mounted to
'sudo mount -o loop cs111 -base.img 'directoryName'' mounts our file system the directory you created.


## Cleaning up

'sudo umount 'directoryName'' to unmount our filesystem
'rmdir 'directoryName'' to remove the directory the filesystem was stored in.
'make clean' to clean up any .o and exe files 
