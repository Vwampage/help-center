---
aliases:
- docs/reference/replicatedctl/replicatedctl_snapshot_restore
categories:
- replicatedctl
date: 2018-02-20T00:45:55Z
description: Restore installation from the specified spanshot
index: docs
title: replicatedctl snapshot restore
weight: "551"
---

## replicatedctl snapshot restore

Restore installation from the specified spanshot

### Synopsis


Restore installation from the specified spanshot

```
replicatedctl snapshot restore ID
```

### Options

```
      --dismiss-preflight-checks   Dismiss preflight checks
      --id string                  Snapshot ID
      --node-timeout int           Number of seconds to wait for nodes to connect (default 60)
```

### Options inherited from parent commands

```
      --host string            Replicated API host (default "unix:///var/run/replicated/replicated-cli.sock")
      --path string            Snapshot location path. The value should be an absolute path. This option is only used with local and sftp backends.
      --s3-bucket string       S3 bucket name. This option is only used with s3 backend.
      --s3-key-id string       ID of the secret key that has write access to the specified S3 bucket. This option is only used with s3 backend.
      --s3-region string       S3 bucket region. This option is only used with s3 backend.
      --s3-secret-key string   Secret key value. This option is only used with s3 backend.
      --sftp-host string       Hostname or IP of the server where snapshots will be stored.
      --sftp-key string        base64 encoded private key PEM data used for authentication. This option is only used with sftp backend.
      --sftp-user string       User name that will be used to login to the SFTP host. This option is only used with sftp backend.
      --store string           Backend store. Valid values are s3, sftp, and local.
```

### SEE ALSO
* [replicatedctl snapshot](/api/replicatedctl/replicatedctl_snapshot/)	 - Manage snapshots
