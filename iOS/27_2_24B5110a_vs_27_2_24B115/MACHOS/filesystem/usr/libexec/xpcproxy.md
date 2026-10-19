## xpcproxy

> `/usr/libexec/xpcproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1a4c` | `0x1a4e` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__dof_launchd`

### Other Changes

```diff
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Wed Oct  7 23:43:14 PDT 2026; root:libxpc_executables-3298.42.1~13/xpcproxy/RELEASE_ARM64E"
+ "Darwin Bootstrapper Trampoline Version 7.0.0: Wed Oct  7 23:43:14 PDT 2026; root:libxpc_executables-3298.42.1~13/xpcproxy/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Sat Oct  3 23:07:12 PDT 2026; root:libxpc_executables-3298.42.1~6/xpcproxy/RELEASE_ARM64E"
- "Darwin Bootstrapper Trampoline Version 7.0.0: Sat Oct  3 23:07:12 PDT 2026; root:libxpc_executables-3298.42.1~6/xpcproxy/RELEASE_ARM64E"
```
