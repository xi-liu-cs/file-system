# file system project
Xi Liu </br>
2021 </br>
* implementation of a file system on disk
* maintains one inode structure for each file
to store metadata about the file
* using the inode structure to implement 
file system interface facilities such as read(), write(),
inode_block_walk(), link(), unlink()...
* to support large files for each inode,
manages a multi-level index structure 
and indirect pointers (which point to more 
pointers, each of which then points to user data)