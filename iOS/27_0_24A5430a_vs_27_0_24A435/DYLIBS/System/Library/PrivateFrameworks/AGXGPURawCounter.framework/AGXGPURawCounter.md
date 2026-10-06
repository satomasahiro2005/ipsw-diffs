## AGXGPURawCounter

> `/System/Library/PrivateFrameworks/AGXGPURawCounter.framework/AGXGPURawCounter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf644` | `0xf870` | **`+0x22c`** |
| `__DATA.__bss` | `0x7c8` | `0x920` | **`+0x158`** |
| `__AUTH_CONST.__const` | `0x800` | `0x880` | **`+0x80`** |
| `__DATA.__data` | `0x1f3` | `0x223` | **`+0x30`** |
| `__TEXT.__const` | `0x200` | `0x220` | **`+0x20`** |

### Other Changes

```diff

-  Functions: 165
-  Symbols:   335
+  Functions: 169
+  Symbols:   342
Symbols:
+ __ZN13AGXGRC_HAL400L13HasMagicTokenEy
+ __ZN13AGXGRC_HAL400L16SampleHeaderSizeEv
+ __ZN13AGXGRC_HAL400L17ParseSampleHeaderEPKyP17AGXSPerfCtrSamplePy
+ __ZN13AGXGRC_HAL400L18KickslotConfigListE
+ __ZN13AGXGRC_HAL400L18sChipDispatchTableE
+ __ZN13AGXGRC_HAL400L21sChipDispatchTableAPSE
+ __ZN13AGXGRC_HAL400L23ResetSampleHeaderParserEy
Functions:
~ __ZN20AGXGPURawCounterImpl10SourceImpl28generateKickTimestampSamplesEjyyPKhjPNS0_13KickslotStateEPj : 1584 -> 1588
~ __ZN20AGXGPURawCounterImpl10SourceImpl14ringBufferInitEyPvj : 212 -> 216
~ __ZNK20AGXGPURawCounterImpl26chipDispatchTableForSourceEjjjPKc : 1616 -> 1788
```
