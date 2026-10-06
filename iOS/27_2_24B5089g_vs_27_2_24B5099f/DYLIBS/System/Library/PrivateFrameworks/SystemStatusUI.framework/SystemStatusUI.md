## SystemStatusUI

> `/System/Library/PrivateFrameworks/SystemStatusUI.framework/SystemStatusUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2ed8` | `0xa35d8` | **`+0x700`** |
| `__AUTH_CONST.__const` | `0x1428` | `0x14a8` | **`+0x80`** |
| `__TEXT.__const` | `0x3c18` | `0x3c78` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x53b0` | `0x53e8` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0xb104` | `0xb12c` | **`+0x28`** |
| `__TEXT.__cstring` | `0x2b5f` | `0x2b84` | **`+0x25`** |
| `__DATA_CONST.__const` | `0x1b18` | `0x1b38` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x280` | `0x2a0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xbd0` | `0xbe8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2610` | `0x2620` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x10a8` | `0x10b0` | **`+0x8`** |

### Other Changes

```diff

-288.1.3.100.0
+288.1.5.0.0

-  Functions: 4216
-  Symbols:   6978
-  CStrings:  624
+  Functions: 4223
+  Symbols:   6993
+  CStrings:  625
Symbols:
+ +[STUIStatusBarWirelessChargerView baseLayerColor]
+ +[STUIStatusBarWirelessChargerView chargingGradientBaseColor]
+ -[STUIStatusBarWirelessChargerView _drawUndefinedLevelInRect:gradient:boltColor:]
+ _CFAutorelease
+ _CGContextDrawLinearGradient
+ _CGGradientCreateWithColors
+ _ChargingGradient.locations
+ _STStatusBarDataWirelessChargerCapacityUnknown
+ _ThermallyLimitedGradient.locations
+ __OBJC_$_CLASS_METHODS_STUIStatusBarWirelessChargerView
+ ___50+[STUIStatusBarWirelessChargerView baseLayerColor]_block_invoke
+ ___50+[STUIStatusBarWirelessChargerView baseLayerColor]_block_invoke_2
+ ___61+[STUIStatusBarWirelessChargerView chargingGradientBaseColor]_block_invoke
+ ___61+[STUIStatusBarWirelessChargerView chargingGradientBaseColor]_block_invoke_2
+ ___block_descriptor_32_e36_"UIColor"16?0"UITraitCollection"8l
CStrings:
+ "@\"UIColor\"16@?0@\"UITraitCollection\"8"
```
