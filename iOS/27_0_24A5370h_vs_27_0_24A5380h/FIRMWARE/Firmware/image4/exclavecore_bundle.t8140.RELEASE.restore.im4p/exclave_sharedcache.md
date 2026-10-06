## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x171e0` | `0x186b0` | **`+0x14d0`** |
| `__TEXT.__const` | `0x121014` | `0x122134` | **`+0x1120`** |
| `__DATA.__const` | `0x3e5f8` | `0x3d578` | **`-0x1080`** |
| `__TEXT.__text` | `0x5e8978` | `0x5e7b24` | **`-0xe54`** |
| `__TEXT.__constg_swiftt` | `0x27094` | `0x27e48` | **`+0xdb4`** |
| `__TEXT.__cstring` | `0x4ffc1` | `0x4f291` | **`-0xd30`** |
| `__DATA.__ENDPOINTS` | `0x19af0` | `0x1a221` | **`+0x731`** |
| `__TEXT.__swift5_fieldmd` | `0x1b914` | `0x1bfc8` | **`+0x6b4`** |
| `__PDATA.__bss` | `0xc8e8` | `0xc4a8` | **`-0x440`** |
| `__TEXT.__swift5_typeref` | `0x13de2` | `0x14022` | **`+0x240`** |
| `__PDATA.__const` | `0x6698` | `0x67b0` | **`+0x118`** |
| `__TEXT.__swift5_reflstr` | `0x11df8` | `0x11ef8` | **`+0x100`** |
| `__TEXT.__swift5_types` | `0x239c` | `0x2474` | **`+0xd8`** |
| `__TEXT.__eh_frame` | `0x34e68` | `0x34f10` | **`+0xa8`** |
| `__DATA.__bss` | `0xe360` | `0xe3e0` | **`+0x80`** |
| `__TEXT.__swift_as_cont` | `0x11b0` | `0x11f8` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0xfe8` | `0x1018` | **`+0x30`** |
| `__DATA.__auth_ptr` | `0x2318` | `0x2338` | **`+0x20`** |
| `__PDATA.__auth_ptr` | `0x268` | `0x280` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x7a08` | `0x7a20` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x3ca0` | `0x3cb4` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x988` | `0x994` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0xafc` | `0xb08` | **`+0xc`** |
| `__DATA.__got` | `0x18` | `0x10` | **`-0x8`** |
| `__TEXT.__chain_fixups` | `0xb0` | `0xb8` | **`+0x8`** |
| `__TEXT.__swift5_types2` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x96c` | `0x970` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__TIGHTBEAM`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__thread_vars`
- `__PDATA.__data`
- `__PDATA.__mod_init_func`
- `__PDATA.__shared_cache`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-1777.0.2.0.4
-  Functions: 22975
+1777.0.16.0.0
+  Functions: 22927

