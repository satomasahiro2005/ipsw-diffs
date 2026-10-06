## remoteappintentsd

> `/usr/libexec/remoteappintentsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7630c` | `0x833e0` | **`+0xd0d4`** |
| `__DATA.__data` | `0x23f0` | `0x2a60` | **`+0x670`** |
| `__DATA_CONST.__const` | `0x3548` | `0x3a70` | **`+0x528`** |
| `__TEXT.__eh_frame` | `0x5ef0` | `0x63c8` | **`+0x4d8`** |
| `__TEXT.__oslogstring` | `0x1cea` | `0x212a` | **`+0x440`** |
| `__TEXT.__const` | `0x23a8` | `0x2670` | **`+0x2c8`** |
| `__TEXT.__swift5_typeref` | `0x1554` | `0x17fc` | **`+0x2a8`** |
| `__TEXT.__constg_swiftt` | `0xf70` | `0x11ec` | **`+0x27c`** |
| `__TEXT.__unwind_info` | `0x2330` | `0x2560` | **`+0x230`** |
| `__TEXT.__swift5_fieldmd` | `0xa38` | `0xc60` | **`+0x228`** |
| `__TEXT.__swift5_reflstr` | `0x8d4` | `0xa74` | **`+0x1a0`** |
| `__DATA.__bss` | `0xf00` | `0x1080` | **`+0x180`** |
| `__TEXT.__auth_stubs` | `0x2b30` | `0x2c80` | **`+0x150`** |
| `__DATA_CONST.__auth_ptr` | `0xae8` | `0xc30` | **`+0x148`** |
| `__DATA.__objc_const` | `0x1648` | `0x1768` | **`+0x120`** |
| `__TEXT.__swift5_capture` | `0x11f0` | `0x130c` | **`+0x11c`** |
| `__TEXT.__cstring` | `0x12cd` | `0x138a` | **`+0xbd`** |
| `__DATA.__common` | `0x378` | `0x2c0` | **`-0xb8`** |
| `__DATA_CONST.__auth_got` | `0x15a0` | `0x1648` | **`+0xa8`** |
| `__TEXT.__objc_methname` | `0x13f5` | `0x1485` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x7e8` | `0x848` | **`+0x60`** |
| `__TEXT.__objc_classname` | `0x785` | `0x7b5` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0xe4` | `0x104` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x3e8` | `0x404` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x78` | `0x90` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x2d0` | `0x2e4` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x88` | `0x98` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xa4` | `0xb4` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x298` | `0x2a8` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x1c` | `0x20` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-41.1.10.0.0
+41.1.15.0.0

-  Functions: 2710
-  Symbols:   1111
-  CStrings:  547
+  Functions: 2900
+  Symbols:   1148
+  CStrings:  572
Symbols:
+ _$s10Foundation4UUIDV18AppIntentsServicesE6prefixSSvg
+ _$s18AppIntentsServices0aB8ProtocolO13PerformActionO8ResponseO015needsContinueInA0yAgE21ExecutionIdentifiableVy__AA0eA6IntentO0ijA7RequestVGcAGmFWC
+ _$s18AppIntentsServices0aB8ProtocolO13PerformActionO8ResponseO05needsF12ConfirmationyAgE21ExecutionIdentifiableVy__AA0eA6IntentO0fI7RequestVGcAGmFWC
+ _$s18AppIntentsServices0aB8ProtocolO13PerformActionO8ResponseO10needsValueyAgE21ExecutionIdentifiableVy__AE05NeedsI7RequestVGcAGmFWC
+ _$s18AppIntentsServices0aB8ProtocolO13PerformActionO8ResponseO11needsChoiceyAgE21ExecutionIdentifiableVy__AE0I7RequestVGcAGmFWC
+ _$s18AppIntentsServices0aB8ProtocolO13PerformActionO8ResponseO17needsConfirmationyAgE21ExecutionIdentifiableVy__AA0eA6IntentO0I7RequestVGcAGmFWC
+ _$s18AppIntentsServices0aB8ProtocolO13PerformActionO8ResponseO19needsDisambiguationyAgE21ExecutionIdentifiableVy__AE0I7RequestVGcAGmFWC
+ _$s18AppIntentsServices0aB8ProtocolO13PerformActionO8ResponseO7unknownyA2GmFWC
+ _$s18AppIntentsServices0bC0O8EndpointV11descriptionSSvg
+ _$s18AppIntentsServices0bC0O8EndpointVMn
+ _$s18AppIntentsServices15InstrumentationO11AttributionV3for12dispatcherId9executionAESSSg_10Foundation4UUIDVSgtFZ
+ _$s18AppIntentsServices15InstrumentationO11AttributionV5emptyAEvgZ
+ _$s18AppIntentsServices15InstrumentationO11AttributionVMa
+ _$s18AppIntentsServices21PerformActionExecutorO16CallContinuationV_9logPrefixAEy_xGScCyxs5NeverOG_SStcfC
+ _$s18AppIntentsServices21PerformActionExecutorO16ResponseHandlingP9logPrefixSSvgTq
+ _$s18AppIntentsServices3LogO11observation2os6LoggerVvgZ
+ _$s18AppIntentsServices3LogO13serialization2os6LoggerVvgZ
+ _$s18AppIntentsServices3LogO14actionExecutor2os6LoggerVvgZ
+ _$s18AppIntentsServices3LogO14activityPrefix13fallingBackToS2S_tFZ
+ _$s18AppIntentsServices3LogO14activityPrefixSSvgZ
+ _$s18AppIntentsServices3LogO16remoteDispatcher2os6LoggerVvgZ
+ _$s18AppIntentsServices3LogO6daemon2os6LoggerVvgZ
+ _$s18AppIntentsServices3LogO7default2os6LoggerVvgZ
+ _$s18AppIntentsServices3LogO9fileStore2os6LoggerVvgZ
+ _$s2os6LoggerV18AppIntentsServicesE19withInstrumentation_11attribution11clientLabel18diagnosticsEnabled15logUponEntering0mN7Leaving0mN8Throwing14parentActivity14payloadPrivacy10signposter10signpostID7closurexAD0G0O0S10DescriptorV_AR11AttributionVSSSgSbSgSSyYbcSgSSxYbcSgSSs5Error_pYbcSgAD0S8Protocol_pSgAD0dE0O07PayloadU0OAA12OSSignposterVSgAA010OSSignpostX0VSgxAR0S0Cy_xGKXEtKs8SendableRzlF
+ _$s2os6LoggerV18AppIntentsServicesE19withInstrumentation_11attribution11clientLabel18diagnosticsEnabled15logUponEntering0mN7Leaving0mN8Throwing14parentActivity14payloadPrivacy10signposter10signpostID9isolation7closurexAD0G0O0S10DescriptorV_AS11AttributionVSSSgSbSgSSyYbcSgSSxYbcSgSSs5Error_pYbcSgAD0S8Protocol_pSgAD0dE0O07PayloadU0OAA12OSSignposterVSgAA010OSSignpostX0VSgScA_pSgYixAS0S0Cy_xGYaKXEtYaKs8SendableRzlF
+ _$s2os6LoggerV18AppIntentsServicesE19withInstrumentation_11attribution11clientLabel18diagnosticsEnabled15logUponEntering0mN7Leaving0mN8Throwing14parentActivity14payloadPrivacy10signposter10signpostID9isolation7closurexAD0G0O0S10DescriptorV_AS11AttributionVSSSgSbSgSSyYbcSgSSxYbcSgSSs5Error_pYbcSgAD0S8Protocol_pSgAD0dE0O07PayloadU0OAA12OSSignposterVSgAA010OSSignpostX0VSgScA_pSgYixAS0S0Cy_xGYaKXEtYaKs8SendableRzlFTu
+ _$s2os6LoggerV18AppIntentsServicesE19withInstrumentation_11attribution11clientLabel18diagnosticsEnabled15logUponEntering0mN7Leaving0mN8Throwing14parentActivity14payloadPrivacy10signposter10signpostID9isolation7closurexAD0G0O0S10DescriptorV_AS11AttributionVSSSgSbSgSSyYbcSgSSxYbcSgSSs5Error_pYbcSgAD0S8Protocol_pSgAD0dE0O07PayloadU0OAA12OSSignposterVSgAA010OSSignpostX0VSgScA_pSgYixAS0S0Cy_xGYaKXEtYaKs8SendableRzlFfA0_
+ _$s2os6LoggerV18AppIntentsServicesE19withInstrumentation_11attribution11clientLabel18diagnosticsEnabled15logUponEntering0mN7Leaving0mN8Throwing14parentActivity14payloadPrivacy10signposter10signpostID9isolation7closurexAD0G0O0S10DescriptorV_AS11AttributionVSSSgSbSgSSyYbcSgSSxYbcSgSSs5Error_pYbcSgAD0S8Protocol_pSgAD0dE0O07PayloadU0OAA12OSSignposterVSgAA010OSSignpostX0VSgScA_pSgYixAS0S0Cy_xGYaKXEtYaKs8SendableRzlFfA7_
+ _$s2os6LoggerV18AppIntentsServicesE8categoryACSS_tcfC
+ _$s2os6LoggerVMn
+ _$s7Network10NWEndpointO8deviceIDSSSgvg
+ _$s7Network21NWActorSystemDelegatePAAE19didHandleRemoteCall6callID6target13actorInstancey10Foundation4UUIDV_SS11Distributed0P5Actor_ptF
+ _$s7Network21NWActorSystemDelegatePAAE20willHandleRemoteCall6callID6target13actorInstancey10Foundation4UUIDV_SS11Distributed0P5Actor_ptF
+ _$sSYsSHRzSH8RawValueSYRpzrlE04hashB0Sivg
+ _$sSYsSHRzSH8RawValueSYRpzrlE08_rawHashB04seedS2i_tF
+ _$sSYsSHRzSH8RawValueSYRpzrlE4hash4intoys6HasherVz_tF
+ _$sSayxGSlsMc
+ _$sSo18OS_dispatch_sourceC8DispatchE19MemoryPressureEventV7warningAEvgZ
+ _$sSo18OS_dispatch_sourceC8DispatchE19MemoryPressureEventV8criticalAEvgZ
+ _$sSo18OS_dispatch_sourceC8DispatchE19MemoryPressureEventVMa
+ _$sSo18OS_dispatch_sourceC8DispatchE19MemoryPressureEventVMn
+ _$sSo18OS_dispatch_sourceC8DispatchE19MemoryPressureEventVs10SetAlgebraACMc
+ _$sSo18OS_dispatch_sourceC8DispatchE24makeMemoryPressureSource9eventMask5queueSo0a1_b1_C15_memorypressure_pAbCE0fG5EventV_So0a1_b1_K0CSgtFZ
+ _$sSo18OS_dispatch_sourceP8DispatchE6cancelyyF
+ _$ss11AnyHashableV13_rawHashValue4seedS2i_tF
+ _$ss11AnyHashableVN
+ _$ss11AnyHashableVSHsWP
+ _$ss21_findStringSwitchCase5cases6stringSiSays06StaticB0VG_SStF
+ _$ss27_diagnoseUnexpectedEnumCase4types5NeverOxm_tlF
+ _$ss8DurationVMn
+ _bzero
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
- _$s18AppIntentsServices0aB8ProtocolO13PerformActionO22UnknownRequestResponseVMa
- _$s18AppIntentsServices15InstrumentationO17currentActivityIdSSvgZ
- _$s18AppIntentsServices21PerformActionExecutorO13DelegateStoreC02onG5Added0iG7RemovedAEy_xGyx_10Foundation4UUIDVtYbcSg_yAKYbcSgtcfC
- _$s18AppIntentsServices21PerformActionExecutorO13DelegateStoreC3add_19executionIdentifieryx_10Foundation4UUIDVtF
- _$s18AppIntentsServices21PerformActionExecutorO13DelegateStoreC3get19executionIdentifierxSg10Foundation4UUIDV_tF
- _$s18AppIntentsServices21PerformActionExecutorO13DelegateStoreC5countSivg
- _$s18AppIntentsServices21PerformActionExecutorO13DelegateStoreC6removeyyxF
- _$s18AppIntentsServices21PerformActionExecutorO13DelegateStoreC9removeAllyyF
- _$s18AppIntentsServices21PerformActionExecutorO13DelegateStoreCMn
- _$s18AppIntentsServices21PerformActionExecutorO16CallContinuationVyAEy_xGScCyxs5NeverOGcfC
- _$s2os6LoggerV18AppIntentsServicesE19withInstrumentation_10basePrefix11clientLabel18diagnosticsEnabled15logUponEntering0nO7Leaving0nO8Throwing14parentActivity14payloadPrivacy10signposter10signpostID7closurexAD0G0O0T10DescriptorV_SSSgAUSbSgSSyYbcSgSSxYbcSgSSs5Error_pYbcSgAD0T8Protocol_pSgAD0dE0O07PayloadV0OAA12OSSignposterVSgAA010OSSignpostY0VSgxAR0T0Cy_xGKXEtKs8SendableRzlF
- _$s2os6LoggerV18AppIntentsServicesE19withInstrumentation_10basePrefix11clientLabel18diagnosticsEnabled15logUponEntering0nO7Leaving0nO8Throwing14parentActivity14payloadPrivacy10signposter10signpostID9isolation7closurexAD0G0O0T10DescriptorV_SSSgAVSbSgSSyYbcSgSSxYbcSgSSs5Error_pYbcSgAD0T8Protocol_pSgAD0dE0O07PayloadV0OAA12OSSignposterVSgAA010OSSignpostY0VSgScA_pSgYixAS0T0Cy_xGYaKXEtYaKs8SendableRzlF
- _$s2os6LoggerV18AppIntentsServicesE19withInstrumentation_10basePrefix11clientLabel18diagnosticsEnabled15logUponEntering0nO7Leaving0nO8Throwing14parentActivity14payloadPrivacy10signposter10signpostID9isolation7closurexAD0G0O0T10DescriptorV_SSSgAVSbSgSSyYbcSgSSxYbcSgSSs5Error_pYbcSgAD0T8Protocol_pSgAD0dE0O07PayloadV0OAA12OSSignposterVSgAA010OSSignpostY0VSgScA_pSgYixAS0T0Cy_xGYaKXEtYaKs8SendableRzlFTu
- _$s2os6LoggerV18AppIntentsServicesE19withInstrumentation_10basePrefix11clientLabel18diagnosticsEnabled15logUponEntering0nO7Leaving0nO8Throwing14parentActivity14payloadPrivacy10signposter10signpostID9isolation7closurexAD0G0O0T10DescriptorV_SSSgAVSbSgSSyYbcSgSSxYbcSgSSs5Error_pYbcSgAD0T8Protocol_pSgAD0dE0O07PayloadV0OAA12OSSignposterVSgAA010OSSignpostY0VSgScA_pSgYixAS0T0Cy_xGYaKXEtYaKs8SendableRzlFfA7_
- _$s2os6LoggerV9subsystem8categoryACSS_SStcfC
- _$s7Network10NWEndpointOs23CustomStringConvertible18AppIntentsServicesMc
- _$s7Network21NWActorSystemDelegatePAAE16inboundWorkBegan6workIDy10Foundation4UUIDV_tF
- _swift_unknownObjectRetain_n
CStrings:
+ " live connection(s)"
+ "%s disconnected with nothing outstanding: tearing down session, details: %s"
+ "%s disconnected: holding its session for %s, details: %s"
+ "%s grace period elapsed: tearing down session"
+ "%s lost a connection but its session is still in use"
+ "%s pre-teardown state:\n%s"
+ "%s reconnected within its grace period: resuming session"
+ "%sCannot cancel execution: executor is nil"
+ "%sDuplicate request for a known execution: replaying its last response instead of performing it again"
+ "%sDuplicate request for an execution still in flight: awaiting its outcome instead of performing it again"
+ "%sExecution has already finished: replaying its retained response"
+ "%sHome device pairing management disabled. Default to allow: true."
+ "%sReceived environmentForViewSnippet request"
+ "%sReceived preferredContentSizeForViewSnippet request"
+ "%sResponding to environment for view snippet | snippetEnvironment=%@"
+ "%sResponding to preferred content size for view snippet | size=%s"
+ "%sResuming completion with error"
+ "%sTurn was already answered: replaying the recorded outcome"
+ "%sWatch pairing management enabled. Default to allow: true."
+ "Cancelling execution %s (%s)"
+ "ClientSessionGracePeriod"
+ "Evicted performAppIntent:%s (%s): %s"
+ "ExecutionResultRetention"
+ "Executions: (none)"
+ "Memory pressure: dropped %ld retained execution result(s) across %ld session(s); a retry for any of them will perform its intent again"
+ "OS_dispatch_source_memorypressure"
+ "Purging %ld retained result(s): the system is under memory pressure"
+ "Tearing down %ld execution(s): their session has ended"
+ "Tracking new connection for %s"
+ "clientSession.grace"
+ "com.apple.remoteappintentsd.GroundControl"
+ "disconnected, awaiting reconnection"
+ "executionResultRetention"
+ "executionStore"
+ "finished"
+ "gracePeriod"
+ "it produced no outcome to retain"
+ "logger"
+ "memoryPressureSource"
+ "no executor was started for it"
+ "performAppIntent:%s finished; retaining its result for %s so a retry can be answered without performing it again"
+ "reserved"
+ "retention window elapsed"
+ "retentionWindow"
+ "running"
- " [connected for "
- "%s disconnected with no active session"
- "%s disconnected: tearing down session, details: %s"
- "%s pre-teardown state: %s"
- "Cannot cancel execution: executor is nil"
- "Connected clients"
- "Home device pairing management disabled. Default to allow: true."
- "LNConnectionStore not available"
- "NWActorCall_legacy"
- "PerformActionDelegates: "
- "Resuming completion with error"
- "Tracking new peer: %s"
- "Watch pairing management enabled. Default to allow: true."
- "[%s] Received environmentForViewSnippet request"
- "[%s] Received preferredContentSizeForViewSnippet request"
- "[%s] Responding to environment for view snippet | snippetEnvironment=%@"
- "[%s] Responding to preferred content size for view snippet | size=%s"
- "delegateStore"
- "performActionDelegateStore"
- "remoteDispatcher"
```
