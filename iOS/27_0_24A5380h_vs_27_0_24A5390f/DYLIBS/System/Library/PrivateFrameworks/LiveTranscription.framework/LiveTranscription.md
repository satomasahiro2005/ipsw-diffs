## LiveTranscription

> `/System/Library/PrivateFrameworks/LiveTranscription.framework/LiveTranscription`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x308b0` | `0x30a5c` | **`+0x1ac`** |
| `__AUTH_CONST.__cfstring` | `0x720` | `0x760` | **`+0x40`** |
| `__DATA.__bss` | `0x6a0` | `0x6c8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xed8` | `0xf00` | **`+0x28`** |
| `__DATA_DIRTY.__bss` | `0x40` | `0x18` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0x16d4` | `0x16ec` | **`+0x18`** |
| `__TEXT.__cstring` | `0x97a` | `0x982` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa48` | `0xa50` | **`+0x8`** |

### Other Changes

```diff

-581.0.0.0.0
+584.0.0.0.0

-  Functions: 999
-  Symbols:   1161
-  CStrings:  293
+  Functions: 1000
+  Symbols:   1163
+  CStrings:  295
Symbols:
+ +[AXLTSpeechTranscriber currentSystemOutputIsMFiHearingInstrument]
+ GCC_except_table295
+ GCC_except_table310
+ GCC_except_table342
+ __OBJC_$_CLASS_METHODS_AXLTSpeechTranscriber
- GCC_except_table294
- GCC_except_table309
- GCC_except_table341
Functions:
~ -[AXLTSpeechTranscriber setupAudioSession] : 704 -> 752
+ +[AXLTSpeechTranscriber currentSystemOutputIsMFiHearingInstrument]
CStrings:
+ "L- "
+ "R- "
```
