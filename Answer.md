1. Explain Working mechanism of Virtual Machine. <br/>
->A virtual machine is a computer file, typically called an image, that behaves like an actual computer. It can run in a window as a separate computing environment, often to run a different operating system or even to function as the user's entire computer experience as common on many people's work computers. The virtual machine is partitioned from the rest of the system, meaning that the software inside a VM can't interfere with the host computer's primary operating system.<br/>
This process is managed by software known as a hypervisor. The hypervisor is responsible for managing and provisioning resources like memory and storage from the host to guests. It also schedules operations in VMs so they don’t overrun each other when using resources.<br/>
<br/>

2. Explain Working mechanism of Containers.<br/>
->Containers hold the components necessary to run desired software. These components include files, environment variables, dependencies and libraries. The host OS constrains the container's access to physical resources, such as CPU, storage and memory, so a single container cannot consume all of a host's physical resources.<br/>
<br/>

3. What problem does Virtualization solves and what is its drawback in context to modern application deployments?<br/>
->They are
1.Resource distribution<br/>
The way virtualization partitions systems can result in varied ways some might function really well, and others might not provide users access to enough resources to meet their needs. <br/>
2.Backward compatibility<br/>
Using legacy systems can cause problems with newer virtualized software programs. Compatibility issues can be time-consuming and difficult to solve. A good provider may be able to suggest upgrades and workarounds to ensure that everything functions the way they should.<br/>
3.Performance monitoring<br/>
Virtualized systems don’t lend themselves to the same kind of performance monitoring as hardware like mainframes and hardware drives do.<br/>
4.Security<br/>
Virtual systems could be vulnerable when users don’t keep them secure and apply best practices for passwords or downloads.
<br/>
1.It can have a high cost of implementation.<br/>
2.It still has limitations.<br/>
3.It creates an availability issue.<br/>
4.It creates a scalability issue. <br/>
<br/>
4. What are the problems Container solves in regard to app deployment and how it solves?<br/>
->they are
1.Less overhead
Containers require less system resources than traditional or hardware virtual machine 
environments because they don’t include operating system images. 
2.Increased portability
Applications running in containers can be deployed easily to multiple different operating 
systems and hardware platforms. 
3.More consistent operation
DevOps teams know applications in containers will run the same, regardless of where they
are deployed. 
4.Greater efficiency
Containers allow applications to be more rapidly deployed, patched, or scaled. 
5.Better application development
Containers support agile and DevOps efforts to accelerate development, test, and production
cycles.
