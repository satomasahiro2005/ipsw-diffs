## SIMSetupUIService

> `/System/Library/AccessibilityBundles/SIMSetupUIService.axbundle/SIMSetupUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b0` | `0x9f8` | **`+0x148`** |
| `__TEXT.__cstring` | `0x1f4` | `0x229` | **`+0x35`** |
| `__DATA_CONST.__objc_selrefs` | `0xf0` | `0x120` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x40` | `0x68` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x60` | `0x70` | **`+0x10`** |
| `__TEXT.__const` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa0` | `0xa8` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 23
-  Symbols:   105
-  CStrings:  27
+  Functions: 24
+  Symbols:   112
+  CStrings:  28
Symbols:
+ _OBJC_CLASS_$_NSCharacterSet
+ _OBJC_CLASS_$_NSMutableAttributedString
+ __NSConcreteStackBlock
+ ___76-[TSDeviceInfoViewControllerAccessibility tableView:viewForHeaderInSection:]_block_invoke
+ ___block_descriptor_40_e8_32s_e52_v56?0"NSString"8{_NSRange=QQ}16{_NSRange=QQ}32^B48ls32l8
+ _objc_release_x24
+ _objc_release_x25
+ _objc_retain_x22
- _OBJC_CLASS_$_NSAttributedString
Functions:
~ -[TSDeviceInfoViewControllerAccessibility tableView:viewForHeaderInSection:] : 316 -> 320
+ ___76-[TSDeviceInfoViewControllerAccessibility tableView:viewForHeaderInSection:]_block_invoke
CStrings:
+ "v56@?0@\"NSString\"8{_NSRange=QQ}16{_NSRange=QQ}32^B48"
```
