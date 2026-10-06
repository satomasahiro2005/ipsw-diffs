## UARPKit

> `/System/Library/PrivateFrameworks/UARPKit.framework/UARPKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14184` | `0x14334` | **`+0x1b0`** |
| `__AUTH.__objc_data` | `0x370` | `0x1e0` | **`-0x190`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x190` | **`+0x190`** |
| `__TEXT.__oslogstring` | `0x742` | `0x8a3` | **`+0x161`** |
| `__AUTH_CONST.__objc_const` | `0x1ea8` | `0x1e88` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x418` | `0x420` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x190` | `0x18c` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1587.0.3.0.3
+1587.0.21.0.0

-  Functions: 512
-  Symbols:   777
-  CStrings:  240
+  Functions: 516
+  Symbols:   776
+  CStrings:  249
Symbols:
+ -[UARPDevice handleDeviceUnresponsive]
+ GCC_except_table35
- -[UARPDevice deactivate]
- GCC_except_table36
- _OBJC_IVAR_$_UARPDevice._deactivated
CStrings:
+ "%s: Not available %@"
+ "%s: device (and transport) are now unavailable %@"
+ "%s: device already unavailable %@"
+ "%s: device not available %@"
+ "%s: device not available ?? %@"
+ "%s: device not available, cannot plumb transport %@"
+ "%s: device not available, cannot plumb transporte %@"
+ "%s: transport already available %@"
+ "%s: transport already unavailable %@"
+ "%s: transport not available %@"
- "%s: DEACTIVATED %@"
```
