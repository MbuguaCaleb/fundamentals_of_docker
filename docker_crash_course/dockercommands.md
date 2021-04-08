**Topics Covered**

```
(a)What is docker

(b)Virtual Machines vs  Containers

(c)Architecture of docker

(d)Installing docker

(e)Development workflow


```

```
What is docker?

Docker helps us to consistently build,run and ship our applications.

Helps us package our application together with everything it needs and therefore our application
is guaranteed to run effectvely in any environment.

if my app works on my dev machinne its guarantted to
work come production.

My teammate also does not have to install every single package which is cumbersome and timeconsuming.

They just run docker compose up and everthing is installed.

```

**What is a Container**

```
A container is an isolated environment for running our application

A virtual machine on the other hand is an abstraction of a real machine.

We create virtual machines by the help of something we call a hypervisor example of
this is something like vmware.

Disavantages of Virtual Machines??
(a)Each VM Needs a fullblown OS.
(b)Slow to Start.Slow bacause the entire Operating
system has to loaded just like starting your computer.
(c)Resource Intensive..share things like disk space..
Hardware resources.


Advantages of containers??

(a)Allow running of mutiple apps in isolation.
(b)Are light weight.They do not need a full Operating System.
(c)Use the OS of the host.All the containers will  share the OS of the Host.
(d)Start quickly
(e)Need less hardware rource.||When you are using a virtual machine you share the headware resources..ie the RAM.

```

**(c)Architecture of docker**

```
Uses Client Server Architecture

All continers share the kernel of the Host.

```

**Installing Docker**

```


```

**Notes By**

```
MbuguaCaleb

```
