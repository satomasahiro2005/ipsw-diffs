## AVD.videodecoder

> `/System/Library/VideoDecoders/AVD.videodecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16ba28` | `0x16bd88` | **`+0x360`** |
| `__TEXT.__oslogstring` | `0x16210` | `0x16252` | **`+0x42`** |
| `__TEXT.__unwind_info` | `0x1dc8` | `0x1de0` | **`+0x18`** |
| `__TEXT.__cstring` | `0x56b6` | `0x56bd` | **`+0x7`** |

### Other Changes

```diff

-991.0.0.0.0
+993.1.0.0.0

-  Functions: 4120
-  Symbols:   3342
-  CStrings:  2073
+  Functions: 4124
+  Symbols:   3345
+  CStrings:  2074
Symbols:
+ __ZN14CAVDAvxDecoder15validateRefBufsEv
+ __ZN14CAVDAvxDecoder18VAUnmapPixelBufferEij
+ __ZN14CAVDLghDecoder15validateRefBufsEv
+ __ZN14CAVDLghDecoder18VAUnmapPixelBufferEij
- GCC_except_table17
Functions:
~ __ZN22AppleAVDCommandBuilder14decodeFrameFigEP26_sAppleAVDDecodeFrameFigInP27_sAppleAVDDecodeFrameFigOut : 4812 -> 4800
~ __ZN14CAVDAvxDecoder13VADecodeFrameEPhijiiiP14avd_seq_params : 3804 -> 3816
+ __ZN14CAVDAvxDecoder15validateRefBufsEv
+ __ZN14CAVDAvxDecoder18VAUnmapPixelBufferEij
~ __ZN14CAVDLghDecoder13VADecodeFrameEPhijiiiP14avd_seq_params : 4168 -> 4200
+ __ZN14CAVDLghDecoder15validateRefBufsEv
+ __ZN14CAVDLghDecoder18VAUnmapPixelBufferEij
~ __ZN14CAVDAvcDecoder24decodeGetRenderTargetRefEjjjPP9_vsurface : 992 -> 1004
~ __ZN22AppleAVDCommandBuilderC2Ejh : 516 -> 504
- __ZN22AppleAVDCommandBuilder15allocRVRAMemoryEjj
+ __ZN22AppleAVDCommandBuilder15allocRVRAMemoryEjj
~ __ZN15CAVDHevcDecoder24decodeGetRenderTargetRefEjPP9_vsurface : 900 -> 916
CStrings:
+ "21:54:05"
+ "21:54:07"
+ "AppleAVD: INFO: %{public}s(): GUARDED: ref[%u] buf=%p dec_buf=%p\n"
+ "Aug  5 2026"
+ "validateRefBufs"
- "21:35:53"
- "21:35:54"
- "21:35:55"
- "Jul 14 2026"
```
