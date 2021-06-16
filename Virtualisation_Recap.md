Virtualisation 3:

Recap. Hypervisor is used to interface between the virtual machine and the host, as opposed to a traditional compute where the operating system interacts with the hardware.

Type 1 hypervisor - “bare metal” on the hardware.
Type 2 - sits on a host OS.


Type 1 considered more secure, generally. This is because more systems mean more potential exploits.


VAGRANT

Tool for building and managing virtual machine environments in single workflow.

Allows the quick reproduction of the production environment, which makes testing much easier.

Workflow of Vagrant:



Containerisation

Abstraction at OS level. NOT a full virtual machine, but a different form of virtualisation. Containers hold all the configurations and everything else related to a particular software. Contains only part of the operating system. Uses the host operating system, all containers share the same host operating system through a container engine

Docker

Docker is a container engine. It can also give us a network of containerised “systems” if needed. Docker commands are run from our host operating system using docker client. Dominant provider of containerisation.

Docker container ls - lists running containers

Docker images - shows stored images.

Stop vs kill: stop will give a grace period to container to finish its work. Kill outright stops the process.


