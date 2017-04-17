# lp-build-snap
Utility to trigger Snap package builds in Launchpad

# Usage
```
lp-build-snap [-h] [--lpname LPNAME] [--arch ARCH] [--series SERIES] snap_name

Trigger a Snap build in Launchpad

positional arguments:
  snap_name        Name of the Snap package being built

optional arguments:
  -h, --help       show this help message and exit
  --lpname LPNAME  Launchpad user or team account to build from
  --arch ARCH      Build architecture to target
  --series SERIES  Ubuntu release to build against
```

