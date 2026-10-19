## AVD.videodecoder

> `/System/Library/VideoDecoders/AVD.videodecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18f7e0` | `0x18fbec` | **`+0x40c`** |
| `__TEXT.__oslogstring` | `0x161a6` | `0x164b3` | **`+0x30d`** |
| `__TEXT.__cstring` | `0x562e` | `0x5669` | **`+0x3b`** |

### Other Changes

```diff

-  Functions: 4380
+  Functions: 4388

-  CStrings:  2067
+  CStrings:  2075
CStrings:
+ "21:08:44"
+ "21:08:45"
+ "21:08:46"
+ "AppleAVD: ERROR: %{public}s(): AppleAVD_HEVCVideoDecoder ERROR: Could not enable multiview decoding\n"
+ "AppleAVD: ERROR: %{public}s(): calcLayersToDecodeFromDisplayLayersList ERROR: numLayersToDecode %d exceeds supported 2\n"
+ "AppleAVD: ERROR: %{public}s(): kVTDecompressionPropertyKey_RequestedMVHEVCVideoLayerIDs cannot be changed after decoding has started (frame# %d)\n"
+ "AppleAVD: ERROR: %{public}s(): kVTDecompressionPropertyKey_RequestedMVHEVCVideoLayerIDs error: invalid layer id at index %d\n"
+ "AppleAVD: ERROR: %{public}s(): kVTDecompressionPropertyKey_RequestedMVHEVCVideoLayerIDs error: videoLayerID %d not declared in VPS at index %d\n"
+ "AppleAVD: ERROR: %{public}s(): kVTDecompressionPropertyKey_RequestedMVHEVCVideoLayerIDs error: videoLayerID %d out of range [0, %d) at index %d\n"
+ "Oct 13 2026"
+ "calcLayersToDecodeFromDisplayLayersList"
+ "m_avc_max_slices"
+ "too many slices!"
- "01:19:33"
- "01:19:34"
- "01:19:35"
- "AVC_MAX_SLICES"
- "Oct 10 2026"
```
