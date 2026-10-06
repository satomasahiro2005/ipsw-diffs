## TVRemoteCore

> `/System/Library/PrivateFrameworks/TVRemoteCore.framework/TVRemoteCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4880c` | `0x48918` | **`+0x10c`** |
| `__DATA_CONST.__const` | `0x1638` | `0x1660` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0xb14` | `0xb28` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x1210` | `0x1220` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3100` | `0x3108` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x6528` | `0x6530` | **`+0x8`** |

### Other Changes

```diff

-627.10.45.0.0
+627.10.47.0.0

-  Functions: 2142
-  Symbols:   3710
+  Functions: 2144
+  Symbols:   3714
Symbols:
+ -[TVRCXPCClient _beginDeviceQueryWithResponse:]
+ GCC_except_table20
+ GCC_except_table52
+ ___47-[TVRCXPCClient _beginDeviceQueryWithResponse:]_block_invoke
+ ___47-[TVRCXPCClient _beginDeviceQueryWithResponse:]_block_invoke_2
+ ___block_descriptor_48_e8_32bs40r_e8_v12?0B8lr40l8s32l8
- GCC_except_table50
- ___46-[TVRCXPCClient beginDeviceQueryWithResponse:]_block_invoke_2
```
