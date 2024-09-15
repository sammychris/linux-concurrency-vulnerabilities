# Final Report: Mitigating Concurrency Vulnerabilities in Linux Kernel

## Introduction
This project aims to mitigate two significant concurrency vulnerabilities in the Linux kernel: CVE-2016-5195 (Dirty COW) and CVE-2015-1325 (Keyring Race Condition). 

## Methodology
- Vulnerabilities were replicated in a controlled environment.
- Fixes were developed using mutexes, semaphores, SELinux, and kernel patches.

## Results
- Kernel patches successfully mitigated both vulnerabilities with 100% effectiveness.
- Synchronization mechanisms (e.g., mutexes) caused deadlocks and system instability.

## Conclusion
The results demonstrate the superiority of kernel patching over synchronization mechanisms in mitigating concurrency vulnerabilities.
