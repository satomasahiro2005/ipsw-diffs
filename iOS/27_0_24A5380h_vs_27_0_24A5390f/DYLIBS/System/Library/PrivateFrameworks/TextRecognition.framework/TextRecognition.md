## TextRecognition

> `/System/Library/PrivateFrameworks/TextRecognition.framework/TextRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x212868` | `0x213310` | **`+0xaa8`** |
| `__TEXT.__eh_frame` | `0xa0fc` | `0xa244` | **`+0x148`** |
| `__TEXT.__unwind_info` | `0x84e8` | `0x8528` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1c0cb` | `0x1c0fb` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x5163` | `0x5193` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x2a14` | `0x29f2` | **`-0x22`** |
| `__TEXT.__const` | `0x7a10` | `0x7a30` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x77c` | `0x794` | **`+0x18`** |
| `__DATA.__data` | `0x15d0` | `0x15c0` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x3128` | `0x3118` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2108` | `0x2110` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x2b28` | `0x2b30` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x2d4` | `0x2dc` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x350` | `0x358` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0xacc` | `0xac8` | **`-0x4`** |

### Other Changes

```diff

-446.10.0.0.0
+446.11.0.0.0

-  Functions: 8688
+  Functions: 8698

-  CStrings:  11302
+  CStrings:  11304
Symbols:
+ _swift_conformsToProtocol2
- _symbolic So26CRMutableRecognitionResultCSg
CStrings:
+ "%s: image={w:%ld,h:%ld} features=%ld config=%s"
+ "document(image:textFeatures:configuration:)"
```
