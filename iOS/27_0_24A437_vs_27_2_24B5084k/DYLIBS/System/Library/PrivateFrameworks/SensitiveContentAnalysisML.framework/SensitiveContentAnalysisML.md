## SensitiveContentAnalysisML

> `/System/Library/PrivateFrameworks/SensitiveContentAnalysisML.framework/SensitiveContentAnalysisML`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf830c` | `0xf9604` | **`+0x12f8`** |
| `__AUTH_CONST.__objc_const` | `0x5628` | `0x5778` | **`+0x150`** |
| `__TEXT.__cstring` | `0x3d76` | `0x3e76` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x1ee3` | `0x1fd3` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x4460` | `0x4534` | **`+0xd4`** |
| `__TEXT.__objc_methlist` | `0x1e54` | `0x1ec4` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x2d0` | `0x320` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x50d0` | `0x5108` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x19c0` | `0x19e8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1168` | `0x1190` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x29a7` | `0x29cd` | **`+0x26`** |
| `__TEXT.__swift5_reflstr` | `0x1149` | `0x1169` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x2570` | `0x2588` | **`+0x18`** |
| `__TEXT.__const` | `0x1156c` | `0x1157c` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x8c98` | `0x8ca8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2f4` | `0x300` | **`+0xc`** |
| `__AUTH_CONST.__const` | `0xa5b8` | `0xa5c0` | **`+0x8`** |
| `__DATA.__data` | `0x27e0` | `0x27e8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x8e0` | `0x8e8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x258` | `0x260` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x120` | `0x128` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x1f68` | `0x1f70` | **`+0x8`** |

### Other Changes

```diff

-165.2.0.0.0
+165.4.0.0.0

-  Functions: 6252
-  Symbols:   3885
-  CStrings:  795
+  Functions: 6265
+  Symbols:   3906
+  CStrings:  803
Symbols:
+ -[SCMLImageSanitization forceNonRegionalSafe:]
+ -[SCMLTextSanitization forceNonRegionalSafe:]
+ -[SCMLTextSanitization rawAdapterViolationLabels]
+ -[SCMLTextSanitization setRawAdapterViolationLabels:]
+ -[SCMLTextSanitizationRawLabel .cxx_destruct]
+ -[SCMLTextSanitizationRawLabel category]
+ -[SCMLTextSanitizationRawLabel initWithCategory:severity:]
+ -[SCMLTextSanitizationRawLabel severity]
+ _OBJC_CLASS_$_SCMLTextSanitizationRawLabel
+ _OBJC_IVAR_$_SCMLTextSanitization._rawAdapterViolationLabels
+ _OBJC_IVAR_$_SCMLTextSanitizationRawLabel._category
+ _OBJC_IVAR_$_SCMLTextSanitizationRawLabel._severity
+ _OBJC_METACLASS_$_SCMLTextSanitizationRawLabel
+ __OBJC_$_INSTANCE_METHODS_SCMLTextSanitizationRawLabel
+ __OBJC_$_INSTANCE_VARIABLES_SCMLTextSanitizationRawLabel
+ __OBJC_$_PROP_LIST_SCMLTextSanitizationRawLabel
+ __OBJC_CLASS_RO_$_SCMLTextSanitizationRawLabel
+ __OBJC_METACLASS_RO_$_SCMLTextSanitizationRawLabel
+ ___swift_memcpy42_8
+ _objc_sync_enter
+ _objc_sync_exit
+ _symbolic SaySo28SCMLTextSanitizationRawLabelCG
- ___swift_memcpy34_8
CStrings:
+ "SCMLImageSanitizer result has been overridden to safe=%{bool}d"
+ "SCMLTextSanitizer result has been overridden to safe=%{bool}d"
+ "Safety config useCase=%{public}s matchedPattern=%{public}s label=%{sensitive}s level=%{sensitive}s"
+ "imageSanitizer.override.nonRegional.input.safe"
+ "imageSanitizer.override.nonRegional.output.safe"
+ "nil (no matching entry had this label)"
+ "textSanitizer.override.nonRegional.input.safe"
+ "textSanitizer.override.nonRegional.output.safe"
```
