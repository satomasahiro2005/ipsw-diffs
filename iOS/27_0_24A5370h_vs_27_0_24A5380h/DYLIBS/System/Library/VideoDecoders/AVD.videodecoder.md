## AVD.videodecoder

> `/System/Library/VideoDecoders/AVD.videodecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1697d0` | `0x169770` | **`-0x60`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-989.0.0.0.0
+989.1.0.0.0
Functions:
~ __ZN10CPBManager13releaseOneCPBEjb : 720 -> 732
~ __ZN10CPBManager11allocOneCPBEjmRjPhPbPS1_ : 1732 -> 1784
~ __ZN8HEVC_RLM11addNewEntryEP15HevcPictureInfo : 276 -> 284
~ __Z5qSortPhhhPFiPKvS1_E : 1436 -> 1348
~ __ZN8AVC_RBSP29scanNalForEmulationPreventionEPhjib : 364 -> 356
~ __ZN7AVC_RLM19dec_ref_pic_markingER15sAvcSliceHeaderR15sAvcPictureInfo : 1976 -> 2004
~ __ZN10BufferPool9getBufferEPjjP10__CVBufferP27OpaqueVTVideoDecoderSessionP25OpaqueVTVideoDecoderFrameb : 1824 -> 1812
~ __ZN14CAHDecTansyAvx15populateAvdWorkEj : 1444 -> 1400
~ __ZN15CAHDecCatnipAvx15populateAvdWorkEj : 1204 -> 1180
~ __ZN14CAVDAvxDecoder11initPictureEj : 3388 -> 3396
~ __ZN7AV1_RLMD2Ev : 516 -> 504
~ __ZN7AV1_RLM20release_frame_bufferEP16av1_frame_buffer : 544 -> 548
~ __ZN7AV1_RLM12dump_fb_infoEP23av1_uncompressed_header : 740 -> 728
~ __ZN10LGH_Syntax20frame_size_with_refsEv : 380 -> 376
~ __ZN14CAVDAvcDecoder13VAStartDecodeEPhi : 744 -> 760
~ __ZN14CAVDAvcDecoder16processParserOutEP13sAvcParserOutRbS2_RiS3_ : 360 -> 384
~ __ZN10CPBManager14evictFromCacheEv : 380 -> 384
~ __ZN10AV1_Syntax20frame_size_with_refsEv : 1324 -> 1316
~ __ZN10AV1_Syntax13get_tile_infoEPhPKhiiP10av1_header : 736 -> 748
~ _av1_read_next_obu : 1116 -> 1108
~ __ZN14CAHDecThymeAvx15populateAvdWorkEj : 1444 -> 1400
CStrings:
+ "21:25:33"
+ "21:25:34"
+ "21:25:35"
+ "Jun 29 2026"
- "19:45:42"
- "19:45:43"
- "19:45:44"
- "Jun 18 2026"
```
