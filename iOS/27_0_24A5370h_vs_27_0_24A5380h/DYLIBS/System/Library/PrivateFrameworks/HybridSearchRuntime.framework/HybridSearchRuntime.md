## HybridSearchRuntime

> `/System/Library/PrivateFrameworks/HybridSearchRuntime.framework/HybridSearchRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x252548` | `0x25ed28` | **`+0xc7e0`** |
| `__TEXT.__eh_frame` | `0x1e4bc` | `0x1f070` | **`+0xbb4`** |
| `__DATA_DIRTY.__data` | `0x2e78` | `0x3700` | **`+0x888`** |
| `__DATA.__bss` | `0x66a0` | `0x5f20` | **`-0x780`** |
| `__DATA_DIRTY.__bss` | `0x2180` | `0x2900` | **`+0x780`** |
| `__AUTH.__data` | `0x2110` | `0x1a38` | **`-0x6d8`** |
| `__TEXT.__unwind_info` | `0x8fd0` | `0x9698` | **`+0x6c8`** |
| `__AUTH_CONST.__const` | `0xd0a0` | `0xd670` | **`+0x5d0`** |
| `__TEXT.__const` | `0xbb90` | `0xbe80` | **`+0x2f0`** |
| `__TEXT.__swift5_capture` | `0x3be8` | `0x3d90` | **`+0x1a8`** |
| `__TEXT.__swift5_typeref` | `0x5aa2` | `0x5c02` | **`+0x160`** |
| `__TEXT.__swift5_fieldmd` | `0x2a50` | `0x2b20` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0x1fb0` | `0x2070` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0x2a88` | `0x2b40` | **`+0xb8`** |
| `__TEXT.__oslogstring` | `0x6dfd` | `0x6ead` | **`+0xb0`** |
| `__AUTH.__objc_data` | `0x240` | `0x1a0` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x250` | `0x2f0` | **`+0xa0`** |
| `__TEXT.__swift_as_ret` | `0x13d4` | `0x1470` | **`+0x9c`** |
| `__TEXT.__constg_swiftt` | `0x3848` | `0x38d8` | **`+0x90`** |
| `__TEXT.__cstring` | `0xe801` | `0xe891` | **`+0x90`** |
| `__TEXT.__swift_as_entry` | `0xdf8` | `0xe88` | **`+0x90`** |
| `__DATA.__data` | `0x2988` | `0x2920` | **`-0x68`** |
| `__DATA.__common` | `0x80` | `0x20` | **`-0x60`** |
| `__DATA_DIRTY.__common` | `0x20` | `0x80` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x25d8` | `0x2618` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x2c88` | `0x2cc4` | **`+0x3c`** |
| `__DATA_CONST.__got` | `0x1cd0` | `0x1ce8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1438` | `0x1448` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x448` | `0x454` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0x5e8` | `0x5ec` | **`+0x4`** |

### Other Changes

```diff

-57.0.1.0.0
+59.0.1.0.0

+  - /System/Library/PrivateFrameworks/HybridSearch.framework/HybridSearch

-  Functions: 12043
+  Functions: 12246

-  CStrings:  942
+  CStrings:  947
Symbols:
+ _AnalyticsSendEventSync
+ __exit
- _objc_release_x12
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "FTSRetokenizeTask"
+ "HybridIndex incremental FTS retokenize succeeded."
+ "Safety check completed: verdict=%{sensitive}s for requestIdentifier: %{public}s"
+ "Start HybridIndex incremental FTS retokenize."
+ "Truncated oversized FTS content: %{public}ld → %{public}ld chars"
+ "com.apple.GenerativeSearch.PeriodicTasks.FTSRetokenizeTask"
+ "com.apple.HybridSearch.search.safetyVerdict"
+ "perform(text:checkSafety:safetyThreshold:safetyBlockingDisabled:embeddingModelProperties:contextLength:allowTruncation:sendAnalyticsEvent:)"
- "Safety Block: query deemed unsafe (score=%f, threshold=%f) for requestIdentifier: %{public}s"
- "_kMDItemIsTwoFactorCode"
- "perform(text:checkSafety:safetyThreshold:embeddingModelProperties:contextLength:allowTruncation:)"
```
