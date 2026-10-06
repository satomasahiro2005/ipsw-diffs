## Transparency

> `/System/Library/PrivateFrameworks/Transparency.framework/Transparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4bbf8` | `0x644b0` | **`+0x188b8`** |
| `__DATA.__bss` | `0x30f0` | `0x5ad0` | **`+0x29e0`** |
| `__TEXT.__const` | `0x1ac0` | `0x3030` | **`+0x1570`** |
| `__TEXT.__eh_frame` | `0x660` | `0x1ba8` | **`+0x1548`** |
| `__AUTH_CONST.__const` | `0x2968` | `0x3610` | **`+0xca8`** |
| `__TEXT.__unwind_info` | `0x1ae8` | `0x2418` | **`+0x930`** |
| `__AUTH_CONST.__objc_const` | `0x76a8` | `0x7f30` | **`+0x888`** |
| `__AUTH.__objc_data` | `0x218` | `0x988` | **`+0x770`** |
| `__TEXT.__swift5_typeref` | `0x471` | `0x9ba` | **`+0x549`** |
| `__TEXT.__cstring` | `0x2909` | `0x2e1c` | **`+0x513`** |
| `__TEXT.__objc_methlist` | `0x4544` | `0x4a20` | **`+0x4dc`** |
| `__TEXT.__constg_swiftt` | `0x360` | `0x7b4` | **`+0x454`** |
| `__DATA.__data` | `0xa38` | `0xe60` | **`+0x428`** |
| `__TEXT.__swift5_fieldmd` | `0x504` | `0x86c` | **`+0x368`** |
| `__AUTH_CONST.__auth_got` | `0x810` | `0xb00` | **`+0x2f0`** |
| `__TEXT.__swift5_capture` | `—` | `0x2c4` | **`+0x2c4`** |
| `__TEXT.__swift5_reflstr` | `0x50b` | `0x73a` | **`+0x22f`** |
| `__TEXT.__oslogstring` | `0x1c12` | `0x1e1b` | **`+0x209`** |
| `__DATA_CONST.__got` | `0x438` | `0x5c0` | **`+0x188`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e68` | `0x1ff0` | **`+0x188`** |
| `__AUTH.__data` | `0x2e8` | `0x450` | **`+0x168`** |
| `__TEXT.__swift5_proto` | `0x178` | `0x2bc` | **`+0x144`** |
| `__TEXT.__swift5_assocty` | `0x108` | `0x1e0` | **`+0xd8`** |
| `__TEXT.__swift_as_cont` | `0x4` | `0xbc` | **`+0xb8`** |
| `__AUTH_CONST.__cfstring` | `0x3a00` | `0x3aa0` | **`+0xa0`** |
| `__TEXT.__swift_as_entry` | `0x4` | `0x6c` | **`+0x68`** |
| `__TEXT.__swift_as_ret` | `0x4` | `0x6c` | **`+0x68`** |
| `__TEXT.__swift5_types` | `0x5c` | `0xb0` | **`+0x54`** |
| `__DATA_CONST.__const` | `0x15c8` | `0x1618` | **`+0x50`** |
| `__TEXT.__swift5_builtin` | `0x64` | `0xb4` | **`+0x50`** |
| `__DATA_CONST.__objc_classlist` | `0x218` | `0x260` | **`+0x48`** |
| `__AUTH_CONST.__objc_intobj` | `0x1b0` | `0x1e0` | **`+0x30`** |
| `__DATA_CONST.__objc_protolist` | `0x88` | `0xa0` | **`+0x18`** |
| `__DATA_CONST.__objc_protorefs` | `0x38` | `0x48` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `—` | `0x8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3a8` | `0x3ac` | **`+0x4`** |

### Other Changes

```diff

-1751.0.0.502.1
+1766.0.13.0.0

+  - /System/Library/Frameworks/CryptoKit.framework/CryptoKit

