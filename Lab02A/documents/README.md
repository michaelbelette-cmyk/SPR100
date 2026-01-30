# Lab02A - Windows VM CPU and Memory Analysis Report

**Student Name:** \[Your Full Name]
**Student ID:** \[Your Student ID]
**Course Section:** \[Your Section Number]
**Completion Date:** 2026-01-29

## Part 1: Virtual Machine Setup and Configuration

### 1.1 VM Configuration Summary

\[cite\_start]**Hypervisor Name:** VMware Workstation Pro \[cite: 352]
**Hypervisor Version:** 17.6.4 build-24832109

* **CPU Cores:** 2
  \[cite\_start]**Memory:** 4GB \[cite: 61]
  **Storage:** 60 GB
* \[cite\_start]**Network:** NAT \[cite: 357]

### 1.2 VM Import and Startup Process

\[cite\_start]**VM File Source:** \\mydrive\\courses\\SPR100\\Win10 \[cite: 359]
\[cite\_start]**Import Method:** selected File > Open, navigated to the .ova file on my SSD, and imported it into the VMware library. \[cite: 360]
\[cite\_start]**VM Name:** win10-mbelette \[cite: 361]
\[cite\_start]**Storage Path:** E:\\SPR100\\Win10 \[cite: 362]

* \[cite\_start]**Startup Time:** 40s \[cite: 363]

### 1.3 Initial System Configuration

\[cite\_start]**Password Change Process:** \[Describe how you changed the Student account password] \[cite: 365]

* \[cite\_start]**Git Installation:** winget install --id Git.Git -e --source winget \[cite: 366]

## Part 2: Windows System Analysis

### 2.1 CPU Analysis Results

#### System Information (msinfo32)

\[cite\_start]**Processor Name:** Intel(R) Core(TM) Ultra 7 265 \[cite: 370]
\[cite\_start]**Number of Cores: 2**  \[cite: 371]

* \[cite\_start]**Logical Processors: 2**  \[cite: 372]

### 2.2 Memory Analysis Results

Physical Memory Capacity (PowerShell): 33554432

\[cite\_start]**Total Physical Memory:** 3.91 GB \[cite: 385]
\[cite\_start]**Available Physical Memory:** 849 MB \[cite: 386]
\[cite\_start]**Total Virtual Memory:** 5.28 GB \[cite: 387]
\[cite\_start]**Available Virtual Memory: 2.62 GB** \[cite: 388]

* \[cite\_start]**Virtual Memory Explanation:** a feature that uses a portion of the hard drive to act as extra RAM when the physical memory is full. Allows the system to run more programs than the physical hardware alone would support \[cite: 389]

## Analysis and Conclusions

### Understanding Questions

\[cite\_start]**Virtual Memory Concept:** A memory management technique where the Operating System uses a portion of the hard drive space, known as a Page File, to act as a temporary extension of physical RAM. This is important because it allows the system to run larger applications or more programs simultaneously than the physical RAM alone could support, preventing "out of memory" errors by swapping data between the disk and RAM. \[cite: 439]
\[cite\_start]**VM Resource Allocation:** The process of dedicating a specific portion of the host's physical hardware (like CPU cores and RAM) to a Virtual Machine. Increasing a VM's RAM from the default 2GB to 4GB provides the guest OS with more "breathing room" to process instructions and manage data, which reduces the need for slow disk swapping and results in a much smoother, faster user experience \[cite: 440]
\[cite\_start]**Performance Monitoring Value:** Allows admins to establish a "baseline" of normal activity and identify anomalies, such as CPU or memory spikes. These spikes can reveal hardware bottlenecks (where the hardware is too weak for the software), poorly optimized applications, or the presence of malware that is consuming system resources in the background. \[cite: 441]

