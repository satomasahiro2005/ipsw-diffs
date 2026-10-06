## LiveTranscription

> `/System/Library/PrivateFrameworks/LiveTranscription.framework/LiveTranscription`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31b64` | `0x33818` | **`+0x1cb4`** |
| `__TEXT.__eh_frame` | `0xb80` | `0xdc0` | **`+0x240`** |
| `__TEXT.__oslogstring` | `0x2bbd` | `0x2d3d` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0xa70` | `0xaf8` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0xbb0` | `0xc28` | **`+0x78`** |
| `__TEXT.__const` | `0x990` | `0x9d0` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x378` | `0x3ac` | **`+0x34`** |
| `__TEXT.__swift_as_ret` | `0x78` | `0x98` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x78` | `0x94` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0x70` | `0x88` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x418` | `0x42c` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x8f8` | `0x900` | **`+0x8`** |

### Other Changes

```diff

-591.4.2.0.0
+591.4.4.0.0

-  Functions: 1008
-  Symbols:   1175
-  CStrings:  301
+  Functions: 1034
+  Symbols:   1177
+  CStrings:  307
Symbols:
+ ___swift_closure_destructor.133Tm
+ ___swift_closure_destructor.13Tm
+ ___swift_closure_destructor.22Tm
+ ___swift_closure_destructor.31Tm
+ _swift_retain_x26
+ _symbolic SdIegy_
+ _symbolic SdytIegnr_
- ___swift_closure_destructor.10Tm
- ___swift_closure_destructor.130Tm
- ___swift_closure_destructor.19Tm
- ___swift_closure_destructor.28Tm
- _swift_release_x28
CStrings:
+ "TranscriberV2: areAssetsInstalled: %{bool}d for locale: %s"
+ "TranscriberV2: asset download progress: %f for locale: %s"
+ "TranscriberV2: assets already installed for locale: %s"
+ "TranscriberV2: assets installed for locale: %s"
+ "TranscriberV2: downloading assets for locale: %s"
+ "TranscriberV2: no installation request, asset present for locale: %s"
```
