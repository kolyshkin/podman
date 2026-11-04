####> This option file is used in:
####>   podman build, container clone, create, farm build, run, update
####> If file is edited, make sure the changes
####> are applicable to all of those.
#### **--cpu-quota**=*limit*

Limit the CPU Completely Fair Scheduler (CFS) quota.

Limit the container's CPU usage. By default, containers run with the full
CPU resource. The limit is a number in microseconds. If a number is provided,
the container is allowed to use that much CPU time until the CPU period
ends (controllable via **--cpu-period**).

@@include options/_rootless-resource-limits.md

This option is not supported on cgroups V1 rootless systems.
