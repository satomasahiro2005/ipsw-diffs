## UnilogInstrumentation

> `/System/Library/PrivateFrameworks/UnilogInstrumentation.framework/UnilogInstrumentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a084` | `0x1b960` | **`+0x18dc`** |
| `__DATA_DIRTY.__data` | `—` | `0x370` | **`+0x370`** |
| `__AUTH.__data` | `0x8a8` | `0x6a8` | **`-0x200`** |
| `__DATA.__data` | `0x650` | `0x520` | **`-0x130`** |
| `__AUTH_CONST.__const` | `0x9a8` | `0xa28` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x1b0` | `0x160` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x311` | `0x361` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x278` | `0x2b0` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0xaf8` | `0xb30` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x140` | `0x170` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x60e` | `0x630` | **`+0x22`** |
| `__TEXT.__constg_swiftt` | `0x69c` | `0x684` | **`-0x18`** |
| `__TEXT.__const` | `0x1050` | `0x1060` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x8c8` | `0x8d0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6b8` | `0x6c0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x30` | `0x34` | **`+0x4`** |

### Other Changes

```diff

-2.0.3.0.0
+2.1.1.0.0

-  Functions: 486
-  Symbols:   334
-  CStrings:  37
+  Functions: 496
+  Symbols:   337
+  CStrings:  39
Symbols:
+ _symbolic $s21UnilogInstrumentation14PrunableStreamP
+ _symbolic ______pXmT 21UnilogInstrumentation14PrunableStreamP
+ _symbolic _____y_____G 21UnilogInstrumentation13SourceWrapper33_551DDB4CD3A161A961E50635C079D2CELLV 27IntelligencePlatformLibrary0O0O7StreamsO0A0O13SafariFeatureO11AggregationO
+ _symbolic _____y_____G 21UnilogInstrumentation13SourceWrapper33_551DDB4CD3A161A961E50635C079D2CELLV 27IntelligencePlatformLibrary0O0O7StreamsO0A0O13SafariFeatureO5StageO
+ _symbolic _____y_____G 21UnilogInstrumentation17PrunableStreamFor33_551DDB4CD3A161A961E50635C079D2CELLO 27IntelligencePlatformLibrary0P0O7StreamsO0A0O13SafariFeatureO11AggregationO
+ _symbolic _____y_____G 21UnilogInstrumentation17PrunableStreamFor33_551DDB4CD3A161A961E50635C079D2CELLO 27IntelligencePlatformLibrary0P0O7StreamsO0A0O13SafariFeatureO5StageO
+ _symbolic _____y_____G 21UnilogInstrumentation17PrunableStreamFor33_551DDB4CD3A161A961E50635C079D2CELLO 27IntelligencePlatformLibrary0P0O7StreamsO0A0O13SafariFeatureO9ProcessedO
- _objc_release_x21
- _objc_release_x23
- _symbolic $s21UnilogInstrumentation14PrunableStream33_551DDB4CD3A161A961E50635C079D2CELLP
- _symbolic ______pXmT 21UnilogInstrumentation14PrunableStream33_551DDB4CD3A161A961E50635C079D2CELLP
CStrings:
+ "Failed to prune future-dated identifiers: %@"
+ "Safari feature client"
```
