## xpcproxy

> `/usr/libexec/xpcproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9948` | `0x989c` | **`-0xac`** |
| `__TEXT.__oslogstring` | `0x1712` | `0x1696` | **`-0x7c`** |
| `__TEXT.__auth_stubs` | `0xb10` | `0xb00` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x588` | `0x580` | **`-0x8`** |
| `__TEXT.__cstring` | `0x19da` | `0x19d2` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__os_assumes_log`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__dof_launchd`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3298.0.4.502.1
+3298.0.10.0.0

-  Symbols:   200
-  CStrings:  298
+  Symbols:   199
+  CStrings:  297
Symbols:
- _posix_spawnattr_set_shared_region_config_np
Functions:
~ sub_100001ee4 : 8068 -> 7896
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Sat Jun 27 00:45:30 PDT 2026; root:libxpc_executables-3298.0.10~15/xpcproxy/RELEASE_ARM64E"
+ "Darwin Bootstrapper Trampoline Version 7.0.0: Sat Jun 27 00:45:30 PDT 2026; root:libxpc_executables-3298.0.10~15/xpcproxy/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Wed Jun 17 22:26:53 PDT 2026; root:libxpc_executables-3298.0.4.502.1~2/xpcproxy/RELEASE_ARM64E"
- "Darwin Bootstrapper Trampoline Version 7.0.0: Wed Jun 17 22:26:53 PDT 2026; root:libxpc_executables-3298.0.4.502.1~2/xpcproxy/RELEASE_ARM64E"
- "assertion failure: \"posix_spawnattr_set_shared_region_config_np(&ctx->psattr, attr->ps_shared_region_config_flags)\" -> %llu"
```