-  Functions: 2606
-  Symbols:   3191
-  CStrings:  705
+  Functions: 3304
+  Symbols:   3420
+  CStrings:  752
Symbols:
+ +[TransparencySettings forceTreeResetPopulating]
+ -[KTVerifierResult setTreeResetInProgress:]
+ -[KTVerifierResult treeResetInProgress]
+ -[TransparencySettings forceTreeResetPopulating]
+ -[TransparencySettings hasInternalDiagnostics]
+ _OBJC_CLASS_$__TtC12Transparency11AETEventKey
+ _OBJC_CLASS_$__TtC12Transparency14AETransparency
+ _OBJC_CLASS_$__TtC12Transparency19AETTransparentEvent
+ _OBJC_CLASS_$__TtC12Transparency21AETVerifyProofRequest
+ _OBJC_CLASS_$__TtC12Transparency22AETVerifyProofResponse
+ _OBJC_CLASS_$__TtC12Transparency26AETEventVerificationResult
+ _OBJC_CLASS_$__TtC12Transparency26AETransparencyXPCInterface
+ _OBJC_CLASS_$__TtC12Transparency28AETransparencyRequestContext
+ _OBJC_CLASS_$__TtC12Transparency8AETEvent
+ _OBJC_IVAR_$_KTVerifierResult._treeResetInProgress
+ _OBJC_METACLASS_$__TtC12Transparency11AETEventKey
+ _OBJC_METACLASS_$__TtC12Transparency14AETransparency
+ _OBJC_METACLASS_$__TtC12Transparency19AETTransparentEvent
+ _OBJC_METACLASS_$__TtC12Transparency21AETVerifyProofRequest
+ _OBJC_METACLASS_$__TtC12Transparency22AETVerifyProofResponse
+ _OBJC_METACLASS_$__TtC12Transparency26AETEventVerificationResult
+ _OBJC_METACLASS_$__TtC12Transparency26AETransparencyXPCInterface
+ _OBJC_METACLASS_$__TtC12Transparency28AETransparencyRequestContext
+ _OBJC_METACLASS_$__TtC12Transparency8AETEvent
+ __Block_copy
+ __Block_release
+ __DATA__TtC12Transparency11AETEventKey
+ __DATA__TtC12Transparency14AETransparency
+ __DATA__TtC12Transparency19AETTransparentEvent
+ __DATA__TtC12Transparency21AETVerifyProofRequest
+ __DATA__TtC12Transparency22AETVerifyProofResponse
+ __DATA__TtC12Transparency26AETEventVerificationResult
+ __DATA__TtC12Transparency26AETransparencyXPCInterface
+ __DATA__TtC12Transparency28AETransparencyRequestContext
+ __DATA__TtC12Transparency8AETEvent
+ __INSTANCE_METHODS__TtC12Transparency11AETEventKey
+ __INSTANCE_METHODS__TtC12Transparency14AETransparency
+ __INSTANCE_METHODS__TtC12Transparency19AETTransparentEvent
+ __INSTANCE_METHODS__TtC12Transparency21AETVerifyProofRequest
+ __INSTANCE_METHODS__TtC12Transparency22AETVerifyProofResponse
+ __INSTANCE_METHODS__TtC12Transparency26AETEventVerificationResult
+ __INSTANCE_METHODS__TtC12Transparency26AETransparencyXPCInterface
+ __INSTANCE_METHODS__TtC12Transparency28AETransparencyRequestContext
+ __INSTANCE_METHODS__TtC12Transparency8AETEvent
+ __IVARS__TtC12Transparency11AETEventKey
+ __IVARS__TtC12Transparency14AETransparency
+ __IVARS__TtC12Transparency19AETTransparentEvent
+ __IVARS__TtC12Transparency21AETVerifyProofRequest
+ __IVARS__TtC12Transparency22AETVerifyProofResponse
+ __IVARS__TtC12Transparency26AETEventVerificationResult
+ __IVARS__TtC12Transparency28AETransparencyRequestContext
+ __IVARS__TtC12Transparency8AETEvent
+ __METACLASS_DATA__TtC12Transparency11AETEventKey
+ __METACLASS_DATA__TtC12Transparency14AETransparency
+ __METACLASS_DATA__TtC12Transparency19AETTransparentEvent
+ __METACLASS_DATA__TtC12Transparency21AETVerifyProofRequest
+ __METACLASS_DATA__TtC12Transparency22AETVerifyProofResponse
+ __METACLASS_DATA__TtC12Transparency26AETEventVerificationResult
+ __METACLASS_DATA__TtC12Transparency26AETransparencyXPCInterface
+ __METACLASS_DATA__TtC12Transparency28AETransparencyRequestContext
+ __METACLASS_DATA__TtC12Transparency8AETEvent
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSXPCProxyCreating
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSXPCProxyCreating
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSXPCProxyCreating
+ __OBJC_LABEL_PROTOCOL_$_NSXPCProxyCreating
+ __OBJC_PROTOCOL_$_NSXPCProxyCreating
+ __PROPERTIES__TtC12Transparency11AETEventKey
+ __PROPERTIES__TtC12Transparency19AETTransparentEvent
+ __PROPERTIES__TtC12Transparency21AETVerifyProofRequest
+ __PROPERTIES__TtC12Transparency22AETVerifyProofResponse
+ __PROPERTIES__TtC12Transparency26AETEventVerificationResult
+ __PROPERTIES__TtC12Transparency28AETransparencyRequestContext
+ __PROPERTIES__TtC12Transparency8AETEvent
+ __PROTOCOL_INSTANCE_METHODS__TtP12Transparency25AETransparencyXPCProtocol_
+ __PROTOCOL_METHOD_TYPES__TtP12Transparency25AETransparencyXPCProtocol_
+ __PROTOCOL__TtP12Transparency25AETransparencyXPCProtocol_
+ ___swift_allocate_value_buffer
+ ___swift_closure_destructor
+ ___swift_closure_destructor.108Tm
+ ___swift_closure_destructor.153Tm
+ ___swift_closure_destructor.20Tm
+ ___swift_closure_destructor.87Tm
+ ___swift_destroy_boxed_opaque_existential_0Tm
+ ___swift_project_boxed_opaque_existential_1Tm
+ ___swift_project_value_buffer
+ __swift_implicitisolationactor_to_executor_cast
+ __swift_stdlib_bridgeErrorToNSError
+ _associated conformance 12Transparency0A12AETErrorCodeOSHAASQ
+ _associated conformance 12Transparency11AETEventKeyC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLOSHAASQ
+ _associated conformance 12Transparency11AETEventKeyC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLOs0dC0AAs23CustomStringConvertible
+ _associated conformance 12Transparency11AETEventKeyC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLOs0dC0AAs28CustomDebugStringConvertible
+ _associated conformance 12Transparency12AETEventTypeOSHAASQ
+ _associated conformance 12Transparency12AETEventTypeOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 12Transparency16AETHashAlgorithmOSHAASQ
+ _associated conformance 12Transparency16AETHashAlgorithmOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 12Transparency19AETTransparentEventC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLOSHAASQ
+ _associated conformance 12Transparency19AETTransparentEventC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLOs0D3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency19AETTransparentEventC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLOs0D3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12Transparency19AETransparencyErrorO10Foundation021_ObjectiveCBridgeableC0AAs0C0
+ _associated conformance 12Transparency19AETransparencyErrorO10Foundation13CustomNSErrorAAs0C0
+ _associated conformance 12Transparency19AETransparencyErrorO10Foundation15_BridgedNSErrorAA8RawValueSY_s17FixedWidthInteger
+ _associated conformance 12Transparency19AETransparencyErrorO10Foundation15_BridgedNSErrorAASH
+ _associated conformance 12Transparency19AETransparencyErrorO10Foundation15_BridgedNSErrorAASY
+ _associated conformance 12Transparency19AETransparencyErrorO10Foundation15_BridgedNSErrorAaD021_ObjectiveCBridgeableC0
+ _associated conformance 12Transparency19AETransparencyErrorOSHAASQ
+ _associated conformance 12Transparency21AETVerifyProofRequestC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLOSHAASQ
+ _associated conformance 12Transparency21AETVerifyProofRequestC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency21AETVerifyProofRequestC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12Transparency22AETVerifyProofResponseC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLOSHAASQ
+ _associated conformance 12Transparency22AETVerifyProofResponseC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency22AETVerifyProofResponseC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12Transparency25AETEventVerificationStateOSHAASQ
+ _associated conformance 12Transparency25AETEventVerificationStateOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 12Transparency26AETEventVerificationResultC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLOSHAASQ
+ _associated conformance 12Transparency26AETEventVerificationResultC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency26AETEventVerificationResultC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12Transparency28AETransparencyRequestContextC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLOSHAASQ
+ _associated conformance 12Transparency28AETransparencyRequestContextC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency28AETransparencyRequestContextC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12Transparency8AETEventC04CoreA026AETVerifiableEventProtocolAA17MetadataHashBytesAdEP_AD18CTBytesConvertible
+ _associated conformance 12Transparency8AETEventC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLOSHAASQ
+ _associated conformance 12Transparency8AETEventC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLOs0C3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency8AETEventC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLOs0C3KeyAAs28CustomDebugStringConvertible
+ _block_copy_helper
+ _block_descriptor
+ _block_destroy_helper
+ _flat unique 12Transparency25AETransparencyXPCProtocol_p
+ _flat unique So18NSXPCProxyCreating_p
+ _objc_autorelease
+ _swift_arrayInitWithCopy
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_continuation_throwingResume
+ _swift_continuation_throwingResumeWithError
+ _swift_deallocObject
+ _swift_dynamicCast
+ _swift_once
+ _swift_release_x19
+ _swift_release_x25
+ _swift_release_x8
+ _swift_retain_x2
+ _swift_retain_x21
+ _swift_retain_x22
+ _swift_retain_x23
+ _swift_retain_x26
+ _swift_task_create
+ _swift_willThrowTypedImpl
+ _symbolic $s12Transparency0A8AETErrorP
+ _symbolic $s12Transparency13AETXPCCodableP
+ _symbolic $s12Transparency25AETransparencyXPCProtocolP
+ _symbolic $s16CoreTransparency26AETVerifiableEventProtocolP
+ _symbolic IeAgH_
+ _symbolic IeghH_
+ _symbolic Say_____G 12Transparency12AETEventTypeO
+ _symbolic Say_____G 12Transparency16AETHashAlgorithmO
+ _symbolic Say_____G 12Transparency19AETTransparentEventC
+ _symbolic Say_____G 12Transparency25AETEventVerificationStateO
+ _symbolic Say_____G 12Transparency26AETEventVerificationResultC
+ _symbolic Say_____G 12Transparency8AETEventC
+ _symbolic Say_____GSg 12Transparency19AETTransparentEventC
+ _symbolic Say_____GSg 12Transparency26AETEventVerificationResultC
+ _symbolic Say_____GSg 12Transparency8AETEventC
+ _symbolic ScA_pSg
+ _symbolic ScCy___________pG 10Foundation4DataV s5ErrorP
+ _symbolic ScPSg
+ _symbolic Sccy___________pG 10Foundation4DataV s5ErrorP
+ _symbolic So6NSDataCSgSo7NSErrorCSgIeyByy_
+ _symbolic So6NSDataCm
+ _symbolic So8NSObjectCSg
+ _symbolic So8NSStringC
+ _symbolic So8NSStringCSgSo7NSErrorCSgIeyByy_
+ _symbolic _____ 10Foundation4DataV
+ _symbolic _____ 10ObjectiveC8ObjCBoolV
+ _symbolic _____ 12Transparency0A12AETErrorCodeO
+ _symbolic _____ 12Transparency11AETEventKeyC
+ _symbolic _____ 12Transparency11AETEventKeyC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLO
+ _symbolic _____ 12Transparency12AETEventTypeO
+ _symbolic _____ 12Transparency14AETransparencyC
+ _symbolic _____ 12Transparency16AETHashAlgorithmO
+ _symbolic _____ 12Transparency19AETTransparentEventC
+ _symbolic _____ 12Transparency19AETTransparentEventC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLO
+ _symbolic _____ 12Transparency19AETransparencyErrorO
+ _symbolic _____ 12Transparency21AETVerifyProofRequestC
+ _symbolic _____ 12Transparency21AETVerifyProofRequestC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLO
+ _symbolic _____ 12Transparency22AETVerifyProofResponseC
+ _symbolic _____ 12Transparency22AETVerifyProofResponseC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLO
+ _symbolic _____ 12Transparency25AETEventVerificationStateO
+ _symbolic _____ 12Transparency26AETEventVerificationResultC
+ _symbolic _____ 12Transparency26AETEventVerificationResultC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLO
+ _symbolic _____ 12Transparency26AETransparencyXPCInterfaceC
+ _symbolic _____ 12Transparency28AETransparencyRequestContextC
+ _symbolic _____ 12Transparency28AETransparencyRequestContextC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLO
+ _symbolic _____ 12Transparency8AETEventC
+ _symbolic _____ 12Transparency8AETEventC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLO
+ _symbolic _____ s5UInt8V
+ _symbolic _____ s6UInt64V
+ _symbolic _____Sg 12Transparency04CoreA15ApplicationShimO
+ _symbolic _____Sg 12Transparency04CoreA21ServerEnvironmentShimO
+ _symbolic _____Sg 12Transparency11AETEventKeyC
+ _symbolic _____Sg 12Transparency25AETEventVerificationStateO
+ _symbolic _____Sg 12Transparency8AETEventC
+ _symbolic _____Sg 16CoreTransparency15AetTlsEventTypeV
+ _symbolic _____SgSo7NSErrorCSgIeyByy_ 12Transparency22AETVerifyProofResponseC
+ _symbolic _____XDXMT 12Transparency14AETransparencyC
+ _symbolic ______p 10Foundation15ContiguousBytesP
+ _symbolic ______p 12Transparency25AETransparencyXPCProtocolP
+ _symbolic ______p So18NSXPCProxyCreatingP
+ _symbolic ______pSgyYbc So18NSXPCProxyCreatingP
+ _symbolic ______p___________pIegHgrzo_ 12Transparency25AETransparencyXPCProtocolP 10Foundation4DataV s5ErrorP
+ _symbolic ______pm 12Transparency25AETransparencyXPCProtocolP
+ _symbolic _____ySSG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency11AETEventKeyC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency19AETTransparentEventC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency21AETVerifyProofRequestC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency22AETVerifyProofResponseC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency26AETEventVerificationResultC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency28AETransparencyRequestContextC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency8AETEventC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency11AETEventKeyC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency19AETTransparentEventC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency21AETVerifyProofRequestC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency22AETVerifyProofResponseC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency26AETEventVerificationResultC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency28AETransparencyRequestContextC10CodingKeys33_B2E81D5B78BC7581F9ED15A295A4D291LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency8AETEventC10CodingKeys33_9EC6913878C59184B1F4C9B49A1B3CEDLLO
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
+ _symbolic _____yypG s23_ContiguousArrayStorageC
+ _symbolic x
+ _symbolic ytIeAgHr_
CStrings:
+ " treeResetInProgress"
+ ", allLoggedEvents="
+ ", proofServerHint="
+ ", proofTimestampMs="
+ ", returnAllLoggedEvents="
+ ", verifiableEventCount="
+ ", verifiableEvents="
+ ", verificationState="
+ "AETEventKey(eventId="
+ "AETEventVerificationResult(verifiableEvent="
+ "AETEventVerificationState(name="
+ "AETTransparentEvent(event="
+ "AETVerifyProofRequest(dsid="
+ "AETVerifyProofResponse(eventVerificationResults="
+ "AETransparencyRequestContext(application="
+ "Error casting proxy to AETransparencyXPCProtocol.\nExpected: %s\nActual: %s"
+ "Error creating proxy: %@"
+ "ErrorStillPopulating"
+ "ErrorStillPopulatingIgnored"
+ "Transparency.AETEventVerificationResult"
+ "Transparency.AETTransparentEvent"
+ "Transparency.AETVerifyProofResponse"
+ "Transparency.AETransparency"
+ "Transparency.AETransparencyError"
+ "Transparency.AETransparencyRequestContext"
+ "Unknown AETHashAlgorithm value %ld, falling back to SHA256"
+ "_allLoggedEvents"
+ "_eventVerificationResults"
+ "_proofTimestampMs"
+ "_returnAllLoggedEvents"
+ "_verifiableEvent"
+ "_verifiableEvents"
+ "_verificationState"
+ "clearCaches with context: %s"
+ "com.apple.Transparency.AETransparencyError"
+ "com.apple.transparencyd.aet"
+ "connectionProvider returned nil (expected only on simulator / no-XPC environments)"
+ "eventMetadataMismatch"
+ "eventNotTransparent"
+ "forceTreeResetPopulating"
+ "garbageCollect with context: %s"
+ "getConfigBag with context: %s"
+ "getPublicKeyBag with context: %s"
+ "makeProofRequestPayload with context: %s dsid: %llu"
+ "treeResetInProgress"
+ "verifyProof with context=%s"
+ "withRemoteObjectProxyImpl(_:)"
```
