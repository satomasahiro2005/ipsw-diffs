## TextToSpeech

> `/System/Library/PrivateFrameworks/TextToSpeech.framework/TextToSpeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34ad40` | `0x34b5a4` | **`+0x864`** |
| `__TEXT.__eh_frame` | `0x17380` | `0x173d0` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x179d0` | `0x179f8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xcaa8` | `0xcad0` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x3310` | `0x3330` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x1268` | `0x126c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xdd0` | `0xdd4` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-727.3.1.0.0
+727.3.2.0.0

-  Functions: 16102
+  Functions: 16110
CStrings:
+ "(?:[0-9A-Fa-f]{1,4}:){7}[0-9A-Fa-f]{1,4}|(?:[0-9A-Fa-f]{1,4}:)+:(?:[0-9A-Fa-f]{1,4}:?)*[0-9A-Fa-f]{0,4}|::(?:[0-9A-Fa-f]{1,4}:?)+[0-9A-Fa-f]{0,4}"
- "(?:[0-9A-Fa-f]{1,4}:){2,7}[0-9A-Fa-f]{1,4}|(?:[0-9A-Fa-f]{1,4}:)+:(?:[0-9A-Fa-f]{1,4}:?)*[0-9A-Fa-f]{0,4}|::(?:[0-9A-Fa-f]{1,4}:?)+[0-9A-Fa-f]{0,4}"
```
