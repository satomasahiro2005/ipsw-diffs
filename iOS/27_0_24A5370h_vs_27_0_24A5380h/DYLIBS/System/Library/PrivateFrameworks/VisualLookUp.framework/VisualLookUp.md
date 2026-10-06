## VisualLookUp

> `/System/Library/PrivateFrameworks/VisualLookUp.framework/VisualLookUp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0xbf28` | `0x15ab0` | **`+0x9b88`** |
| `__AUTH.__data` | `0xbef0` | `0x3538` | **`-0x89b8`** |
| `__AUTH.__objc_data` | `0x15f0` | `0x1b0` | **`-0x1440`** |
| `__DATA_DIRTY.__objc_data` | `0x1818` | `0x2c58` | **`+0x1440`** |
| `__DATA.__data` | `0xaa18` | `0x98c8` | **`-0x1150`** |
| `__TEXT.__text` | `0x4a9138` | `0x4a96a4` | **`+0x56c`** |
| `__DATA.__bss` | `0x48bb0` | `0x487b0` | **`-0x400`** |
| `__DATA_DIRTY.__bss` | `0xc310` | `0xc710` | **`+0x400`** |
| `__TEXT.__oslogstring` | `0x8704` | `0x88a4` | **`+0x1a0`** |
| `__AUTH_CONST.__const` | `0x143a8` | `0x14308` | **`-0xa0`** |
| `__TEXT.__swift5_capture` | `0x1bf0` | `0x1b50` | **`-0xa0`** |
| `__TEXT.__eh_frame` | `0x17f4c` | `0x17fc8` | **`+0x7c`** |
| `__TEXT.__unwind_info` | `0x111d0` | `0x11210` | **`+0x40`** |
| `__TEXT.__const` | `0x37940` | `0x37950` | **`+0x10`** |
| `__DATA.__common` | `0x738` | `0x730` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1340` | `0x1338` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x858` | `0x860` | **`+0x8`** |

### Other Changes

```diff

-6.0.10.0.0
+6.0.11.0.0

-  Functions: 25419
+  Functions: 25415

-  CStrings:  2901
+  CStrings:  2907
Symbols:
+ ___swift_closure_destructor.31Tm
+ ___swift_closure_destructor.43Tm
+ ___swift_closure_destructor.50Tm
+ _keypath_get.118Tm
+ _keypath_get.643Tm
- ___swift_closure_destructor.40Tm
- ___swift_closure_destructor.4Tm
- ___swift_closure_destructor.51Tm
- ___swift_closure_destructor.54Tm
- ___swift_closure_destructor.58Tm
CStrings:
+ "parseCameraFrame grounding[%ld]: primary='%s' topK=%s"
+ "parseCameraFrame: %ld grounding detection(s), allowedDomains=%s"
+ "toDetectedResults[pos=%ld]: primary='%s' → added, domain=%s"
+ "toDetectedResults[pos=%ld]: primary='%s' → skipped, not in configMap"
+ "toDetectedResults[pos=%ld]: topK[%ld]='%s' → added, domain=%s"
+ "toDetectedResults[pos=%ld]: topK[%ld]='%s' → skipped, not in configMap"
```
