####> This option file is used in:
####>   podman create, run, update
####> If file is edited, make sure the changes
####> are applicable to all of those.
#### **--cpus**=*number*

Number of CPUs. The default is *0.0* which means no limit. This is shorthand
for **--cpu-period** and **--cpu-quota**, therefore the option cannot be specified with
**--cpu-period** or **--cpu-quota**.

@@include options/_rootless-resource-limits.md

This option is not supported on cgroups V1 rootless systems.
