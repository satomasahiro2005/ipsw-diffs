## CoreLocation

> `/System/Library/Frameworks/CoreLocation.framework/CoreLocation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x208954` | `0x208d18` | **`+0x3c4`** |
| `__TEXT.__cstring` | `0x2525f` | `0x252c7` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x3aeb6` | `0x3aef0` | **`+0x3a`** |
| `__TEXT.__objc_methlist` | `0x9cb4` | `0x9ce4` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x5338` | `0x5358` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xf188` | `0xf1a8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x5710` | `0x5730` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x104e0` | `0x104f0` | **`+0x10`** |

### Other Changes

```diff

-3186.0.17.0.1
+3186.0.21.0.0

-  Functions: 5240
+  Functions: 5244

-  CStrings:  5584
+  CStrings:  5586
CStrings:
+ "#Spi, _CLInternalClearLocationAuthorizationLoctool failed"
+ "-[CLLocationInternalClient clearLocationAuthorizationForLoctoolWithBundleId:orBundlePath:]_block_invoke"
+ "22:32:03"
+ "Sep 28 2026"
- "21:49:49"
- "Sep 15 2026"
```
