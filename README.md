# beresheet-node

This repository tracks [edgeware-node](https://github.com/hicommonwealth/edgeware-node)
and only adds changes to the runtime's version and chain ID, which are used to deploy
the runtime on Beresheet testnet.

- Runtime name `100xx` instead of `xx` (e.g. 10047 instead of 47)
- EVM chain ID `2022` instead of `2021`

### Getting started

After cloning this repository, add edgeware-node as an upstream:

```
git remote add edgeware git@github.com:hicommonwealth/edgeware-node.git
```

When edgeware-node is updated, merge in changes:

```
git fetch edgeware
git merge edgeware/master
```

To build the node and runtime, follow the instructions in [edgeware-node](https://github.com/hicommonwealth/edgeware-node).