-  CStrings:  7324
+  CStrings:  7283
CStrings:
+ " nodes; falling back to first node"
+ "Deferred send unsupported"
+ "Invalid configuration"
+ "Message encode failed"
+ "No notification pending"
+ "Notification check-in failed"
+ "Notification receive failed"
+ "Validation failed"
+ "] Created Contrast Checker with configuration: "
+ "] No matching contrast-indicator node found among "
+ "contrast-indicator-"
+ "malloc assertion \"!memtag_config.tag_data\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8865)"
+ "malloc assertion \"(chunk_capacity & 1) == 0 || chunk_padding != 0\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8293)"
+ "malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2730)"
+ "malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2905)"
+ "malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7834)"
+ "malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:969)"
+ "malloc assertion \"middle_pte % XZM_PAGE_TABLE_GRANULE == 0\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:995)"
+ "malloc assertion \"middle_pte_middle < ranges[0].max_address\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:1035)"
+ "malloc assertion \"old_size\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:6830)"
+ "malloc assertion \"range_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:990)"
+ "malloc assertion \"ranges[0].min_address < middle_pte_middle\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:1034)"
+ "malloc assertion \"ranges[0].min_address < ranges[0].max_address\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:971)"
+ "malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5336)"
+ "no fixup data for faultable range [%#lx, %#lx) found"
+ "rawServiceConnection: message is not backed by a service connection"
+ "write_float_string"
- "ALSManager is already configured!"
- "invalid handler object, does not conform to AneUpcallsMethods"
- "invalid handler object, does not conform to AoeUpcallsMethods"
- "invalid handler object, does not conform to BackingMethods"
- "invalid handler object, does not conform to ConclaveUpcallsMethods"
- "invalid handler object, does not conform to CoreAudioOrchestrationUpcallsMethods"
- "invalid handler object, does not conform to DaemonNotificationServerMethods"
- "invalid handler object, does not conform to DartMethods"
- "invalid handler object, does not conform to DeviceServerMethods"
- "invalid handler object, does not conform to DriverUpcallsMethods"
- "invalid handler object, does not conform to DumpMethods"
- "invalid handler object, does not conform to EXBrightComponentMethods"
- "invalid handler object, does not conform to EXDARTDriverMethods"
- "invalid handler object, does not conform to EntropyBrokerComponentMethods"
- "invalid handler object, does not conform to ExclaveAudioArbiterControllerMethods"
- "invalid handler object, does not conform to ExclaveCoprocessorEndpointComponentMethods"
- "invalid handler object, does not conform to ExclaveCoprocessorGatewayComponentMethods"
- "invalid handler object, does not conform to ExclaveCredentialManagerComponentMethods"
- "invalid handler object, does not conform to ExclaveDARTMemoryMapperComponentMethods"
- "invalid handler object, does not conform to ExclaveIndicatorControllerMethods"
- "invalid handler object, does not conform to ExclaveSEPManagerMethods"
- "invalid handler object, does not conform to ExfiltrationUpcallsMethods"
- "invalid handler object, does not conform to IDumpMethods"
- "invalid handler object, does not conform to IReadAccessMethods"
- "invalid handler object, does not conform to IWriteAccessMethods"
- "invalid handler object, does not conform to LegacyUpcallsMethods"
- "invalid handler object, does not conform to LogServerMethods"
- "invalid handler object, does not conform to LpwUpcallsMethods"
- "invalid handler object, does not conform to MemoryUpcallsMethods"
- "invalid handler object, does not conform to NotificationUpcallsMethods"
- "invalid handler object, does not conform to ReadAccessMethods"
- "invalid handler object, does not conform to RedactedLogServerMethods"
- "invalid handler object, does not conform to Span0Methods"
- "invalid handler object, does not conform to Span1Methods"
- "invalid handler object, does not conform to Span2Methods"
- "invalid handler object, does not conform to Span3Methods"
- "invalid handler object, does not conform to Span4Methods"
- "invalid handler object, does not conform to Span5Methods"
- "invalid handler object, does not conform to Span6Methods"
- "invalid handler object, does not conform to Span7Methods"
- "invalid handler object, does not conform to StackshotServerFilterMethods"
- "invalid handler object, does not conform to StackshotServerRedactedComponentMethods"
- "invalid handler object, does not conform to StatsServerComponentMethods"
- "invalid handler object, does not conform to StorageUpcallsMethods"
- "invalid handler object, does not conform to TestUpcallsMethods"
- "invalid handler object, does not conform to WriteAccessMethods"
- "invalid handler object, does not conform to XBackingMethods"
- "invalid handler object, does not conform to XDumpMethods"
- "invalid handler object, does not conform to XReadAccessMethods"
- "invalid handler object, does not conform to XWriteAccessMethods"
- "invalid handler object, does not conform to XnuAccessMethods"
- "invalid handler object, does not conform to XnuContentUpcallsMethods"
- "invalid handler object, does not conform to XnuProxyNotificationServerMethods"
- "malloc assertion \"!memtag_config.tag_data\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8856)"
- "malloc assertion \"(chunk_capacity & 1) == 0 || chunk_padding != 0\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8284)"
- "malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2723)"
- "malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2897)"
- "malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7826)"
- "malloc assertion \"allocation_front_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:963)"
- "malloc assertion \"middle_pte % XZM_PAGE_TABLE_GRANULE == 0\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:989)"
- "malloc assertion \"middle_pte_middle < ranges[0].max_address\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:1029)"
- "malloc assertion \"old_size\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:6822)"
- "malloc assertion \"range_count == 2\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:984)"
- "malloc assertion \"ranges[0].min_address < middle_pte_middle\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:1028)"
- "malloc assertion \"ranges[0].min_address < ranges[0].max_address\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:965)"
- "malloc assertion \"success\" failed (/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5328)"
- "serviceConnection: message is not backed by a service connection"
- "write_float"
```
