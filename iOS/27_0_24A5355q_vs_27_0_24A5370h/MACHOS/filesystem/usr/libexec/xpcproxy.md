## xpcproxy

> `/usr/libexec/xpcproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x98a8` | `0x9948` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x1696` | `0x1712` | **`+0x7c`** |
| `__TEXT.__auth_stubs` | `0xb00` | `0xb10` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x580` | `0x588` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__os_assumes_log`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__dof_launchd`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3295.0.0.502.1
+3298.0.4.502.1

-  Symbols:   199
-  CStrings:  297
+  Symbols:   200
+  CStrings:  298
Symbols:
+ _posix_spawnattr_set_shared_region_config_np
Functions:
~ sub_100001ee4 : 7900 -> 8068
~ sub_100003e28 -> sub_100003ed0 : 160 -> 164
~ sub_1000040a0 -> sub_10000414c : 720 -> 716
~ sub_100005ad8 -> sub_100005b80 : 596 -> 600
~ sub_100006b1c -> sub_100006bc8 : 592 -> 608
~ sub_100006d6c -> sub_100006e28 : 3060 -> 3044
~ sub_100008478 -> sub_100008524 : 256 -> 252
~ sub_100008644 -> sub_1000086ec : 276 -> 272
~ sub_100008758 -> sub_1000087fc : 344 -> 340
~ sub_1000088b0 -> sub_100008950 : 268 -> 264
~ sub_100009c68 -> sub_100009d04 : 104 -> 108
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Wed Jun 17 22:26:53 PDT 2026; root:libxpc_executables-3298.0.4.502.1~2/xpcproxy/RELEASE_ARM64E"
+ "Darwin Bootstrapper Trampoline Version 7.0.0: Wed Jun 17 22:26:53 PDT 2026; root:libxpc_executables-3298.0.4.502.1~2/xpcproxy/RELEASE_ARM64E"
+ "assertion failure: \"posix_spawnattr_set_shared_region_config_np(&ctx->psattr, attr->ps_shared_region_config_flags)\" -> %llu"
- "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Tue May 26 21:31:49 PDT 2026; root:libxpc_executables-3295.0.0.502.1~1/xpcproxy/RELEASE_ARM64E"
- "Darwin Bootstrapper Trampoline Version 7.0.0: Tue May 26 21:31:49 PDT 2026; root:libxpc_executables-3295.0.0.502.1~1/xpcproxy/RELEASE_ARM64E"
```
