## AskTo

> `/System/Library/PrivateFrameworks/AskTo.framework/AskTo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69a0` | `0x8618` | **`+0x1c78`** |
| `__TEXT.__eh_frame` | `0x5d4` | `0x6ac` | **`+0xd8`** |
| `__AUTH_CONST.__auth_got` | `0x408` | `0x488` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x177` | `0x1d3` | **`+0x5c`** |
| `__TEXT.__unwind_info` | `0x2c8` | `0x320` | **`+0x58`** |
| `__AUTH_CONST.__const` | `0x290` | `0x2e0` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x72` | `0xc2` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x298` | `0x2d8` | **`+0x40`** |
| `__TEXT.__const` | `0x3b8` | `0x3e8` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0xec` | `0x118` | **`+0x2c`** |
| `__DATA.__data` | `0x80` | `0xa8` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x1de` | `0x1bd` | **`-0x21`** |
| `__TEXT.__cstring` | `0x122` | `0x142` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xb8` | `0xd0` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x8c` | `0xa0` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x50` | `0x60` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0x80` | `0x90` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x40` | `0x4c` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x44` | `0x50` | **`+0xc`** |

### Other Changes

```diff

-88.0.0.0.0
+90.1.0.0.0

-  Functions: 185
-  Symbols:   187
-  CStrings:  14
+  Functions: 210
+  Symbols:   202
+  CStrings:  15
Symbols:
+ _OBJC_CLASS_$_NSLock
+ ___swift_closure_destructor.24Tm
+ __swift_implicitisolationactor_to_executor_cast
+ _bzero
+ _objc_retain_x21
+ _objc_retain_x22
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_release_x22
+ _swift_release_x24
+ _symbolic SDySSScCySb______pGG s5ErrorP
+ _symbolic ScCySb______pG s5ErrorP
+ _symbolic ScCySb______pGSg s5ErrorP
+ _symbolic So6NSLockC
+ _symbolic _____ySSScCySb______pGG s18_DictionaryStorageC s5ErrorP
- ___swift_closure_destructor.23Tm
- _objc_release_x27
CStrings:
+ "%s called. didSend: %{bool}d"
+ "sendAwaitingCompose(_:to:)"
- "%s called. ATDispatchCenter.delegate is %s. didSend: %{bool}d"
```
