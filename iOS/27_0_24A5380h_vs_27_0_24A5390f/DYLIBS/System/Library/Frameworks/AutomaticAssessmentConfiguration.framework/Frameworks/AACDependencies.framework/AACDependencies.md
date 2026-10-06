## AACDependencies

> `/System/Library/Frameworks/AutomaticAssessmentConfiguration.framework/Frameworks/AACDependencies.framework/AACDependencies`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0xaf0` | `0xb20` | **`+0x30`** |
| `__TEXT.__text` | `0x1c88` | `0x1cac` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x408` | `0x420` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x35c` | `0x374` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x68` | `0x6c` | **`+0x4`** |

### Other Changes

```diff

-55.0.0.0.0
+56.0.0.0.0

-  Functions: 71
-  Symbols:   262
+  Functions: 73
+  Symbols:   265
Symbols:
+ -[AEDSingleAppModeConfiguration allowsAutoCapitalization]
+ -[AEDSingleAppModeConfiguration setAllowsAutoCapitalization:]
+ _OBJC_IVAR_$_AEDSingleAppModeConfiguration._allowsAutoCapitalization
```
