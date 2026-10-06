## AppleDepthCore

> `/System/Library/PrivateFrameworks/AppleDepthCore.framework/AppleDepthCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x600b8` | `0x600b0` | **`-0x8`** |

### Other Changes

```diff

-170.0.0.0.0
+171.0.1.0.0
Functions:
~ -[ADStreamSync checkOnceForMatch:] : 568 -> 556
~ __Z17compareRawBuffersIffE19BaselineTestStats_sPT_mPT0_mmmbbf : 992 -> 1004
~ __Z17compareRawBuffersIDhDhE19BaselineTestStats_sPT_mPT0_mmmbbf : 1000 -> 1012
~ __Z17compareRawBuffersIDhfE19BaselineTestStats_sPT_mPT0_mmmbbf : 996 -> 1008
~ __Z17compareRawBuffersIhhE19BaselineTestStats_sPT_mPT0_mmmbbf : 792 -> 804
~ __Z17compareRawBuffersIttE19BaselineTestStats_sPT_mPT0_mmmbbf : 792 -> 804
~ -[ADAggregatedPointCloudRefiner pointCloudByRemovingPeridotShortRangeOccludedPoints:] : 1104 -> 1100
~ __Z20countDiffsRawBuffersIhEiP13vImage_BufferS1_mff : 196 -> 204
~ __Z20countDiffsRawBuffersIfEiP13vImage_BufferS1_mff : 188 -> 196
~ __Z20countDiffsRawBuffersIDhEiP13vImage_BufferS1_mff : 196 -> 204
~ __Z12calcDiffsRawIhEvP13vImage_BufferS1_S1_bim : 304 -> 308
~ __ZN16PixelBufferUtils25colorizedDepthPixelBufferEP10__CVBufferbffbPfS1_ : 2032 -> 1944
~ -[ADReprojection vectorizeCameraPixels:] : 1336 -> 1356
~ __ZNKSt3__113__string_hashIcNS_9allocatorIcEEEclB9fqe220106ERKNS_12basic_stringIcNS_11char_traitsIcEES2_EE : 1092 -> 1080
```
