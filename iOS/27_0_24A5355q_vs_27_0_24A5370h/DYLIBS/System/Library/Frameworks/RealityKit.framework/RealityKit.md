## RealityKit

> `/System/Library/Frameworks/RealityKit.framework/RealityKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7acfc` | `0x7aeec` | **`+0x1f0`** |
| `__AUTH_CONST.__auth_got` | `0x2688` | `0x2698` | **`+0x10`** |
| `__TEXT.__const` | `0x47c0` | `0x47d0` | **`+0x10`** |

### Other Changes

```diff

-453.0.0.0.11
+453.0.2.0.5

-  - /System/Library/Frameworks/MobileCoreServices.framework/MobileCoreServices

-  Functions: 2715
-  Symbols:   7440
+  Functions: 2716
+  Symbols:   7443
Symbols:
+ _$s10RealityKit5SceneC0A10FoundationE5rolesSo12RESceneRolesVvM
+ _$s10RealityKit5SceneC0A10FoundationE5rolesSo12RESceneRolesVvs
+ _$s10RealityKit6ARViewC7setupARyyF
Functions:
~ _$s10RealityKit43GroupActivitiesSynchronizationDiscoveryViewC6remove11participanty0cD011ParticipantV_tF : 572 -> 576
~ _$s10RealityKit43GroupActivitiesSynchronizationProtocolLayerC7sessionAC0cD00C7SessionCyxG_tcAE0C8ActivityRzlufcys13OpaquePointerV_SbtcfU2_ : 296 -> 304
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 : 280 -> 276
~ _$s10RealityKit37GroupActivitiesSynchronizationServiceC13giveOwnership2of6toPeerSbAA6EntityC_AA0eK2ID_ptF : 872 -> 860
~ _$s10RealityKit37GroupActivitiesSynchronizationServiceC8__toCore6peerIDAA11__PeerIDRefVAA0ekJ0_p_tF : 832 -> 840
~ _$s10RealityKit37GroupActivitiesSynchronizationSessionC7session13discoveryViewACyxG0cD00cF0CyxG_AA0cde9DiscoveryI0CtcfcyAI5StateOyx_GcfU1_ : 1124 -> 1128
~ _$s10RealityKit37GroupActivitiesSynchronizationSessionC7session13discoveryViewACyxG0cD00cF0CyxG_AA0cde9DiscoveryI0CtcfcyShyAG11ParticipantVGcfU2_yANXEfU_ : 644 -> 628
~ _$s17RealityFoundation24ParticleEmitterComponentV0A3KitE6timingAcDE6TimingOvg : 364 -> 356
~ _$sSlsE3mapySayqd__Gqd__7ElementQzqd_0_YKXEqd_0_YKs5ErrorRd_0_r0_lFShy17RealityFoundation22SpatialTrackingSessionC13ConfigurationV16AnchorCapabilityVG_SSs5NeverOTg504$s17d12Foundation22fgh57C23UnavailableCapabilitiesV0A3KitE11descriptionSSvgSSAC13i3V16jK54Vcfu_33_0e2f2957bef5a9ec78f2a038ea1e8673AKSSTf3nnnpk_nTf1cn_nTm : 788 -> 796
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF10RealityKit015ARConfigurationE6ResultV_Tg5Tm : 480 -> 484
~ _$s10RealityKit35ARWorldTrackingConfigurationBuilderV010supportingE00A10Foundation07SpatialD7SessionC0E0VyF : 1116 -> 1096
~ _$s10RealityKit34ARFaceTrackingConfigurationBuilderV010supportingE00A10Foundation07SpatialD7SessionC0E0VyF : 712 -> 724
~ _$s10RealityKit21createARConfiguration22requestedConfigurationAA0D12CreateResultVSg0A10Foundation22SpatialTrackingSessionC0F0V_tF : 1024 -> 1108
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_ypTt0gq5Tf4g_n : 256 -> 276
~ _$s10RealityKit16ARSessionManagerC32runARKitSessionWithoutRequesting25withSupportedCapabilitiesy0A10Foundation015SpatialTrackingG0C13ConfigurationV_tFAH011UnavailableL0VSgyYacfU_TA.29 : 248 -> 252
~ _$s10RealityKit6ARViewC5frame10cameraModeACSo6CGRectV_AC06CameraF0OtcfC : 180 -> 120
~ _$s10RealityKit6ARViewC5frame10cameraMode29automaticallyConfigureSessionACSo6CGRectV_AC06CameraF0OSbtcfc : 952 -> 888
~ _$s10RealityKit6ARViewC16doUpdateCallback6engine9deltaTimeyAA8__EngineC_SftF : 2256 -> 2264
~ _$s10RealityKit6ARViewC23onDrawingManagerCreatedyyF : 592 -> 608
~ _$s10RealityKit6ARViewC14checkProximity33_0FA867E138516716E31F9F5CDB435E5BLLyyF : 1704 -> 1712
~ _$s10RealityKit6ARViewC10commonInityyAA8__EngineCSgFTf4dn_n : 2304 -> 2168
~ _$s10RealityKit6ARViewC10cameraModeAC06CameraE0Ovs : 132 -> 248
+ _$s10RealityKit6ARViewC7setupARyyF
~ _$s10RealityKit6ARViewC10cameraModeAC06CameraE0OvM.resume.0 : 156 -> 72
~ _$s10RealityKit6ARViewC31updateReferenceObjectsAndImages33_13C3C1EE7E90C9B899AEA8AAB2DF1D7ALLyyF : 2540 -> 2532
~ _$s10RealityKit6ARViewC28requiredSessionConfiguration33_13C3C1EE7E90C9B899AEA8AAB2DF1D7ALL13currentConfigSbSo15ARConfigurationCSgz_tF : 4028 -> 4112
~ _$s10RealityKit6ARViewC41compareReferenceImageNamesAndWidthByGroup33_13C3C1EE7E90C9B899AEA8AAB2DF1D7ALL09referencefghijK0SbSDySSSaySS_12CoreGraphics7CGFloatVtGG_tF : 928 -> 944
~ _$sSTsSQ7ElementRpzrlE13elementsEqualySbqd__STRd__AAQyd__ABRSlFSaySSG_AETg5 : 308 -> 316
~ _$s10RealityKit6ARViewC19loadReferenceImages33_13C3C1EE7E90C9B899AEA8AAB2DF1D7ALLyShySo16ARReferenceImageCGSDySSSaySS_12CoreGraphics7CGFloatVtGGF : 3900 -> 3896
~ _$s10RealityKit6ARViewC20loadReferenceObjects33_13C3C1EE7E90C9B899AEA8AAB2DF1D7ALLyShySo17ARReferenceObjectCGSDySSSaySSGGF : 3748 -> 3716
~ _$sSTsSQ7ElementRpzrlE8containsySbABFSaySSG_Tg5 : 116 -> 132
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_SaySS_12CoreGraphics7CGFloatVtGTt0g5Tf4g_nTm : 244 -> 268
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfC10Foundation4UUIDV_10RealityKit6EntityCTt0g5Tf4g_nTm : 424 -> 420
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfC10RealityKit10RKARSystemC18HitTestScreenPoint33_7C42569567E429B6AB2725E2C535D529LLV_AC013CollisionCastF0VSgTt0g5Tf4g_n : 420 -> 416
~ _$s10RealityKit6ARViewC23updateEnvironmentReverb020_EF0F98D1B43B5A1E846K11D992B3E9F7CLLyyAC0E0V0F0OF : 192 -> 188
~ _$s10RealityKit6ARViewC11EnvironmentVwst : 104 -> 96
~ _$s10RealityKit6ARViewC15installGestures_3forSayAA23EntityGestureRecognizer_pGAC0gE0V_AA12HasCollision_ptF : 828 -> 848
~ _$s10RealityKit6ARViewC8entities2atSayAA6EntityCGSo7CGPointV_tF : 736 -> 744
~ _$ss10SetAlgebraPs7ElementQz012ArrayLiteralC0RtzrlE05arrayE0xAFd_tcfC10RealityKit6ARViewC19__StatisticsOptionsV_Tg5Tm : 204 -> 196
~ _$ss10SetAlgebraPs7ElementQz012ArrayLiteralC0RtzrlE05arrayE0xAFd_tcfC10RealityKit6ARViewC12DebugOptionsV_Tg5Tm : 196 -> 188
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF10Foundation4UUIDV_So8ARAnchorCt_Tg5 : 496 -> 500
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF17RealityFoundation22AccessibilityComponentV17RotorTypeInternalO_Tg5 : 472 -> 476
~ _$s10RealityKit6EntityC29__calculateScreenBoundingRect2inSo6CGRectVAA6ARViewC_tF : 608 -> 624
~ _$s10RealityKit28__EntityAccessibilityWrapperC06entityD12CustomRotorsSaySo015UIAccessibilityG5RotorCGvg : 1224 -> 1232
~ _$s10RealityKit28__EntityAccessibilityWrapperC06entityD13CustomActionsSaySo015UIAccessibilityG6ActionCGvg : 900 -> 936
~ _$s10RealityKit28__EntityAccessibilityWrapperC06entityD13CustomContent33_B7223185F4910C4AFB6AF4C6C0F033B0LLSaySo08AXCustomH0CGvg : 684 -> 696
~ ___swift_closure_destructor : 148 -> 156
~ ___swift_closure_destructor.17 : 216 -> 220
~ _$sSlsE3mapySayqd__Gqd__7ElementQzqd_0_YKXEqd_0_YKs5ErrorRd_0_r0_lFShy10RealityKit10RKARSystemC16HashableARAnchor33_7C42569567E429B6AB2725E2C535D529LLVG_So0H0Cs5NeverOTg504$s10d5Kit10f72C8updateAR6engine12viewportSize9timeDeltayAA8__EngineC_So6CGSizeVSdtFSo8h5CAC08g6M033_7ijklmnO8LLVXEfU_Tf1cn_nTm : 516 -> 512
~ _$s10RealityKit10RKARSystemC17updateCameraNoise33_7C42569567E429B6AB2725E2C535D529LL3forySo7ARFrameC_tF : 1236 -> 1272
~ _$s10RealityKit10RKARSystemC18updateBodyTracking33_7C42569567E429B6AB2725E2C535D529LL4withySaySo8ARAnchorCG_tF : 2380 -> 2372
~ _$s10RealityKit10RKARSystemCMr : 396 -> 404
~ _$s10RealityKit10RKARSystemC6engine6arViewAcA8__EngineC_AA6ARViewCtcfcTf4ggn_n : 3592 -> 3600
~ _$s10RealityKit10RKARSystemC13updateAnchors33_7C42569567E429B6AB2725E2C535D529LL_5frameySaySo8ARAnchorCG_So7ARFrameCtFTf4ndn_n : 2492 -> 2472
~ _$ss17_NativeDictionaryV5merge20trappingOnDuplicatesyqd__n_tSTRd__x_q_t7ElementRtd__lF10Foundation4UUIDV_So8ARAnchorCSayAI_AKtGTg5Tf4gn_n : 708 -> 720
~ _$s10RealityKit10RKARSystemC8updateAR6engine12viewportSize9timeDeltayAA8__EngineC_So6CGSizeVSdtFTf4nndn_n : 7120 -> 7156
~ _$s10RealityKit10RKARSystemC7session_6didAddySo9ARSessionC_SaySo8ARAnchorCGtFTf4dnn_n : 712 -> 720
~ _$s10RealityKit10RKARSystemC7session_9didUpdateySo9ARSessionC_SaySo8ARAnchorCGtFTf4dnn_n : 544 -> 552
~ _$s10RealityKit10RKARSystemC7session_9didRemoveySo9ARSessionC_SaySo8ARAnchorCGtFTf4dnn_n : 672 -> 680
~ _$s10RealityKit10RKARSystemC15sendDataToPeers33_D861A27B9169D106C693FA544C23AF3ELL_0D10UnreliablySbSo6NSDataC_SbtFyyScMYccfU_ : 268 -> 284
~ _$s10RealityKit10RKARSystemC34createDebugVisualizationForAnchors33_3BAB4A5C6A65A4F7702FE156321CE6DCLL2inySo7ARFrameC_tF : 1076 -> 1080
~ _$s10RealityKit10RKARSystemC39createDebugVisualizationForAnchorPlanes33_3BAB4A5C6A65A4F7702FE156321CE6DCLL2inySo7ARFrameC_tF : 2336 -> 2344
~ _$ss17_NativeDictionaryV4copyyyFSS_ShySo16ARReferenceImageCGTg5Tm : 352 -> 344
~ _$ss17_NativeDictionaryV4copyyyFSo22MTKTextureLoaderOptiona_ypTg5 : 380 -> 376
```
