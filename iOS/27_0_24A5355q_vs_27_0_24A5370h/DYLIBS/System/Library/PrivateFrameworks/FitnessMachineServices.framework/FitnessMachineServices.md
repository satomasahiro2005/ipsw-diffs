## FitnessMachineServices

> `/System/Library/PrivateFrameworks/FitnessMachineServices.framework/FitnessMachineServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4db5c` | `0x4df30` | **`+0x3d4`** |
| `__TEXT.__gcc_except_tab` | `0x414` | `0x458` | **`+0x44`** |
| `__DATA_CONST.__const` | `0x900` | `0x928` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xda0` | `0xdb8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1500` | `0x1518` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x640` | `0x650` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1288` | `0x1290` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2027.0.113.1.1
+2027.0.125.0.0

-  Functions: 2181
-  Symbols:   5258
+  Functions: 2182
+  Symbols:   5264
Symbols:
+ GCC_except_table30
+ GCC_except_table51
+ _OBJC_CLASS_$_UIAlertAction
+ _OBJC_CLASS_$_UIAlertController
+ _WKUIWorkoutUIBundle
+ ___97-[NLAPMachinePairingAlertUIController _presentUninterruptibleActiveWorkoutIntentViewWithMessage:]_block_invoke
+ ___block_descriptor_40_e8_32w_e23_v16?0"UIAlertAction"8lw32l8
- GCC_except_table50
Functions:
~ -[NLAPMachinePairingLogoView initWithFrame:] : 1080 -> 1160
~ -[NLAPMachinePairingLogoView _makeConnectingSpriteImageViewForStyle:] : 444 -> 468
~ -[NLAPMachinePairingAlertUIController _presentUninterruptibleActiveWorkoutIntentViewWithMessage:] : 216 -> 712
+ ___97-[NLAPMachinePairingAlertUIController _presentUninterruptibleActiveWorkoutIntentViewWithMessage:]_block_invoke
~ _$s22FitnessMachineServices0aB13PairingTesterC27observeTestingNotificationsyyF : 576 -> 580
~ _$s22FitnessMachineServices28SeymourCompatibilityProviderC07seymourE011machineType0D14CoreFoundation7PromiseVyAA0dE0O_SuSbtGSo010_HKFitnessbI0V_tF : 756 -> 760
~ _$s22FitnessMachineServices28SeymourCompatibilityProviderC07seymourE011machineType0D14CoreFoundation7PromiseVyAA0dE0O_SuSbtGSo010_HKFitnessbI0V_tFAK0dJ013ConfigurationVYbcfU0_ : 748 -> 740
~ ___swift_closure_destructor.25 : 140 -> 148
~ ___swift_closure_destructorTm : 148 -> 156
~ ___swift_closure_destructor.48 : 128 -> 136
~ _$s21SeymourCoreFoundation7PromiseV7success5valueACyxGx_tFZxyYbcfU_0aB013ConfigurationV_Tg5TA : 104 -> 112
~ _$s22FitnessMachineServices31MockSeymourAvailabilityProviderC15notifyObserversyyF : 336 -> 344
~ _$s22FitnessMachineServices0B21GuidedWorkoutLauncherC06launchdE018machineSessionUUID17workoutIdentifier9startTime10completionySS_SSSdys5Error_pSgYbctF : 3060 -> 3068
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 : 280 -> 276
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCs11AnyHashableV_ypTt0g5Tf4g_n : 256 -> 264
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_ypTt0g5Tf4g_n : 256 -> 276
~ _$s22FitnessMachineServices0B21GuidedWorkoutLauncherC06launchdE018machineSessionUUID17workoutIdentifier9startTime10completionySS_SSSdys5Error_pSgYbctF024$sSo7NSErrorCSgIeyBhy_s5P12_pSgIeghg_TRSo0S0CSgIeyBhy_Tf1nnncn_nTf4nnndg_n : 2964 -> 2944
~ ___swift_closure_destructorTm : 152 -> 160
~ _$s22FitnessMachineServices23SecureHostingControllerC5coderACyxGSgSo7NSCoderC_tcfc : 172 -> 176
~ _$s22FitnessMachineServices23SecureHostingControllerCfD : 124 -> 128
~ ___swift_closure_destructor.27Tm : 148 -> 156
~ _$s22FitnessMachineServices0B33GuidedWorkoutPickerViewControllerC010collectionG0_15didSelectItemAtySo012UICollectionG0C_10Foundation9IndexPathVtFys5Error_pYbcfU0_ytSgyYaYbScMYccfU_TA : 248 -> 252
~ _$s22FitnessMachineServices0B33GuidedWorkoutPickerViewControllerC010collectionG0_15didSelectItemAtySo012UICollectionG0C_10Foundation9IndexPathVtFy11SeymourCore16ResumableSessionVYbcfU_ytSgyYaYbScMYccfU_TA : 356 -> 360
~ _$s22FitnessMachineServices0B33GuidedWorkoutPickerViewControllerC12catalogStore19dependenciesWrapper15mediaTypeBridgeACSo09SMCatalogJ0C_So14SMDependenciesCSo0p5MediaN0Vtcfcy13SeymourClient22CatalogMetadataUpdatedVYbcfU_ytSgyYaYbScMYccfU_TA : 248 -> 252
~ _$s22FitnessMachineServices0B36PairingIntentConnectionStateProviderC6$state7Combine9PublishedV9PublisherVySo011NLAPMachinedefG0V_GvM.resume.0Tm : 232 -> 236
~ _$s22FitnessMachineServices25MockWheelchairUseProviderC15notifyObservers33_5A035EFE99A5728C1B1488B7778305F4LLyyF : 936 -> 932
~ _$s22FitnessMachineServices0B17PairingIntentViewV09containerF4_iOS33_1DF4A5DC906E290B45C9215F45954BAFLLQrvg7SwiftUI0F0PAFE16scrollIndicators_4axesQrAF25ScrollIndicatorVisibilityV_AF4AxisO3SetVtFQOyAhFE0S14BounceBehavior_AJQrAF0V14BounceBehaviorV_APtFQOyAF0vF0VyAhFE5frame8minWidth10idealWidth8maxWidth9minHeight11idealHeight9maxHeight9alignmentQr12CoreGraphics7CGFloatVSg_A5_A5_A5_A5_A5_AF9AlignmentVtFQOyAhFE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQOyAhFE7paddingyQrAF4EdgeOAOV_A5_tFQOyAC014pairingContentf2_iH0AELLQrvpQOy_Qo__Qo__Qo__Qo_G_Qo__Qo_AF13GeometryProxyVcfU_A22_yXEfU_yyYacfU_TA : 220 -> 224
~ _$s22FitnessMachineServices06RemoteB12PairingStateO7payloadSDySSs8Sendable_pGvg : 1196 -> 1180
~ _$ss17_NativeDictionaryV4copyyyF22FitnessMachineServices10PayloadKey33_DA329DDD2049B321F11536FA53B08B35LLO_s8Sendable_pTg5 : 376 -> 372
~ _$ss17_NativeDictionaryV5merge20trappingOnDuplicatesyqd__n_tSTRd__x_q_t7ElementRtd__lFSS_s8Sendable_pSaySS_sAG_ptGTg5Tf4gn_n : 488 -> 496
CStrings:
+ "spartan_connecting_sprite_ios"
+ "spartan_pulsing_sprite_ios"
+ "v16@?0@\"UIAlertAction\"8"
- "spartan_connecting_sprite"
- "spartan_pulsing_sprite"
- "spartan_small_connecting_sprite"
```
