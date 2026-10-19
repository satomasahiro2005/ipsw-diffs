## launchd

> `/sbin/launchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x16984` | `0x16986` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Wed Oct  7 23:41:26 PDT 2026; root:libxpc_executables-3298.42.1~13/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Wed Oct  7 23:41:26 PDT 2026; root:libxpc_executables-3298.42.1~13/launchd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sat Oct  3 23:05:26 PDT 2026; root:libxpc_executables-3298.42.1~6/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Sat Oct  3 23:05:26 PDT 2026; root:libxpc_executables-3298.42.1~6/launchd/RELEASE_ARM64E"
```
