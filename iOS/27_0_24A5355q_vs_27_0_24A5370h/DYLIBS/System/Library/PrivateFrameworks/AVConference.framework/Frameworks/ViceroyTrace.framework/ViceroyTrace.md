## ViceroyTrace

> `/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ViceroyTrace.framework/ViceroyTrace`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb413c` | `0xb9228` | **`+0x50ec`** |
| `__TEXT.__oslogstring` | `0xdf77` | `0xf2dd` | **`+0x1366`** |
| `__AUTH_CONST.__objc_const` | `0x17688` | `0x178d8` | **`+0x250`** |
| `__TEXT.__cstring` | `0xf280` | `0xf44f` | **`+0x1cf`** |
| `__AUTH_CONST.__cfstring` | `0xebe0` | `0xeda0` | **`+0x1c0`** |
| `__TEXT.__objc_methlist` | `0x9258` | `0x9328` | **`+0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0x4690` | `0x46f8` | **`+0x68`** |
| `__TEXT.__const` | `0x27b0` | `0x27f0` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x21b8` | `0x21f4` | **`+0x3c`** |
| `__TEXT.__unwind_info` | `0x1848` | `0x1870` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x368` | `0x380` | **`+0x18`** |

### Other Changes

```diff

-2235.48.1.0.0
+2235.52.1.11.1

