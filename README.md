# Personal-OS


Installation: 
	1: Bootable OS - make mykernel.bin

	Then update grub chf file and add to the os to the boot loader by:

sudo vim /boot/grub/grub.cfg


###BEGIN MYKERNEL###
menuentry 'Name of Operating System'
{
	multiboot /boot/mykernel.bin
	boot
}
###END MYKERNEL###

	2: VirtualBox - make mykernel.iso

	This creates the disk image of your os to install it in a virtual machine

	2b: Automatic update/run - make run

	This reboots the virtual computer in with the updated operating system to test your changes.

