## xpcproxy

> `/usr/libexec/xpcproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9a68` | `0x9a98` | **`+0x30`** |
| `__TEXT.__cstring` | `0x1a35` | `0x1a50` | **`+0x1b`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__os_assumes_log`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__dof_launchd`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3298.40.20.0.0
+3298.40.28.0.0

-  CStrings:  301
+  CStrings:  302
Functions:
~ sub_100001278 : 2744 -> 2792
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Sat Sep 26 06:08:35 PDT 2026; root:libxpc_executables-3298.40.28~39/xpcproxy/RELEASE_ARM64E"
+ "Darwin Bootstrapper Trampoline Version 7.0.0: Sat Sep 26 06:08:35 PDT 2026; root:libxpc_executables-3298.40.28~39/xpcproxy/RELEASE_ARM64E"
+ "Unable to unpack bundle path"
- "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Sun Sep 13 20:55:09 PDT 2026; root:libxpc_executables-3298.40.20~223/xpcproxy/RELEASE_ARM64E"
- "Darwin Bootstrapper Trampoline Version 7.0.0: Sun Sep 13 20:55:09 PDT 2026; root:libxpc_executables-3298.40.20~223/xpcproxy/RELEASE_ARM64E"
```
