## ave.videoencoder

> `/System/Library/VideoCodecs/ave.videoencoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16afb8` | `0x16fc0c` | **`+0x4c54`** |
| `__TEXT.__cstring` | `0x4b2bf` | `0x4c3fc` | **`+0x113d`** |
| `__AUTH_CONST.__const` | `0x56d0` | `0x57d0` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x2f40` | `0x3020` | **`+0xe0`** |
| `__TEXT.__const` | `0x2535c` | `0x252b4` | **`-0xa8`** |
| `__TEXT.__unwind_info` | `0xa40` | `0xa48` | **`+0x8`** |

### Other Changes

```diff

-913.8.0.0.0
+913.29.1.0.0

-  Functions: 1518
-  Symbols:   2319
-  CStrings:  6252
+  Functions: 1527
+  Symbols:   2328
+  CStrings:  6331
Symbols:
+ __Z24AVE_DevCap_FindSwFeature12_E_AVE_DevID
+ __Z33AVE_Prop_HEVC_GetHEVCAuxiliaryIDsPvS_PK13__CFAllocatorPK10__CFStringS_
+ __Z33AVE_Prop_HEVC_SetHEVCAuxiliaryIDsPvS_PK10__CFStringPKv
+ __Z38AVE_Prop_HEVC_GetHEVCAuxiliaryLayerIDsPvS_PK13__CFAllocatorPK10__CFStringS_
+ __Z38AVE_Prop_HEVC_SetHEVCAuxiliaryLayerIDsPvS_PK10__CFStringPKv
+ __Z41AVE_Prop_HEVC_GetAuxiliaryLayerPropertiesPvS_PK13__CFAllocatorPK10__CFStringS_
+ __Z41AVE_Prop_HEVC_SetAuxiliaryLayerPropertiesPvS_PK10__CFStringPKv
+ __Z42AVE_Prop_HEVC_GetEncodesAuxiliaryWithAuxIDPvS_PK13__CFAllocatorPK10__CFStringS_
+ __Z42AVE_Prop_HEVC_SetEncodesAuxiliaryWithAuxIDPvS_PK10__CFStringPKv
CStrings:
+ "%lld %d AVE %s: %s:%d %s | auxiliary ID must be > 0 and < 160, received %d %p %lld %p %p %p"
+ "%lld %d AVE %s: %s:%d %s | auxiliary ID must be > 0 and < 160, received %d %p %lld %p %p %p\n"
+ "%lld %d AVE %s: %s:%d %s | expecting 1-%d values received %d %p %lld %p %p %p"
+ "%lld %d AVE %s: %s:%d %s | expecting 1-%d values received %d %p %lld %p %p %p\n"
+ "%lld %d AVE %s: %s:%d %s | fail to create CFDictionaryCreateMutable %p %lld %p %p %p %p %d"
+ "%lld %d AVE %s: %s:%d %s | fail to create CFDictionaryCreateMutable %p %lld %p %p %p %p %d\n"
+ "%lld %d AVE %s: %s:%d %s | fail to create height CFNumber %p %lld %p %p %p %p %d"
+ "%lld %d AVE %s: %s:%d %s | fail to create height CFNumber %p %lld %p %p %p %p %d\n"
+ "%lld %d AVE %s: %s:%d %s | fail to create width CFNumber %p %lld %p %p %p %p %d"
+ "%lld %d AVE %s: %s:%d %s | fail to create width CFNumber %p %lld %p %p %p %p %d\n"
+ "%lld %d AVE %s: %s:%d %s | fail to find AutoLevel profile string for profile=%d  %p %lld %p %p %p %p %d"
+ "%lld %d AVE %s: %s:%d %s | fail to find AutoLevel profile string for profile=%d  %p %lld %p %p %p %p %d\n"
+ "%lld %d AVE %s: %s:%d %s | fail to get Height from dictionary %p %lld %p %p %p"
+ "%lld %d AVE %s: %s:%d %s | fail to get Height from dictionary %p %lld %p %p %p\n"
+ "%lld %d AVE %s: %s:%d %s | fail to get ProfileLevel from dictionary %p %lld %p %p %p"
+ "%lld %d AVE %s: %s:%d %s | fail to get ProfileLevel from dictionary %p %lld %p %p %p\n"
+ "%lld %d AVE %s: %s:%d %s | fail to get Width from dictionary %p %lld %p %p %p"
+ "%lld %d AVE %s: %s:%d %s | fail to get Width from dictionary %p %lld %p %p %p\n"
+ "%lld %d AVE %s: %s:%d %s | failed to copy ProfileLevel string %p %lld %p %p %p %d"
+ "%lld %d AVE %s: %s:%d %s | failed to copy ProfileLevel string %p %lld %p %p %p %d\n"
+ "%lld %d AVE %s: %s:%d %s | invalid height=%d %p %lld %p %p %p"
+ "%lld %d AVE %s: %s:%d %s | invalid height=%d %p %lld %p %p %p\n"
+ "%lld %d AVE %s: %s:%d %s | invalid profile level string %p %lld %p %p %p"
+ "%lld %d AVE %s: %s:%d %s | invalid profile level string %p %lld %p %p %p\n"
+ "%lld %d AVE %s: %s:%d %s | invalid width=%d %p %lld %p %p %p"
+ "%lld %d AVE %s: %s:%d %s | invalid width=%d %p %lld %p %p %p\n"
+ "%lld %d AVE %s: %s:%d %s | layer ID must be > %d and < %d, received %d %p %lld %p %p %p"
+ "%lld %d AVE %s: %s:%d %s | layer ID must be > %d and < %d, received %d %p %lld %p %p %p\n"
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %d %d %lld"
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s:%d %s | wrong Height type %p %lld %p %p %p %ld"
+ "%lld %d AVE %s: %s:%d %s | wrong Height type %p %lld %p %p %p %ld\n"
+ "%lld %d AVE %s: %s:%d %s | wrong ProfileLevel type %p %lld %p %p %p %ld"
+ "%lld %d AVE %s: %s:%d %s | wrong ProfileLevel type %p %lld %p %p %p %ld\n"
+ "%lld %d AVE %s: %s:%d %s | wrong Width type %p %lld %p %p %p %ld"
+ "%lld %d AVE %s: %s:%d %s | wrong Width type %p %lld %p %p %p %ld\n"
+ "%lld %d AVE %s: %s::%s:%d  ps[%d] aveType=%d layerID=%d size=%d byte0=0x%02x byte1=0x%02x hevcNalType=%d"
+ "%lld %d AVE %s: %s::%s:%d  ps[%d] aveType=%d layerID=%d size=%d byte0=0x%02x byte1=0x%02x hevcNalType=%d\n"
+ "%lld %d AVE %s: %s::%s:%d VTEncoderSessionCreateVideoFormatDescription failed res=%d; dumping %d HEVC NAL units"
+ "%lld %d AVE %s: %s::%s:%d VTEncoderSessionCreateVideoFormatDescription failed res=%d; dumping %d HEVC NAL units\n"
+ "%s%s:%d:%d"
+ ","
+ "21:35:16"
+ "21:35:17"
+ "913.29.1"
+ "AVE_CalcBufSizeOfMBInputCtrl"
+ "AVE_Prop_HEVC_GetAuxiliaryLayerProperties"
+ "AVE_Prop_HEVC_GetEncodesAuxiliaryWithAuxID"
+ "AVE_Prop_HEVC_GetHEVCAuxiliaryIDs"
+ "AVE_Prop_HEVC_GetHEVCAuxiliaryLayerIDs"
+ "AVE_Prop_HEVC_SetAuxiliaryLayerProperties"
+ "AVE_Prop_HEVC_SetEncodesAuxiliaryWithAuxID"
+ "AVE_Prop_HEVC_SetHEVCAuxiliaryIDs"
+ "AVE_Prop_HEVC_SetHEVCAuxiliaryLayerIDs"
+ "AuxiliaryLayerHeight"
+ "AuxiliaryLayerProperties"
+ "AuxiliaryLayerProperties = "
+ "AuxiliaryLayerWidth"
+ "CFNumberGetTypeID() == CFGetTypeID(pHeightNum)"
+ "CFNumberGetTypeID() == CFGetTypeID(pWidthNum)"
+ "CFStringGetTypeID() == CFGetTypeID(pProfileLevelStr)"
+ "EncodesAuxiliaryWithAuxID"
+ "EncodesAuxiliaryWithAuxID = %d\n"
+ "HEVCAuxiliaryIDs"
+ "HEVCAuxiliaryIDs = "
+ "HEVCAuxiliaryLayerIDs"
+ "HEVCAuxiliaryLayerIDs = "
+ "Jul 14 2026"
+ "UserEncodeNumber"
+ "iAuxID > 0 && iAuxID < 160"
+ "iHeight > 0"
+ "iLayerID > 0 && iLayerID < (63 + 1)"
+ "iNum > 0 && iNum <= 8"
+ "iWidth > 0"
+ "kVTCompressionPropertyKey_AuxiliaryLayerProperties"
+ "kVTCompressionPropertyKey_EncodesAuxiliaryWithAuxID"
+ "kVTCompressionPropertyKey_HEVCAuxiliaryIDs"
+ "kVTCompressionPropertyKey_HEVCAuxiliaryLayerIDs"
+ "pHeightNum != __null"
+ "pProfileLevelStr != __null"
+ "pWidthNum != __null"
+ "size >= 0 && size <= 2147483647"
- "21:19:06"
- "913.8.0"
- "Jun 29 2026"
```
