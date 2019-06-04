A simple shell script and configuration file for backing-up ZFS datasets (file
systems).

You specify which datasets to backup, and snapshots are replicated to both
external and offsite locations as well as saved locally.

The script must be run as user `root` (because the ZFS on Linux tools require
this) and can be invoked as simply as:

```
sudo my-zfs-backup
```

Requires the Syncoid tool from [Sanoid](https://github.com/jimsalterjrs/sanoid).
