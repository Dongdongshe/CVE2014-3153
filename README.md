##Towelroot for Ubuntu14.04 x86

Learning CVE2014-3153 and towelroot.

kernel through version 3.14, use rbtree to store rt_waiter, more complex! 

IA have diffrent thread_info with ARM!!

![](./final.png)

Source from geekben/towelroot and timwr/CVE-2014-3153

###Compile and run

```
$ gcc -fno-stack-protector -m32 -O0 -pthread mytowel.c -o mytowel
$ ./mytowel
```
