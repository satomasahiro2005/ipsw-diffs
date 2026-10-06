## launchd

> `/sbin/launchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b820` | `0x5b82c` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__os_assumes_log`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__dof_launchd`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Functions:
~ sub_100017d48 : 476 -> 480
~ sub_10004eb70 -> sub_10004eb74 : 220 -> 224
~ sub_10004ec4c -> sub_10004ec54 : 608 -> 612
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sat Aug  8 16:38:05 PDT 2026; root:libxpc_executables-3298.2.1~23/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Sat Aug  8 16:38:05 PDT 2026; root:libxpc_executables-3298.2.1~23/launchd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sat Aug  8 19:38:49 PDT 2026; root:libxpc_executables-3298.2.1~26/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Sat Aug  8 19:38:49 PDT 2026; root:libxpc_executables-3298.2.1~26/launchd/RELEASE_ARM64E"
```
