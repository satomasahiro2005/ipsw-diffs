## AACCore

> `/System/Library/PrivateFrameworks/AACCore.framework/AACCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11c3c` | `0x11d1c` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x1989` | `0x19d5` | **`+0x4c`** |
| `__AUTH_CONST.__cfstring` | `0x15a0` | `0x15e0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x4740` | `0x4780` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1a3c` | `0x1a64` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xc80` | `0xc98` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x280` | `0x284` | **`+0x4`** |

### Other Changes

```diff

-50.0.0.0.0
+53.0.0.0.0

-  Functions: 606
-  Symbols:   1481
-  CStrings:  217
+  Functions: 609
+  Symbols:   1486
+  CStrings:  220
Symbols:
+ -[AEAssessmentIndividualConfiguration allowGracefulTermination]
+ -[AEAssessmentIndividualConfiguration setAllowGracefulTermination:]
+ -[AEPreferences sessionStartDelay]
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ _OBJC_IVAR_$_AEAssessmentIndividualConfiguration._allowGracefulTermination
CStrings:
+ "<%@: %p { allowsNetworkAccess = %@, required = %@, allowGracefulTermination = %@, allowedMenuItems = %@, configurationInfo = %@ }>"
+ "SessionStartDelay"
+ "allowGracefulTermination"
+ "i"
- "<%@: %p { allowsNetworkAccess = %@, required = %@, allowedMenuItems = %@, configurationInfo = %@ }>"
```
