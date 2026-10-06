## AppleIDSetup

> `/System/Library/PrivateFrameworks/AppleIDSetup.framework/AppleIDSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x219a88` | `0x219ca0` | **`+0x218`** |
| `__TEXT.__cstring` | `0x38a3` | `0x38f3` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x4e00` | `0x4e40` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x1110c` | `0x11134` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x7060` | `0x7080` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x81d4` | `0x81ec` | **`+0x18`** |
| `__AUTH.__data` | `0x3638` | `0x3628` | **`-0x10`** |
| `__AUTH.__objc_data` | `0x1ef8` | `0x1f08` | **`+0x10`** |
| `__DATA.__data` | `0x9880` | `0x9890` | **`+0x10`** |
| `__TEXT.__const` | `0x2cae0` | `0x2caf0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xb28` | `0xb18` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0x87fc` | `0x8804` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa358` | `0xa360` | **`+0x8`** |

### Other Changes

```diff

-129.125.3.0.0
+129.125.6.1.0

-  Functions: 14027
+  Functions: 14024

-  CStrings:  873
+  CStrings:  875
Symbols:
+ ___swift_closure_destructor.155Tm
+ ___swift_closure_destructor.42Tm
+ ___swift_closure_destructor.51Tm
- ___swift_closure_destructor.154Tm
- ___swift_closure_destructor.41Tm
- ___swift_closure_destructor.50Tm
CStrings:
+ "DEVICE_GENERIC_NAME"
+ "SetupCoordinatedAckFromReceiveClosure"
```
