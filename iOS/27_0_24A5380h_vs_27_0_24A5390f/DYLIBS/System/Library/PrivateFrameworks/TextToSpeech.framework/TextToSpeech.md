## TextToSpeech

> `/System/Library/PrivateFrameworks/TextToSpeech.framework/TextToSpeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31701c` | `0x324974` | **`+0xd958`** |
| `__AUTH_CONST.__const` | `0x161b0` | `0x165d8` | **`+0x428`** |
| `__TEXT.__eh_frame` | `0x16e90` | `0x16c00` | **`-0x290`** |
| `__TEXT.__const` | `0x3eba9` | `0x3ede9` | **`+0x240`** |
| `__TEXT.__constg_swiftt` | `0x7bb8` | `0x7d30` | **`+0x178`** |
| `__TEXT.__swift5_fieldmd` | `0x5d48` | `0x5ec0` | **`+0x178`** |
| `__AUTH.__data` | `0x41f0` | `0x42f0` | **`+0x100`** |
| `__DATA.__bss` | `0x25638` | `0x256f8` | **`+0xc0`** |
| `__TEXT.__swift5_capture` | `0x3160` | `0x30a8` | **`-0xb8`** |
| `__TEXT.__swift5_reflstr` | `0x48d0` | `0x4960` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x7332` | `0x73c2` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0xc660` | `0xc5d0` | **`-0x90`** |
| `__TEXT.__cstring` | `0x78ee` | `0x796e` | **`+0x80`** |
| `__TEXT.__swift_as_ret` | `0xcf4` | `0xd6c` | **`+0x78`** |
| `__TEXT.__swift_as_entry` | `0xc1c` | `0xc80` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0xa510` | `0xa570` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x2978` | `0x29b0` | **`+0x38`** |
| `__DATA_DIRTY.__data` | `0xd08` | `0xd40` | **`+0x38`** |
| `__TEXT.__swift5_types` | `0x740` | `0x75c` | **`+0x1c`** |
| `__DATA.__data` | `0x3af8` | `0x3b10` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x488` | `0x49c` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x1284` | `0x1290` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x28c0` | `0x28c8` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x134` | `0x13c` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x1260` | `0x125c` | **`-0x4`** |

### Other Changes

```diff

-718.0.0.0.0
+720.0.0.0.0

-  Functions: 15580
+  Functions: 15616

-  CStrings:  1572
+  CStrings:  1575
CStrings:
+ "(?<!-)(?<!\\d:)\\b\\d+:\\d{1,2}(?:\\.\\d+)?\\b(?!:\\d)"
+ "(?<!-)(?<!\\d:)\\b\\d+:\\d{1,2}:\\d{1,2}(?:\\.\\d+)?\\b(?!:\\d)"
+ ")\\s*(\\d{1,2}):(\\d{2})(?::(\\d{2}))?\\s*[時时分秒]*"
+ "emoji.suffix.plural"
+ "enqueue(work:run:)"
+ "repeat.filter.no.spaces"
- "(?<!-)(?<!\\d:)\\b\\d+:\\d{2}(?:\\.\\d+)?\\b"
- "(?<!-)(?<!\\d:)\\b\\d+:\\d{2}:\\d{2}(?:\\.\\d+)?\\b"
- "doSchedulingOperationSync(work:)"
```
