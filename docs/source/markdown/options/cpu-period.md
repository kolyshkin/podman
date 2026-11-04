####> This option file is used in:
####>   podman build, container clone, create, farm build, run, update
####> If file is edited, make sure the changes
####> are applicable to all of those.
#### **--cpu-period**=*limit*

Set the CPU period for the Completely Fair Scheduler (CFS), which is a
duration in microseconds. Once the container's CPU quota is used up, it will not
be scheduled to run until the current period ends. Defaults to 100000
microseconds.

@@include options/_rootless-resource-limits.md

This option is not supported on cgroups V1 rootless systems.
