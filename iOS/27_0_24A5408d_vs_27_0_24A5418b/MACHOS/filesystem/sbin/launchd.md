## launchd

> `/sbin/launchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x16a38` | `0x16a2c` | **`-0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__dof_launchd`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3298.0.26.502.1
+3298.2.1.0.0
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sat Aug  8 19:38:49 PDT 2026; root:libxpc_executables-3298.2.1~26/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Sat Aug  8 19:38:49 PDT 2026; root:libxpc_executables-3298.2.1~26/launchd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Wed Aug  5 00:07:47 PDT 2026; root:libxpc_executables-3298.0.26.502.1~2/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Wed Aug  5 00:07:47 PDT 2026; root:libxpc_executables-3298.0.26.502.1~2/launchd/RELEASE_ARM64E"
```
