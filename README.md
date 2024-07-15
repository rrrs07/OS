# Lec-2 Types of Operating System

### first four are very imp

**1.Single Process OS**

- eg: MS DOS
- Execute job one by one cannot multitask (maximum utilization of CPU is not   done)
- Process starvation
- no high priority

**2.Batch Processing**

- eg:ATLAS OS
- Batch wise execution
- low cpu utilization
- Process Starvation inside batch
- Batch Starvation
- no high priority

**3.Multi Programming OS**

- eg: THE
- single cpu
- multitask
- context switching: when P1 goes for IO and P2 comes to execute.P1 gets stored in PCB(Process Control Block)

**4.Multitasking OS**

- eg: CTSS
- single cpu
- time sharing(when time is reached then next task is executed by stopping the previous one)
- max cpu utilization
- no starvation
- context switching
- high priority

**5.Multi Processing**

- eg: Windows
- time sharing
- context switching
- multiple cpu

**6.Distributed OS**

- eg: Solaris
- loosely coupled
- connected through network

**7.Real Time OS**

- eg: air traffic control in airport
- for high accuracy
- industrial applications like nuclear plant