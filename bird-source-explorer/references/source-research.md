# BIRD Source Research Guide

## Repositories

- GitHub mirror: `https://github.com/CZ-NIC/bird`
- Official GitLab: `https://gitlab.nic.cz/labs/bird`

Use the GitHub mirror for deepwiki / Context7 / GitHub search. If the mirror
lags, fall back to GitLab raw URLs.

## Useful search strategies

- **Find a keyword parser entry:** search `conf/` for the keyword string; it
  usually maps to a `CF_KEYWORD` macro.
- **Find a filter function:** look in `filter/f-inst.c` and `filter/filter.h`.
- **Find a BGP attribute:** look in `proto/bgp/attr.c` and `proto/bgp/packets.c`.
- **Find a protocol state machine:** look in `proto/<name>/<name>.c` for
  `static struct protocol` and `proto_*` callbacks.
- **Find an OS-specific helper:** search `sysdep/unix/` or `sysdep/linux/`.

## Version tags

When possible, pin source references to a tag:

- BIRD2: `v2.19.1`
- BIRD3: `v3.3.1`

Raw file URL pattern:

```
https://raw.githubusercontent.com/CZ-NIC/bird/v2.19.1/proto/bgp/attr.c
```
