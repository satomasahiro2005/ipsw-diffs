## ReminderKit

> `/System/Library/PrivateFrameworks/ReminderKit.framework/ReminderKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13bd04` | `0x13bedc` | **`+0x1d8`** |
| `__AUTH_CONST.__cfstring` | `0xe620` | `0xe660` | **`+0x40`** |
| `__TEXT.__cstring` | `0xe500` | `0xe532` | **`+0x32`** |
| `__TEXT.__objc_methlist` | `0x15bc8` | `0x15bf0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x7b88` | `0x7ba0` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x24808` | `0x24818` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x2a40` | `0x2a48` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6ad0` | `0x6ad8` | **`+0x8`** |

### Other Changes

```diff

-4040.0.0.0.0
+4043.0.0.0.0

-  Functions: 8800
-  Symbols:   14297
-  CStrings:  2970
+  Functions: 8804
+  Symbols:   14302
+  CStrings:  2972
Symbols:
+ -[REMDaemonUserDefaults enableNaturalLanguageInput]
+ -[REMDaemonUserDefaults observeEnableNaturalLanguageInputWithBlock:]
+ -[REMDaemonUserDefaults setEnableNaturalLanguageInput:]
+ _REMSettingsNaturalLanguageInputIdentifier
+ ___68-[REMDaemonUserDefaults observeEnableNaturalLanguageInputWithBlock:]_block_invoke
CStrings:
+ "NATURAL_LANGUAGE_INPUT"
+ "enableNaturalLanguageInput"
```
