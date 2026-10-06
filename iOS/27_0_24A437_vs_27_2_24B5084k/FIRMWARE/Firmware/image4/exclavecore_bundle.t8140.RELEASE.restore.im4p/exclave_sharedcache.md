## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5f2020` | `0x5fc6b8` | **`+0xa698`** |
| `__TEXT.__swift5_reflstr` | `0x12398` | `0x13508` | **`+0x1170`** |
| `__TEXT.__const` | `0x122d14` | `0x123d84` | **`+0x1070`** |
| `__DATA.__const` | `0x3dac8` | `0x3e5d0` | **`+0xb08`** |
| `__TEXT.__cstring` | `0x4ffc1` | `0x50a21` | **`+0xa60`** |
| `__TEXT.__eh_frame` | `0x35448` | `0x35d38` | **`+0x8f0`** |
| `__TEXT.__swift5_fieldmd` | `0x1c4d4` | `0x1cdb0` | **`+0x8dc`** |
| `__TEXT.__constg_swiftt` | `0x28564` | `0x28a48` | **`+0x4e4`** |
| `__DATA.__data` | `0x18de0` | `0x19110` | **`+0x330`** |
| `__DATA.__ENDPOINTS` | `0x1a328` | `0x1a536` | **`+0x20e`** |
| `__TEXT.__swift5_assocty` | `0x7b78` | `0x7d10` | **`+0x198`** |
| `__TEXT.__swift5_typeref` | `0x1439a` | `0x144ee` | **`+0x154`** |
| `__TEXT.__swift5_proto` | `0x3ddc` | `0x3e94` | **`+0xb8`** |
| `__DATA.__auth_ptr` | `0x2420` | `0x2490` | **`+0x70`** |
| `__PDATA.__const` | `0x67b0` | `0x6800` | **`+0x50`** |
| `__TEXT.__swift5_types` | `0x24cc` | `0x251c` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x1018` | `0x1048` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x11f8` | `0x1224` | **`+0x2c`** |
| `__TEXT.__swift_as_ret` | `0xb08` | `0xb2c` | **`+0x24`** |
| `__TEXT.__swift5_mpenum` | `0x3d4` | `0x3b8` | **`-0x1c`** |
| `__TEXT.__swift_as_entry` | `0x998` | `0x9b4` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0x15cc` | `0x15b8` | **`-0x14`** |
| `__TEXT.__swift5_protos` | `0x988` | `0x998` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__TIGHTBEAM`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__thread_vars`
- `__PDATA.__auth_ptr`
- `__PDATA.__data`
- `__PDATA.__mod_init_func`
- `__PDATA.__shared_cache`
- `__TEXT.__chain_fixups`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_types2`

### Other Changes

