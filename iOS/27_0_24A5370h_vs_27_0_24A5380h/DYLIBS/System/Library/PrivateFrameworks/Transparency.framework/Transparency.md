## Transparency

> `/System/Library/PrivateFrameworks/Transparency.framework/Transparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x644b0` | `0x6fe24` | **`+0xb974`** |
| `__TEXT.__const` | `0x3030` | `0x3d44` | **`+0xd14`** |
| `__DATA.__bss` | `0x5ad0` | `0x6620` | **`+0xb50`** |
| `__TEXT.__eh_frame` | `0x1ba8` | `0x26a8` | **`+0xb00`** |
| `__DATA_DIRTY.__bss` | `0x198` | `0x910` | **`+0x778`** |
| `__DATA_DIRTY.__objc_data` | `0x13f8` | `0x1af8` | **`+0x700`** |
| `__AUTH.__objc_data` | `0x988` | `0x2d8` | **`-0x6b0`** |
| `__AUTH_CONST.__const` | `0x3610` | `0x39e8` | **`+0x3d8`** |
| `__TEXT.__unwind_info` | `0x2418` | `0x27f0` | **`+0x3d8`** |
| `__TEXT.__swift5_typeref` | `0x9ba` | `0xd2c` | **`+0x372`** |
| `__TEXT.__swift5_fieldmd` | `0x86c` | `0xab8` | **`+0x24c`** |
| `__DATA_DIRTY.__data` | `0x30` | `0x230` | **`+0x200`** |
| `__TEXT.__constg_swiftt` | `0x7b4` | `0x954` | **`+0x1a0`** |
| `__AUTH_CONST.__auth_got` | `0xb00` | `0xc58` | **`+0x158`** |
| `__TEXT.__swift5_reflstr` | `0x73a` | `0x88f` | **`+0x155`** |
| `__TEXT.__cstring` | `0x2e1c` | `0x2f41` | **`+0x125`** |
| `__DATA.__data` | `0xe60` | `0xf70` | **`+0x110`** |
| `__AUTH_CONST.__objc_const` | `0x7f30` | `0x8018` | **`+0xe8`** |
| `__TEXT.__swift5_proto` | `0x2bc` | `0x34c` | **`+0x90`** |
| `__TEXT.__swift5_acfuncs` | `—` | `0x78` | **`+0x78`** |
| `__TEXT.__swift_as_cont` | `0xbc` | `0x128` | **`+0x6c`** |
| `__DATA_CONST.__got` | `0x5c0` | `0x618` | **`+0x58`** |
| `__TEXT.__swift5_assocty` | `0x1e0` | `0x230` | **`+0x50`** |
| `__TEXT.__swift_as_entry` | `0x6c` | `0xa8` | **`+0x3c`** |
| `__AUTH.__data` | `0x450` | `0x420` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x4a20` | `0x4a50` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x6c` | `0x9c` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1618` | `0x1638` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ff0` | `0x2010` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0xb0` | `0xd0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x4bc` | `0x4d8` | **`+0x1c`** |
| `__DATA.__common` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x1e1b` | `0x1e12` | **`-0x9`** |
| `__DATA_CONST.__objc_classlist` | `0x260` | `0x268` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3ac` | `0x3b0` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x8` | `0xc` | **`+0x4`** |

### Other Changes

