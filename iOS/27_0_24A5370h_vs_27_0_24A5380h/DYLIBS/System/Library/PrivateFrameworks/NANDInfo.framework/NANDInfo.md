## NANDInfo

> `/System/Library/PrivateFrameworks/NANDInfo.framework/NANDInfo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_intobj` | `0x10158` | `0x10398` | **`+0x240`** |
| `__AUTH_CONST.__cfstring` | `0xea20` | `0xeba0` | **`+0x180`** |
| `__DATA_CONST.__objc_arraydata` | `0xc518` | `0xc698` | **`+0x180`** |
| `__TEXT.__cstring` | `0xb9d8` | `0xbb17` | **`+0x13f`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x8340` | `0x8460` | **`+0x120`** |
| `__TEXT.__text` | `0x1c5a4` | `0x1c6ac` | **`+0x108`** |

### Other Changes

```diff

-843.0.0.0.0
+847.0.0.0.0

-  CStrings:  2243
+  CStrings:  2255
Functions:
~ _buildFTLStatsArrayDictionary : 25588 -> 25876
~ _findNandExporter : 412 -> 388
CStrings:
+ "RD_CBDR_requested"
+ "RD_CBDRwasFailedToRun"
+ "RD_CBDRwasFailedToRunQlc"
+ "RD_OptionalPORefresh"
+ "RD_OptionalPORefreshAlignRegular"
+ "RD_OptionalPORefreshAlignRegularFailed"
+ "RD_OptionalPORefreshFailed"
+ "RD_OptionalPORefreshHotBand"
+ "RD_OptionalPORefreshHotBandFailed"
+ "RD_RefreshOnSampling"
+ "RD_RefreshOnSamplingQlc"
+ "RD_closedBandEvictCountQlc"
```
