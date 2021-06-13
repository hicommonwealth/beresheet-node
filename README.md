# beresheet-node

This repository tracks [edgeware-node](https://github.com/hicommonwealth/edgeware-node).

The only change is to the runtime's name and chain ID:
- Runtime name `beresheet` instead of `edgeware`
- EVM chain ID `2022` instead of `2021`

After cloning this repository, you may want to add edgeware-node as an upstream:

```
git remote add edgeware git@github.com:hicommonwealth/edgeware-node.git
```

To merge in changes from edgeware-node:

```
git fetch edgeware
git merge edgeware/master
```

To build the node and runtime, follow the instructions in [edgeware-node](https://github.com/hicommonwealth/edgeware-node).
