## SpotlightServices

> `/System/Library/PrivateFrameworks/SpotlightServices.framework/SpotlightServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15f5e4` | `0x15f69c` | **`+0xb8`** |
| `__AUTH_CONST.__cfstring` | `0x36be0` | `0x36c00` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3438` | `0x3450` | **`+0x18`** |
| `__TEXT.__cstring` | `0x3a8aa` | `0x3a8ba` | **`+0x10`** |

### Other Changes

```diff

-2459.102.0.0.0
+2459.105.0.0.0

-  CStrings:  7928
+  CStrings:  7929
Functions:
~ -[SSSectionRankingBlender _computeQualityForResult:] : 868 -> 928
~ -[SSSectionRankingBlender spotlightResultQuality] : 144 -> 224
~ ___63-[SSRankingFeedbackHandler fetchBundleRenderAndEngagementInfo:]_block_invoke : 1264 -> 1252
~ -[SSSectionRankingBlender spotlightResultQualityBreakdown] : 1804 -> 1860
CStrings:
+ "spellCorrectedApp"
```
