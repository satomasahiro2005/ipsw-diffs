## VisionHealthAppPlugin

> `/System/Library/Health/FeedItemPlugins/VisionHealthAppPlugin.healthplugin/VisionHealthAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8fda0` | `0x8da84` | **`-0x231c`** |
| `__DATA.__bss` | `0x3f00` | `0x3c80` | **`-0x280`** |
| `__TEXT.__const` | `0x3930` | `0x37a0` | **`-0x190`** |
| `__TEXT.__cstring` | `0x45c7` | `0x44b7` | **`-0x110`** |
| `__TEXT.__unwind_info` | `0x17a8` | `0x1748` | **`-0x60`** |
| `__DATA.__data` | `0x23a8` | `0x2370` | **`-0x38`** |
| `__TEXT.__eh_frame` | `0x528` | `0x560` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0x1f0` | `0x1c0` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x29b4` | `0x2988` | **`-0x2c`** |
| `__AUTH_CONST.__const` | `0x2e59` | `0x2e31` | **`-0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x156c` | `0x1550` | **`-0x1c`** |
| `__TEXT.__swift5_typeref` | `0x12c3` | `0x12ad` | **`-0x16`** |
| `__TEXT.__swift5_builtin` | `0xa0` | `0x8c` | **`-0x14`** |
| `__TEXT.__swift5_proto` | `0x21c` | `0x208` | **`-0x14`** |
| `__AUTH_CONST.__auth_got` | `0x1598` | `0x15a0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x16c` | `0x168` | **`-0x4`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

-  Functions: 2290
+  Functions: 2265

-  CStrings:  473
+  CStrings:  470
Symbols:
+ _OBJC_CLASS_$_LSApplicationWorkspace
- _OBJC_CLASS_$_UIApplication
CStrings:
- "VisionHealthAppPlugin/VisionPrescriptionField+SectionedDataSourceItem.swift"
- "VisionHealthAppPlugin/VisionPrescriptionManualDataEntryHeaderDataSourceItem.swift"
- "VisionHealthAppPlugin/VisionPrescriptionManualDataEntryMeasurementFieldDataSource.swift"
```
