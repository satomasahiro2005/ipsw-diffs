## MobileActivationMigrator

> `/System/Library/DataClassMigrators/MobileActivationMigrator.migrator/MobileActivationMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3424` | `0x3451` | **`+0x2d`** |
| `__DATA_CONST.__cfstring` | `0x5200` | `0x5220` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x588` | `0x5a0` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x1028` | `0x1030` | **`+0x8`** |
| `__TEXT.__text` | `0x2d68` | `0x2d60` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1137.0.0.0.0
+1144.0.0.0.0

-  Symbols:   767
-  CStrings:  833
+  Symbols:   768
+  CStrings:  834
Symbols:
+ _kMAEnhancedActivationValidationBootSessionUUID
Functions:
~ _formatURLRequest : 616 -> 612
~ _formatURLResponse : 544 -> 540
CStrings:
+ "EnhancedActivationValidationBootSessionUUID"
+ "inboxupdaterd"
- "inboxupaterd"
```
