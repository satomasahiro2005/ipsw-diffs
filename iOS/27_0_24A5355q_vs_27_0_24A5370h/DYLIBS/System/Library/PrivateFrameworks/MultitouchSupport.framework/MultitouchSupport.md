## MultitouchSupport

> `/System/Library/PrivateFrameworks/MultitouchSupport.framework/MultitouchSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e350` | `0x1e660` | **`+0x310`** |

### Other Changes

```diff

-9170.34.1.0.0
+10100.39.0.0.0
Functions:
~ _mt_HandleMultitouchFrame : 728 -> 756
~ _mt_ProcessMultitouchFrame : 3384 -> 3560
~ _mt_PostFullFrameCallbacks : 132 -> 156
~ _mt_ForwardBinaryContacts : 624 -> 608
~ _MTAlg_IssuePathCallbacks : 260 -> 284
~ _mt_PostLegacyFrameHeaderCallbacks : 668 -> 708
~ __Z26MTParse_PrecisePathPayloadPhiP28MTParsedMultitouchFrameRep_tP10__MTDeviceittb : 788 -> 808
~ __ZN14SABinaryParser15parseInjExtDataEPFbPvRK21_SABinaryInjExtPacketPKhES7_PFbS0_RK20_SABinaryInjExtPointE : 412 -> 416
~ _mt_CheckForTimestampErrors : 500 -> 516
~ _mt_PostButtonStateCallbacks : 172 -> 188
~ _mt_PostForceCentroidCallbacks : 172 -> 196
~ _MTAlg_IssueInputDetectionStateCallback : 144 -> 160
~ _MTAlg_IssueOpticalProximityCallback : 204 -> 216
~ _mt_PathLifeCycleFromPreciseContact : 256 -> 260
~ _MTAlg_IssueFarfieldProximityCallback : 180 -> 192
~ _mt_CleanupOldPaths : 184 -> 200
~ _MTAlg_IssueContactFrameCallbacks : 244 -> 260
~ __ZZ16MTParse_SABinaryEN3$_18__invokeEPvRK21_SABinaryInjExtPacketPKh : 1516 -> 1544
~ +[MTAHTSupport getDeviceInServiceTree:] : 396 -> 408
~ +[MTAHTSupport getInterfaceInServiceTree:] : 396 -> 408
~ _mt_ParseExternalMessageIDs : 208 -> 204
~ _mt_RecursiveMakeDirectory : 404 -> 384
~ _MTDriverCreateResetInfo : 548 -> 544
~ _MTDeviceGetResetCount : 240 -> 236
~ _mt_CreateBinaryFilters : 4980 -> 4976
~ _mt_ApplyBinaryFilters : 468 -> 464
~ _mt_SetBinaryFiltersProperty : 528 -> 524
~ _mt_Scale8BitBufferTo16BitRange : 60 -> 68
~ _mt_Scale16BitRangeTo8Bits : 104 -> 108
~ _mt_UncompressTouchpadCodecV1Force : 760 -> 744
~ ___MTDeviceInit : 404 -> 440
~ _alg_InitRowColXYConvert : 620 -> 612
~ _mt_PostNotificationEvent : 100 -> 116
~ _mt_IsExternalMessage : 64 -> 72
~ _mt_PostWorkIntervalEvent : 100 -> 116
~ _mt_PostExternalMessage : 148 -> 164
~ _mt_PostFrameProcessingEntryExitEvent : 112 -> 136
~ _MTUnregisterFrameProcessingEntryExitCallback : 80 -> 76
~ _MTUnregisterFullFrameCallback : 80 -> 76
~ _MTUnregisterNotificationEventCallback : 80 -> 76
~ _MTParse_CompactBinaryPath : 664 -> 688
~ _MTParse_CompactV3orV5BinaryPath : 428 -> 436
~ _MTParse_CompactV4BinaryPath : 384 -> 392
~ _MTParse_CompactV7BinaryPath : 404 -> 412
~ _MTParse_CompactV9BinaryPath : 284 -> 312
~ __Z30MTCompactV8BinaryContactUnpackP24MTCompactBinaryContactV8Phjh : 584 -> 580
~ _MTParse_CompactV8BinaryPath : 436 -> 448
~ __Z26MTParse_BinaryImagePayloadPhiP28MTParsedMultitouchFrameRep_tP10__MTDevice : 572 -> 564
~ _MTParse_V3BinaryPathOrImage : 696 -> 720
~ __Z27MTParse_V4BinaryPathPayloadPhiP28MTParsedMultitouchFrameRep_tP10__MTDeviceitt : 596 -> 624
~ __Z29MTParse_GenerateRingCentroidsP28MTParsedMultitouchFrameRep_tP10__MTDevice : 180 -> 192
~ _MTParse_HostPathAndImage : 416 -> 424
~ _MTParse_BinaryPathOrImage : 656 -> 676
~ _MTProcess_0xCC_Data : 744 -> 748
~ _MTParseSensorRegionsReport : 272 -> 312
~ _MTRegisterImageCallback : 88 -> 92
~ _MTRegisterImageCallbackWithRefcon : 88 -> 92
~ _MTAlg_IssueImageCallbacks : 420 -> 444
~ _MTUnregisterForceCentroidCallback : 80 -> 76
~ _MTUnregisterContactFrameCallback : 80 -> 76
~ _MTRegisterPathCallback : 76 -> 72
~ _MTUnregisterPathCallback : 80 -> 76
~ _MTUnregisterPathCallbackWithRefcon : 80 -> 76
~ _MTZephyrSetRowCalibTable : 372 -> 368
~ _MTZephyrGetRowCalibTable : 348 -> 360
~ _MTZephyrGetPhantomACDMIDColumnSamples : 124 -> 132
~ _MTUnregisterButtonStateCallback : 88 -> 84
~ _mt_PostTrackingCallbacks : 136 -> 152
~ _mt_PostRelativePointerCallbacks : 136 -> 160
~ _MTUnregisterRelativePointerCallback : 88 -> 84
~ _MTUnregisterTrackingCallback : 88 -> 84
~ _mt_PostOffTableHeightCallbacks : 144 -> 160
~ _MTUnregisterOffTableHeightCallback : 88 -> 84
~ _MTRegisterOpticalProximityChangedCallback : 108 -> 88
~ _MTUnregisterOpticalProximityChangedCallback : 112 -> 92
~ _MTRegisterFarfieldProximityChangedCallback : 108 -> 88
~ _MTUnregisterFarfieldProximityChangedCallback : 112 -> 92
~ _MTUnregisterInputDetectionCallback : 88 -> 84
~ _mt_PostStatisticsChannelEvent : 100 -> 124
~ _MTRegisterStatisticsChannelCallback : 160 -> 156
~ _MTUnregisterStatisticsChannelCallback : 88 -> 84
~ _MTStatisticsChannelGetValues : 180 -> 168
~ _MTActuationFillParametricBufferWithWaveform : 484 -> 512
~ _mt_InitPathLifeCycles : 152 -> 156
~ _mt_PlayerPlaybackTimerHandler : 444 -> 440
~ _mt_ForwardSpecificImageRegion : 416 -> 420
~ _mt_ForwardCombinedImageRegions : 492 -> 504
~ __MTActuationLoadActuationsFromPropertyListV2orV3 : 1072 -> 1068
~ _touchpadCodecDecodeImage : 1380 -> 1368
~ _touchpadCodecCreate : 216 -> 224
~ _codecResetModel : 88 -> 96
~ _codecGetFooterID : 52 -> 60
```
