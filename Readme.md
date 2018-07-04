## Welcome to PureDarwin 17.4 Beta OS

* To run this, you'll need Qemu running the command below and extract it using xz 

* qemu-system-x86_64 -m 4096 -cpu Penryn -smp 2  -net nic,model=e1000,name=network0,macaddr="FE:DC:BA:98:76:54" -net user,name=network0 -serial stdio -drive format=vmdk,file=pd_17_4.vmdk


* This is not full os like Xmas was, As Apple Inc, has closed down a lot of their opensource coreOS releases we the community have to pick up the slack. 
* There is still a lot of work to be done but it can be completed if we band together. If you would like to view what's on this vm please use Paragon VMDK mounter for macOS users, all other please see what you need to do to mount and read an hfs filesystem on your os.


* Please do not ask us questions on how to run macOS applications and none open source work on PureDarwin. If you want something to hack on, then this is it.

* We have not finished all the system/network cmds. We built as much as we could without pulling headers from Apple's Xcode SDK's.


## Projects 

[Libxpc/Launchd](https://github.com/PureDarwin/launchd-and-libxpc)

[PureFoundation](https://github.com/PureDarwin/PureFoundation)

[CoreFoundation](https://github.com/PureDarwin/CoreFoundation)

[ddisnoted](https://github.com/PureDarwin/ddistnoted)

[DarwinBuild](https://github.com/PureDarwin/DarwinBuild)

[Enoch Bootloader](http://forge.voodooprojects.org/p/chameleon/source/tree/HEAD/branches/ErmaC/Enoch)


## To Do

* Finish out Family Driver Support(USB/SATA/NVME/AHCI/PD-APCIPlatform)
* Finish out System Commands(Reboot/Shutdown)
* Finish out the Networking
* Finish out the Multi-User



## Credits
* We would like to thank:

* Apple, Inc. for releasing Darwin as Open Source 
* David Elliott for his work on boot-132
* The Chameleon team for their work on boot-132
* The xnu-dev team for their work on the XNU kernel
* Stuart Crook for his work on PureFoundation, ddisnoted and libxpc/launchd work
* Ethan Sheriff for his work on the libsystem-plaform and libxpc/launchd work
* William Kent for his work on the Darwinbuild upgrade 
* Rafirafi for his work on Generic Platform and PDCrypto kexts
* Mac OS Forge for The DarwinBuild project 

## Contact Us!

### Admins

* Ferdinand Klinzer - bart@pd-devs.org
* Clifford Sekel - insanedarwin@pd-devs.org

### Core Dev’s

* Avi Saven - avisaven@pd-devs.org
* Ethan Sherriff - libsystem_ethan@pd-devs.org
* Stuart Cook - sjc@pd-devs.org
* William Kent - wjk@pd-devs.org
