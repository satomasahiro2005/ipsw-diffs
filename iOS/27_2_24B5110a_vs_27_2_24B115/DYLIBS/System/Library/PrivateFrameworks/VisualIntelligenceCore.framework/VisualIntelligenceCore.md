## VisualIntelligenceCore

> `/System/Library/PrivateFrameworks/VisualIntelligenceCore.framework/VisualIntelligenceCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5fb590` | `0x613138` | **`+0x17ba8`** |
| `__TEXT.__eh_frame` | `0x22908` | `0x22e68` | **`+0x560`** |
| `__TEXT.__oslogstring` | `0xb0a6` | `0xb3c6` | **`+0x320`** |
| `__TEXT.__cstring` | `0xfa3f` | `0xfc0f` | **`+0x1d0`** |
| `__AUTH_CONST.__const` | `0x29af8` | `0x29c40` | **`+0x148`** |
| `__TEXT.__unwind_info` | `0x12698` | `0x127b0` | **`+0x118`** |
| `__TEXT.__const` | `0x4b9fc` | `0x4bafc` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0x113ad` | `0x1149d` | **`+0xf0`** |
| `__DATA.__data` | `0xa714` | `0xa7b4` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x22c4` | `0x2334` | **`+0x70`** |
| `__TEXT.__lazy_helpers` | `0x1a94` | `0x1ae8` | **`+0x54`** |
| `__AUTH_CONST.__auth_got` | `0x3df8` | `0x3e48` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x1578` | `0x15a4` | **`+0x2c`** |
| `__TEXT.__swift_as_ret` | `0x9a4` | `0x9c0` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x1730` | `0x1740` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0xc828` | `0xc838` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x8c8` | `0x8d4` | **`+0xc`** |
| `__AUTH_CONST.__lazy_load_got` | `0x228` | `0x230` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1f50` | `0x1f58` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 24508
-  Symbols:   7574
-  CStrings:  2251
+  Functions: 24609
+  Symbols:   7596
+  CStrings:  2271
Symbols:
+ _CGContextAddPath
+ _CGContextStrokePath
+ _CGDataProviderCreateWithURL
+ _CGImageCreateWithPNGDataProvider
+ _CGPathCreateWithRoundedRect
+ _CTFontCreateUIFontForLanguage
+ _CTFontCreateUIFontForLanguage$lazyAuthGOT_IA_ad_0
+ _CTFontCreateUIFontForLanguage$lazyLoadStub
+ ___swift_closure_destructor.191Tm
+ ___swift_closure_destructor.204Tm
+ ___swift_closure_destructor.231Tm
+ ___swift_closure_destructor.70Tm
+ _symbolic SS5title_SS5valuet
+ _symbolic SdIegd_
+ _symbolic Si6offset______7elementt 22VisualIntelligenceCore27NutritionAdapterFoodContentV
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
- ___swift_closure_destructor.69Tm
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
+ "nutritionLookup-postProcessedOutputTokens_boxes.png"
+ "nutritionLookup-postProcessedOutputTokens_image"
+ "openMissedPauseRadarDraft: failed to construct or open draft URL: %s"
+ "openMissingIntelligenceRadarDraft: failed to construct or open draft URL: %s"
+ "retainedHEICURL: materialization failed for timestamp %f: %@"
- "openMissedPauseRadarDraft: TTR unavailable on this platform/build; dropping request."
- "openMissingIntelligenceRadarDraft: TTR unavailable on this platform/build; dropping request."
```
