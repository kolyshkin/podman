####> This option file is used in:
####>   podman container clone, create, pod clone, pod create, run, update
####> If file is edited, make sure the changes
####> are applicable to all of those.
#### **--device-read-bps**=*path:rate*

Limit read rate (in bytes per second) from a device (e.g. **--device-read-bps=/dev/sda:1mb**).

@@include options/_rootless-resource-limits.md

This option is not supported on cgroups V1 rootless systems.
