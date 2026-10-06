## SwiftCRLite

> `/System/Library/PrivateFrameworks/SwiftCRLite.framework/SwiftCRLite`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x936b8` | `0xafc9c` | **`+0x1c5e4`** |
| `__DATA.__bss` | `0x9500` | `0xad10` | **`+0x1810`** |
| `__TEXT.__const` | `0x7ad8` | `0x9234` | **`+0x175c`** |
| `__AUTH_CONST.__const` | `0x4a70` | `0x59f9` | **`+0xf89`** |
| `__TEXT.__eh_frame` | `0x3ec8` | `0x4acc` | **`+0xc04`** |
| `__TEXT.__swift5_fieldmd` | `0x2290` | `0x2af0` | **`+0x860`** |
| `__TEXT.__swift5_reflstr` | `0x1692` | `0x1dc5` | **`+0x733`** |
| `__DATA.__data` | `0xef8` | `0x1538` | **`+0x640`** |
| `__AUTH_CONST.__objc_const` | `0x1158` | `0x1758` | **`+0x600`** |
| `__TEXT.__unwind_info` | `0x1ef0` | `0x24f0` | **`+0x600`** |
| `__TEXT.__cstring` | `0x3aaf` | `0x405c` | **`+0x5ad`** |
| `__TEXT.__swift5_typeref` | `0x1a83` | `0x1ed7` | **`+0x454`** |
| `__AUTH.__data` | `0x2d8` | `0x6f0` | **`+0x418`** |
| `__TEXT.__constg_swiftt` | `0x1794` | `0x1b8c` | **`+0x3f8`** |
| `__TEXT.__oslogstring` | `0x1256` | `0x164e` | **`+0x3f8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2b0` | `0x450` | **`+0x1a0`** |
| `__TEXT.__objc_methlist` | `0x38c` | `0x4bc` | **`+0x130`** |
| `__AUTH.__objc_data` | `0xe0` | `0x1e0` | **`+0x100`** |
| `__DATA_DIRTY.__data` | `0x18d0` | `0x17e8` | **`-0xe8`** |
| `__TEXT.__swift5_proto` | `0x61c` | `0x6e4` | **`+0xc8`** |
| `__DATA_CONST.__got` | `0x4e0` | `0x560` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x368` | `0x3e4` | **`+0x7c`** |
| `__AUTH_CONST.__auth_got` | `0x1148` | `0x11b0` | **`+0x68`** |
| `__TEXT.__swift5_types` | `0x208` | `0x270` | **`+0x68`** |
| `__DATA_DIRTY.__objc_data` | `0x590` | `0x540` | **`-0x50`** |
| `__TEXT.__swift5_assocty` | `0x330` | `0x380` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xd0` | `0x110` | **`+0x40`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x60` | **`+0x40`** |
| `__DATA_CONST.__objc_classlist` | `0x90` | `0xb0` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x30` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x74` | `0x8c` | **`+0x18`** |
| `__DATA.__common` | `0x18` | `0x28` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x4c` | `0x58` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x80` | `0x8c` | **`+0xc`** |
| `__TEXT.__swift5_protos` | `0x14` | `0x1c` | **`+0x8`** |

### Other Changes

