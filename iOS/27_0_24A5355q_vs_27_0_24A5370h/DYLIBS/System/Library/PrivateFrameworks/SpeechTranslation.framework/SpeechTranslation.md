## SpeechTranslation

> `/System/Library/PrivateFrameworks/SpeechTranslation.framework/SpeechTranslation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x2ab5` | `0x2b75` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0xe50` | `0xd98` | **`-0xb8`** |
| `__TEXT.__text` | `0x32460` | `0x324f4` | **`+0x94`** |
| `__TEXT.__swift_as_cont` | `0x114` | `0xc4` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0xcf8` | `0xcc0` | **`-0x38`** |
| `__TEXT.__const` | `0xcbc` | `0xc8c` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x2458` | `0x2478` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xbc0` | `0xba8` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x450` | `0x460` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xa88` | `0xa98` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x58` | `0x48` | **`-0x10`** |

### Other Changes

```diff

-380.1.0.0.0
+384.1.0.0.0

-  Functions: 1029
-  Symbols:   1053
-  CStrings:  277
+  Functions: 1001
+  Symbols:   1051
+  CStrings:  281
Symbols:
+ _OBJC_CLASS_$__LTNullableLocalePair
+ ___swift_closure_destructor.108Tm
+ ___swift_closure_destructor.117Tm
+ ___swift_closure_destructor.74Tm
+ _swift_retain_x22
- ___swift_closure_destructor.124Tm
- ___swift_closure_destructor.133Tm
- ___swift_closure_destructor.89Tm
- _objc_retain_x27
- _swift_asyncLet_begin
- _swift_asyncLet_finish
- _swift_asyncLet_get
CStrings:
+ "ASR model version for feedback: %{public}s"
+ "ASR model version unavailable on output"
+ "Cached ASR model version: %{public}s"
+ "Model version in feedback: %{public}s"
```
