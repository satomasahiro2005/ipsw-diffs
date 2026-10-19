## AppleCVAPhoto

> `/System/Library/PrivateFrameworks/AppleCVAPhoto.framework/AppleCVAPhoto`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x5b80` | `0x5ce0` | **`+0x160`** |
| `__TEXT.__cstring` | `0x7904` | `0x79f3` | **`+0xef`** |
| `__TEXT.__text` | `0x4c844` | `0x4c8f0` | **`+0xac`** |
| `__TEXT.__gcc_except_tab` | `0x62c0` | `0x62d4` | **`+0x14`** |

### Other Changes

```diff

-  CStrings:  933
+  CStrings:  944
Functions:
~ sub_257e16960 -> sub_258426960 : 1120 -> 1136
~ sub_257e16fe0 -> sub_258426ff0 : 728 -> 740
~ sub_257e186bc -> sub_2584286d8 : 2200 -> 2212
~ sub_257e1ac74 -> sub_25842ac9c : 460 -> 484
~ sub_257e242ec -> sub_25843432c : 5668 -> 5676
~ sub_257e32a9c -> sub_258442ae4 : 8420 -> 8432
~ sub_257e373c8 -> sub_25844741c : 516 -> 532
~ sub_257e3774c -> sub_2584477b0 : 1928 -> 1940
~ sub_257e38098 -> sub_258448108 : 2256 -> 2268
~ sub_257e3a998 -> sub_25844aa14 : 3876 -> 3900
~ sub_257e3ba8c -> sub_25844bb20 : 972 -> 984
~ sub_257e3e008 -> sub_25844e0a8 : 696 -> 708
CStrings:
+ "GaussianPyramid"
+ "MPS-prewarming"
+ "MPSImageBox"
+ "MPSImageLanczosScale"
+ "alpha blend"
+ "alphaMattingWithPostprocessedDisparity"
+ "disparityPostprocessingWithCanonicalDisparity"
+ "perf profiler"
+ "renderContinuousWithSource"
+ "segmentationAverage"
+ "video relighting"
```
