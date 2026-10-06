## AccessibilitySettings

> `/System/Library/NanoPreferenceBundles/General/AccessibilitySettings.bundle/AccessibilitySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x386e4` | `0x38b2c` | **`+0x448`** |
| `__AUTH_CONST.__objc_intobj` | `0x3a8` | `0x3f0` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x4ae0` | `0x4b20` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x266` | `0x29f` | **`+0x39`** |
| `__TEXT.__cstring` | `0x4445` | `0x4477` | **`+0x32`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b90` | `0x1bb8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x2960` | `0x2988` | **`+0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xd8` | `0xf0` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0xf0` | `0x108` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x9c0` | `0x9d0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xce8` | `0xcf8` | **`+0x10`** |
| `__TEXT.__const` | `0x410` | `0x418` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 1051
-  Symbols:   2041
-  CStrings:  651
+  Functions: 1054
+  Symbols:   2046
+  CStrings:  655
Symbols:
+ -[AXSiriSettingsController _currentAccessibleEndpointer]
+ -[AXSiriSettingsController _shouldHideTypeToSiri]
+ -[AXSiriSettingsController setAccessibleEndpointer:]
+ GCC_except_table824
+ _OBJC_CLASS_$_AFSystemAssistantExperienceStatusManager
+ _kAXSWatchSiriEndpointerThresholdPreference
- GCC_except_table821
CStrings:
+ "SIRI_ENDPOINTER_FOOTER_TEXT"
+ "SIRI_ENDPOINTER_TITLE"
+ "[TypeToSiri] Siri AI enabled"
+ "[TypeToSiri] shouldHide: %i"
```
