---
title: "Verify the installation"
weight: 6
type: docs
sectionnumber: 1
---

## Verify the installation

You should now be able to execute `oc` in the command prompt. To test, execute:

```bash
oc version
```

You should now see something like (the version number may vary):

```
Client Version: 4.6.9
...
```

If you don't see a similar output, possibly there are issues with the `PATH` variable.

{{% alert title="Warning" color="secondary" %}}
Make sure to use at least `oc` version `4.6.x`.
{{% /alert %}}


## First steps with oc

The `oc` binary has many commands and sub-commands. Invoke `oc --help` (or simply `-h`) to get a list of all commands; `oc <command> --help` gives you detailed help about a command.

If you don't want to memorize all `oc` options then use the `oc` cheat sheet: <https://developers.redhat.com/cheat-sheets/red-hat-openshift-container-platform>


## Optional tools

Have a look at the optional tools mentioned in [Other tools to work with OpenShift](../05/) if you're interested.


## Next steps

When you're ready to go, head on over to the [labs](../../docs/) and begin with the training!
