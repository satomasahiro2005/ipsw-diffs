## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe8584c` | `0xea8830` | **`+0x22fe4`** |
| `__TEXT.__eh_frame` | `0x7d0e8` | `0x7f694` | **`+0x25ac`** |
| `__TEXT.__cstring` | `0xb0771` | `0xb12d1` | **`+0xb60`** |
| `__TEXT.__swift5_reflstr` | `0x47558` | `0x47fc8` | **`+0xa70`** |
| `__TEXT.__swift5_fieldmd` | `0x7632c` | `0x76b18` | **`+0x7ec`** |
| `__DATA.__const` | `0x138ca0` | `0x139408` | **`+0x768`** |
| `__TEXT.__constg_swiftt` | `0x6dde8` | `0x6e2c4` | **`+0x4dc`** |
| `__TEXT.__const` | `0x1e4614` | `0x1e4ae4` | **`+0x4d0`** |
| `__DATA.__data` | `0x56560` | `0x568f8` | **`+0x398`** |
| `__DATA.__bss` | `0x244e0` | `0x247f0` | **`+0x310`** |
| `__PDATA.__const` | `0x6468` | `0x6698` | **`+0x230`** |
| `__DATA.__auth_ptr` | `0x7c40` | `0x7a70` | **`-0x1d0`** |
| `__DATA.__ENDPOINTS` | `0x1ae75` | `0x1af7c` | **`+0x107`** |
| `__TEXT.__swift5_capture` | `0x360c` | `0x36c0` | **`+0xb4`** |
| `__TEXT.__swift5_assocty` | `0xf5d8` | `0xf650` | **`+0x78`** |
| `__TEXT.__swift_as_cont` | `0x2cf8` | `0x2d54` | **`+0x5c`** |
| `__TEXT.__swift5_types` | `0x731c` | `0x7370` | **`+0x54`** |
| `__DATA.__common` | `0x47b1` | `0x47f1` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x4fa` | `0x536` | **`+0x3c`** |
| `__TEXT.__swift5_builtin` | `0x2aa8` | `0x2ae4` | **`+0x3c`** |
| `__TEXT.__swift5_proto` | `0xba74` | `0xbaac` | **`+0x38`** |
| `__DATA.__TIGHTBEAM_VT` | `0x14a0` | `0x1470` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x6b77` | `0x6ba7` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x17b4` | `0x17e4` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x15e4` | `0x1604` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x2fcd8` | `0x2fcbc` | **`-0x1c`** |
| `__TEXT.__swift5_types2` | `0xac` | `0xb8` | **`+0xc`** |
| `__DATA.__TIGHTBEAM` | `0x578` | `0x570` | **`-0x8`** |
| `__PDATA.__data` | `0x2ae8` | `0x2af0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x1470` | `0x1474` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__thread_vars`
- `__PDATA.__auth_ptr`
- `__PDATA.__mod_init_func`
- `__PDATA.__shared_cache`
- `__TEXT.__chain_fixups`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-1754.0.0.502.5
-  Functions: 52078
+1777.0.2.0.4
+  Functions: 52522