```diff

-1777.0.27.0.0
-  Functions: 23028
+1777.40.23.502.2
+  Functions: 23140

-  CStrings:  7363
+  CStrings:  7418
CStrings:
+ "  Quick start = "
+ " message to SEP. ane_id: "
+ " succeeded for ane_id "
+ " will start once sensor sessions are resumed"
+ "$JgExclaveSEPManager.ExclaveSEPANEControlEndpoint"
+ ") < rampUp startTs ("
+ "), this should never happen!"
+ ", nextSubCheck @ "
+ ", priorFiltered="
+ ".failureNoFilteredIB"
+ ".failureRampUpNoProgress(checkType="
+ ".failureTimestampUnderflow"
+ ".failureTimestampUnderflow(lhs="
+ ".rampUp(start @ "
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveCore.iPhoneOS.platform/Developer/SDKs/ExclaveCore.iPhoneOS27.2.Internal.sdk/System/ExclaveCore/System/Library/Frameworks/xrt.framework/Headers/thread.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveCore.iPhoneOS.platform/Developer/SDKs/ExclaveCore.iPhoneOS27.2.Internal.sdk/System/ExclaveCore/usr/local/standalone/RTKit/usr/include/protocols/mbi_tightbeam_protocol.h"
+ "ANE power op returned unknown status byte: "
+ "Active pause requests: "
+ "Adding pause request: "
+ "BUG IN LIBTRACE: log payload "
+ "Failed to get frames from region "
+ "I14@?0{easm_space_unmapxnucontentregionwithflags__result_s=C(?={easm_failure_s=CS})}8"
+ "I28@?0Q8I16@?<I@?{easm_space_unmapxnucontentregionwithflags__result_s=C(?={easm_failure_s=CS})}>20"
+ "Ignoring duplicate pause request: "
+ "Ignoring pause request due to non-enforcing mode: "
+ "Ignoring pause request since ISP watchdog is disabled: "
+ "Ignoring pause request since health checks are disabled: "
+ "Invalid key value while decoding result type for hold_ane_power_assertion"
+ "Invalid key value while decoding result type for release_ane_power_assertion"
+ "Invalid key value while decoding result type for unloadMemoryWithFlags"
+ "Invalid key value while decoding result type for updateXnuContentWithFlags"
+ "Log payload exceeds "
+ "Quick start policy canceled ("
+ "Quick start policy resolved @ GLTB "
+ "Quick start policy violated @ GLTB "
+ "Removed pause request: "
+ "Starting quick start policy @ GLTB "
+ "TB_FATAL: invalid result returned from unmapXnuContentRegionWithFlags (%s:%d)\n"
+ "VIOLATION: CIL never came on during quick start policy"
+ "[LogServer] error: "
+ "]\n  defaultDisplayChanged: triggered="
+ "] .rampUp -> .steady. Ctx: filteredNits="
+ "] .rampUp restart: start "
+ "] Failed to get filtered IB for rampUp, this should never happen! (items: "
+ "] In .rampUp, but currentMIB is nil. This should never happen!"
+ "])\n  medinaStateDisplayWake: allowance="
+ "])\n  quickStart: allowance="
+ "_insecure_random_buf"
+ "_os_log_payload_size(olp), OS_LOG_EXCLAVES_PAYLOAD_MAX"
+ "hold_ane_power_assertion threw an unexpected error type"
+ "i24@?0^{?=^{thread}}8^{thread={allocation=^{allocation_map}{?=s}{?=AC}^{allocation}}QCQQQ^{?}(?={?=^{thread}^^{thread}}{heap_element=^{?}{?=^{thread}}{?=^{thread}}Q})^{turnstile}{?={?=CQ}Q}QQQ{inherit_set=^{turnstile}}{?={?=s}Q}QQQCS}16"
+ "invalid rawValue for ExclaveSEPANEControlEndpoint.Selector "
+ "invalid rawValue for SensorPauseReason: "
+ "invalid rawValue for XnuContentANEFlags: unexpected bits in value, "
+ "invalid rawValue for XnuContentUnloadFlags: unexpected bits in value, "
+ "malloc assertion \"!(zone->xzz_memtag_config.enabled && zone->xzz_memtag_config.max_block_size > XZM_SMALL_BLOCK_SIZE_MAX)\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:982)"
+ "malloc assertion \"!memtag_config.tag_data\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8903)"
+ "malloc assertion \"(chunk_capacity & 1) == 0 || chunk_padding != 0\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8331)"
+ "malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7872)"
+ "malloc assertion \"old_size\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:6854)"
+ "malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:2216)"
+ "malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5356)"
+ "ms\n  displayPower: triggered="
+ "ms, lastFiltered="
+ "nits preserved (MIB="
+ "nits, currentFiltered="
+ "nits, expectedGrowth="
+ "octopus_medina_state_display_wake_allowance"
+ "octopus_no_quick_start"
+ "octopus_quick_start"
+ "olp->olp_tpb.tp_size, OS_LOG_EXCLAVES_TRACEPOINT_HDR_SIZE"
+ "quick-start-allowance"
+ "release_ane_power_assertion threw an unexpected error type"
+ "s[0] || s[1]"
+ "total_memory_usage_bytes"
+ "unmapXnuContentRegionWithFlags"
+ "updateXnuContent(refId:ranges:flags:)"
+ "v14@?0{easm_space_unmapxnucontentregionwithflags__result_s=C(?={easm_failure_s=CS})}8"
+ "vas__easm_unmap_xnu_content_region_with_flags"
+ "x, actualGrowth="
- ", Last increase: "
- ", lastIncreasedIB="
- ".failureRampUpBrightnessBelowStartIB(startIB="
- ".failureRampUpBrightnessDecreased(startIB="
- ".failureRampUpNoProgress(lastIncreasedIB="
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveCore.iPhoneOS.platform/Developer/SDKs/ExclaveCore.iPhoneOS27.0.Internal.sdk/System/ExclaveCore/System/Library/Frameworks/xrt.framework/Headers/thread.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveCore.iPhoneOS.platform/Developer/SDKs/ExclaveCore.iPhoneOS27.0.Internal.sdk/System/ExclaveCore/usr/local/standalone/RTKit/usr/include/protocols/mbi_tightbeam_protocol.h"
- "BUG IN LIBTRACE: Received a BATCH_ERROR while creating a LogBatch"
- "] Cannot estimate ramp duration, invalid target brightness value: "
- "] Switched to MIB ramp up mode during brightness ramp down, ignoring this frame."
- "][healthCheckMode] .rampUp -> .steady. Ctx: adjustedIBNitsFiltered="
- "_os_log_payload_size(olp), OS_LOG_PAYLOAD_HARD_MAX_SIZE"
- "i24@?0^{?=^{thread}}8^{thread={allocation=^{allocation_map}{?=s}{?=AC}^{allocation}}QCQQQ^{?}(?={?=^{thread}^^{thread}}{heap_element=^{?}{?=^{thread}}{?=^{thread}}Q})^{turnstile}{?={?=CQ}Q}QQQ{inherit_set=^{turnstile}}{?={?=s}{?=s}}QQQCS}16"
- "malloc assertion \"!(zone->xzz_memtag_config.enabled && zone->xzz_memtag_config.max_block_size > XZM_SMALL_BLOCK_SIZE_MAX)\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:981)"
- "malloc assertion \"!memtag_config.tag_data\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8865)"
- "malloc assertion \"(chunk_capacity & 1) == 0 || chunk_padding != 0\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8293)"
- "malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7834)"
- "malloc assertion \"old_size\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:6830)"
- "malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:2197)"
- "malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5336)"
- "nits, elapsedWithoutIBIncrease="
- "olp->olp_tpb.tp_size, OS_LOG_PAYLOAD_HDR_SIZE"
- "total_memory_kib"
- "v14@?0{easm_space_unmapxnucontentregion__result_s=C(?={easm_failure_s=CS})}8"
- "vas__easm_unmap_xnu_content_region"
```
