## pachctl copy file

Copy files between pfs paths.

### Synopsis


Copy files between pfs paths.

```
pachctl copy file <src-repo>@<src-branch-or-commit>:<src-path> <dst-repo>@<dst-branch-or-commit>:<dst-path>
```

### Options

```
  -o, --overwrite   Overwrite the existing content of the file, either from previous commits or previous calls to 'put file' within this commit.
```

### Options inherited from parent commands

```
      --no-metrics           Don't report user metrics for this command
      --no-port-forwarding   Disable implicit port forwarding
  -v, --verbose              Output verbose logs
```

