####> This option file is used in:
####>   podman build, container clone, create, farm build, pod clone, pod create, run, update
####> If file is edited, make sure the changes
####> are applicable to all of those.
#### **--cpuset-mems**=*nodes*

Memory nodes (MEMs) in which to allow execution (0-3, 0,1). Only effective on
NUMA systems.

If there are four memory nodes on the system (0-3), use **--cpuset-mems=0,1**
then processes in the container only uses memory from the first
two memory nodes.

@@include options/_rootless-resource-limits.md

This option is not supported on cgroups V1 rootless systems.
