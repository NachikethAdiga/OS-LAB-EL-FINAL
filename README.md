This repo contains OS part B project.

There is no in built memory detector in C (unlike Java). So, this code helps in detecting memory leaks (if any). There are mainly three types of memory leaks. 
The 3 types are:
1) If we borrow memory from OS and don't release it.
2) If we free the same memory twice.
3) If we try to access memory that has already been freed.

Our MLD detects all these 3 types of leaks and thus, these leaks can be removed. 
