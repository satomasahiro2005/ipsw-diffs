## xpcproxy

> `/usr/libexec/xpcproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9a98` | `0x9a68` | **`-0x30`** |
| `__TEXT.__cstring` | `0x1a4c` | `0x1a33` | **`-0x19`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__os_assumes_log`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__dof_launchd`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3298.2.1.0.0
+3298.40.20.0.0

-  CStrings:  302
+  CStrings:  301
Functions:
~ sub_100001278 : 2792 -> 2744
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Fri Sep  4 20:50:56 PDT 2026; root:libxpc_executables-3298.40.20~24/xpcproxy/RELEASE_ARM64E"
+ "Darwin Bootstrapper Trampoline Version 7.0.0: Fri Sep  4 20:50:56 PDT 2026; root:libxpc_executables-3298.40.20~24/xpcproxy/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Sat Aug  8 16:39:58 PDT 2026; root:libxpc_executables-3298.2.1~23/xpcproxy/RELEASE_ARM64E"
- "Darwin Bootstrapper Trampoline Version 7.0.0: Sat Aug  8 16:39:58 PDT 2026; root:libxpc_executables-3298.2.1~23/xpcproxy/RELEASE_ARM64E"
- "Unable to unpack bundle path"
```
