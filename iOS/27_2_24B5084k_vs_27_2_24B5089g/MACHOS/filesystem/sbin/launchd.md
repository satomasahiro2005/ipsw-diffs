## launchd

> `/sbin/launchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x168c4` | `0x168c6` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`

### Other Changes

```diff
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sun Sep 13 20:53:38 PDT 2026; root:libxpc_executables-3298.40.20~223/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Sun Sep 13 20:53:38 PDT 2026; root:libxpc_executables-3298.40.20~223/launchd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Fri Sep  4 20:49:10 PDT 2026; root:libxpc_executables-3298.40.20~24/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Fri Sep  4 20:49:10 PDT 2026; root:libxpc_executables-3298.40.20~24/launchd/RELEASE_ARM64E"
```
