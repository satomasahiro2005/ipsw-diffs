## SiriTTSService

> `/System/Library/PrivateFrameworks/SiriTTSService.framework/SiriTTSService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e16d0` | `0x1e2410` | **`+0xd40`** |
| `__AUTH_CONST.__const` | `0x175c0` | `0x177b0` | **`+0x1f0`** |
| `__TEXT.__swift5_capture` | `0x3a6c` | `0x3b4c` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x759e` | `0x765e` | **`+0xc0`** |
| `__TEXT.__cstring` | `0xd9cd` | `0xda7d` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x45c5` | `0x4669` | **`+0xa4`** |
| `__TEXT.__unwind_info` | `0x9930` | `0x98e0` | **`-0x50`** |
| `__TEXT.__objc_methlist` | `0x6880` | `0x68c8` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x86dc` | `0x86a0` | **`-0x3c`** |
| `__AUTH_CONST.__objc_const` | `0x11db8` | `0x11de8` | **`+0x30`** |
| `__DATA.__data` | `0x3c10` | `0x3be0` | **`-0x30`** |
| `__TEXT.__const` | `0x10490` | `0x104c0` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x2000` | `0x2028` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0x7718` | `0x76f8` | **`-0x20`** |
| `__DATA_DIRTY.__objc_data` | `0x4c88` | `0x4ca8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x40f7` | `0x4117` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2460` | `0x2478` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x4de0` | `0x4df8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xbd0` | `0xbe0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x7f04` | `0x7f14` | **`+0x10`** |

### Other Changes

```diff

-3605.33.1.1.1
+3605.41.1.0.0

-  Functions: 16411
-  Symbols:   6380
-  CStrings:  2090
+  Functions: 16426
+  Symbols:   6390
+  CStrings:  2098
Symbols:
+ -[SiriTTSSpeechRequest(SwiftProxy) disableFallbackVoice]
+ -[SiriTTSSpeechRequest(SwiftProxy) setDisableFallbackVoice:]
+ -[SiriTTSSynthesisRequest(SwiftProxy) disableFallbackVoice]
+ -[SiriTTSSynthesisRequest(SwiftProxy) setDisableFallbackVoice:]
+ GCC_except_table1494
+ GCC_except_table1495
+ GCC_except_table1500
+ GCC_except_table1501
+ GCC_except_table1502
+ ___swift_closure_destructor.151Tm
+ ___swift_closure_destructor.862Tm
+ _generic environment SkRzl
+ _swift_getAtKeyPath
+ _swift_getKeyPath
+ _symbolic 7ElementSTQz
+ _symbolic Si6offset_7ElementSTQz7elementt
+ _symbolic _____ySSypGIegr_ 14SiriTTSService20AccessSafeDictionaryC
- GCC_except_table1490
- GCC_except_table1491
- GCC_except_table1492
- GCC_except_table1497
- GCC_except_table1498
- ___swift_closure_destructor.103Tm
- ___swift_closure_destructor.849Tm
CStrings:
+ "#SiriDataDetector phone number match was likely a false-positive"
+ "/[:alpha:][:digit:]+[-\\/ ]+$/"
+ "/^[-\\/ ]+[:digit:]+[:alpha:]/"
+ "Defaults set forceIFP"
+ "OpusDecoder: packet %ld is %ld bytes, exceeds capacity %u; skipping"
+ "com.apple.WorkflowKit.BackgroundShortcutRunner"
+ "com.apple.shortcuts"
+ "disableFallbackVoice"
```