-  Functions: 4213
-  Symbols:   6683
-  CStrings:  3272
+  Functions: 4247
+  Symbols:   6732
+  CStrings:  3348
Symbols:
+ -[DownlinkSegment storeToReport:value:key:streamGroup:]
+ -[DownlinkSegment storeVRIFDFreezeMetrics:freezeCountNoticeable:freezeCountDisruptive:freezeDurationMs:ifdTotalMs:ifdTotalSquaredMs:ifdFramesRendered:streamGroup:]
+ -[MultiwayCall _processAltVideoStallStreamData:streamGroupStats:]
+ -[MultiwayCall _processVideoStallStreamData:streamGroupStats:]
+ -[MultiwayStream ifdFreezeCountDisruptive]
+ -[MultiwayStream ifdFreezeCountNoticeable]
+ -[MultiwayStream ifdFreezeDurationMs]
+ -[StreamGroupStats ifdFreezeCountDisruptive]
+ -[StreamGroupStats ifdFreezeCountNoticeable]
+ -[StreamGroupStats ifdFreezeDurationMs]
+ -[StreamGroupStats setIfdFreezeCountDisruptive:]
+ -[StreamGroupStats setIfdFreezeCountNoticeable:]
+ -[StreamGroupStats setIfdFreezeDurationMs:]
+ -[StreamGroupStats videoStallAlt]
+ -[VCAggregatorMultiway checkAudioOnlyBitrateViolationWithTargetBitrate:]
+ -[VCAggregatorMultiway storeVRIFDFreezeMetrics:freezeCountNoticeable:freezeCountDisruptive:freezeDurationMs:ifdTotalMs:ifdTotalSquaredMs:ifdFramesRendered:streamGroup:]
+ -[VCSymptomReporter reportBitrateExceededDuringAudioOnlySession]
+ -[VCSymptomReporter reportVideoOperatingModeDuringAudioOnlySession]
+ GCC_except_table1344
+ GCC_except_table42
+ GCC_except_table83
+ _OBJC_IVAR_$_MultiwayStream._ifdFreezeCountDisruptive
+ _OBJC_IVAR_$_MultiwayStream._ifdFreezeCountNoticeable
+ _OBJC_IVAR_$_MultiwayStream._ifdFreezeDurationMs
+ _OBJC_IVAR_$_StreamGroupStats._ifdFreezeCountDisruptive
+ _OBJC_IVAR_$_StreamGroupStats._ifdFreezeCountNoticeable
+ _OBJC_IVAR_$_StreamGroupStats._ifdFreezeDurationMs
+ _OBJC_IVAR_$_StreamGroupStats._videoStallAlt
+ _OBJC_IVAR_$_VCAggregatorFaceTime._callIFDFreezeCountDisruptive
+ _OBJC_IVAR_$_VCAggregatorFaceTime._callIFDFreezeCountNoticeable
+ _OBJC_IVAR_$_VCAggregatorFaceTime._callIFDFreezeDurationMs
+ _OBJC_IVAR_$_VCAggregatorMultiway._hasReportedBitrateExceededDuringAudioOnly
+ _OBJC_IVAR_$_VCAggregatorMultiway._hasReportedVideoOperatingModeDuringAudioOnly
+ _OBJC_IVAR_$_VCAggregatorVideoStream._ifdFreezeCountDisruptive
+ _OBJC_IVAR_$_VCAggregatorVideoStream._ifdFreezeCountNoticeable
+ _OBJC_IVAR_$_VCAggregatorVideoStream._ifdFreezeDurationMs
+ _OUTLINED_FUNCTION_100
+ _OUTLINED_FUNCTION_101
+ _OUTLINED_FUNCTION_102
+ _OUTLINED_FUNCTION_103
+ _OUTLINED_FUNCTION_104
+ _OUTLINED_FUNCTION_105
+ _OUTLINED_FUNCTION_106
+ _OUTLINED_FUNCTION_107
+ _OUTLINED_FUNCTION_108
+ _OUTLINED_FUNCTION_98
+ _OUTLINED_FUNCTION_99
+ _VCReporting_SetClientType
+ __VCReporting_AddItemToDictionary
+ ___50-[VCAggregatorVideoStream processInterframeDelay:]_block_invoke_7
+ ___50-[VCAggregatorVideoStream processInterframeDelay:]_block_invoke_8
+ ___50-[VCAggregatorVideoStream processInterframeDelay:]_block_invoke_9
- GCC_except_table1329
- GCC_except_table41
- GCC_except_table81
CStrings:
+ " [%s] %s:%d %@(%p) "
+ " [%s] %s:%d %@(%p) AdaptiveLearning: Updating Target Bitrate history for segment=%@"
+ " [%s] %s:%d %@(%p) AlgosScoreCombiner scoreDictionary: %@"
+ " [%s] %s:%d %@(%p) Audio tier with bitrate=%u bps has no matching bucket in AudioTierBitrate array. File a radar to AVConference Audio to add it."
+ " [%s] %s:%d %@(%p) Audio-only session uplink targetBitrate=%u exceeds max=%u"
+ " [%s] %s:%d %@(%p) Call with participantID=%@ reported DRTN=%@sec"
+ " [%s] %s:%d %@(%p) Camera duration tracking initialized: currentCameraState=%u"
+ " [%s] %s:%d %@(%p) Connection timing V2 for participantID=%@, measured by streamGroupID=%@, TotalConnectionTime=%@, TotalConnectionTimeStarted=%@"
+ " [%s] %s:%d %@(%p) Connection timing V2 for participantID=%@: totalConnectionTime=%d, mediaCreatedToStartedTime=%d, mediaStartedToFirstPacketTime=%d, mediaFirstPacketToFirstFrameTime=%d, mediaFirstMKITime=%@, mediaStallSaveTime=%@, original dictionary=%@"
+ " [%s] %s:%d %@(%p) Do not create participant stats for self"
+ " [%s] %s:%d %@(%p) Downlink segment=%@ has already been reported. Ignoring request..."
+ " [%s] %s:%d %@(%p) Handshake with participant=%@ completed, duration=%f"
+ " [%s] %s:%d %@(%p) Handshake with participant=%@ started"
+ " [%s] %s:%d %@(%p) PHS: Failed to get profile"
+ " [%s] %s:%d %@(%p) PHS: WiFi interface profile=%@"
+ " [%s] %s:%d %@(%p) PHS: returned value=%d"
+ " [%s] %s:%d %@(%p) Switched to video calling operating mode during an audio-only session"
+ " [%s] %s:%d %@(%p) Updated to audioStartToFirstPacketTime=%d"
+ " [%s] %s:%d %@(%p) Updated to auioCreationTime=%d"
+ " [%s] %s:%d %@(%p) Updated to auioStartingTime=%d"
+ " [%s] %s:%d %@(%p) Uplink segment=%@ has already been reported. Ignoring request..."
+ " [%s] %s:%d %@(%p) VCAggregator: Attempt to report incomplete common timing for streamGroupID=%@, mediaFirstMKITime=%@, mediaStallSaveTime=%@"
+ " [%s] %s:%d %@(%p) VCAggregator: streamGroupStats for streamGroupID=%@ not found. Ignoring common connection timing"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: Audio for call with participantID '%@' was set to '%@'"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: Call for participantID '%@' already exists"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: Call for participantID '%@' has been finalized"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: Call for participantID '%@' was added"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: Can not set audio state for call when participantID is nil"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: Can not set audio state for call with participantID '%@' as it does not exists"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: Can not set screen state for call when participantID is nil"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: Can not set screen state for call with participantID '%@' as it does not exists"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: Can not set video state for call when participantID is nil"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: New downlink segment started due to activeStreamGroups change from [%@] to [%@]"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: New segment started due to activeStreamGroups change from [%@] to [%@]"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: Participant was added with empty participantID"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: Video for call with participantID '%@' was set to '%@'"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: mediaQueueSchedulePolicy=%d"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: participantID[%@] isUplinkRetransmissionEnabled=%d isRemoteQUICPod=%d"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: participantID[%@] isUplinkRetransmissionEnabled=%d isRemoteQUICPod=%d remoteMediaQueueSchedulePolicy=%d"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: participantID[%@] rateControlExperimentVersionRemote=%d rateControlExperimentGroupIndexRemote=%d"
+ " [%s] %s:%d %@(%p) VCAggregatorMultiway: participantID[%@] rateControlSmartBrakeTrialVersionRemote=%d"
+ " [%s] %s:%d %@(%p) Video resolution not set for participantID=%@"
+ " [%s] %s:%d %@(%p) _isSymptomReportingEnabled=%d"
+ " [%s] %s:%d %@(%p) locaPHYMode=%@"
+ " [%s] %s:%d %@(%p) participantID %s participant scoreDictionary %@"
+ " [%s] %s:%d %@(%p) result is nil"
+ " [%s] %s:%d %@(%p) segmentStreamGroups=%u streamGroups=%@"
+ " [%s] %s:%d Audio-only session uplink targetBitrate=%u exceeds max=%u"
+ " [%s] %s:%d Call with participantID=%@ reported DRTN=%@sec"
+ " [%s] %s:%d Switched to video calling operating mode during an audio-only session"
+ " [%s] %s:%d SymptomReporter: reporting symptom on BitrateExceededDuringAudioOnlySession for session=%u"
+ " [%s] %s:%d SymptomReporter: reporting symptom on VideoOperatingModeDuringAudioOnlySession for session=%u"
+ "-[VCAggregatorMultiway aggregatedCallReports]_block_invoke"
+ "-[VCAggregatorMultiway checkAudioOnlyBitrateViolationWithTargetBitrate:]"
+ "-[VCSymptomReporter reportBitrateExceededDuringAudioOnlySession]"
+ "-[VCSymptomReporter reportVideoOperatingModeDuringAudioOnlySession]"
+ "BitrateExceededDuringAudioOnlySession"
+ "ReportingVC [%s] %s:%d %@(%p) RTCReportingAgent: created symptom reporter"
+ "ReportingVC [%s] %s:%d %@(%p) Releasing RTCReportingAgent instance=%@"
+ "ReportingVC [%s] %s:%d %@(%p) Second aggregator disabled by mode"
+ "ReportingVC [%s] %s:%d %@(%p) Sending Network score dictionary=%@"
+ "ReportingVC [%s] %s:%d %@(%p) finalizeAggregation: aggregater is nil!"
+ "ReportingVC [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: (%p) Init time userInfo=%@"
+ "ReportingVC [%s] %s:%d RTCReportingAgent (%p) established rtcreportingSessionID=%@"
+ "SVSH_A"
+ "VCSPTargetBitrate"
+ "VRIFDAFD"
+ "VRIFDFCD"
+ "VRIFDFCN"
+ "VRIFDFD"
+ "VRIFDFF"
+ "VRIFDNJ"
+ "VRIFDSD"
+ "VRVIQIFDFCD"
+ "VRVIQIFDFCN"
+ "VRVIQIFDFD"
+ "VideoOperatingModeDuringAudioOnlySession"
- "ReportingVC [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: Init time userInfo=%@"
```
