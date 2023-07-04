# Features

## High Availability

- In High Availability when the host crashes or fails the VM gets restarted.

- Very Small Downtime.

- Automatic detection of server failure.

- Completely automatic process. Do not need any admin (person).

- At least two host required.

- Automatic syncying the available other ESXi Host.

- No existing backup required / No extra host required.

- Not Required create a duplicate VM.

- High Availability does not use Vmotion.

**High Availability need following things**

- Cluster

- Shared Storage

- Vcenter server configured for the environment.



## Fault Tolerance

- Automatic Syncying other VM.

- 0% downtime.

- Does not goes down or restart.

- Primary VM goes down instantly secondary VM takes over and continue operation.

- Fault tolerance works on VM.


## Distributed Resource Schedular (DRS)

- Managed by Vcenter server.

- It balances load of VM acroceses ESXi host.

- Distributed load equally to all ESXi Host. 
