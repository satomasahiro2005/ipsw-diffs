## sharingd

> `/usr/libexec/sharingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6a1820` | `0x6ad4c8` | **`+0xbca8`** |
| `__TEXT.__oslogstring` | `0x3cbb3` | `0x3d183` | **`+0x5d0`** |
| `__DATA.__bss` | `0x15960` | `0x15e00` | **`+0x4a0`** |
| `__TEXT.__const` | `0x15b58` | `0x15eb8` | **`+0x360`** |
| `__TEXT.__objc_methname` | `0x4e8c5` | `0x4ebe5` | **`+0x320`** |
| `__DATA.__objc_const` | `0x383f0` | `0x38698` | **`+0x2a8`** |
| `__TEXT.__objc_stubs` | `0x37460` | `0x37700` | **`+0x2a0`** |
| `__DATA_CONST.__const` | `0x1ca38` | `0x1cc98` | **`+0x260`** |
| `__TEXT.__eh_frame` | `0x245e4` | `0x2480c` | **`+0x228`** |
| `__TEXT.__cstring` | `0x3ec11` | `0x3ede1` | **`+0x1d0`** |
| `__DATA.__data` | `0x148b8` | `0x14a78` | **`+0x1c0`** |
| `__TEXT.__auth_stubs` | `0xaec0` | `0xb060` | **`+0x1a0`** |
| `__TEXT.__swift5_fieldmd` | `0x5e90` | `0x5fec` | **`+0x15c`** |
| `__TEXT.__swift5_typeref` | `0x7f8c` | `0x80e2` | **`+0x156`** |
| `__TEXT.__unwind_info` | `0x14768` | `0x148a0` | **`+0x138`** |
| `__TEXT.__swift5_reflstr` | `0x5a09` | `0x5b39` | **`+0x130`** |
| `__DATA_CONST.__auth_ptr` | `0x42f8` | `0x4418` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x1e52c` | `0x1e604` | **`+0xd8`** |
| `__DATA_CONST.__auth_got` | `0x5770` | `0x5840` | **`+0xd0`** |
| `__DATA.__objc_selrefs` | `0x11038` | `0x110e8` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x785c` | `0x78f4` | **`+0x98`** |
| `__DATA_CONST.__got` | `0x39a8` | `0x3a30` | **`+0x88`** |
| `__TEXT.__objc_methtype` | `0xbc22` | `0xbca2` | **`+0x80`** |
| `__DATA.__objc_data` | `0xa0e0` | `0xa150` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x5188` | `0x51f0` | **`+0x68`** |
| `__DATA_CONST.__cfstring` | `0x19660` | `0x196c0` | **`+0x60`** |
| `__DATA_CONST.__objc_intobj` | `0xd68` | `0xdc8` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x6840` | `0x688c` | **`+0x4c`** |
| `__DATA.__objc_ivar` | `0x2914` | `0x293c` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0xca8` | `0xccc` | **`+0x24`** |
| `__TEXT.__swift_as_cont` | `0x21ec` | `0x220c` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0xca8` | `0xcc0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x2e4` | `0x2f8` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0xe28` | `0xe3c` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0xf48` | `0xf5c` | **`+0x14`** |
| `__TEXT.__objc_classname` | `0x5ae7` | `0x5af7` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x5e4` | `0x5f4` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xe08` | `0xe10` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x6f0` | `0x6f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-2126.10.4.0.0
+2131.10.1.2.7

+  - /System/Library/PrivateFrameworks/AttentionAwareness.framework/AttentionAwareness

