## xpcproxy

> `/usr/libexec/xpcproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9a90` | `0x9a98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT.__dof_launchd`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Functions:
~ sub_100006c34 : 220 -> 224
~ sub_100006d10 -> sub_100006d14 : 608 -> 612
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Sat Aug  8 16:39:58 PDT 2026; root:libxpc_executables-3298.2.1~23/xpcproxy/RELEASE_ARM64E"
+ "Darwin Bootstrapper Trampoline Version 7.0.0: Sat Aug  8 16:39:58 PDT 2026; root:libxpc_executables-3298.2.1~23/xpcproxy/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Sat Aug  8 19:40:41 PDT 2026; root:libxpc_executables-3298.2.1~26/xpcproxy/RELEASE_ARM64E"
- "Darwin Bootstrapper Trampoline Version 7.0.0: Sat Aug  8 19:40:41 PDT 2026; root:libxpc_executables-3298.2.1~26/xpcproxy/RELEASE_ARM64E"
```
