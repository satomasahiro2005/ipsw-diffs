## TextToSpeech

> `/System/Library/PrivateFrameworks/TextToSpeech.framework/TextToSpeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34b5a4` | `0x350528` | **`+0x4f84`** |
| `__AUTH_CONST.__objc_const` | `0xab00` | `0xacd8` | **`+0x1d8`** |
| `__DATA.__bss` | `0x26c58` | `0x26e08` | **`+0x1b0`** |
| `__AUTH_CONST.__const` | `0x179f8` | `0x17b98` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x2f94` | `0x30f4` | **`+0x160`** |
| `__TEXT.__constg_swiftt` | `0x85a4` | `0x86f8` | **`+0x154`** |
| `__TEXT.__const` | `0x3fb49` | `0x3fc89` | **`+0x140`** |
| `__TEXT.__swift5_reflstr` | `0x4fd0` | `0x5100` | **`+0x130`** |
| `__TEXT.__eh_frame` | `0x173d0` | `0x174f8` | **`+0x128`** |
| `__AUTH.__objc_data` | `0x3258` | `0x3360` | **`+0x108`** |
| `__TEXT.__swift5_fieldmd` | `0x6360` | `0x645c` | **`+0xfc`** |
| `__AUTH.__data` | `0x40d0` | `0x4198` | **`+0xc8`** |
| `__TEXT.__unwind_info` | `0xcad0` | `0xcb28` | **`+0x58`** |
| `__TEXT.__cstring` | `0x855d` | `0x850d` | **`-0x50`** |
| `__TEXT.__swift5_typeref` | `0x7934` | `0x794e` | **`+0x1a`** |
| `__AUTH_CONST.__auth_got` | `0x2ae0` | `0x2af8` | **`+0x18`** |
| `__DATA.__common` | `0x518` | `0x528` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x1348` | `0x1354` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x7b0` | `0x7bc` | **`+0xc`** |
| `__DATA.__data` | `0x3d48` | `0x3d40` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x368` | `0x370` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2980` | `0x2978` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0x3330` | `0x3334` | **`+0x4`** |

### Other Changes

```diff

-727.3.2.0.0
+727.3.3.0.0

-  Functions: 16110
-  Symbols:   1372
-  CStrings:  1655
+  Functions: 16140
+  Symbols:   1373
+  CStrings:  1661
Symbols:
+ _uscript_getScript
CStrings:
+ "(?<![\\d(])\\+?\\(?\\d{1,4}\\)?(?:[-. ]?\\(?\\d{1,5}\\)?){0,5}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?(?!\\d)"
+ "AudioQueue session timings (%{public}s): ioBufferDuration=%.*fms (requested %.*fms), outputLatency=%.*fms, wirelessTransport=%{bool}d, headroom=%.*fms, bufferDuration=%.*fms, buffersPerIOCycle=%.*f, stagedTarget=%ld, ioCycleFloor=%.*fms, effectivePriming=%.*fms, effectiveMaxBuffered=%.*fms"
+ "Failed to enqueue silence buffer: %d"
+ "PRAGMA journal_mode=TRUNCATE"
+ "Ranged event spans elements with distinct source text; dropped %ld range(s) from consolidation"
+ "Regex cache left in journal mode '%{public}s'; discarding the database file"
+ "Stop wind-down: hardwareDepth=%ld, repaying %ld of %ld deferred enqueue(s) with silence"
+ "Top-up enqueue failed"
+ "test"
- "(?:\\(\\d{3}\\)\\s?|\\d{3}[-. ])\\d{3}[-. ]?\\d{4}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?|\\d{10}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?|\\d{3}[-. ]\\d{4}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?|\\d{7}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?"
- "AudioQueue session timings (%{public}s): ioBufferDuration=%.*fms (requested %.*fms), outputLatency=%.*fms, headroom=%.*fms, otherAudioPlaying=%{bool}d, bufferDuration=%.*fms, buffersPerIOCycle=%.*f, stagedTarget=%ld, ioCycleFloor=%.*fms, effectivePriming=%.*fms, effectiveMaxBuffered=%.*fms"
- "PRAGMA journal_mode=WAL"
```
