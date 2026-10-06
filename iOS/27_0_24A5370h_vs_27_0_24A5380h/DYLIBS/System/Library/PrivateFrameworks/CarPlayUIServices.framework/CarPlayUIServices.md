## CarPlayUIServices

> `/System/Library/PrivateFrameworks/CarPlayUIServices.framework/CarPlayUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f598` | `0x38d18` | **`+0x9780`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x2018` | **`+0x2018`** |
| `__AUTH.__objc_data` | `0x2180` | `0x300` | **`-0x1e80`** |
| `__TEXT.__const` | `0x904` | `0xe94` | **`+0x590`** |
| `__TEXT.__constg_swiftt` | `0x26c` | `0x7a4` | **`+0x538`** |
| `__AUTH.__data` | `0x168` | `0x668` | **`+0x500`** |
| `__DATA.__bss` | `0xad0` | `0xec0` | **`+0x3f0`** |
| `__AUTH_CONST.__const` | `0xdb0` | `0x10d8` | **`+0x328`** |
| `__TEXT.__oslogstring` | `0x1474` | `0x1778` | **`+0x304`** |
| `__AUTH_CONST.__objc_const` | `0x11950` | `0x11c40` | **`+0x2f0`** |
| `__TEXT.__swift5_typeref` | `0x354` | `0x628` | **`+0x2d4`** |
| `__TEXT.__unwind_info` | `0xf18` | `0x1180` | **`+0x268`** |
| `__TEXT.__swift5_fieldmd` | `0x1b4` | `0x3a0` | **`+0x1ec`** |
| `__AUTH_CONST.__auth_got` | `0x780` | `0x960` | **`+0x1e0`** |
| `__TEXT.__swift5_reflstr` | `0x1be` | `0x34b` | **`+0x18d`** |
| `__DATA_DIRTY.__data` | `—` | `0x168` | **`+0x168`** |
| `__DATA.__data` | `0x14e0` | `0x1630` | **`+0x150`** |
| `__DATA_CONST.__got` | `0x5b0` | `0x6c8` | **`+0x118`** |
| `__TEXT.__eh_frame` | `0xe0` | `0x1d0` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x38f4` | `0x398c` | **`+0x98`** |
| `__TEXT.__swift5_capture` | `0x74` | `0xe4` | **`+0x70`** |
| `__TEXT.__swift5_assocty` | `0x60` | `0xc0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b30` | `0x1b78` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x15c0` | `0x1600` | **`+0x40`** |
| `__DATA_CONST.__const` | `0xb30` | `0xb68` | **`+0x38`** |
| `__DATA.__common` | `0x160` | `0x188` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x30` | `0x58` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x320` | `0x338` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x4c` | `0x60` | **`+0x14`** |
| `__TEXT.__cstring` | `0x1ac2` | `0x1ad2` | **`+0x10`** |

### Other Changes

