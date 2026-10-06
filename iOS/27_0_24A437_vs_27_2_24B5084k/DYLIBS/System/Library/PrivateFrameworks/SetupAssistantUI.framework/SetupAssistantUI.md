## SetupAssistantUI

> `/System/Library/PrivateFrameworks/SetupAssistantUI.framework/SetupAssistantUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x237f8` | `0x23920` | **`+0x128`** |
| `__AUTH_CONST.__cfstring` | `0x7c0` | `0x800` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x59a8` | `0x59d8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x8c7` | `0x8f7` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x36a0` | `0x36c8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2428` | `0x2440` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x2a0` | `0x2a4` | **`+0x4`** |

### Other Changes

```diff

-5411.101.0.0.0
+5411.103.0.0.0

-  Functions: 928
-  Symbols:   1977
-  CStrings:  209
+  Functions: 931
+  Symbols:   1981
+  CStrings:  211
Symbols:
+ -[BFFFaceIDViewController _detailText]
+ -[BFFFaceIDViewController setShowsAdultAgeVerificationDetail:]
+ -[BFFFaceIDViewController showsAdultAgeVerificationDetail]
+ GCC_except_table27
+ _OBJC_IVAR_$_BFFFaceIDViewController._showsAdultAgeVerificationDetail
- GCC_except_table26
CStrings:
+ "%@\n\n%@"
+ "FACE_ID_ADULT_AGE_VERIFICATION_DETAIL"
```
