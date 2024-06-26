# kusion workspace update

Update a workspace configuration

### Synopsis

This command updates a workspace configuration with specified configuration file, where the file must be in the YAML format.

```
kusion workspace update
```

### Examples

```
  # Update a workspace configuration
  kusion workspace update dev -f dev.yaml
```

### Options

```
  -f, --file string   the path of workspace configuration file
  -h, --help          help for update
```

### Options inherited from parent commands

```
      --profile string          Name of profile to capture. One of (none|cpu|heap|goroutine|threadcreate|block|mutex) (default "none")
      --profile-output string   Name of the file to write the profile to (default "profile.pprof")
```

### SEE ALSO

* [kusion workspace](kusion-workspace.md)	 - Workspace is a logical concept representing a target that stacks will be deployed to

###### Auto generated by spf13/cobra on 4-Jan-2024