-  CStrings:  16269
+  CStrings:  16314
CStrings:
+ "  [at.apple.com/exclave-code-sign] "
+ " (intraPageOffset: "
+ " [at.apple.com/exclave-code-sign] "
+ " during model unload"
+ "$JgExclaveIndicatorControllerComponent.ExclaveIndicatorController.init(allowInternalEICSecurityPolicies:isRestore:exAudioArbiter:osLog:exHealthCheck:scAOP:buttonDetection:crashDetection:sepVariables:voiceTriggerEvent:prox:exBrightPIL:bufferArbiter:accessoryIndicatorTimestampGetter:ttrDaemonNotification:requestForwarding:medinaState:cameraControl:altDaemonNotification:exHealthCheckB:altDaemonNotificationB:)"
+ "$JgExclavesMessageQueueProxyComponent.ExclavesMessageQueueProxyComponent.init(osLog:consumers:serviceIds:workerCounts:schedulingCategories:)"
+ "%s: Invalid data digest input"
+ "%s: Invalid data digest length: %ld"
+ "%s: fdrDecode->dataImg4.payload_hashed is false"
+ "%s: kAMFDRDecodeOptionManifestOnly, kAMFDRDecodeOptionSubCCOnly, kAMFDRDecodeOptionDataDigestOnly needs to be exclusive to each other"
+ "%s: trust evaluation on customized payload format requires a reStitchManifest"
+ "(managed_unt->managed_bitmap[bitmap_index] & BIT(bit)) == 0"
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
+ "374"
+ "429"
+ ": starting at root, "
+ ": starting in the middle, inserting fake IPCStackEntry"
+ ": storage error "
+ "========== TEST MARKER: "
+ "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Tue Jun 16 00:39:20 PDT 2026; root:AppleImage4_exclavecore-374~4760/ExclaveImage4/RELEASE_ARM64E"
+ "AOEUpcall failed for serviceId: %llu with %s"
+ "Allocated new FW Trusted L2 spill buffer for isoID "
+ "Audio passcode requested too soon after randomK was revealed"
+ "B16@?0^v8"
+ "B16@?0^{tb_message_accumulator_s=QQQ*}8"
+ "BIT STRING encoded with constructed encoding"
+ "Build Date: Tue Jun 16 00:17:18 PDT 2026"
+ "CAS_STACK_NEXT(handle, next) == NULL"
+ "Cannot create dependent member type with NULL base."
+ "Continuation was deinitialized without being resumed."
+ "Creating DART mapping"
+ "DecodingError.typeMismatch: Expected value of type "
+ "Deferred client teardown completed for clientID: "
+ "Deferred client teardown failed for clientID: "
+ "ERROR: Invalid macho header "
+ "ERROR: Skipping "
+ "EXSurface allocationOffset ("
+ "ExclaveOS Image4 Framework Version 7.0.0: Tue Jun 16 00:39:20 PDT 2026; root:AppleImage4_exclavecore-374~4760/ExclaveImage4/RELEASE_ARM64E"
+ "ExclaveSISP-6.12.2"
+ "ExclaveStorage: Can't read dir: "
+ "Explicit tag was not constructed"
+ "FaceLiveliness_Int"
+ "FacePrint_RGB_Int"
+ "Failed to allocate L2 spill buffer: "
+ "Failed to allocate handle"
+ "Failed to consume message for serviceId: %llu with %s"
+ "Failed to free pages and slots, "
+ "Failed to get DVA for new L2 spill buffer UUID: "
+ "Firmware deregistration failed for L2 spill buffer isoID "
+ "Firmware deregistration failed for isoID "
+ "Firmware registration failed for L2 spill buffer, rolling back"
+ "Freed FW Trusted L2 spill buffer UUID "
+ "IISAudioDeviceComponent/IISAudioDeviceComponent_swift.swift"
+ "IISAudioOutputStreamDeviceComponent/IISAudioOutputStreamDeviceComponent_swift.swift"
+ "INTEGER encoded with constructed encoding"
+ "INVALID SIGNATURE "
+ "INVALID SIGNATURE: "
+ "Invalid key value while decoding result type for isPaired"
+ "LearnedFeaturesDenseFeat"
+ "LearnedFeaturesGloMatcher"
+ "LearnedFeaturesGlobalFeat"
+ "LearnedFeaturesLoMatcher"
+ "LearnedFeaturesLoMatcherState"
+ "Missing listeningInfoRevealedTimestamp"
+ "Missing passcodePlaybackStartTimestamp"
+ "OCTET STRING encoded with constructed encoding"
+ "OID encoded with constructed encoding"
+ "PeopleUnderstanding"
+ "Processing deferred client teardown for clientID: "
+ "RandomK requested too soon after passcode playback started"
+ "ResumeWithFlags"
+ "Setting sample timeout = "
+ "Simulate restore state (external: "
+ "Simulate save state (external: "
+ "StorageExclave threw "
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/Vision_internal.framework/Resources/facelivelinessfull_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/Vision_internal.framework/Resources/faceprintrgb_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/Vision_internal.framework/Resources/personalized_object_embedding_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/Frameworks/Vision.framework/faceliveliness_ek_fp16.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/LearnedFeatures.framework/Models/DenseFeat/model.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/LearnedFeatures.framework/Models/GloFeatMatch/model.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/LearnedFeatures.framework/Models/GlobalFeat/model.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/LearnedFeatures.framework/Models/LoFeatMatch/model.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/LearnedFeatures.framework/Models/LoFeatMatchState/model.bundle/*.bundle/main/main_ane"
+ "System/ExclaveKit/System/Library/PrivateFrameworks/PeopleUnderstandingDetection.framework/NoSpeechDetectorModel/model.bundle/*.bundle/main/main_ane"
+ "Thread %p tried to free resource %p (handle %p) that was not in the held resource list"
+ "Thread %p tried to free resource %p that was acquired by another thread (%p, caller=%llx)"
+ "Thread held resource count underflowed %p"
+ "Unexpected exception when calling getPublicKey: "
+ "Unexpected exception when calling getSignature: "
+ "Unexpected resource type in trusted path for isoID "
+ "Unexpected return from endpoint!"
+ "Wed Jun 17 22:30:27 PDT 2026"
+ "XrtHosted_ResumeWithFlags_t"
+ "[VAS abort in function %s at line %d] [true: (%s)] Unable to unmap frame %#lx from vas zeroer %p\n"
+ "[healthCheckMode] .rampUp -> .steady. Ctx: adjustedIBNitsFiltered="
+ "^v8@?0"
+ "_Concurrency/Continuation.swift"
+ "_Img4DecodeInitDummyPayloadForDataDigest"
+ "aneexclavetriage"
+ "bitmap_index < RAM_BITMAP_SLOTS / BITS_PER_UINT64"
+ "cleanupCatInfosForInactiveClients()"
+ "flags"
+ "i24@?0^{?=^{thread}}8^{thread={allocation=^{allocation_map}{?=s}{?=AC}^{allocation}}QCQQQ^{?}(?={?=^{thread}^^{thread}}{heap_element=^{?}{?=^{thread}}{?=^{thread}}Q})^{turnstile}{?={?=CQ}Q}QQQ{inherit_set=^{turnstile}}{?={?=s}{?=s}}QQQCS}16"
+ "isAnyCatalogueDirty(catInfoSnapshot:)"
+ "isPaired threw an unexpected error type"
+ "is_managed_notification"
+ "malloc assertion \"!memtag_config.tag_data\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8856)"
+ "malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2723)"
+ "malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2897)"
+ "malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7826)"
+ "malloc assertion \"old_size\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:6822)"
+ "malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5328)"
+ "storage not ready"
+ "struct XrtHosted_Request_t"
+ "struct XrtHosted_Response_t"
+ "tb_list.c"
+ "thread 0x%x tried to abort conclave transition that was not inflight."
+ "thread holds resources after return from call"
+ "unmapSharedMemoryBuffer: invalid clientHandle "
+ "v20@?0^{tb_connection_s=(?=[97c]^v)}8I16"
+ "v24@?0^{xrt_thread_info=IQQ{?=QQQ}{?=AIIQQQ}Q}8Q16"
+ "v32@?0Q8^{xrt_thread_info=IQQ{?=QQQ}{?=AIIQQQ}Q}16Q24"
+ "vascore__zeroer_zero_attrs_leave_mapped"
+ "workerInvoke failed for serviceId: %llu with %s"
+ "writeAndSyncCatalogue(fullSync:failIfNotDirty:)"
+ "writeFileInternal(client:catInfo:name:offset:length:encrypted:)"
+ "xrt_thread_resource_acquire"
- "\nAneEngineL2SpillBufferMapInfo Summary\n===\nisoId: "
- "\nAneEngineL2SpillBufferMemMap Summary\n===\npriority: "
- " (expected during cleanup before allocation)"
- " but found null instead"
- " from StorageExclave"
- "$JgExclavesMessageQueueProxyComponent.ExclavesMessageQueueProxyComponent.init(osLog:consumerService1:serviceId1:workerCount1:consumerService2:serviceId2:workerCount2:consumerService3:serviceId3:workerCount3:consumerService4:serviceId4:workerCount4:consumerService5:serviceId5:workerCount5:consumerService6:serviceId6:workerCount6:)"
- "$JgFrameBankComponent.FrameBankComponent.init(assetLoader:storageSharedMemory:)"
- "$JgFrameBankComponent.FrameBankXnuContentComponent.init()"
- "%s: cannot set kAMFDRDecodeOptionManifestOnly and kAMFDRDecodeOptionSubCCOnly at the same time"
- "%s: fdrDecode->sealingManifestImg4.payload_hashed is false"
- "%s: trust evaluation on subCC requires a reStitchManifest"
- "(_boot_info.untyped_regions[UNTYPED_MANAGED] .managed_bitmap[bitmap_word] & BIT(bit)) == 0"
- "(_boot_info.untyped_regions[UNTYPED_MANAGED].managed_bitmap[bitmap_word] & BIT(bit)) == 0"
- ", spillBufferDVA: "
- "372"
- "422.0.0.502.1"
- "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Tue Jun  2 21:20:44 PDT 2026; root:AppleImage4_exclavecore-372~1316/ExclaveImage4/RELEASE_ARM64E"
- "AOEUpcall failed"
- "Build Date: Tue Jun  2 20:57:15 PDT 2026"
- "Can't decrement assertion count, SleepCycle: "
- "Can't read dir: "
- "Commit catalog for "
- "Created DMA mapping for EXSurface with DVA "
- "DecodingError.typeMismatch: expected value of type "
- "Decremented L2 spill buffer refCount for isoID "
- "Error creating memory descriptor"
- "ExclaveOS Image4 Framework Version 7.0.0: Tue Jun  2 21:20:44 PDT 2026; root:AppleImage4_exclavecore-372~1316/ExclaveImage4/RELEASE_ARM64E"
- "ExclavePlatform runtime error: FrameLevel2 allocation is not supported yet"
- "ExclaveSISP-6.10.3"
- "Failed to consume message"
- "Failed to deregister L2 spill buffer with FW for isoID: "
- "Failed to get DVA for spill buffer with UUID: "
- "Failed to register L2 spill buffer with FW for "
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
- "FrameAuditerComponents/FrameAuditerComponents.swift"
- "Fri Jun  5 03:29:58 PDT 2026"
- "IISAudioDeviceComponent/IISAudioDeviceComponent_Swift.swift"
- "IISAudioOutputStreamDeviceComponent/IISAudioOutputStreamDeviceComponent_Swift.swift"
- "Invalid isoID to map L2 spill buffer"
- "Managed Phys Base is "
- "Message was enqueued for %llu"
- "No L2 spill buffer tracked for isoID "
- "Region overlaps with previous region"
- "Simulate restore state"
- "Simulate save state"
- "Spill buffer not initialized for trusted compartment"
- "Trying to create CPU mapping for EXSurface"
- "Trying to create DMA mapping for EXSurface"
- "Unexpected exception when calling getAKSSignature: "
- "Updating sample timeout "
- "[StackshotConclaveSupport] Offline done"
- "[StackshotConclaveSupport] Offline start"
- "[StackshotConclaveSupport] no 0x%lx in text segment info\n"
- "[VAS abort in function %s at line %d] [true: (%s)] Unable to unmap frame %#lx from table %#lx at addr %#lx for zeroing\n"
- "bitmap_word <= RAM_BITMAP_SLOTS / BITS_PER_UINT64"
- "cached procedure"
- "chunk is partially present at "
- "getAKSSignature -> AKSSignature(data["
- "getID(clientHandle:)"
- "getRandomK threw an unexpected error type"
- "geting memoryObject"
- "i24@?0^{?=^{thread}}8^{thread={allocation=^{allocation_map}{?=s}{?=AC}^{allocation}}QCQQQ^{?}(?={?=^{thread}^^{thread}}{heap_element=^{?}{?=^{thread}}{?=^{thread}}Q})^{turnstile}{?={?=CQ}Q}QQQ{inherit_set=^{turnstile}}{?={?=s}{?=s}}QQBCS}16"
- "inference request"
- "isAnyCatalogueDirty()"
- "malloc assertion \"!memtag_config.tag_data\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8855)"
- "malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2722)"
- "malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2896)"
- "malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7825)"
- "malloc assertion \"old_size\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:6821)"
- "malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5326)"
- "manualSegManagement(clientHandle:enable:)"
- "sync(clientHandle:)"
- "unlockSubCatalogues(cleanupUnactive:)"
- "unmapRange(clientHandle:)"
- "workerInvoke failed"
- "write(clientHandle:name:offset:length:encrypted:)"
- "writeAndSyncCatalogue(fstag:fullSync:failIfNotDirty:)"
- "writeFileInternal(client:name:offset:length:encrypted:)"
- "writeNoSync(clientHandle:name:offset:length:encrypted:)"
```
