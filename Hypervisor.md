# Hypervisor

- Hypervisor is a peace of software or firmware that creates and run virtual machine.

- A hypervisor is sometimes also called a virtual machine message (VMM).

							

### Types Of Hypervisor

<img src="Image\Hypervisortype.jpg?raw=true" alt="Types Of Hypervisor">


## Type-1 Hypervisor (Firmware)

>- Firmware is installed just above the hardware.

<img src="Image\Firmware.jpg?raw=true" alt="Type-1 Hypervisor">

- Type-1 Hypervisor run directly on the system hardware.

- A guest operating system run on another level above the hypervisor.

- VMware ESXi is a type of hypervisor that runs on the host server hardware without on underlying operating system.

- Type-1 hypervisor act as their own operating system. 

- Hypervisor(ESXi) provides a virtualization layer that abstract the CPU Storage memory and networking resources of the physical host into multiple virtual machine.

- **Examples,**
>- VMware ESXi
>- Microsoft hyperV
>- Cytric xenserver


## Type-2 Hypervisor (Software)

>- Software is installed above the operating system.

- It is also known as Hosted type.

<img src="Image\software.jpg?raw=true" alt="Type-2 Hypervisor">

- Hypervisor that runs within a conventional operating system environment and the host operating system provides.

- It does not have direct access to the host Hardware and Resources.

- **Examples,**
>- VMware Workstation
>- Oracle Virtual box
>- Microsoft Virtual PC

### Difference Between Type-1 & Type-2 Hypervisor

<img src="Image\Difference.jpg?raw=true" alt="Difference">


 



