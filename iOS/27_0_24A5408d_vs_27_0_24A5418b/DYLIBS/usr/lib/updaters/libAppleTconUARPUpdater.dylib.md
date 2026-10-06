## libAppleTconUARPUpdater.dylib

> `/usr/lib/updaters/libAppleTconUARPUpdater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x71424` | `0x71230` | **`-0x1f4`** |
| `__DATA_CONST.__const` | `0xdd0` | `0xdf8` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x14` | `0x3c` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0xd2b8` | `0xd2d8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1aa0` | `0x1ac0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x3d8` | `0x3f0` | **`+0x18`** |
| `__TEXT.__cstring` | `0x7763` | `0x7771` | **`+0xe`** |
| `__DATA.__objc_ivar` | `0x8b4` | `0x8b8` | **`+0x4`** |

### Other Changes

```diff

-1587.2.2.0.0
+1587.2.3.0.0

-  Functions: 2948
-  Symbols:   4834
+  Functions: 2950
+  Symbols:   4843
Symbols:
+ GCC_except_table21
+ GCC_except_table23
+ _OBJC_IVAR_$_UARPEndpointLayer3._kInternalQueueKey
+ ___35-[UARPEndpointLayer3 configuration]_block_invoke
+ ___41-[UARPEndpointLayer3 directConfiguration]_block_invoke
+ ___block_descriptor_48_e8_32s40r_e5_v8?0lr40l8s32l8
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
+ _objc_retainBlock
CStrings:
+ "-[UARPEndpointLayer3 directConfiguration]_block_invoke"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xb31"
- "-[UARPEndpointLayer3 directConfiguration]"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xa31"
```
