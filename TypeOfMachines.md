# Written Homework #4
### 1. State what the advantages of Virtual Machines are
* It's easy to create a virtual machine for a specific task and then delete it
* They are programmable
* Movable
* Can detect CPU contention
### 2. State what the advantages of containers are
* Less wasteful than virtual machines 
  * they consume resources at the same fine-grained level as processes
* Are very lightweight because they do not require an entire OS - Only specific files that are needed are copied
* They enable customers to be isolated from each other while still sharing physical machines - efficient for shared services
* Because they are self-contained they eliminate dependencies and conflicts
### 3. State when you might select physical machines over virtual machines
* You would pick a Physical machine because you can use the full CPU at almost full capacity for monthes
* Physical Server O/S is less expensive
* If that one physical machine is suffering it won't affect the other physical machines unlike how a virtual machine would
* Virtual machines are heavy-weight they run on a full operating system which requires a lot of disk space. Having one physical machine just will use one O/S
"Physical servers give benefits when:
* The number of services is constant
* Each of the services requires constant resources.
* It is possible to size a server to use close to 100% of its capacity, constantly.
* Very few changes over time.
---
## How the cloud would aid microservices.

