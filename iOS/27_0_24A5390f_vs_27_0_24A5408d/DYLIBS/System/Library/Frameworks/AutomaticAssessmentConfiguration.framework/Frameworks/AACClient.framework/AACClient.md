## AACClient

> `/System/Library/Frameworks/AutomaticAssessmentConfiguration.framework/Frameworks/AACClient.framework/AACClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21c90` | `0x22894` | **`+0xc04`** |
| `__AUTH_CONST.__objc_const` | `0x3168` | `0x32e8` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0x1348` | `0x1408` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0xbe0` | `0xc60` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0xf9b` | `0x101b` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x18b8` | `0x1918` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x3d0` | `0x410` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x7b8` | `0x7f8` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0xbc8` | `0xbf8` | **`+0x30`** |
| `__DATA.__data` | `0x13d0` | `0x13f0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xa18` | `0xa38` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xe4` | `0xf4` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-56.0.0.0.0
+56.0.3.0.0

-  Functions: 1387
-  Symbols:   947
+  Functions: 1435
+  Symbols:   959
Symbols:
+ -[AECAssessmentConfigurationWrapper _allowsAccessibilityIntelligence]
+ -[AECAssessmentConfigurationWrapper _allowsVisualIntelligence]
+ -[AECAssessmentConfigurationWrapper allowVirtualMachine]
+ -[AECAssessmentConfigurationWrapper allowsForceQuit]
+ -[AECAssessmentConfigurationWrapper setAllowVirtualMachine:]
+ -[AECAssessmentConfigurationWrapper setAllowsForceQuit:]
+ -[AECAssessmentConfigurationWrapper set_allowsAccessibilityIntelligence:]
+ -[AECAssessmentConfigurationWrapper set_allowsVisualIntelligence:]
+ _OBJC_IVAR_$_AECAssessmentConfigurationWrapper.__allowsAccessibilityIntelligence
+ _OBJC_IVAR_$_AECAssessmentConfigurationWrapper.__allowsVisualIntelligence
+ _OBJC_IVAR_$_AECAssessmentConfigurationWrapper._allowVirtualMachine
+ _OBJC_IVAR_$_AECAssessmentConfigurationWrapper._allowsForceQuit
+ _keypath_get.114Tm
+ _keypath_get.56Tm
+ _keypath_set.113Tm
+ _keypath_set.57Tm
- _keypath_get.110Tm
- _keypath_get.52Tm
- _keypath_set.109Tm
- _keypath_set.53Tm
```
