## UID: 105817312

(IMPORTANT: Only replace the above numbers with your true UID, do not modify spacing and newlines, otherwise your tarfile might not be created correctly)

# Hey! I'm Filing Here

A 1 MiB ext2 file system with 2 directories, 1 regular file, and 1 symbolic link.

## Building

To build the program, run

    make clean

    make

## Running

Show how to compile, mount, and example output of `ls -ain` your mounted filesystem.

    mkdir mnt
    sudo mount -o loop cs111-base.img mnt
    cd mnt
    ls -ain 


total 7
    2 drwxr -xr-x 3 0 0 1024 .
                            ..
    13 lrw-r--r-- 1 1000 1000 11 hello -> hello -world
    12 -rw-r--r-- 1 1000 1000 12 hello -world
    11 drwxr -xr-x 2 0 0 1024 lost+found

## Cleaning up

Explain briefly how to unmount the filesystem, remove the mount directory, and
clean up all binary files.
