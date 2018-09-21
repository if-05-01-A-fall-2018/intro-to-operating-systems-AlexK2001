# Assignment 1: Research on Operating Systems and Installation
## VxWorks
### Description of VxWorks

VxWorks is a real-time operating system (RTOS) developed as software by Wind River Systems, an Intel subsidiary of Alameda, California, US. First released in 1987, VxWorks is designed for use in  systems requiring real-time, performance and, in many cases, safety and security certification, for industries, such as aerospace and defense, medical devices, industrial equipment, robotics, energy, transportation, network infrastructure, automotive, and consumer electronics.

VxWorks supports Intel architecture, POWER architecture, and ARM architectures. The RTOS can be used in multicore asymmetric multiprocessing (AMP), symmetric multiprocessing (SMP), and mixed modes.

VxWorks comes with the kernel, middleware, board support packages, Wind River Workbench development suite and complementary third-party software and hardware technologies. In its latest release, VxWorks 7, the RTOS has been re-engineered for modularity and upgradeability so the OS kernel is separate from middleware, applications and other packages. Scalability, security, safety, connectivity, and graphics have been improved

### History of VxWorks

0. 1980s: VxWorks adds support for 32-bit processors.
1. 1990s: VxWorks 5 becomes the first RTOS with a networking stack.
2. 2000s: VxWorks 6 supports SMP and adds derivative industry-specific platforms.
3. 2010s: VxWorks adds support for 64-bit processing and introduces VxWorks 7 for IoT in 2016.

### features
4. 64-bit operating system (only one 64-bit architecture supported: x86-64)
5. User-mode applications ("Real-Time Processes", or RTP)
6. SMP, AM
7. Error handling framework
8. Bluetooth, USB
9. distributed message queues
10. File systems: High Reliability File System, FAT-based file system, Network File System
11. Dual-mode IPv6 networking stack with IPv6 Ready Logo certification
12. Memory protection including real-time processes, error detection and reporting
13. Human machine interface with Vector Graphics
14. Graphical user interface (GUI)
15. Connectivity with Bluetooth and SocketCAN protocol stacks

### interesting details

RTOS = such software manages the time of a microprocessor or microcontroller. Also, an RTOS offers a multitasking environment in which several things happen simultaneously. To do this, it breaks up a program into several tasks. This measure pretends to the system that there are several CPUs available. In addition to multitasking, a real-time operating system also offers valuable services: delays, protection of shared resources and communication between tasks are all typical functions.

An asymmetric multiprocessor system is a multiprocessor architecture in which a given processor executes the operating system and distributes processes to itself and the rest of the processors. However, multiple processors can also run certain parts of the operating system to reduce the load. As a result, if one primary processor is unavailable (freeze due to full utilization or failure), the entire system becomes unusable.

A symmetric multiprocessor (SMP) system in information technology is a multiprocessor architecture in which two or more identical processors share a common address space. This means that each processor with the same (physical) address addresses the same memory cell or peripheral register. Most multiprocessor systems today are SMP architectures. An SMP architecture allows the running processes to be distributed dynamically to all available processors.

IoT = is a collective term for technologies of a global infrastructure of information societies, which makes it possible to network physical and virtual objects and to let them work together through information and communication techniques. Functions implemented with technologies of the "Internet of Things" allow the interaction between humans and here networked any electronic systems and between the systems themselves. You can also help people with their activities.

kernel = the Kernel is a central modul of a OS.




###tranlation and description of words
subsidiary = Tochtergesellschaft
simultaneously = gleichzeitig
pretend = vorgeben, sich verstellen
distribute = verteilen
common address space = gemeinsamen Adressraum
memory cell = Speicherzelle
derivative industry-specific platforms = Ableitung branchenspezifische Plattformen
