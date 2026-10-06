## MP4VH8.videodecoder

> `/System/Library/VideoDecoders/MP4VH8.videodecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x112b0` | `0x112dc` | **`+0x2c`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ _AppleD5500DecodeFrame : 2076 -> 2084
~ __ZN9HEVC_RBSP13initScanOrderEv : 176 -> 180
~ __ZN9HEVC_RBSP20parseScalingListDataEP24hevc_scaling_list_data_t : 948 -> 988
~ __ZN9HEVC_RBSP25setDefaultScalingListDataEP24hevc_scaling_list_data_t : 340 -> 348
~ __ZN9HEVC_RBSP20parsePredWeightTableEP29hevc_sequence_parameter_set_tP27hevc_slice_segment_header_tj : 2352 -> 2320
~ __ZN9HEVC_RBSP26parseSeiDecodedPictureHashEP29hevc_sequence_parameter_set_tP31hevc_sei_decoded_picture_hash_t : 244 -> 236
~ __ZN10BufferPool12pruneBuffersEv : 284 -> 288
~ __ZN10BufferPool9getBufferEPjj : 1024 -> 1032
~ __ZN10BufferPool9putBufferEPjjP10__CVBufferjj : 856 -> 868
CStrings:
+ "21:36:42"
- "22:23:07"
```