```diff

-574.2.0.0.0
+577.2.0.0.0

+  - /System/Library/Frameworks/SwiftUI.framework/SwiftUI

+  - /usr/lib/swift/libswiftCoreAudio.dylib

+  - /usr/lib/swift/libswiftObservation.dylib

-  Functions: 1480
-  Symbols:   2797
-  CStrings:  385
+  Functions: 1696
+  Symbols:   2912
+  CStrings:  395
Symbols:
+ -[CRSUIClusterThemeManager resolveWallpaper:options:]
+ -[CRSUIInstrumentClusterSceneSettings sceneVariant]
+ -[CRSUIMutableInstrumentClusterSceneSettings sceneVariant]
+ -[CRSUIMutableInstrumentClusterSceneSettings setSceneVariant:]
+ -[CRSUISystemWallpaperProvider resolveWallpaper:options:]
+ _CATransform3DMakeAffineTransform
+ _CGRectGetHeight
+ _CGRectGetWidth
+ _OBJC_CLASS_$_CAState
+ _OBJC_METACLASS_$_CALayer
+ _OBJC_METACLASS_$__TtCO17CarPlayUIServices14CRSUICAPackageP33_4BBA49F6C9B1D1A214DD69B48DDD035D18CAPackageViewLayer
+ _UIRectGetCenter
+ __DATA__TtCO17CarPlayUIServices14CRSUICAPackageP33_4BBA49F6C9B1D1A214DD69B48DDD035D17AnimatedViewState
+ __DATA__TtCO17CarPlayUIServices14CRSUICAPackageP33_4BBA49F6C9B1D1A214DD69B48DDD035D18CAPackageViewLayer
+ __DATA__TtCO17CarPlayUIServices14CRSUICAPackageP33_4BBA49F6C9B1D1A214DD69B48DDD035D9ViewState
+ __INSTANCE_METHODS__TtCO17CarPlayUIServices14CRSUICAPackageP33_4BBA49F6C9B1D1A214DD69B48DDD035D18CAPackageViewLayer
+ __IVARS__TtCO17CarPlayUIServices14CRSUICAPackageP33_4BBA49F6C9B1D1A214DD69B48DDD035D17AnimatedViewState
+ __IVARS__TtCO17CarPlayUIServices14CRSUICAPackageP33_4BBA49F6C9B1D1A214DD69B48DDD035D18CAPackageViewLayer
+ __IVARS__TtCO17CarPlayUIServices14CRSUICAPackageP33_4BBA49F6C9B1D1A214DD69B48DDD035D9ViewState
+ __METACLASS_DATA__TtCO17CarPlayUIServices14CRSUICAPackageP33_4BBA49F6C9B1D1A214DD69B48DDD035D17AnimatedViewState
+ __METACLASS_DATA__TtCO17CarPlayUIServices14CRSUICAPackageP33_4BBA49F6C9B1D1A214DD69B48DDD035D18CAPackageViewLayer
+ __METACLASS_DATA__TtCO17CarPlayUIServices14CRSUICAPackageP33_4BBA49F6C9B1D1A214DD69B48DDD035D9ViewState
+ ___53-[CRSUIClusterThemeManager resolveWallpaper:options:]_block_invoke
+ ___swift_closure_destructor.136Tm
+ ___swift_closure_destructorTm
+ ___swift_instantiateGenericMetadata
+ ___swift_memcpy0_1
+ ___swift_memcpy48_8
+ __swift_FORCE_LOAD_$_swiftCoreAudio
+ __swift_FORCE_LOAD_$_swiftCoreAudio_$_CarPlayUIServices
+ _associated conformance 17CarPlayUIServices14CRSUICAPackageO12AnimatedViewV7SwiftUI0F0AA4BodyAfGP_AfG
+ _associated conformance 17CarPlayUIServices14CRSUICAPackageO13AnimationView33_4BBA49F6C9B1D1A214DD69B48DDD035DLLV7SwiftUI0F0AA4BodyAgHP_AgH
+ _associated conformance 17CarPlayUIServices14CRSUICAPackageO4ViewV7SwiftUIAdA4BodyAfDP_AfD
+ _get_witness_table 17CarPlayUIServices14CRSUICAPackageO13AnimationView33_4BBA49F6C9B1D1A214DD69B48DDD035DLLV7SwiftUI0F0HPyHC
+ _get_witness_table 7SwiftUI4ViewRzlAA15ModifiedContentVyxAA30_EnvironmentKeyWritingModifierVyAA5ColorVGGAaBHPxAaBHD1__AiA0cI0HPyHCHC
+ _get_witness_table qd0__7SwiftUI4ViewHD3_AaBPAAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQOyAA15ModifiedContentVy17CarPlayUIServices14CRSUICAPackageO09AnimationC033_4BBA49F6C9B1D1A214DD69B48DDD035DLLVAA25_AppearanceActionModifierVG_SbQo_HO
+ _get_witness_table qd0__7SwiftUI4ViewHD3_AaBPAAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQOyAcAEAdeF_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAA15ModifiedContentVyAA08_CALayerC0Vy17CarPlayUIServices14CRSUICAPackageO09CAPackageC5Layer33_4BBA49F6C9B1D1A214DD69B48DDD035DLLCGAA25_AppearanceActionModifierVG_SSSgQo__AA10ScenePhaseOQo_HO
+ _kCAFilterColorMonochrome
+ _kCAFilterInputBias
+ _kCAFilterInputColor
+ _kCAPackageTypeCAMLBundle
+ _swift_checkMetadataState
+ _swift_cvw_allocateGenericValueMetadataWithLayoutString
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithCopy
+ _swift_cvw_initWithTake
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_getAtKeyPath
+ _swift_getEnumCaseMultiPayload
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getGenericMetadata
+ _swift_getKeyPath
+ _swift_getOpaqueTypeConformance2
+ _swift_getSingletonMetadata
+ _swift_retain
+ _swift_retain_x21
+ _swift_retain_x23
+ _swift_retain_x8
+ _swift_storeEnumTagMultiPayload
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_updateClassMetadata2
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _symbolic $s7SwiftUI14EnvironmentKeyP
+ _symbolic $s7SwiftUI4ViewP
+ _symbolic SSSg
+ _symbolic So17CAStateControllerCSg
+ _symbolic So7CALayerCSg
+ _symbolic So7CAStateCSg
+ _symbolic So8NSBundleCSg
+ _symbolic So9CAPackageCSg
+ _symbolic _____ 11Observation0A9RegistrarV
+ _symbolic _____ 17CarPlayUIServices0abC9NamespaceV
+ _symbolic _____ 17CarPlayUIServices14CRSUICAPackageO
+ _symbolic _____ 17CarPlayUIServices14CRSUICAPackageO12AnimatedViewV
+ _symbolic _____ 17CarPlayUIServices14CRSUICAPackageO13AnimationView33_4BBA49F6C9B1D1A214DD69B48DDD035DLLV
+ _symbolic _____ 17CarPlayUIServices14CRSUICAPackageO17AnimatedViewState33_4BBA49F6C9B1D1A214DD69B48DDD035DLLC
+ _symbolic _____ 17CarPlayUIServices14CRSUICAPackageO18CAPackageViewLayer33_4BBA49F6C9B1D1A214DD69B48DDD035DLLC
+ _symbolic _____ 17CarPlayUIServices14CRSUICAPackageO4ViewV
+ _symbolic _____ 17CarPlayUIServices14CRSUICAPackageO9ViewState33_4BBA49F6C9B1D1A214DD69B48DDD035DLLC
+ _symbolic _____ 17CarPlayUIServices36CRSUICAPackageViewForegroundColorKeyV
+ _symbolic _____ 7SwiftUI10ScenePhaseO
+ _symbolic _____ 7SwiftUI11ColorSchemeO
+ _symbolic _____ 7SwiftUI17EnvironmentValuesV
+ _symbolic _____ 7SwiftUI5ColorV
+ _symbolic _____Sg So10CGColorRefa
+ _symbolic _____SgXw 17CarPlayUIServices14CRSUICAPackageO17AnimatedViewState33_4BBA49F6C9B1D1A214DD69B48DDD035DLLC
+ _symbolic _____y_____G 17CarPlayUIServices0abC9NamespaceV 7SwiftUI17EnvironmentValuesV
+ _symbolic _____y_____G 7SwiftUI11EnvironmentV AA10ScenePhaseO
+ _symbolic _____y_____G 7SwiftUI11EnvironmentV AA11ColorSchemeO
+ _symbolic _____y_____G 7SwiftUI11EnvironmentV AA5ColorV
+ _symbolic _____y_____G 7SwiftUI12_CALayerViewV 17CarPlayUIServices14CRSUICAPackageO09CAPackageD5Layer33_4BBA49F6C9B1D1A214DD69B48DDD035DLLC
+ _symbolic _____y_____G 7SwiftUI30_EnvironmentKeyWritingModifierV AA5ColorV
+ _symbolic _____y_____G 7SwiftUI5StateV 17CarPlayUIServices14CRSUICAPackageO012AnimatedViewC033_4BBA49F6C9B1D1A214DD69B48DDD035DLLC
+ _symbolic _____y_____G 7SwiftUI5StateV 17CarPlayUIServices14CRSUICAPackageO04ViewC033_4BBA49F6C9B1D1A214DD69B48DDD035DLLC
+ _symbolic _____y_____G 7SwiftUI9LazyStateV 17CarPlayUIServices14CRSUICAPackageO012AnimatedViewD033_4BBA49F6C9B1D1A214DD69B48DDD035DLLC
+ _symbolic _____y______G 7SwiftUI11EnvironmentV7ContentO AA10ScenePhaseO
+ _symbolic _____y______G 7SwiftUI11EnvironmentV7ContentO AA11ColorSchemeO
+ _symbolic _____y______G 7SwiftUI9LazyStateV7StorageO 17CarPlayUIServices14CRSUICAPackageO012AnimatedViewD033_4BBA49F6C9B1D1A214DD69B48DDD035DLLC
+ _symbolic _____y______G_yXlSgt 7SwiftUI9LazyStateV7StorageO 17CarPlayUIServices14CRSUICAPackageO012AnimatedViewD033_4BBA49F6C9B1D1A214DD69B48DDD035DLLC
+ _symbolic _____y__________G 7SwiftUI15ModifiedContentV 17CarPlayUIServices14CRSUICAPackageO13AnimationView33_4BBA49F6C9B1D1A214DD69B48DDD035DLLV AA25_AppearanceActionModifierV
+ _symbolic _____y_____y_____G_____G 7SwiftUI15ModifiedContentV AA12_CALayerViewV 17CarPlayUIServices14CRSUICAPackageO09CAPackageF5Layer33_4BBA49F6C9B1D1A214DD69B48DDD035DLLC AA25_AppearanceActionModifierV
+ _symbolic _____y_____y__________G_SbQo_ 7SwiftUI4ViewPAAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQO AA15ModifiedContentV 17CarPlayUIServices14CRSUICAPackageO09AnimationC033_4BBA49F6C9B1D1A214DD69B48DDD035DLLV AA25_AppearanceActionModifierV
+ _symbolic _____y_____y_____y_____G_____G_SSSgQo_ 7SwiftUI4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA15ModifiedContentV AA08_CALayerC0V 17CarPlayUIServices14CRSUICAPackageO09CAPackageC5Layer33_4BBA49F6C9B1D1A214DD69B48DDD035DLLC AA25_AppearanceActionModifierV
+ _symbolic _____y_____y_____y_____y_____G_____G_SSSgQo_______Qo_ 7SwiftUI4ViewPAAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQO AcAEAdeF_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA15ModifiedContentV AA08_CALayerC0V 17CarPlayUIServices14CRSUICAPackageO09CAPackageC5Layer33_4BBA49F6C9B1D1A214DD69B48DDD035DLLC AA25_AppearanceActionModifierV AA10ScenePhaseO
+ _symbolic _____yxG 17CarPlayUIServices0abC9NamespaceV
+ _symbolic _____yx_____y_____GG 7SwiftUI15ModifiedContentV AA30_EnvironmentKeyWritingModifierV AA5ColorV
+ _symbolic _____yypG s23_ContiguousArrayStorageC
+ _symbolic qd__
+ _symbolic ySo9CAPackageCcSg
+ _symbolic yyc
+ _type_layout_string 17CarPlayUIServices14CRSUICAPackageO4ViewV
- ___45-[CRSUIClusterThemeManager resolveWallpaper:]_block_invoke
CStrings:
+ " sceneVariant: %@"
+ "%{public}s: %{public}s CAPackageView _CALayerView update closure called with state %{public}s"
+ "%{public}s: %{public}s CAPackageView appeared, updating state to %{public}s"
+ "%{public}s: %{public}s CAPackageView scene phase changed to %{public}s, updating state to %{public}s"
+ "%{public}s: %{public}s CAPackageView selected state changed from %{public}s to %{public}s"
+ "%{public}s: %{public}s ViewState ignoring update to %{public}s: state already set"
+ "%{public}s: %{public}s ViewState loaded package "
+ "%{public}s: %{public}s ViewState updating stateController to %{public}s"
+ "(nil)"
+ "Accessing Environment<%s>'s value outside of being installed on a View. This will always read the default value and will not update."
```
