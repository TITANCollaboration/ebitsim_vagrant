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
git pull
```

From the ebitsim directory you can run the simulation via : pypy3 ./ebitsim.py

# Notes from original ebitsim project

Example usage :

Using command line arguments:

pypy3 ebitsim.py -z 51 -a 129 --chargeStates 46 47 48 49 50 51 --beamEnergy=25000.0 --breedingTime=12.0 --outputFile=BE25_I0.02_SB51_46_51.png

Using config file:

pypy3 ebitsim.py --configFile ebitsim.cfg

-------------

Grabbed periodic table of elements csv from : https://gist.github.com/GoodmanSciences/c2dd862cd38f21b0ad36b8f96b4bf1ee  -  Thank you!
