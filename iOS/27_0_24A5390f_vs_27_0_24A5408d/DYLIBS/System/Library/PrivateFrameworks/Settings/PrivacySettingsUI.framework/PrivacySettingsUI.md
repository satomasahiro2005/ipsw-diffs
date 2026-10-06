## PrivacySettingsUI

> `/System/Library/PrivateFrameworks/Settings/PrivacySettingsUI.framework/PrivacySettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6773c` | `0x677dc` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x3350` | `0x3368` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x4274` | `0x4284` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xa78` | `0xa80` | **`+0x8`** |

### Other Changes

```diff

-2027.0.4.0.0
+2027.0.6.101.0

-  Functions: 2126
-  Symbols:   3696
+  Functions: 2127
+  Symbols:   3698
Symbols:
+ +[PUIReportSensorManager legacyIconCacheKeyForCategory:]
+ _OBJC_CLASS_$_PKIconImageCache
Functions:
~ -[PUIReportSensorAppController specifiers] : 1540 -> 1692
+ +[PUIReportSensorManager legacyIconCacheKeyForCategory:]
```
