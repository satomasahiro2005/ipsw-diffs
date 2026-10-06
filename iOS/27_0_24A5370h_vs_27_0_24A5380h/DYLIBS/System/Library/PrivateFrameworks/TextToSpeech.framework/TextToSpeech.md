## TextToSpeech

> `/System/Library/PrivateFrameworks/TextToSpeech.framework/TextToSpeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31394c` | `0x31701c` | **`+0x36d0`** |
| `__AUTH_CONST.__const` | `0x15c48` | `0x161b0` | **`+0x568`** |
| `__DATA.__bss` | `0x25278` | `0x25638` | **`+0x3c0`** |
| `__TEXT.__eh_frame` | `0x17100` | `0x16e90` | **`-0x270`** |
| `__TEXT.__const` | `0x3e949` | `0x3eba9` | **`+0x260`** |
| `__TEXT.__swift5_capture` | `0x2fd8` | `0x3160` | **`+0x188`** |
| `__AUTH.__objc_data` | `0x2d30` | `0x2e28` | **`+0xf8`** |
| `__DATA_DIRTY.__objc_data` | `0x610` | `0x520` | **`-0xf0`** |
| `__TEXT.__swift5_fieldmd` | `0x5c6c` | `0x5d48` | **`+0xdc`** |
| `__TEXT.__swift5_typeref` | `0x726e` | `0x7332` | **`+0xc4`** |
| `__TEXT.__swift5_reflstr` | `0x4810` | `0x48d0` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x7b30` | `0x7bb8` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0xc5f0` | `0xc660` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x3d08` | `0x3ca8` | **`-0x60`** |
| `__DATA.__data` | `0x3b48` | `0x3af8` | **`-0x50`** |
| `__AUTH_CONST.__auth_got` | `0x2948` | `0x2978` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x1284` | `0x1260` | **`-0x24`** |
| `__AUTH.__data` | `0x41d0` | `0x41f0` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x1678` | `0x1690` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0xd0c` | `0xcf4` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x1270` | `0x1284` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x72c` | `0x740` | **`+0x14`** |
| `__AUTH_CONST.__objc_const` | `0xa500` | `0xa510` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xd00` | `0xd10` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0xc0` | `0xb0` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x28b0` | `0x28c0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0xd18` | `0xd08` | **`-0x10`** |
| `__TEXT.__cstring` | `0x78fe` | `0x78ee` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0xc28` | `0xc1c` | **`-0xc`** |
| `__DATA_CONST.__objc_protorefs` | `0x50` | `0x48` | **`-0x8`** |

### Other Changes

```diff

-716.0.0.0.0
+718.0.0.0.0

+  - /System/Library/Frameworks/Security.framework/Security

-  Functions: 15491
-  Symbols:   1356
-  CStrings:  1570
+  Functions: 15580
+  Symbols:   1360
+  CStrings:  1572
Symbols:
+ _SecTaskCreateFromSelf
+ _SecTaskGetCodeSignStatus
+ _TTSIsPlatformBinary
+ _sqlite3_busy_timeout
CStrings:
+ "BEGIN IMMEDIATE"
+ "PRAGMA quick_check"
+ "PRAGMA synchronous=OFF"
+ "com.apple.TextToSpeech.regexCacheFlush"
+ "regex_cache.wipe"
- "AVSS Compatibility layer does not support TTSMarkup. This should never occur."
- "PRAGMA synchronous=NORMAL"
- "TextToSpeech/CoreSynthesizer+AVSpeechSynthesizer.swift"
```