```diff

-1766.0.13.0.0
+1766.0.27.0.0

+  - /System/Library/PrivateFrameworks/XPCDistributed.framework/XPCDistributed

+  - /usr/lib/swift/libswiftDistributed.dylib

-  Functions: 3304
-  Symbols:   3420
-  CStrings:  752
+  Functions: 3550
+  Symbols:   3504
+  CStrings:  761
Symbols:
+ -[SoftwareTransparency dealloc]
+ -[SoftwareTransparency endpointConnection]
+ -[SoftwareTransparency setEndpointConnection:]
+ -[TransparencySettings getInt:]
+ GCC_except_table24
+ _OBJC_CLASS_$__TtCs12_SwiftObject
+ _OBJC_IVAR_$_SoftwareTransparency._endpointConnection
+ _OBJC_METACLASS_$__TtCs12_SwiftObject
+ __DATA__TtC12Transparency22$CKVDiagnosticsService
+ __IVARS__TtC12Transparency22$CKVDiagnosticsService
+ __METACLASS_DATA__TtC12Transparency22$CKVDiagnosticsService
+ ___34-[SoftwareTransparency connection]_block_invoke
+ ___swift_memcpy32_8
+ ___swift_memcpy48_8
+ _associated conformance 12Transparency12KTErrorChainV10CodingKeys33_63819914047055CD79FAC449C1F06B4BLLOSHAASQ
+ _associated conformance 12Transparency12KTErrorChainV10CodingKeys33_63819914047055CD79FAC449C1F06B4BLLOs0D3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency12KTErrorChainV10CodingKeys33_63819914047055CD79FAC449C1F06B4BLLOs0D3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12Transparency12KTErrorChainVSHAASQ
+ _associated conformance 12Transparency16CKVDeviceFailureV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOSHAASQ
+ _associated conformance 12Transparency16CKVDeviceFailureV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0D3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency16CKVDeviceFailureV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0D3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12Transparency22$CKVDiagnosticsServiceC11Distributed01_D9ActorStubAaD0dE0
+ _associated conformance 12Transparency22$CKVDiagnosticsServiceC11Distributed0D5ActorAA0E6SystemAdEP_AD0deF0
+ _associated conformance 12Transparency22$CKVDiagnosticsServiceC11Distributed0D5ActorAASH
+ _associated conformance 12Transparency22$CKVDiagnosticsServiceC11Distributed0D5ActorAAs12Identifiable
+ _associated conformance 12Transparency22$CKVDiagnosticsServiceCSHAASQ
+ _associated conformance 12Transparency22$CKVDiagnosticsServiceCs12IdentifiableAA2IDsADP_SH
+ _associated conformance 12Transparency22CKVFailureHistoryEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOSHAASQ
+ _associated conformance 12Transparency22CKVFailureHistoryEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency22CKVFailureHistoryEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12Transparency22CKVFailureHistoryEntryV6SourceOSHAASQ
+ _generic environment 11Distributed01_A9ActorStubRz12Transparency21CKVDiagnosticsServiceRzl
+ _generic environment 12Transparency21CKVDiagnosticsServiceRzl
+ _object_getClass
+ _swift_bridgeObjectRelease_n
+ _swift_bridgeObjectRetain_n
+ _swift_conformsToProtocol2
+ _swift_defaultActor_deallocate
+ _swift_defaultActor_destroy
+ _swift_defaultActor_initialize
+ _swift_distributedActor_remote_initialize
+ _swift_distributed_actor_is_remote
+ _swift_release_x22
+ _swift_retain_x19
+ _symbolic $s11Distributed0A5ActorP
+ _symbolic $s12Transparency21CKVDiagnosticsServiceP
+ _symbolic $ss12IdentifiableP
+ _symbolic 11ActorSystem_____Qz 11Distributed0A5ActorP
+ _symbolic BD
+ _symbolic SDySSypG
+ _symbolic SSSgSSxSay_____G______p_____Rz_____RzlIetMHgTgTgozo_ 12Transparency22CKVFailureHistoryEntryV s5ErrorP 11Distributed01_F9ActorStubP AA21CKVDiagnosticsServiceP
+ _symbolic SSSgSSxSay_____G______p_____RzlIetWHgTgTgozo_ 12Transparency22CKVFailureHistoryEntryV s5ErrorP AA21CKVDiagnosticsServiceP
+ _symbolic SSSgSSx______p_____Rz_____RzlIetMHgTgTgzo_ s5ErrorP 11Distributed01_B9ActorStubP 12Transparency21CKVDiagnosticsServiceP
+ _symbolic SSSgSSx______p_____RzlIetWHgTgTgzo_ s5ErrorP 12Transparency21CKVDiagnosticsServiceP
+ _symbolic SSxSaySSG______p_____Rz_____RzlIetMHgTgozo_ s5ErrorP 11Distributed01_B9ActorStubP 12Transparency21CKVDiagnosticsServiceP
+ _symbolic SSxSaySSG______p_____RzlIetWHgTgozo_ s5ErrorP 12Transparency21CKVDiagnosticsServiceP
+ _symbolic SaySDySSypGG
+ _symbolic Say_____G 12Transparency12KTErrorChainV
+ _symbolic Say_____G 12Transparency16CKVDeviceFailureV
+ _symbolic Say_____G 12Transparency22CKVFailureHistoryEntryV
+ _symbolic Say_____GSg 12Transparency12KTErrorChainV
+ _symbolic Se_SEp
+ _symbolic _____ 12Transparency12KTErrorChainV
+ _symbolic _____ 12Transparency12KTErrorChainV10CodingKeys33_63819914047055CD79FAC449C1F06B4BLLO
+ _symbolic _____ 12Transparency16CKVDeviceFailureV
+ _symbolic _____ 12Transparency16CKVDeviceFailureV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____ 12Transparency22$CKVDiagnosticsServiceC
+ _symbolic _____ 12Transparency22CKVFailureHistoryEntryV
+ _symbolic _____ 12Transparency22CKVFailureHistoryEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____ 12Transparency22CKVFailureHistoryEntryV6SourceO
+ _symbolic _____ 14XPCDistributed9XPCSystemC
+ _symbolic _____ 14XPCDistributed9XPCSystemC7ActorIDV
+ _symbolic _____Sg 12Transparency12KTErrorChainV
+ _symbolic _____ySDySSypGG s23_ContiguousArrayStorageC
+ _symbolic _____ySSG 11Distributed18RemoteCallArgumentV
+ _symbolic _____ySSSgG 11Distributed18RemoteCallArgumentV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency12KTErrorChainV10CodingKeys33_63819914047055CD79FAC449C1F06B4BLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency16CKVDeviceFailureV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency22CKVFailureHistoryEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency12KTErrorChainV10CodingKeys33_63819914047055CD79FAC449C1F06B4BLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency16CKVDeviceFailureV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency22CKVFailureHistoryEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12Transparency12KTErrorChainV
+ _type_layout_string 12Transparency12KTErrorChainV
+ _type_layout_string 12Transparency16CKVDeviceFailureV
- _swift_willThrowTypedImpl
CStrings:
+ "clearFailureHistory(forURI:application:)"
+ "com.apple.transparencyd.ckv"
+ "concurrent"
+ "failureHistory(forURI:application:)"
+ "idsKTVerification"
+ "successfulDeviceCount"
+ "uiStatusRawValue"
+ "underlyingErrors"
+ "urisWithFailures(application:)"
```
