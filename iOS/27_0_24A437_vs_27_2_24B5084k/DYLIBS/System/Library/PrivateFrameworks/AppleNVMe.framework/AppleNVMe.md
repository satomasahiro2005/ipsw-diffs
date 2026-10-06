## AppleNVMe

> `/System/Library/PrivateFrameworks/AppleNVMe.framework/AppleNVMe`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22d0` | `0x23cc` | **`+0xfc`** |
| `__AUTH_CONST.__cfstring` | `0x140` | `0x180` | **`+0x40`** |
| `__TEXT.__cstring` | `0xbaa` | `0xbd2` | **`+0x28`** |

### Other Changes

```diff

-877.0.7.0.0
+877.40.5.0.0

-  Functions: 86
-  Symbols:   90
-  CStrings:  95
+  Functions: 87
+  Symbols:   92
+  CStrings:  97
Symbols:
+ _AppleNVMeGetSanitizeStatus
+ _IORegistryEntrySetCFProperties
Functions:
+ _AppleNVMeGetSanitizeStatus
CStrings:
+ "Sanitize Status SSTAT"
+ "sanitize-counters"
```