-  Functions: 26261
-  Symbols:   4973
-  CStrings:  27486
+  Functions: 26393
+  Symbols:   5017
+  CStrings:  27556
Symbols:
+ _$s10Foundation12DataProtocolPAAE9copyBytes2to4fromSiSw_qd__tSXRd__5BoundQyd__5IndexRtzlF
+ _$s7Network10NWListenerC7ServiceV5ScopeV11shared_homeAGvgZ
+ _$s7Network10NWListenerC7ServiceV5ScopeV6familyAGvgZ
+ _$s7Network10NWListenerC7ServiceV5ScopeV8contactsAGvgZ
+ _$s7Network10NWListenerC7ServiceV5ScopeV8personalAGvgZ
+ _$s7Network10NWListenerC7ServiceV5ScopeV8rawValueAGs6UInt32V_tcfC
+ _$s7Network10NWListenerC7ServiceV5ScopeVMa
+ _$s7Network10NWListenerC7ServiceV5ScopeVMn
+ _$s7Network10NWListenerC7ServiceV5ScopeVs10SetAlgebraAAMc
+ _$s7Network10NWListenerC7ServiceV5scopeAE5ScopeVvs
+ _$s7Sharing20SFAirDropInvocationsO17ReportBoopOutcomeCAA22SFXPCInvocableProtocolAAMc
+ _$s7Sharing20SFAirDropInvocationsO17ReportBoopOutcomeCMa
+ _$s7Sharing20SFAirDropInvocationsO17ReportBoopOutcomeCMn
+ _$s7Sharing6SFBoopO11CancelStageO10afterShareyA2EmFWC
+ _$s7Sharing6SFBoopO11CancelStageO16afterReceiveOnlyyA2EmFWC
+ _$s7Sharing6SFBoopO11CancelStageO9dismissedyA2EmFWC
+ _$s7Sharing6SFBoopO11CancelStageOMa
+ _$s7Sharing6SFBoopO11FailureCodeO8pullAwayyA2EmFWC
+ _$s7Sharing6SFBoopO11FailureCodeO8rawValueSivg
+ _$s7Sharing6SFBoopO11FailureCodeOMa
+ _$s7Sharing6SFBoopO13OutcomeReportV13transactionID10Foundation4UUIDVvg
+ _$s7Sharing6SFBoopO13OutcomeReportV7outcomeAC0C0Ovg
+ _$s7Sharing6SFBoopO13OutcomeReportVMa
+ _$s7Sharing6SFBoopO7OutcomeO10bannerOnlyyA2EmFWC
+ _$s7Sharing6SFBoopO7OutcomeO6failedyAeC11FailureCodeO_tcAEmFWC
+ _$s7Sharing6SFBoopO7OutcomeO9cancelledyAeC11CancelStageO_tcAEmFWC
+ _$s7Sharing6SFBoopO7OutcomeO9completedyA2EmFWC
+ _$s7Sharing6SFBoopO7OutcomeOMa
+ _$sSDMa
+ _$sSf10FoundationE19_bridgeToObjectiveCSo8NSNumberCyF
+ _$sSnyxGSXsMc
+ _$sSo21SCSensitivityAnalysisC016SensitiveContentB0E12goreDetectedABvgZ
+ _$sSo21SCSensitivityAnalysisC016SensitiveContentB0E14nudityDetectedABvgZ
+ _$ss22KeyedDecodingContainerV6decode_6forKeyS2fm_xtKF
+ _$ss22KeyedDecodingContainerV6decode_6forKeys4Int8VAFm_xtKF
+ _$ss22KeyedEncodingContainerV6encode_6forKeyySf_xtKF
+ _$ss22KeyedEncodingContainerV6encode_6forKeyys4Int8V_xtKF
+ _$ss5Int64V10FoundationE19_bridgeToObjectiveCSo8NSNumberCyF
+ _OBJC_CLASS_$_AWAttentionAwarenessClient
+ _OBJC_CLASS_$_AWAttentionAwarenessConfiguration
+ _OBJC_CLASS_$_AWAttentionLostEvent
+ _RPOptionStatusFlags
+ _SBSCopyFrontmostApplicationDisplayIdentifier
+ _atan2f
+ _fmodf
- _BKSHIDServicesLastUserEventTime
CStrings:
+ " enableTelemetry=YES %{public, signpost.description:end_time}llu"
+ " enableTelemetry=YES always-on=%{public, signpost.telemetry:string1}@ %{public,signpost.description.begin_time}llu"
+ " enableTelemetry=YES always-on=%{public, signpost.telemetry:string1}@ family=%d clink=%d d2dencrypt=%d %{public, signpost.description:begin_time}llu"
+ " enableTelemetry=YES clientID=%{public, signpost.telemetry:string1}@, %{public, signpost.description:begin_time}llu"
+ " enableTelemetry=YES result=%{public, signpost.telemetry:string2}@ %{public,signpost.description.begin_time}llu"
+ "-[SDHotspotAgent _advertiserUpdate]_block_invoke_3"
+ "@\"AWAttentionAwarenessClient\""
+ "@\"SDAttentionMonitor\""
+ "B24@0:8d16"
+ "Could not invalidate AttentionAwareness: %{public}@"
+ "Paired Contact Manager: process %d tried to connect, but it was not entitled"
+ "SDAirDropNearFieldService: Failed to enforce single band mode with error:%@"
+ "SDAirDropNearFieldService: boop outcome grace period expired for transactionID:%s, emitting unreported boop-session"
+ "SDAirDropNearFieldService: boop received - isDeviceLocked=%{bool}d isInLockScreen=%{bool}d isInSpringBoard=%{bool}d frontmostApp=%s"
+ "SDAirDropNearFieldService: created endpoint:%s for transactionID:%s"
+ "SDAirDropNearFieldService: ignoring boop outcome report for unknown transactionID:%s"
+ "SDAirDropNearFieldService: launch Wallet UI for nearbyPeerPayment tap"
+ "SDAirDropNearFieldService: localExchangePayload is nil"
+ "SDAirDropNearFieldService: no local identity"
+ "SDAirDropNearFieldService: no remote device public key data"
+ "SDAttentionMonitor"
+ "SDAttentionMonitorUtilities: Could not resume AttentionAwareness on init: %{public}@"
+ "SDAttentionMonitorUtilities: attention regained for event %{public}@"
+ "SDAttentionMonitorUtilities: event mask=0x%llx ts=%g"
+ "SDAttentionMonitorUtilities: isUserIdleLongerThan:%g -> delta=%g"
+ "SDAttentionMonitorUtilities: lastUserEventDelta: attention lost -> %g"
+ "SDAttentionMonitorUtilities: seeding initial state from lastEvent"
+ "SDAttentionMonitorUtilities: setConfiguration failed: %{public}@"
+ "SDNearFieldMotion: unexpected wire size %{public}ld, expected %{public}ld"
+ "TB,N,GisAttentionLost,V_attentionLost"
+ "TQ,N,V_signpostID"
+ "Td,R,N"
+ "Ti,N,V_screenBlankedToken"
+ "Transfer removed, removing handler for transferID: %s"
+ "_attentionAwarenessClient"
+ "_attentionLost"
+ "_attentionLostState"
+ "_attentionLostTimestamp"
+ "_attentionMonitor"
+ "_endTetheringEnableSignpostForRequest:error:"
+ "_handleEvent:"
+ "_haveObservedEvent"
+ "_signpostID"
+ "attentionLost"
+ "attentionLostTimeout"
+ "com.apple.private.sharing.paired-contacts"
+ "com.apple.sharing.airdrop.boop-session"
+ "com.apple.sharing.airdrop.boop-setting"
+ "com.apple.sharingd.SDAttentionMonitor"
+ "com.apple.sharingd.airdrop.nearby-sharing-metric-daily"
+ "com.apple.sharingd.attentionMonitor"
+ "com.apple.springboard.hasBlankedScreen"
+ "dailyNearbySharingMetricScheduler"
+ "eventMask"
+ "failure"
+ "fetchExistingShareForFileOrFolderURL:completionHandler:"
+ "handleScreenBlankedStateChanged:"
+ "initWithChar:"
+ "initializing SDAttentionMonitor"
+ "invalidateWithError:"
+ "isAttentionLost"
+ "isUserIdleLongerThan:"
+ "lastEvent"
+ "lastUserEventDelta"
+ "localDeviceMotion"
+ "pendingBoopMetrics"
+ "pendingBoopMetricsDrainTasks"
+ "processingTapMetrics"
+ "remoteDeviceMotion"
+ "resumeWithError:"
+ "rotationRateLocal"
+ "rotationRateRemote"
+ "screenBlankedToken"
+ "setAttentionLost:"
+ "setAttentionLostTimeout:"
+ "setConfiguration:shouldReset:error:"
+ "setEventHandlerWithQueue:block:"
+ "setEventMask:"
+ "setScreenBlankedToken:"
+ "setSignpostID:"
+ "signpostID"
+ "timestamp"
+ "userAcceleration"
+ "userAccelerationLocal"
+ "userAccelerationRemote"
+ "v16@?0@\"AWAttentionEvent\"8"
+ "v32@0:8@\"NSURL\"16@?<v@?@\"CKShare\"@\"NSError\">24"
- " enableTelemetry=YES %{public, signpost.description:end_time}llu}"
- " enableTelemetry=YES %{public,signpost.description.begin_time}llu"
- " enableTelemetry=YES clientID=%{signpost.telemetry.string1}@, %{public, signpost.description:begin_time}llu"
- " enableTelemetry=YES family=%d clink=%d d2dencrypt=%d %{public, signpost.description:begin_time}llu"
- " enableTelemetry=YES success %d %{public,signpost.description.begin_time}llu"
- "-[SDHotspotAgent _advertiserUpdate]_block_invoke_6"
- "MockA2DPActivity"
- "No identity"
- "No identity to start server"
- "SDAirDropNearFieldService: Failed to enforce single band mode"
- "SDAirDropNearFieldService: Tap doesn't contain any public key data, this isn't supported"
- "Ti,N,V_screenDisplayChangedToken"
- "_screenDisplayChangedToken"
- "com.apple.iokit.hid.displayStatus"
- "handleDisplayStateChanged:"
- "screenDisplayChangedToken"
- "setScreenDisplayChangedToken:"
```
