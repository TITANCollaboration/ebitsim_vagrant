# ebitsim_vagrant

This is a fully functional Vagrantfile for use with Vagrant.  It contains
the EBITSIM software and pypy3 with all dependencies.

-----

Linux & Windows 10 64bit instructions, you just don't need the reboot on
linux:

Download Virtual Box from https://www.virtualbox.org/  (Probably 6.0, not 6.1 currently)


Download Vagrant from https://www.vagrantup.com/

Restart PC (Installation may ask to reboot).

Download Vagrantfile file from the link into its own directory :  https://github.com/TITANCollaboration/ebitsim_vagrant

Change to the directory where you put the Vagrantfile

Use command ‘vagrant up’; This will download all the files required.

Use command ‘vagrant ssh’ to login to virtual machine.

------

If this is your first time running this or just a good practice do the
following to ensure the simulation code is up to date:

```
cd ebitsim
git update
```

From the ebitsim directory you can run the simulation via : pypy3 ./ebitsim.py

 
