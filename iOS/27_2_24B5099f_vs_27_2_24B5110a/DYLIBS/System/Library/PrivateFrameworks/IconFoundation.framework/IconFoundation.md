## IconFoundation

> `/System/Library/PrivateFrameworks/IconFoundation.framework/IconFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39e18` | `0x3a1a0` | **`+0x388`** |
| `__AUTH_CONST.__const` | `0x8a8` | `0x8c8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x12cd8` | `0x12cf8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x31b4` | `0x31d4` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f48` | `0x1f60` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x4e38` | `0x4e48` | **`+0x10`** |
| `__DATA.__bss` | `0x2d8` | `0x2e8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xf40` | `0xf48` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 1553
-  Symbols:   2564
-  CStrings:  2890
+  Functions: 1558
+  Symbols:   2570
+  CStrings:  2891
Symbols:
+ +[IFIconSpecification(Constructors) homeAccessoryAppIconSpecification]
+ -[IFDeviceInfo _isForceHomeAccessoryDeviceEnabled]
+ -[IFDeviceInfo isHomeAccessoryDevice]
+ ___70+[IFIconSpecification(Constructors) homeAccessoryAppIconSpecification]_block_invoke
+ _homeAccessoryAppIconSpecification.iconSpecification
+ _homeAccessoryAppIconSpecification.onceToken
CStrings:
+ "force_home_accessory_device"
```
