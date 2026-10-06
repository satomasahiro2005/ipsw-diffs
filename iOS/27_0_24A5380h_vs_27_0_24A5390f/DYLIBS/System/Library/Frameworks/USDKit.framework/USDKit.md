## USDKit

> `/System/Library/Frameworks/USDKit.framework/USDKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2dafe0` | `0x2dc7b4` | **`+0x17d4`** |
| `__TEXT.__eh_frame` | `0xb36a0` | `0xb3890` | **`+0x1f0`** |
| `__TEXT.__gcc_except_tab` | `0x45a5c` | `0x45bc4` | **`+0x168`** |
| `__TEXT.__cstring` | `0x172ea` | `0x1744a` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0x44440` | `0x444e8` | **`+0xa8`** |
| `__AUTH_CONST.__const` | `0x23af0` | `0x23b90` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x22c` | `0x25c` | **`+0x30`** |
| `__TEXT.__const` | `0x2cfb5` | `0x2cfa5` | **`-0x10`** |

### Other Changes

```diff

-106.0.5.0.1
+106.0.7.0.0

-  Functions: 34518
-  Symbols:   64147
-  CStrings:  921
+  Functions: 34536
+  Symbols:   64159
+  CStrings:  929
Symbols:
+ _$s6USDKit038SdfLayerStateDelegateProxy_MarkCurrentD7AsDirty05layerdeF0yyXl_tF
+ _$s6USDKit7USDPrimV9AttributeV5clearSbyF
+ _$s6USDKit7USDPrimV9AttributeV5value2atxSgAA8USDStageV8TimeCodeV_tAE5ValueRzlF
+ _$s6USDKit7USDPrimV9AttributeV8setValue_2atSbx_AA8USDStageV8TimeCodeVtAE0E0RzlF
+ _$s6USDKit8USDStageV13exportPackage7options10Foundation4DataVAC13ExportOptionsV_tKF
+ _$s6USDKit8USDStageV13exportPackage7options10Foundation4DataVAC13ExportOptionsV_tKFAHyKXEfU_
+ _$s6USDKit8USDStageV18packageStageToData33_57162A78D47379E2A596B8953E4FE2D0LL10Foundation0F0VyKF
+ _$s6USDKit8USDStageV18packageStageToData33_57162A78D47379E2A596B8953E4FE2D0LL10Foundation0F0VyKFySv_SitcfU_TA
+ _$s6USDKit8USDStageV19compressStageToData33_57162A78D47379E2A596B8953E4FE2D0LL7options10Foundation0F0VAC13ExportOptionsV_tKF
+ _$s6USDKit8USDStageV19compressStageToData33_57162A78D47379E2A596B8953E4FE2D0LL7options10Foundation0F0VAC13ExportOptionsV_tKFySv_SitcfU_TA
+ _$s6USDKit8USDStageV33validateAllDependenciesResolvable33_57162A78D47379E2A596B8953E4FE2D0LLyyKF
+ _$sSo019pxrInternal__aapl__A10Reserved__O0060TfWeakPtrpxrInternal__aapl__pxrReserved__SdfLayer_lxHGtqtareVAB22UsdUtilsDependencyInfoVAFIeyBnnr_Ad2FIegnnr_TR
+ __USDStageKitSwift_SdfLayerStateDelegateProxy_MarkCurrentStateAsDirty
+ __ZN17aaplUsdGclOverlayL24compressedStageBitstreamERKN32pxrInternal__aapl__pxrReserved__12VtDictionaryE
- __Z57__release__ZN32pxrInternal__aapl__pxrReserved__8SdfLayerEPN32pxrInternal__aapl__pxrReserved__8SdfLayerE
- __ZN32pxrInternal__aapl__pxrReserved__8TfRefPtrINS_8SdfLayerEE16_RemoveRefStaticEPKNS_9TfRefBaseE
CStrings:
+ " referenced asset(s) could not be resolved:"
+ "Could not compute dependencies for root layer '"
+ "Export aborted: "
+ "Failed to compress stage to data (code "
+ "Failed to package stage to data."
+ "Failed to read compressed stage data."
+ "Failed to read packaged stage data."
+ "exportPackageToData"
```
