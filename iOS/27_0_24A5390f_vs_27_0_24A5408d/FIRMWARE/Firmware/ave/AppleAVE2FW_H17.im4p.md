## AppleAVE2FW_H17.im4p

> `Firmware/ave/AppleAVE2FW_H17.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x112768` | `0x114044` | **`+0x18dc`** |
| `__TEXT.__cstring` | `0x17c45` | `0x17e51` | **`+0x20c`** |
| `__TEXT.__const` | `0x266d4` | `0x266f4` | **`+0x20`** |
| `__DATA.__const` | `0x3cd8` | `0x3cf0` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`

### Other Changes

```diff

-  Functions: 1221
-  Symbols:   1710
-  CStrings:  2698
+  Functions: 1223
+  Symbols:   1712
+  CStrings:  2713
Symbols:
+ __ZN11RateControl18processRateControlExx11_S_AVE_Timejjii
+ __ZN11RateControl19updateBitsFromCAVLCExxi
+ __ZN11RateControl19updateCplxForZeroLAExd
+ __ZN15CMCTFController14GetRefCompInfoEbPK18AVE_PICMGMT_PARAMSP14MCTF_FrameInfoS4_iPbPhS6_P17_S_AVE_CompBufExt
+ __ZN15CMCTFController17GetRefCompOutInfoEPK18AVE_PICMGMT_PARAMSP14MCTF_FrameInfoiP17_S_AVE_CompBufExt
+ __ZN21ConstantQpRateControl18processRateControlExx11_S_AVE_Timejjii
+ __ZN9BlurRatio6updateERK10FrameStatsP18RateControlContext
- __ZN11RateControl18processRateControlExii
- __ZN15CMCTFController14GetRefCompInfoEbPK18AVE_PICMGMT_PARAMSP14MCTF_FrameInfoS4_PbPhS6_P17_S_AVE_CompBufExt
- __ZN15CMCTFController17GetRefCompOutInfoEPK18AVE_PICMGMT_PARAMSP14MCTF_FrameInfoP17_S_AVE_CompBufExt
- __ZN21ConstantQpRateControl18processRateControlExii
- __ZN9BlurRatio6updateERK10FrameStats
CStrings:
+ "%s:%d  FwHeaderWrite Overwriting sps_temporal_id_nesting_flag to true."
+ "%s:%s EncCommParams.use_CAVLC_bits %d"
+ "%s:%s EncCommParams.use_CAVLC_bits %d RCiFeature %llu, CommiFeature %llu"
+ "%s::%s Enter, bit = %lld"
+ "%s::%s cplx= %d.%03d cplxFiltered=%d.%03d"
+ "%s::%s lookahead_frames=%d"
+ "%s::%s:%d LA0 (%lld %lld) frameType %d tid %d dts %lld tscale %d past %d.%03d %d.%03d %d.%03d %d.%03d"
+ "%s::%s:%d PTS gap: interval=%lld nominal=%lld excess=%lld accumulated=%lld"
+ "./RTKit/platform/common/CDockChannel.cpp"
+ "9013.45.1"
+ "Caller is /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleAVE2FW/External/Algorithm/RateControl.cpp:1019"
+ "Caller is /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleAVE2FW/External/Algorithm/RateControl.cpp:1024"
+ "Caller is /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleAVE2FW/External/Algorithm/RateControl.cpp:1072"
+ "Caller is /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleAVE2FW/External/Algorithm/RateControl.cpp:1084"
+ "RTK_DockChannel_init"
+ "RTK_ST_OK == tStatus"
+ "Received cmd 0x%llx for invalid client:%d"
+ "handleLargePTSGap"
+ "iBufAddr != 0"
+ "updateBitsFromCAVLC"
+ "updateCplxForZeroLA"
- "(m_sSPS.sps_max_sub_layers_minus1 != 0) || (m_sSPS.sps_max_sub_layers_minus1 == 0 && m_sSPS.sps_temporal_id_nesting_flag == true)"
- "9013.35.1"
- "Caller is /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleAVE2FW/External/Algorithm/RateControl.cpp:855"
- "Caller is /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleAVE2FW/External/Algorithm/RateControl.cpp:860"
- "Caller is /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleAVE2FW/External/Algorithm/RateControl.cpp:901"
- "Caller is /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleAVE2FW/External/Algorithm/RateControl.cpp:913"
```