```diff

-116.0.0.0.2
+134.0.7.0.1
+  - /System/Library/Frameworks/CFNetwork.framework/CFNetwork

-  - /System/Library/PrivateFrameworks/CascadingFilters.framework/CascadingFilters

+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags
+  - /System/Library/PrivateFrameworks/MessageSecurity.framework/MessageSecurity

+  - /usr/lib/libcompression.dylib

+  - /usr/lib/swift/libswiftCompression.dylib

-  Functions: 2750
-  Symbols:   1134
-  CStrings:  460
+  Functions: 3300
+  Symbols:   1327
+  CStrings:  526
Symbols:
+ -[SwiftCRLiteClient initWithURL:creationAllowed:isDaemon:error:]
+ _MSCMSContentTypeData
+ _MSCMSContentTypeSignedData
+ _OBJC_CLASS_$_MSCMSContentInfo
+ _OBJC_CLASS_$_MSCMSSignedData
+ _OBJC_CLASS_$_MSCMSSignerInfo
+ _OBJC_CLASS_$_NSFileHandle
+ _OBJC_CLASS_$_NSHTTPURLResponse
+ _OBJC_CLASS_$_NSISO8601DateFormatter
+ _OBJC_CLASS_$_NSJSONSerialization
+ _OBJC_CLASS_$_NSMutableURLRequest
+ _OBJC_CLASS_$_NSNumber
+ _OBJC_CLASS_$_NSURLProtocol
+ _OBJC_CLASS_$_OS_dispatch_source
+ _OBJC_CLASS_$__TtC11SwiftCRLite17StreamingDownload
+ _OBJC_METACLASS_$__TtC11SwiftCRLite17StreamingDownload
+ _SecCertificateCopyCommonName
+ _SecCertificateCopySignatureAlgorithm
+ _SecCertificateNotValidAfter
+ _SecCertificateNotValidBefore
+ __DATA__TtC11SwiftCRLite17StreamingDownload
+ __DATA__TtC11SwiftCRLite19DecompressionStream
+ __DATA__TtC11SwiftCRLite19ValidMetricCounters
+ __DATA__TtC11SwiftCRLite26ValidConfigurationRegistry
+ __INSTANCE_METHODS__TtC11SwiftCRLite17StreamingDownload
+ __IVARS__TtC11SwiftCRLite17StreamingDownload
+ __IVARS__TtC11SwiftCRLite19DecompressionStream
+ __IVARS__TtC11SwiftCRLite19ValidMetricCounters
+ __IVARS__TtC11SwiftCRLite26ValidConfigurationRegistry
+ __METACLASS_DATA__TtC11SwiftCRLite17StreamingDownload
+ __METACLASS_DATA__TtC11SwiftCRLite19DecompressionStream
+ __METACLASS_DATA__TtC11SwiftCRLite19ValidMetricCounters
+ __METACLASS_DATA__TtC11SwiftCRLite26ValidConfigurationRegistry
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSURLSessionDataDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSURLSessionTaskDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSURLSessionDataDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSURLSessionTaskDelegate
+ __OBJC_$_PROTOCOL_REFS_NSURLSessionDataDelegate
+ __OBJC_$_PROTOCOL_REFS_NSURLSessionTaskDelegate
+ __OBJC_$_PROTOCOL_REFS_OS_dispatch_source
+ __OBJC_$_PROTOCOL_REFS_OS_dispatch_source_timer
+ __OBJC_LABEL_PROTOCOL_$_NSURLSessionDataDelegate
+ __OBJC_LABEL_PROTOCOL_$_NSURLSessionTaskDelegate
+ __OBJC_LABEL_PROTOCOL_$_OS_dispatch_source
+ __OBJC_LABEL_PROTOCOL_$_OS_dispatch_source_timer
+ __OBJC_PROTOCOL_$_NSURLSessionDataDelegate
+ __OBJC_PROTOCOL_$_NSURLSessionTaskDelegate
+ __OBJC_PROTOCOL_$_OS_dispatch_source
+ __OBJC_PROTOCOL_$_OS_dispatch_source_timer
+ __PROTOCOLS__TtC11SwiftCRLite17StreamingDownload
+ ___swift_get_extra_inhabitant_index.8Tm
+ ___swift_memcpy104_8
+ ___swift_memcpy48_8
+ ___swift_project_boxed_opaque_existential_0Tm
+ ___swift_store_extra_inhabitant_index.9Tm
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_SwiftCRLite
+ __swift_implicitisolationactor_to_executor_cast
+ _associated conformance 11SwiftCRLite0B12FilterStatusOSHAASQ
+ _associated conformance 11SwiftCRLite0B12LogTimestampVSHAASQ
+ _associated conformance 11SwiftCRLite0B6ResultV6StatusOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 11SwiftCRLite0aB12FeatureFlagsOSHAASQ
+ _associated conformance 11SwiftCRLite10MembershipOSHAASQ
+ _associated conformance 11SwiftCRLite15CMSVerifyResultV10CodingKeys33_75B79980D8B07C50D666890C9A66D941LLOSHAASQ
+ _associated conformance 11SwiftCRLite15CMSVerifyResultV10CodingKeys33_75B79980D8B07C50D666890C9A66D941LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 11SwiftCRLite15CMSVerifyResultV10CodingKeys33_75B79980D8B07C50D666890C9A66D941LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 11SwiftCRLite15CMSVerifyResultV6SignerV10CodingKeys33_75B79980D8B07C50D666890C9A66D941LLOSHAASQ
+ _associated conformance 11SwiftCRLite15CMSVerifyResultV6SignerV10CodingKeys33_75B79980D8B07C50D666890C9A66D941LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 11SwiftCRLite15CMSVerifyResultV6SignerV10CodingKeys33_75B79980D8B07C50D666890C9A66D941LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 11SwiftCRLite17TimestampIntervalVSHAASQ
+ _associated conformance 11SwiftCRLite18ClubcardIndexEntryVSHAASQ
+ _associated conformance 11SwiftCRLite18ValidConfigurationV10CodingKeys33_A6F63318F2F3DBDFAFCAA401DD988FEALLOSHAASQ
+ _associated conformance 11SwiftCRLite18ValidConfigurationV10CodingKeys33_A6F63318F2F3DBDFAFCAA401DD988FEALLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 11SwiftCRLite18ValidConfigurationV10CodingKeys33_A6F63318F2F3DBDFAFCAA401DD988FEALLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 11SwiftCRLite19ValidMetricCountersC0D8SnapshotV10CodingKeys33_490DD993B471F368E0A77DD556CCE0FCLLOSHAASQ
+ _associated conformance 11SwiftCRLite19ValidMetricCountersC0D8SnapshotV10CodingKeys33_490DD993B471F368E0A77DD556CCE0FCLLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 11SwiftCRLite19ValidMetricCountersC0D8SnapshotV10CodingKeys33_490DD993B471F368E0A77DD556CCE0FCLLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 11SwiftCRLite20ClubcardParsingErrorO10Foundation09LocalizedE0AAs0E0
+ _associated conformance 11SwiftCRLite20ClubcardParsingErrorOSHAASQ
+ _associated conformance 11SwiftCRLite25ValidMetricCloudTelemetryC5EventOSHAASQ
+ _compression_stream_destroy
+ _compression_stream_init
+ _compression_stream_process
+ _flat unique So24OS_dispatch_source_timer_p
+ _ftruncate
+ _get_enum_tag_for_layout_string 11SwiftCRLite0B12LogTimestampVSg
+ _get_type_metadata 15Synchronization5MutexVy10Foundation4UUIDVSgG noncopyable
+ _get_type_metadata 15Synchronization5MutexVy11SwiftCRLite16CachedFilterFileVSgG noncopyable
+ _get_type_metadata 15Synchronization5MutexVySDy10Foundation4UUIDVy11SwiftCRLite18ValidConfigurationVYbcGG noncopyable
+ _get_type_metadata 15Synchronization5MutexVySo24OS_dispatch_source_timer_pSgG noncopyable
+ _kCFURLRequestDoNotDecodeData
+ _mmap
+ _munmap
+ _objc_release_x9
+ _objc_retainAutorelease
+ _sched_yield
+ _shm_open
+ _sqlite3_get_autocommit
+ _swift_getAtKeyPath
+ _swift_getKeyPath
+ _swift_getObjCClassFromMetadata
+ _swift_release_x9
+ _swift_retain_x27
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _symbolic $s11SwiftCRLite7AsQueryP
+ _symbolic $s11SwiftCRLite9QueryableP
+ _symbolic SDySSSbG
+ _symbolic SDySSypG
+ _symbolic SDy__________G 10Foundation4DataV 11SwiftCRLite17TimestampIntervalV
+ _symbolic SDy__________G 10Foundation4DataV 11SwiftCRLite18ClubcardIndexEntryV
+ _symbolic SDy_____y_____YbcG 10Foundation4UUIDV 11SwiftCRLite18ValidConfigurationV
+ _symbolic SPy_____G s5UInt8V
+ _symbolic SRy_____G s5UInt8V
+ _symbolic SaySay_____GG s6UInt64V
+ _symbolic Say_____G 11SwiftCRLite0B12LogTimestampV
+ _symbolic Say_____G 11SwiftCRLite0B6ResultV6StatusO
+ _symbolic Say_____G 11SwiftCRLite0B8ClubcardV
+ _symbolic Say_____G 11SwiftCRLite15CMSVerifyResultV6SignerV
+ _symbolic Say_____G 8Dispatch0A13WorkItemFlagsV
+ _symbolic Say_____G So18OS_dispatch_sourceC8DispatchE10TimerFlagsV
+ _symbolic Say_____G s6UInt64V
+ _symbolic Say______pG16underlyingErrors_t s5ErrorP
+ _symbolic ScCy___________pG 10Foundation3URLV s5ErrorP
+ _symbolic ScCy___________pGSg 10Foundation3URLV s5ErrorP
+ _symbolic Si6status_t
+ _symbolic SnySiG
+ _symbolic So12NSFileHandleCSg
+ _symbolic Spy_____G s5UInt8V
+ _symbolic Sry_____G s5UInt8V
+ _symbolic Sv
+ _symbolic SvSg
+ _symbolic _____ 11SwiftCRLite0B12FilterStatusO
+ _symbolic _____ 11SwiftCRLite0B12LogTimestampV
+ _symbolic _____ 11SwiftCRLite0B3KeyV
+ _symbolic _____ 11SwiftCRLite0B5QueryV
+ _symbolic _____ 11SwiftCRLite0B8ClubcardV
+ _symbolic _____ 11SwiftCRLite0aB12FeatureFlagsO
+ _symbolic _____ 11SwiftCRLite10ByteBufferV
+ _symbolic _____ 11SwiftCRLite10MembershipO
+ _symbolic _____ 11SwiftCRLite15CMSVerifyResultV
+ _symbolic _____ 11SwiftCRLite15CMSVerifyResultV10CodingKeys33_75B79980D8B07C50D666890C9A66D941LLO
+ _symbolic _____ 11SwiftCRLite15CMSVerifyResultV6SignerV
+ _symbolic _____ 11SwiftCRLite15CMSVerifyResultV6SignerV10CodingKeys33_75B79980D8B07C50D666890C9A66D941LLO
+ _symbolic _____ 11SwiftCRLite15CertificateInfo33_75B79980D8B07C50D666890C9A66D941LLV
+ _symbolic _____ 11SwiftCRLite16CachedFilterFileV
+ _symbolic _____ 11SwiftCRLite16ClubcardEquationV
+ _symbolic _____ 11SwiftCRLite16ClubcardUniverseV
+ _symbolic _____ 11SwiftCRLite17StreamingDownloadC
+ _symbolic _____ 11SwiftCRLite17TimestampIntervalV
+ _symbolic _____ 11SwiftCRLite18ClubcardIndexEntryV
+ _symbolic _____ 11SwiftCRLite18ValidConfigurationV
+ _symbolic _____ 11SwiftCRLite18ValidConfigurationV10CodingKeys33_A6F63318F2F3DBDFAFCAA401DD988FEALLO
+ _symbolic _____ 11SwiftCRLite19DecompressionStreamC
+ _symbolic _____ 11SwiftCRLite19ValidMetricCountersC
+ _symbolic _____ 11SwiftCRLite19ValidMetricCountersC0D8SnapshotV
+ _symbolic _____ 11SwiftCRLite19ValidMetricCountersC0D8SnapshotV10CodingKeys33_490DD993B471F368E0A77DD556CCE0FCLLO
+ _symbolic _____ 11SwiftCRLite20ClubcardParsingErrorO
+ _symbolic _____ 11SwiftCRLite25ValidMetricCloudTelemetryC5EventO
+ _symbolic _____ 11SwiftCRLite26ValidConfigurationRegistryC
+ _symbolic _____ 11SwiftCRLite8ClubcardV
+ _symbolic _____ So18compression_streama
+ _symbolic _____ s5UInt8V
+ _symbolic _____3key______5entryt 10Foundation4DataV 11SwiftCRLite18ClubcardIndexEntryV
+ _symbolic _____3key______5valuet 10Foundation4DataV 11SwiftCRLite18ClubcardIndexEntryV
+ _symbolic _____Ieghn_ 11SwiftCRLite18ValidConfigurationV
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic _____Sg 11SwiftCRLite0B12LogTimestampV
+ _symbolic _____Sg 11SwiftCRLite0B8ClubcardV
+ _symbolic _____Sg 11SwiftCRLite16CachedFilterFileV
+ _symbolic _____Sg 11SwiftCRLite19DecompressionStreamC
+ _symbolic _____Sg 11SwiftCRLite19ValidMetricCountersC
+ _symbolic _____Sg So20NSFileProtectionTypea
+ _symbolic _____Sg s5Int64V
+ _symbolic _____SgXw 11SwiftCRLite13ValidDatabaseC
+ _symbolic _____SgXw 11SwiftCRLite25ValidMetricCloudTelemetryC
+ _symbolic _____SgXwz_Xx 11SwiftCRLite25ValidMetricCloudTelemetryC
+ _symbolic ______pSg So24OS_dispatch_source_timerP
+ _symbolic ______pSg10underlying_t s5ErrorP
+ _symbolic _____ySDy_____y_____YbcGG 15Synchronization5MutexVAARi_zrlE 10Foundation4UUIDV 11SwiftCRLite18ValidConfigurationV
+ _symbolic _____ySSSbG s18_DictionaryStorageC
+ _symbolic _____ySay_____GG s23_ContiguousArrayStorageC s6UInt64V
+ _symbolic _____y_____3key______5entrytG s23_ContiguousArrayStorageC 10Foundation4DataV 11SwiftCRLite18ClubcardIndexEntryV
+ _symbolic _____y_____G s11_SetStorageC 11SwiftCRLite0D12LogTimestampV
+ _symbolic _____y_____G s11_SetStorageC 11SwiftCRLite25ValidMetricCloudTelemetryC5EventO
+ _symbolic _____y_____G s11_SetStorageC s11AnyHashableV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 11SwiftCRLite15CMSVerifyResultV10CodingKeys33_75B79980D8B07C50D666890C9A66D941LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 11SwiftCRLite15CMSVerifyResultV6SignerV10CodingKeys33_75B79980D8B07C50D666890C9A66D941LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 11SwiftCRLite18ValidConfigurationV10CodingKeys33_A6F63318F2F3DBDFAFCAA401DD988FEALLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 11SwiftCRLite19ValidMetricCountersC0G8SnapshotV10CodingKeys33_490DD993B471F368E0A77DD556CCE0FCLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 11SwiftCRLite15CMSVerifyResultV10CodingKeys33_75B79980D8B07C50D666890C9A66D941LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 11SwiftCRLite15CMSVerifyResultV6SignerV10CodingKeys33_75B79980D8B07C50D666890C9A66D941LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 11SwiftCRLite18ValidConfigurationV10CodingKeys33_A6F63318F2F3DBDFAFCAA401DD988FEALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 11SwiftCRLite19ValidMetricCountersC0G8SnapshotV10CodingKeys33_490DD993B471F368E0A77DD556CCE0FCLLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11SwiftCRLite0E12LogTimestampV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11SwiftCRLite0E8ClubcardV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11SwiftCRLite15CMSVerifyResultV6SignerV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s11AnyHashableV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s6UInt32V
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s6UInt64V
+ _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE 10Foundation4UUIDV
+ _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE 11SwiftCRLite16CachedFilterFileV
+ _symbolic _____y_____SgG 15Synchronization5_CellVAARi_zrlE 10Foundation4UUIDV
+ _symbolic _____y__________G s18_DictionaryStorageC 10Foundation4DataV 11SwiftCRLite17TimestampIntervalV
+ _symbolic _____y__________G s18_DictionaryStorageC 10Foundation4DataV 11SwiftCRLite18ClubcardIndexEntryV
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s5ErrorP
+ _symbolic _____y______pSgG 15Synchronization5MutexVAARi_zrlE So24OS_dispatch_source_timerP
+ _symbolic _____y_____y_____YbcG s18_DictionaryStorageC 10Foundation4UUIDV 11SwiftCRLite18ValidConfigurationV
+ _symbolic x
+ _symbolic yt
+ _time
+ _type_layout_string 11SwiftCRLite0B12LogTimestampV
+ _type_layout_string 11SwiftCRLite0B16KeyAndTimestampsV
+ _type_layout_string 11SwiftCRLite0B3KeyV
+ _type_layout_string 11SwiftCRLite0B5QueryV
+ _type_layout_string 11SwiftCRLite0B8ClubcardV
+ _type_layout_string 11SwiftCRLite10ByteBufferV
+ _type_layout_string 11SwiftCRLite16CachedFilterFileV
+ _type_layout_string 11SwiftCRLite16ClubcardEquationV
+ _type_layout_string 11SwiftCRLite16ClubcardUniverseV
+ _type_layout_string 11SwiftCRLite17TimestampIntervalV
+ _type_layout_string 11SwiftCRLite18ClubcardIndexEntryV
+ _type_layout_string 11SwiftCRLite18ValidConfigurationV
+ _type_layout_string 11SwiftCRLite19ValidMetricCountersC0D8SnapshotV
+ _type_layout_string 11SwiftCRLite8ClubcardV
+ _type_layout_string So18compression_streama
+ _valid_shm_open
- _SecCMSVerify
- _SecTrustGetTrustResult
- _associated conformance 11SwiftCRLite15DownloadContextV10CodingKeys33_1666189628132F99924DFE8EA4664B5DLLOSHAASQ
- _associated conformance 11SwiftCRLite15DownloadContextV10CodingKeys33_1666189628132F99924DFE8EA4664B5DLLOs0E3KeyAAs23CustomStringConvertible
- _associated conformance 11SwiftCRLite15DownloadContextV10CodingKeys33_1666189628132F99924DFE8EA4664B5DLLOs0E3KeyAAs28CustomDebugStringConvertible
- _get_type_metadata 15Synchronization5MutexVy11SwiftCRLite16CachedFilterFile011_DB83DCB2C0J20B812CDB9A1B19594C35ELLVSgG noncopyable
- _os_variant_has_internal_diagnostics
- _swift_release_x12
- _swift_retain_n
- _swift_retain_x24
- _symbolic Say_____G 16CascadingFilters14CRLiteClubcardV
- _symbolic Say_____G 16CascadingFilters18CRLiteLogTimestampV
- _symbolic Si6offset______3key______5valuet7elementt 10Foundation4DataV 16CascadingFilters18ClubcardIndexEntryV
- _symbolic _____ 11SwiftCRLite15DownloadContextV
- _symbolic _____ 11SwiftCRLite15DownloadContextV10CodingKeys33_1666189628132F99924DFE8EA4664B5DLLO
- _symbolic _____ 11SwiftCRLite16CachedFilterFile011_DB83DCB2C0H20B812CDB9A1B19594C35ELLV
- _symbolic _____ 16CascadingFilters9CRLiteKeyV
- _symbolic _____ So18SecTrustResultTypeV
- _symbolic _____3key______5valuet 10Foundation4DataV 16CascadingFilters17TimestampIntervalV
- _symbolic _____3key______5valuet 10Foundation4DataV 16CascadingFilters18ClubcardIndexEntryV
- _symbolic _____Sg 11SwiftCRLite16CachedFilterFile011_DB83DCB2C0H20B812CDB9A1B19594C35ELLV
- _symbolic _____Sg 16CascadingFilters10ByteBufferV
- _symbolic _____Sg 16CascadingFilters14CRLiteClubcardV
- _symbolic _____Sg 16CascadingFilters18CRLiteLogTimestampV
- _symbolic _____Sg 16CascadingFilters18ClubcardIndexEntryV
- _symbolic _____Sg So10CFErrorRefa
- _symbolic _____Sg So11SecTrustRefa
- _symbolic _____y_____3key______5valuetG s23_ContiguousArrayStorageC 10Foundation4DataV 16CascadingFilters18ClubcardIndexEntryV
- _symbolic _____y_____G s11_SetStorageC 16CascadingFilters18CRLiteLogTimestampV
- _symbolic _____y_____G s22KeyedDecodingContainerV 11SwiftCRLite15DownloadContextV10CodingKeys33_1666189628132F99924DFE8EA4664B5DLLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 11SwiftCRLite15DownloadContextV10CodingKeys33_1666189628132F99924DFE8EA4664B5DLLO
- _symbolic _____y_____G s23_ContiguousArrayStorageC 16CascadingFilters14CRLiteClubcardV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 16CascadingFilters18CRLiteLogTimestampV
- _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE 11SwiftCRLite16CachedFilterFile011_DB83DCB2C0J20B812CDB9A1B19594C35ELLV
- _type_layout_string 11SwiftCRLite16CachedFilterFile011_DB83DCB2C0H20B812CDB9A1B19594C35ELLV
CStrings:
+ "Bad HTTP status: "
+ "CMS encapsulated content type is not id-data"
+ "CMS encapsulated content type is not id-data (got: %{public}s)"
+ "CMS message does not contain a SignedData (got: %{public}s)"
+ "CMS message has no signers"
+ "CMS message is not a SignedData ContentInfo"
+ "CMS message is not a detached signature"
+ "CMS message is not detached"
+ "CMS verification successful: %{public}s"
+ "CMS verify failed ("
+ "CMSVerifyResult(failed, "
+ "CMSVerifyResult(verified by '"
+ "CRLite key extraction failed: %@"
+ "Content-Encoding"
+ "Counters stale (%llus since last drain), flushing immediately"
+ "Download decompression failed"
+ "EnableValidUpdater"
+ "Failed to apply ValidConfiguration update: %@"
+ "Failed to apply initial ValidConfiguration: %@"
+ "Failed to mmap shared memory for metrics"
+ "Failed to open metric counters shm: %s"
+ "Failed to open shared memory for metrics"
+ "Metric flush timer fired"
+ "NTO1V1Writer"
+ "PRAGMA cache_size = "
+ "PRAGMA cache_spill = "
+ "SELECT value FROM admin WHERE key = 'disable_background_updates'"
+ "SecPolicyCreateAppleValidCMS returned nil"
+ "Starting metric flush timer (%llu min interval, first fire in %lds)"
+ "SwiftCRLite.StreamingDownload"
+ "Unsupported Content-Encoding: "
+ "ValidClient.create failed: %@"
+ "br, gzip, deflate"
+ "bundle"
+ "certificateSignatureAlgorithm"
+ "cmsSignatureAlgorithmOID"
+ "com.apple.trustd.metrics"
+ "com.apple.trustd.metrics-"
+ "crliteEvalCounters"
+ "crliteEvalCounters: %s"
+ "crliteStatus"
+ "disable_background_updates"
+ "domain"
+ "environment"
+ "failed to decode CMS message: %{public}@"
+ "flags"
+ "isRevoked"
+ "lastDrainedTimestamp"
+ "matched"
+ "metricFlushInterval"
+ "notAfter"
+ "notBefore"
+ "other data"
+ "other data length"
+ "performStreamingDownload(url:acceptEncoding:protection:)"
+ "sct"
+ "seedDatabaseIfNeeded: failed to record attempted version: %@"
+ "signatureVerified"
+ "signatureVerifyError"
+ "signer '%{public}s' failed to create trust ref: %{public}@"
+ "signer '%{public}s' not trusted: %{public}@"
+ "signer '%{public}s' signature verification failed: %{public}@"
+ "sqliteCacheSpill"
+ "streaming download: Content-Encoding=%s Content-Length=%s"
+ "streaming download: completed, %ld bytes received"
+ "streaming download: failed after %ld bytes: %s"
+ "streaming download: received chunk %ld bytes, %ld total"
+ "streaming download: starting request to %s accept-encoding=%s timeout=%f"
+ "trust evaluation failed"
+ "trustResultDetailsJSON"
+ "valid-streaming-"
- "CRLite key extraction failed: %{public}@"
- "Database already at uptodate version, skipping update"
- "SecTrustEvaluate failed with error: %d"
- "SecTrustEvaluate not trusted: %u details: %{public}@"
- "ValidClient.create failed: %{public}@"
```
