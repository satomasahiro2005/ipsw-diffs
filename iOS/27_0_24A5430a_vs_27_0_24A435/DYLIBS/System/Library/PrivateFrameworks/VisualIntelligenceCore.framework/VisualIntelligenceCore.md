## VisualIntelligenceCore

> `/System/Library/PrivateFrameworks/VisualIntelligenceCore.framework/VisualIntelligenceCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5ba8ac` | `0x5d215c` | **`+0x178b0`** |
| `__TEXT.__eh_frame` | `0x21848` | `0x21da8` | **`+0x560`** |
| `__TEXT.__oslogstring` | `0xa8b6` | `0xabd6` | **`+0x320`** |
| `__TEXT.__cstring` | `0xe98f` | `0xeb1f` | **`+0x190`** |
| `__TEXT.__const` | `0x4a02c` | `0x4a17c` | **`+0x150`** |
| `__AUTH_CONST.__const` | `0x28ae8` | `0x28c30` | **`+0x148`** |
| `__TEXT.__unwind_info` | `0x11ee0` | `0x12018` | **`+0x138`** |
| `__TEXT.__swift5_typeref` | `0x1105f` | `0x1115f` | **`+0x100`** |
| `__DATA.__data` | `0xac18` | `0xaca8` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0xd040` | `0xd0b0` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x22a0` | `0x2310` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x3cd8` | `0x3d30` | **`+0x58`** |
| `__TEXT.__lazy_helpers` | `0x1b3c` | `0x1b90` | **`+0x54`** |
| `__TEXT.__swift_as_cont` | `0x1508` | `0x1534` | **`+0x2c`** |
| `__DATA_CONST.__objc_selrefs` | `0x1718` | `0x1738` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x97c` | `0x998` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x186c` | `0x1884` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x8ac` | `0x8b8` | **`+0xc`** |
| `__AUTH_CONST.__lazy_load_got` | `0x230` | `0x238` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1ea8` | `0x1eb0` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 23863
-  Symbols:   7455
-  CStrings:  2125
+  Functions: 23962
+  Symbols:   7477
+  CStrings:  2144
Symbols:
+ _CGContextAddPath
+ _CGContextStrokePath
+ _CGDataProviderCreateWithURL
+ _CGImageCreateWithPNGDataProvider
+ _CGPathCreateWithRoundedRect
+ _CTFontCreateUIFontForLanguage
+ _CTFontCreateUIFontForLanguage$lazyAuthGOT_IA_ad_0
+ _CTFontCreateUIFontForLanguage$lazyLoadStub
+ _MGGetProductType
+ ___swift_closure_destructor.191Tm
+ ___swift_closure_destructor.204Tm
+ ___swift_closure_destructor.231Tm
+ ___swift_closure_destructor.69Tm
+ _symbolic SS5title_SS5valuet
+ _symbolic SdIegd_
+ _symbolic Si6offset_______Sft7elementt 22VisualIntelligenceCore8CVBundleV
+ _symbolic _____SgXw 22VisualIntelligenceCore21BuiltInActionExecutorC
+ _symbolic ______SSt So10CGImageRefa
+ _symbolic ______Sft 10Foundation4UUIDV
+ _symbolic ______Sit 10Foundation4UUIDV
+ _symbolic _____ySS5title_SS5valuetG s23_ContiguousArrayStorageC
+ _symbolic _____y_____SfG s18_DictionaryStorageC 10Foundation4UUIDV
+ _symbolic _____y______SStG s23_ContiguousArrayStorageC So10CGImageRefa
+ _symbolic _____y______SftG s23_ContiguousArrayStorageC 10Foundation4UUIDV
+ _symbolic _____y______SitG s23_ContiguousArrayStorageC 10Foundation4UUIDV
+ _symbolic _____yySpy_____Gz_SpySo8NSObjectCSgGSgzSpyypGSgztcG s23_ContiguousArrayStorageC s5UInt8V
- ___swift_closure_destructor.180Tm
- ___swift_closure_destructor.193Tm
- ___swift_closure_destructor.220Tm
- ___swift_closure_destructor.68Tm
CStrings:
+ " \"Unavailable\" overlay shown unexpectedly"
+ " Shutter failed to pause"
+ "Cannot PNG-encode pixel buffer for TTR debug artifact: %{public}s"
+ "Cannot serialize AFM to JSON for debug artifact: %s"
+ "Failed to obtain pixel buffer for TTR draft attachment"
+ "InProcessStream prepareTapToRadarDraft: image attachment failed: %s"
+ "Original_Still.png"
+ "Still_pixelbuffer."
+ "TTROverlayRenderer renderOverlay failed to create CGContext, no-op'ing."
+ "TTROverlayRenderer renderOverlay invalid dimensions w: %f h: %f, no-op'ing."
+ "The Visual Intelligence \"Unavailable\" overlay appeared in a state that should be unreachable for an external user.\n\nEntry point: "
+ "createTapToRadar: attached HEIC for entity %s"
+ "createTapToRadar: cancelled while waiting for entity"
+ "createTapToRadar: could not get entity for HEIC: %s"
+ "createTapToRadar: entity %s had no retained HEIC, will fall back to PNG"
+ "createTapToRadar: entity not available in time, proceeding without HEIC"
+ "createTapToRadar: fell back to PNG attachment"
+ "nutritionLookup-postProcessedOutputTokens_image"
+ "openMissedPauseRadarDraft: failed to construct or open draft URL: %s"
+ "openMissingIntelligenceRadarDraft: failed to construct or open draft URL: %s"
+ "retainedHEICURL: materialization failed for timestamp %f: %@"
- "openMissedPauseRadarDraft: TTR unavailable on this platform/build; dropping request."
- "openMissingIntelligenceRadarDraft: TTR unavailable on this platform/build; dropping request."
```
