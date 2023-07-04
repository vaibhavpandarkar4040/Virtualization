# Migration

- 	Migration is the technique of moving a virtual machine from one host to another host or from one datastore to another datastore.

## Types Of Migration

<img src="Image\migration.jpg?raw=true" alt="Migration">

Note :- Database stores virtual machine files, log files, virtual disk & ISO images.

Two Types :- VMFS & NFS

**Cold Migration**

- Movement of virtual machine to another host in powered-off state.

- VM must be powered-off during migration.

- Your VM shut down mandatory.

- Cold migration can be used to move virtual machine between data centers 
are on the same vcenter server instance.

- Success rate is high.

- Chances of failure is less in cold migration in comparision to host migration.
	
**Suspended Migration**

- Migrating a virtual machine that is in suspended state.
	
- Suspended state is like paused state / sleep state in which you resume from same point on later stage.

- Suspended migration are considered hot because in case the virtual machine is running.

- The primary reason to suspend a virtual machine on an ESXi host is for troubleshooting.


**VMotion**

- It is also known as Live Migration.

- Migrating a virtual machine that is in Powered ON state.
	
- This is very useful as this doed not cause any downtime for the VM.

- In Vmware Vmotion machine is migrated from one ESXi host to another in Powered ON state, where as in storage VMotion machine is migrated from one datastore to another datastore in powered ON state.

- Vmotion moves a running virtual machine to a different ESXi host in the same cluster.

**Physical to Virtual (P2V)**

- Convert a physical computer to virtual one.

*Example,* 

You have a webserver running on physical hardware. You can run Vmware Vcenter converter, target the webserver  and have a copy of the physical server created on ESXi Host.

**Virtual to Virtual (V2V)**

- 	V2V Migration are exactly like P2V migration expect that the source machine is already a virtual machine.


*Example,*

Migrating from hyperV and Vmware workstation to ESXi host would be considered a V2V migration.


