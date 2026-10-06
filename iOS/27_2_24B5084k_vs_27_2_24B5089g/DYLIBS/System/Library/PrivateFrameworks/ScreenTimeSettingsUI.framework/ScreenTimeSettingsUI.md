## ScreenTimeSettingsUI

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsUI.framework/ScreenTimeSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12b160` | `0x12b2a0` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x26230` | `0x262c0` | **`+0x90`** |
| `__AUTH.__objc_data` | `0x5278` | `0x52c8` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x70c8` | `0x70e8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xc84c` | `0xc864` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x14d0` | `0x14e0` | **`+0x10`** |
| `__TEXT.__const` | `0x3da4` | `0x3db4` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x7b0` | `0x7b8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x610` | `0x618` | **`+0x8`** |

### Other Changes

```diff

-655.1.6.1.0
+655.1.9.1.0

+  - /System/Library/PrivateFrameworks/HelpKit.framework/HelpKit

-  Functions: 6344
-  Symbols:   8522
+  Functions: 6345
+  Symbols:   8530
Symbols:
+ -[STDevicePINPane layoutSubviews]
+ _OBJC_CLASS_$_HLPHelpViewController
+ _OBJC_CLASS_$_STDevicePINPane
+ _OBJC_METACLASS_$_DevicePINPane
+ _OBJC_METACLASS_$_STDevicePINPane
+ _STChinaSKUHiddenBundleIdentifiers
+ __OBJC_$_INSTANCE_METHODS_STDevicePINPane
+ __OBJC_CLASS_RO_$_STDevicePINPane
+ __OBJC_METACLASS_RO_$_STDevicePINPane
- _STImagePlaygroundBundleIdentifiers
Functions:
~ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _openLearnMore] : 124 -> 232
+ -[STDevicePINPane layoutSubviews]
```
