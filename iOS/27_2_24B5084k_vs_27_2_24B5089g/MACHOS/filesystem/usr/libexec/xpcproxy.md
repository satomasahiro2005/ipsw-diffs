## xpcproxy

> `/usr/libexec/xpcproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1a33` | `0x1a35` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__dof_launchd`

### Other Changes

```diff
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Sun Sep 13 20:55:09 PDT 2026; root:libxpc_executables-3298.40.20~223/xpcproxy/RELEASE_ARM64E"
+ "Darwin Bootstrapper Trampoline Version 7.0.0: Sun Sep 13 20:55:09 PDT 2026; root:libxpc_executables-3298.40.20~223/xpcproxy/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Fri Sep  4 20:50:56 PDT 2026; root:libxpc_executables-3298.40.20~24/xpcproxy/RELEASE_ARM64E"
- "Darwin Bootstrapper Trampoline Version 7.0.0: Fri Sep  4 20:50:56 PDT 2026; root:libxpc_executables-3298.40.20~24/xpcproxy/RELEASE_ARM64E"
```
