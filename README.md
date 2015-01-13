##Towelroot for Ubuntu x86

This exp has been tested on ubuntu 14.04 x86 and ubuntu 12.04.2 x86 successfully.

Learning CVE2014-3153 and towelroot.

Kernel through version 3.14, use `rbtree` to store rt_waiter(not `plist_node`), more complex! 

IA have diffrent thread_info with ARM!!

![](./final.png)

Source from geekben/towelroot and timwr/CVE-2014-3153

###Compile and run

```
$ gcc -fno-stack-protector -m32 -O0 -pthread mytowel.c -o mytowel
$ ./mytowel
```
