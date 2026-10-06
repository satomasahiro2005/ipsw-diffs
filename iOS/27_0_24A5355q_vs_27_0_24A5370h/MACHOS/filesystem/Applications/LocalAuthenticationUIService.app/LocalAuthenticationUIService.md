## LocalAuthenticationUIService

> `/Applications/LocalAuthenticationUIService.app/LocalAuthenticationUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c1ac` | `0x6c15c` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x34c8` | `0x34a0` | **`-0x28`** |
| `__TEXT.__const` | `0x3424` | `0x3444` | **`+0x20`** |
| `__TEXT.__cstring` | `0x159e` | `0x157e` | **`-0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2305.0.0.0.1
+2319.0.16.502.1

-  Functions: 2647
-  Symbols:   7851
-  CStrings:  2344
+  Functions: 2646
+  Symbols:   7849
+  CStrings:  2343
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PasscodeContentViewControllerFullScreen-ea505ba7b87a9b6bdbbd8d150c96718e.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PinViewController-66ef26aea9eff4a2deb9e65b8e29fd81.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PasscodeContentViewControllerFullScreen-471fb702a0ffe9b89cdf87e68d57d268.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PinViewController-f3a6e8af644bbe048f7552884213915b.o
- ___45-[PasscodeViewController _showPasscodeScreen]_block_invoke
- ___block_descriptor_40_e8_32s_e29_"LACUIPasscodeViewState"8?0ls32l8
Functions:
~ -[TransitionViewController didReceiveAuthenticationData] : 1204 -> 1192
~ -[TransitionViewController _destroyScenesSessions:] : 800 -> 796
~ -[TransitionViewController _allSceneSessions] : 528 -> 520
~ -[PasscodeEmbeddedViewController loadView] : 3588 -> 3584
~ -[PasscodeEmbeddedViewController traitCollectionDidChange:] : 640 -> 636
~ -[PasscodeViewController _showPasscodeScreen] : 156 -> 412
- ___45-[PasscodeViewController _showPasscodeScreen]_block_invoke
~ -[TouchIdAlertController setActions:] : 292 -> 288
~ -[PasscodeContentViewBackground _removePreviousBackgroundFromView:] : 300 -> 296
~ _$ss17_NativeDictionaryV4copyyyFs11AnyHashableV_ypTg5 : 392 -> 384
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCs11AnyHashableV_ypTt0g5Tf4g_n : 256 -> 264
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSi_SbTt0g5Tf4g_n : 220 -> 232
~ _$s28LocalAuthenticationUIService25SceneControllerFrontBoardC15sceneDidConnect_7options4urlsySo10LACUIScene_p_SDys11AnyHashableVypGSgSay10Foundation3URLVGSgtF : 948 -> 956
~ _$s28LocalAuthenticationUIService25SceneControllerFrontBoardC02isD12Deactivating15sceneIdentifierSbSS_tF : 840 -> 848
~ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtFSS_SSTg5 : 692 -> 684
~ _$ss17_NativeDictionaryV4copyyyFSS_SSTg5 : 376 -> 372
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 : 280 -> 276
~ _$ss17_NativeDictionaryV5merge_8isUnique16uniquingKeysWithyqd__n_Sbq_q__q_tqd_0_YKXEtqd_0_YKSTRd__s5ErrorRd_0_x_q_t7ElementRtd__r0_lFSS_SSSaySS_SStGs5NeverOTg5170$s28LocalAuthenticationUIService25SceneControllerFrontBoardC15sceneDidConnect_7options4urlsySo10LACUIScene_p_SDys11AnyHashableVypGSgSay10Foundation3URLVGSgtFS2S_SStXEfU0_Tf1nncn_nTf4gnn_n : 736 -> 748
~ _$s28LocalAuthenticationUIService31BiometryCompanionViewControllerC13viewDidAppearyySbF : 1016 -> 1020
~ _$s28LocalAuthenticationUIService19TransitionViewModelC14mechanismEvent_5value5replyySo012LACMechanismH0V_ypSgyycSgtF : 584 -> 600
~ __swift_closure_destructor.30 : 128 -> 136
~ _$s28LocalAuthenticationUIService19TransitionViewModelC15setupConnection12withEndpointySo013NSXPCListenerJ0C_tFys5Error_pcfU1_TA : 376 -> 380
~ __swift_closure_destructor.37 : 148 -> 156
~ _$s28LocalAuthenticationUIService19TransitionViewModelC15setupConnection12withEndpointySo013NSXPCListenerJ0C_tFySo14LACUIMechanism_pSg_So17LACBackoffCounter_pSg10Foundation4DataVSgs5Error_pSgtYbcfU2_TA : 924 -> 928
~ _$s28LocalAuthenticationUIService19TransitionViewModelC12setupBinding33_F7639C7524F389F0AAFE4A2F9CA35C1DLLyyFySo21LACRemoteUIControllerV10controller_SDys11AnyHashableVypG12internalInfoSo14LACUIMechanism_p9mechanism10Foundation4DataVSg19externalizedContextySb_s5Error_pSgtcSg17completionHandlert_tcfU6_TA : 1108 -> 1100
~ _$s28LocalAuthenticationUIService26SceneControllerRemoteAlertC02isD12Deactivating15sceneIdentifierSbSS_tF : 840 -> 848
~ _$sSlsE3mapySayqd__Gqd__7ElementQzqd_0_YKXEqd_0_YKs5ErrorRd_0_r0_lFShySo16UIOpenURLContextCG_10Foundation3URLVs5NeverOTg50162$s28LocalAuthenticationUIService24SceneDelegateRemoteAlertC5scene_13willConnectTo7optionsySo7UISceneC_So0M7SessionCSo0M17ConnectionOptionsCtF10Foundation3URLVSo16dE6CXEfU_Tf1cn_n : 1028 -> 1012
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF10Foundation3URLV_Tg5 : 472 -> 476
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_SSTt0g5Tf4g_n : 272 -> 276
~ $s28LocalAuthenticationUIService22AuthorizationViewModelC05$showdE07Combine9PublishedV9PublisherVySb_GvM.resume.0Tm : 232 -> 236
~ _$s28LocalAuthenticationUIService22AuthorizationViewModelC11lockoutTextSSSgvg : 1184 -> 1188
~ _$s28LocalAuthenticationUIService22AuthorizationViewModelCMr : 772 -> 780
~ _$sSlsE3mapySayqd__Gqd__7ElementQzqd_0_YKXEqd_0_YKs5ErrorRd_0_r0_lFShySo16UIOpenURLContextCG_10Foundation3URLVs5NeverOTg50161$s28LocalAuthenticationUIService23SceneDelegateFrontBoardC5scene_13willConnectTo7optionsySo7UISceneC_So0M7SessionCSo0M17ConnectionOptionsCtF10Foundation3URLVSo16dE6CXEfU_Tf1cn_n : 1028 -> 1012
~ _$s28LocalAuthenticationUIService11LogCategoryVs25ExpressibleByArrayLiteralAAsADP05arrayI0x0hI7ElementQzd_tcfCTW : 172 -> 176
~ _$ss17_NativeDictionaryV4copyyyFSS_2os6LoggerVTg5 : 652 -> 648
CStrings:
- "@\"LACUIPasscodeViewState\"8@?0"
```
