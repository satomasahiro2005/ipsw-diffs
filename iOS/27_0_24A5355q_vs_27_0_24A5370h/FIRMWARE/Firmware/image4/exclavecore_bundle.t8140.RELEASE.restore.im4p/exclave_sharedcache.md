## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5e0a88` | `0x5e8978` | **`+0x7ef0`** |
| `__TEXT.__eh_frame` | `0x33f20` | `0x34e68` | **`+0xf48`** |
| `__TEXT.__cstring` | `0x4fb61` | `0x4ffc1` | **`+0x460`** |
| `__TEXT.__swift5_reflstr` | `0x119b8` | `0x11df8` | **`+0x440`** |
| `__TEXT.__swift5_fieldmd` | `0x1b560` | `0x1b914` | **`+0x3b4`** |
| `__DATA.__const` | `0x3e2b8` | `0x3e5f8` | **`+0x340`** |
| `__PDATA.__const` | `0x6468` | `0x6698` | **`+0x230`** |
| `__TEXT.__constg_swiftt` | `0x26eac` | `0x27094` | **`+0x1e8`** |
| `__DATA.__auth_ptr` | `0x2498` | `0x2318` | **`-0x180`** |
| `__TEXT.__swift5_typeref` | `0x13f3a` | `0x13de2` | **`-0x158`** |
| `__DATA.__ENDPOINTS` | `0x199e9` | `0x19af0` | **`+0x107`** |
| `__TEXT.__const` | `0x120f14` | `0x121014` | **`+0x100`** |
| `__TEXT.__swift5_assocty` | `0x7990` | `0x7a08` | **`+0x78`** |
| `__DATA.__data` | `0x17228` | `0x171e0` | **`-0x48`** |
| `__DATA.__TIGHTBEAM_VT` | `0x870` | `0x8a0` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0x2370` | `0x239c` | **`+0x2c`** |
| `__DATA.__common` | `0x6fa` | `0x71a` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x3c80` | `0x3ca0` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x15a4` | `0x1590` | **`-0x14`** |
| `__DATA.__bss` | `0xe350` | `0xe360` | **`+0x10`** |
| `__DATA.__TIGHTBEAM` | `0x230` | `0x238` | **`+0x8`** |
| `__PDATA.__data` | `0x2ae8` | `0x2af0` | **`+0x8`** |
| `__TEXT.__swift5_types2` | `0x50` | `0x58` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__thread_vars`
- `__PDATA.__auth_ptr`
- `__PDATA.__mod_init_func`
- `__PDATA.__shared_cache`
- `__TEXT.__chain_fixups`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1754.0.0.502.5
-  Functions: 22871
+1777.0.2.0.4
+  Functions: 22975

-  CStrings:  7304
+  CStrings:  7324
CStrings:
+ "$JgExclaveIndicatorControllerComponent.ExclaveIndicatorController.init(allowInternalEICSecurityPolicies:isRestore:exAudioArbiter:osLog:exHealthCheck:scAOP:buttonDetection:crashDetection:sepVariables:voiceTriggerEvent:prox:exBrightPIL:bufferArbiter:accessoryIndicatorTimestampGetter:ttrDaemonNotification:requestForwarding:medinaState:cameraControl:altDaemonNotification:exHealthCheckB:altDaemonNotificationB:)"
+ ".failureALSElectrostaticDischarge"
+ ".failureBrightnessBelowMIB"
+ ".failureHibernationCountChanged"
+ ".failureInvalidDisplayID"
+ ".failureNoALSCalibration"
+ ".failureNoXTalkStats"
+ ".failureNotEnoughContrast"
+ ".failureRampUpBrightnessBelowStartIB"
+ ".failureRampUpBrightnessDecreased"
+ ".failureRampUpDelayed"
+ ".failureRampUpNoProgress"
+ ".failureStaleMIB"
+ ".failureXTalkStatsVerification"
+ "B16@?0^v8"
+ "B16@?0^{tb_message_accumulator_s=QQQ*}8"
+ "CAS_STACK_NEXT(handle, next) == NULL"
+ "Cannot create dependent member type with NULL base."
+ "Continuation was deinitialized without being resumed."
+ "DecodingError.typeMismatch: Expected value of type "
+ "Failed to allocate handle"
+ "ResumeWithFlags"
+ "Setting sample timeout = "
+ "Thread %p tried to free resource %p (handle %p) that was not in the held resource list"
+ "Thread %p tried to free resource %p that was acquired by another thread (%p, caller=%llx)"
+ "Thread held resource count underflowed %p"
+ "Unexpected return from endpoint!"
+ "XrtHosted_ResumeWithFlags_t"
+ "[VAS abort in function %s at line %d] [true: (%s)] Unable to unmap frame %#lx from vas zeroer %p\n"
+ "[healthCheckMode] .rampUp -> .steady. Ctx: adjustedIBNitsFiltered="
+ "^v8@?0"
+ "_Concurrency/Continuation.swift"
+ "flags"
+ "i24@?0^{?=^{thread}}8^{thread={allocation=^{allocation_map}{?=s}{?=AC}^{allocation}}QCQQQ^{?}(?={?=^{thread}^^{thread}}{heap_element=^{?}{?=^{thread}}{?=^{thread}}Q})^{turnstile}{?={?=CQ}Q}QQQ{inherit_set=^{turnstile}}{?={?=s}{?=s}}QQQCS}16"
+ "malloc assertion \"!memtag_config.tag_data\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8856)"
+ "malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2723)"
+ "malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2897)"
+ "malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7826)"
+ "malloc assertion \"old_size\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:6822)"
+ "malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5328)"
+ "struct XrtHosted_Request_t"
+ "struct XrtHosted_Response_t"
+ "tb_list.c"
+ "thread 0x%x tried to abort conclave transition that was not inflight."
+ "thread holds resources after return from call"
+ "v20@?0^{tb_connection_s=(?=[97c]^v)}8I16"
+ "vascore__zeroer_zero_attrs_leave_mapped"
+ "xrt_thread_resource_acquire"
- " but found null instead"
- "DecodingError.typeMismatch: expected value of type "
- "Failure: ALS electrostatic discharge!"
- "Failure: Brightness below MIB!"
- "Failure: Hibernation count changed and our state was not cleared!"
- "Failure: Invalid display ID!"
- "Failure: No ALS calibration!"
- "Failure: No ALS!"
- "Failure: No MIB!"
- "Failure: No XTalk stats!"
- "Failure: Not enough contrast!"
- "Failure: PMU brightness health failure!"
- "Failure: Ramp up brightness below starting IB!"
- "Failure: Ramp up brightness decreased!"
- "Failure: Ramp up delayed!"
- "Failure: Ramp up no progress!"
- "Failure: SIL not enabled!"
- "Failure: Stale MIB!"
- "Failure: XTalk stats verification!"
- "Updating sample timeout "
- "[VAS abort in function %s at line %d] [true: (%s)] Unable to unmap frame %#lx from table %#lx at addr %#lx for zeroing\n"
- "i24@?0^{?=^{thread}}8^{thread={allocation=^{allocation_map}{?=s}{?=AC}^{allocation}}QCQQQ^{?}(?={?=^{thread}^^{thread}}{heap_element=^{?}{?=^{thread}}{?=^{thread}}Q})^{turnstile}{?={?=CQ}Q}QQQ{inherit_set=^{turnstile}}{?={?=s}{?=s}}QQBCS}16"
- "malloc assertion \"!memtag_config.tag_data\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8855)"
- "malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2722)"
- "malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2896)"
- "malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7825)"
- "malloc assertion \"old_size\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:6821)"
- "malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5326)"
```
