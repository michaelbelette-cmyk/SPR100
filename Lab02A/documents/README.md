# Lab02A - Windows VM CPU and Memory Analysis Report

**Student Name:** [Your Full Name]
**Student ID:** [Your Student ID]
**Course Section:** [Your Section Number]
**Completion Date:** 2026-01-29

## Part 1: Virtual Machine Setup and Configuration
### 1.1 VM Configuration Summary
[cite_start]**Hypervisor Name:** VMware Workstation Pro [cite: 352]
**Hypervisor Version:** [Fill in during lab]
- **CPU Cores:** [Fill in during lab]
[cite_start]**Memory:** 4GB [cite: 61]
**Storage:** [Fill in during lab]
- [cite_start]**Network:** NAT [cite: 357]

### 1.2 VM Import and Startup Process
[cite_start]**VM File Source:** \\mydrive\courses\SPR100\Win10 [cite: 359]
[cite_start]**Import Method:** [Describe how you imported win_nov22.ova] [cite: 360]
[cite_start]**VM Name:** win10-[your username] [cite: 361]
[cite_start]**Storage Path:** [Path on your external SSD drive] [cite: 362]
- [cite_start]**Startup Time:** [Time from power-on to login screen] [cite: 363]

### 1.3 Initial System Configuration
[cite_start]**Password Change Process:** [Describe how you changed the Student account password] [cite: 365]
- [cite_start]**Git Installation:** [Describe the Git installation using winget] [cite: 366]

## Part 2: Windows System Analysis
### 2.1 CPU Analysis Results
#### System Information (msinfo32)
[cite_start]**Processor Name:** [Full name from System Summary] [cite: 370]
[cite_start]**Number of Cores:** [Physical cores from Processor section] [cite: 371]
- [cite_start]**Logical Processors:** [Total logical processors] [cite: 372]

### 2.2 Memory Analysis Results
[cite_start]**Total Physical Memory:** [Amount from msinfo32] [cite: 385]
[cite_start]**Available Physical Memory:** [Amount from msinfo32] [cite: 386]
[cite_start]**Total Virtual Memory:** [Amount from msinfo32] [cite: 387]
[cite_start]**Available Virtual Memory:** [Amount from msinfo32] [cite: 388]

- [cite_start]**Virtual Memory Explanation:** [Draft your explanation here] [cite: 389]

## Analysis and Conclusions
### Understanding Questions
[cite_start]**Virtual Memory Concept:** [A memory management technique where the Operating System uses a portion of the hard drive space, known as a Page File, to act as a temporary extension of physical RAM. This is important because it allows the system to run larger applications or more programs simultaneously than the physical RAM alone could support, preventing "out of memory" errors by swapping data between the disk and RAM.] [cite: 439]
[cite_start]**VM Resource Allocation:** [The process of dedicating a specific portion of the host's physical hardware (like CPU cores and RAM) to a Virtual Machine. Increasing a VM's RAM from the default 2GB to 4GB provides the guest OS with more "breathing room" to process instructions and manage data, which reduces the need for slow disk swapping and results in a much smoother, faster user experience] [cite: 440]
[cite_start]**Performance Monitoring Value:** [Allows admins to establish a "baseline" of normal activity and identify anomalies, such as CPU or memory spikes. These spikes can reveal hardware bottlenecks (where the hardware is too weak for the software), poorly optimized applications, or the presence of malware that is consuming system resources in the background.] [cite: 441]
