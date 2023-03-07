# CGGMP Webassembly

Compiles the [cggmp-threshold-ecdsa][] library to webassembly using some forks which update dependencies to remove conflicts.

Once these PRs are merged then we can revert to the `webb-tools` versions:

1) https://github.com/webb-tools/multi-party-ecdsa/pull/14
2) https://github.com/webb-tools/fs-dkr/pull/12
3) https://github.com/webb-tools/cggmp-threshold-ecdsa/pull/13

[cggmp-threshold-ecdsa]: https://github.com/webb-tools/cggmp-threshold-ecdsa/
