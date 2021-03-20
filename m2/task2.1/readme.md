#### PART 1. HYPERVISORS


### What are the most popular hypervisors for infrastructure virtualization
- VMware
- Oracle Virtual Box
- Citrix XenServer 

### Briefly describe the main differences of the most popular hypervisors
- VMware
    * VirtualBox is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use. Not only is VirtualBox an extremely feature rich, high performance product for enterprise customers, it is also the only professional solution that is freely available as Open Source Software under the terms of the GNU General Public License. VirtualBox runs on Windows, Linux, Macintosh, and Solaris hosts and supports a large number of guest operating systems including but not limited to Windows (NT 4.0, 2000, XP, Server 2003, Vista, Windows 7, Windows 8, Windows 10), DOS/Windows 3.x, Linux (2.4, 2.6, 3.x and 4.x), Solaris and OpenSolaris, OS/2, and OpenBSD
- Oracle Virtual Box
    *  It is a hosted hypervisor that runs on x64 versions of Windows and Linux operating systems, An operating systems license is needed to use proprietary ones such as Windows.



#### PART 2. WORK WITH VIRTUALBOX

+ 1.2  I downloaded the latest stable version of VirtualBox according to the host operating system From the official VirtualBox site and  installed on the workplace.Downloaded the latest stable version of Ubuntu Desktop from the official site
+ 1.3  Created VM1 and installed Ubuntu using the instructions . Called the machine - Ubuntu20.04_Gurskyi
![Create VM](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/1.PNG)
+ 1.5 I cloned an existing VM1 by creating a VM2
![Clone VM](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/2.PNG)
+ 1.6 I have created a group of two VM
![Group VM](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/3.PNG)
+ 1.7 For VM1, changed its state, taked several different snapshots
![Snapshots](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/4.PNG)
+ 1.8 
    Export VM1
![Export](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/5.PNG)
    Import VM
![Import](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/5_1.PNG)
+ 2.2 Configured the USB to connect the USB ports of the host machine to the VM
![USB](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/6.PNG)
+ 2.3 Configured a shared folder to exchange data between the virtual machine and the host
![shared folder](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/7.PNG)
+ 2.4 Configured different network modes for VM1, VM2. Check the connection between VM1, VM2, Host, Internet for different network modes. Maked a table of possible connections.
![Network](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/Network.png)
+ 3 Work with CLI through VBoxManage
![CLI1](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/8_1.PNG)
![CLI2](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/8_2.PNG)
![CLI3](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/8_3.PNG)



#### PART 3. WORK WITH VAGRANT

![Vagrant1](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/vag1.PNG)
![Vagrant2](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/vag2.PNG)
![Vagrant3](https://github.com/shizgara/DevOps_online_Rivne_2021Q2/blob/master/m2/task2.1/images/vag3.PNG)






