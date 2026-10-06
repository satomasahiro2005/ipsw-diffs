## SummarizationKit

> `/System/Library/PrivateFrameworks/SummarizationKit.framework/SummarizationKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1732f8` | `0x173b3c` | **`+0x844`** |
| `__TEXT.__oslogstring` | `0x5365` | `0x5505` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x5bfa` | `0x5c5a` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x5ac0` | `0x5b10` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0xc600` | `0xc628` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x15f8` | `0x1620` | **`+0x28`** |
| `__TEXT.__const` | `0xa7d0` | `0xa7c0` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x3518` | `0x3528` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2654` | `0x2660` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x2488` | `0x247e` | **`-0xa`** |
| `__DATA_DIRTY.__data` | `0x4d90` | `0x4d88` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x4d78` | `0x4d80` | **`+0x8`** |

### Other Changes

```diff

-18.0.0.0.0
+20.0.0.0.0

-  Functions: 6460
-  Symbols:   1251
-  CStrings:  578
+  Functions: 6465
+  Symbols:   1250
+  CStrings:  582
Symbols:
- _symbolic ______SSt 15TokenGeneration16PromptCompletionV
CStrings:
+ "--------------------------------------------------------------------------------\n# Partial response for request %{public}s\n--------------------------------------------------------------------------------\n%{private}s\n--------------------------------------------------------------------------------"
+ "Response extraction failed for request %{public}s: finishReason=%{public}s, completionTokenCount=%{public}ld"
+ "Summarization request was rejected due to suspected abuse."
+ "unknown (no candidates)"
```
