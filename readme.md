## tooling

[link](https://kubernetes.io/docs/tasks/tools/)

kind 
lets you run Kubernetes on your local computer. This tool requires that you have Docker installed and configured.

Kubectl
allows you to run commands against Kubernetes clusters. You can use kubectl to deploy applications, inspect and manage cluster resources, and view logs. For more information including a complete list of kubectl operations, see the kubectl reference documentation.




## seccomp

Seccomp: Filter a process's system calls.

Seccomp stands for secure computing mode and has been a feature of the Linux kernel since version 2.6.12. It can be used to sandbox the privileges of a process, restricting the calls it is able to make from userspace into the kernel. Kubernetes lets you automatically apply seccomp profiles loaded onto a node to your Pods and containers.
[link](https://kubernetes.io/docs/tutorials/security/seccomp/)

## selinux

Security Enhanced Linux (SELinux): Objects are assigned security labels.

Security-Enhanced Linux (SELinux) is a Linux kernel security module that provides a mechanism for supporting access control security policies, including mandatory access controls (MAC).
