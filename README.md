<br />
<p align="center">
  <a href="https://rayanfam.com">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Hypervisor From Scratch</h3>

  <p align="center">
    A tutorial on creating a hypervisor from scratch
    <br />
    <a href="https://rayanfam.com/tutorials/"><strong>All the parts »</strong></a>
    <br />
    <br />
    <a href="https://rayanfam.com/topics/hypervisor-from-scratch-part-1/">Part 1</a>
    ·
    <a href="https://rayanfam.com/topics/hypervisor-from-scratch-part-2/">Part 2</a>
    ·
  <a href="https://rayanfam.com/topics/hypervisor-from-scratch-part-3/">Part 3</a>
    ·
  <a href="https://rayanfam.com/topics/hypervisor-from-scratch-part-4/">Part 4</a>
    ·
  <a href="https://rayanfam.com/topics/hypervisor-from-scratch-part-5/">Part 5</a>
    ·
  <a href="https://rayanfam.com/topics/hypervisor-from-scratch-part-6/">Part 6</a>
    ·
  <a href="https://rayanfam.com/topics/hypervisor-from-scratch-part-7/">Part 7</a>
    ·
  <a href="https://rayanfam.com/topics/hypervisor-from-scratch-part-8/">Part 8</a>
  </p>
</p>

**If you're looking to use a hypervisor for analysis and reverse engineering tasks, check out [HyperDbg](https://github.com/HyperDbg/HyperDbg) Debugger. It's a hypervisor-based debugger designed specifically for analyzing, fuzzing, and reversing applications.**

**Notice**: The _**Hypervisor From Scratch**_ tutorial is completely revised in **August 2022**. Codes from all parts are updated, unnecessary details are removed, and new explanations and materials are added to the tutorial.

# Hypervisor From Scratch

Source code of a multiple series of tutorials about the hypervisor. 

Available at: https://rayanfam.com/tutorials


**Part 1 - Basic Concepts & Configure Testing Environment**
(https://rayanfam.com/topics/hypervisor-from-scratch-part-1)


**Part 2 - Entering VMX Operation** 
(https://rayanfam.com/topics/hypervisor-from-scratch-part-2)


**Part 3 - Setting up Our First Virtual Machine** 
(https://rayanfam.com/topics/hypervisor-from-scratch-part-3)


**Part 4 - Address Translation Using Extended Page Table (EPT)** 
(https://rayanfam.com/topics/hypervisor-from-scratch-part-4)


**Part 5 - Setting up VMCS &amp; Running Guest Code** 
(https://rayanfam.com/topics/hypervisor-from-scratch-part-5)


**Part 6 - Virtualizing An Already Running System** 
(https://rayanfam.com/topics/hypervisor-from-scratch-part-6)


**Part 7 - Using EPT & Page-Level Monitoring Features** 
(https://rayanfam.com/topics/hypervisor-from-scratch-part-7)


**Part 8 - How To Do Magic With Hypervisor!**
(https://rayanfam.com/topics/hypervisor-from-scratch-part-8)

## Note

**Note**: please keep in mind that hypervisors change over time because new features are added to the operating systems or using new technologies. For example, updates to Meltdown & Spectre have made a lot of changes to the hypervisors, so if you want to use Hypervisor From Scratch in your projects, research, or whatever, you have to use the driver from the latest parts of these tutorial series as this tutorial is actively updated and changes are applied to the newer parts (earlier parts keep untouched) so you might encounter errors and instability problems in the earlier parts thus make sure to use the latest parts in real-world projects.



## Compile & Install

In order to compile this project, you have to use Windows Driver Kit (WDK), first install Visual Studio, then install WDK. After that, you can compile it.

## Environment

All the drivers are tested on both physical-machine, and VMWare Workstations's nested-virtualization, from part 8 support to Hyper-V is added, which means that you can test part 8 and newer parts on physical-machine, VMWare Workstation's nested-virtualization, and Hyper-V's nested-virtualization.


## Other Articles & Projects

If you want to know more about hypervisors, you can visit the [awesome virtualization](https://github.com/Wenzel/awesome-virtualization) repo.

## Credits
 This series is written by:<br />
- <a href="https://twitter.com/Intel80x86">Sina Karvandi</a><br />
- <a href="https://twitter.com/PetrBenes">Petr Beneš</a><br />

 Special Thanks to these guys for their help and contributions:<br />
- <a href="https://twitter.com/aionescu">Alex Ionescu</a><br />
- <a href="https://twitter.com/standa_t">Satoshi Tanda</a><br />
- <a href="https://twitter.com/Liran_Alon">Liran Alon</a><br />
- <a href="https://twitter.com/gerhart_x">gerhart</a><br />
- <a href="https://twitter.com/@daaximus">Daax</a><br />
- <a href="https://twitter.com/LordNoteworthy">Noteworthy</a><br />
- <a href="https://twitter.com/ivansprundel">ivs</a><br />
- <a href="https://twitter.com/honorary_bot">Artem Shishkin</a><br />
- <a href="https://twitter.com/shahriar_ee">Shahriar</a><br />
- <a href="https://twitter.com/ahmadgzi">Ahmad</a><br />
- ...and many other people who helped to solve the problems</a><br />


<!-- LICENSE -->
## License

**Hypervisor From Scratch** is licensed under an **MIT** license.

[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/SinaKarvandi/Hypervisor-From-Scratch/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/SinaKarvandi/Hypervisor-From-Scratch/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/SinaKarvandi/Hypervisor-From-Scratch/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/SinaKarvandi/Hypervisor-From-Scratch/issues
