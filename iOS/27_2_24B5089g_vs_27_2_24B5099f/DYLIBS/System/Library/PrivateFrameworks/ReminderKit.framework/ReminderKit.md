## ReminderKit

> `/System/Library/PrivateFrameworks/ReminderKit.framework/ReminderKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13c314` | `0x13c3ac` | **`+0x98`** |
| `__AUTH_CONST.__cfstring` | `0xe6a0` | `0xe6c0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x15c40` | `0x15c60` | **`+0x20`** |
| `__TEXT.__cstring` | `0xe5c9` | `0xe5e7` | **`+0x1e`** |
| `__AUTH_CONST.__objc_const` | `0x24848` | `0x24860` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x7bd0` | `0x7be8` | **`+0x18`** |

### Other Changes

```diff

-4077.0.0.0.0
+4079.0.0.0.0

-  Functions: 8810
-  Symbols:   14312
-  CStrings:  2976
+  Functions: 8812
+  Symbols:   14314
+  CStrings:  2977
Symbols:
+ -[REMDaemonUserDefaults disableWindowStateRestoration]
+ -[REMDaemonUserDefaults setDisableWindowStateRestoration:]
CStrings:
+ "disableWindowStateRestoration"
```
