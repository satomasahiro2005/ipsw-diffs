## CallKit

> `/System/Library/Frameworks/CallKit.framework/CallKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x2300` | `0x1c20` | **`-0x6e0`** |
| `__DATA_DIRTY.__objc_data` | `0x5a0` | `0xc80` | **`+0x6e0`** |
| `__TEXT.__text` | `0x68358` | `0x68388` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x3cf6` | `0x3d16` | **`+0x20`** |

### Other Changes

```diff

-1406.200.51.2.1
+1406.200.62.0.0

-  CStrings:  1013
+  CStrings:  1014
Functions:
~ -[CXCallDirectoryStore migrateAllDataFromExtensionWithBundleID:toExtensionWithBundleID:error:] : 324 -> 372
CStrings:
+ "Executing application migration"
```
