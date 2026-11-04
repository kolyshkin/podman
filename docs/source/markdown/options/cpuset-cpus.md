####> This option file is used in:
####>   podman build, container clone, create, farm build, pod clone, pod create, run, update
####> If file is edited, make sure the changes
####> are applicable to all of those.
#### **--cpuset-cpus**=*number*

CPUs in which to allow execution. Can be specified as a comma-separated list
(e.g. **0,1**), as a range (e.g. **0-3**), or any combination thereof
(e.g. **0-3,7,11-15**).

@@include options/_rootless-resource-limits.md

This option is not supported on cgroups V1 rootless systems.
