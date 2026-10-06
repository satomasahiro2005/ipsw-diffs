## CoreTransparency

> `/System/Library/PrivateFrameworks/CoreTransparency.framework/CoreTransparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27bfc` | `0x3f128` | **`+0x1752c`** |
| `__TEXT.__const` | `0x4614` | `0x70e4` | **`+0x2ad0`** |
| `__DATA.__bss` | `0x5180` | `0x7380` | **`+0x2200`** |
| `__TEXT.__swift5_reflstr` | `0x11cd` | `0x202d` | **`+0xe60`** |
| `__AUTH_CONST.__const` | `0x2940` | `0x3638` | **`+0xcf8`** |
| `__TEXT.__eh_frame` | `0x14c8` | `0x1df0` | **`+0x928`** |
| `__TEXT.__swift5_fieldmd` | `0x135c` | `0x1b64` | **`+0x808`** |
| `__TEXT.__unwind_info` | `0xf38` | `0x16b0` | **`+0x778`** |
| `__TEXT.__swift5_typeref` | `0x1278` | `0x17ca` | **`+0x552`** |
| `__TEXT.__constg_swiftt` | `0x1628` | `0x1ae8` | **`+0x4c0`** |
| `__DATA.__data` | `0x6c0` | `0x9f0` | **`+0x330`** |
| `__TEXT.__cstring` | `0x71e` | `0x9be` | **`+0x2a0`** |
| `__AUTH_CONST.__auth_got` | `0x670` | `0x880` | **`+0x210`** |
| `__TEXT.__swift5_proto` | `0x2ec` | `0x414` | **`+0x128`** |
| `__TEXT.__swift5_assocty` | `0x488` | `0x568` | **`+0xe0`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0xc8` | **`+0x78`** |
| `__AUTH.__data` | `0x920` | `0x990` | **`+0x70`** |
| `__TEXT.__swift5_types` | `0x104` | `0x15c` | **`+0x58`** |
| `__TEXT.__swift5_mpenum` | `0x20` | `0x60` | **`+0x40`** |
| `__TEXT.__swift5_protos` | `0x88` | `0x9c` | **`+0x14`** |

### Other Changes

```diff

-1751.0.0.502.1
+1766.0.13.0.0
+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

+  - /System/Library/Frameworks/Security.framework/Security

-  Functions: 1906
-  Symbols:   542
-  CStrings:  57
+  Functions: 2754
+  Symbols:   692
+  CStrings:  76
Symbols:
+ _CFDataCreateWithBytesNoCopy
+ _NSUnderlyingErrorKey
+ _OBJC_CLASS_$_NSError
+ _SecCertificateCreateWithData
+ _SecKeyVerifySignature
+ _SecPolicyCreateAppleIDSService
+ _SecTrustCopyKey
+ _SecTrustCreateWithCertificates
+ _SecTrustEvaluateWithError
+ _SecTrustSetVerifyDate
+ ___swift_memcpy136_8
+ ___swift_memcpy26_8
+ ___swift_memcpy32_8
+ ___swift_memcpy41_8
+ ___swift_memcpy96_8
+ ___swift_mutable_project_boxed_opaque_existential_1
+ _associated conformance 16CoreTransparency11AetTlsEventVSHAASQ
+ _associated conformance 16CoreTransparency11AetTlsEventVSLAASQ
+ _associated conformance 16CoreTransparency12AETErrorCodeOSHAASQ
+ _associated conformance 16CoreTransparency13AetTlsMapLeafVSHAASQ
+ _associated conformance 16CoreTransparency14AetTlsEventKeyVSHAASQ
+ _associated conformance 16CoreTransparency15AetTlsEventTypeVSHAASQ
+ _associated conformance 16CoreTransparency15AetTlsEventTypeVs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 16CoreTransparency15AetTlsExtensionOSHAASQ
+ _associated conformance 16CoreTransparency15AetTlsExtensionOSLAASQ
+ _associated conformance 16CoreTransparency16AETVerifierErrorO10Foundation13CustomNSErrorAAs0D0
+ _associated conformance 16CoreTransparency17SignedObjectErrorO10Foundation13CustomNSErrorAAs0E0
+ _associated conformance 16CoreTransparency19AetTlsExtensionTypeVSHAASQ
+ _associated conformance 16CoreTransparency19AetTlsExtensionTypeVSLAASQ
+ _associated conformance 16CoreTransparency20AETEscapableVerifierVAA19AETVerifierProtocolAA26AETProofVerificationResultAaDP_AA0ghiF0
+ _associated conformance 16CoreTransparency21ConsistencyProofErrorO10Foundation13CustomNSErrorAAs0E0
+ _associated conformance 16CoreTransparency23CTVerificationErrorCodeOSHAASQ
+ _associated conformance 16CoreTransparency23MerkleLogInclusionErrorO10Foundation13CustomNSErrorAAs0F0
+ _associated conformance 16CoreTransparency23MerkleLogInclusionErrorOSHAASQ
+ _associated conformance 16CoreTransparency24LogHeadVerificationErrorO10Foundation13CustomNSErrorAAs0F0
+ _associated conformance 16CoreTransparency24MapHeadVerificationErrorO10Foundation13CustomNSErrorAAs0F0
+ _associated conformance 16CoreTransparency25LogEntryVerificationErrorO10Foundation13CustomNSErrorAAs0F0
+ _associated conformance 16CoreTransparency25MapProofVerificationErrorO10Foundation13CustomNSErrorAAs0F0
+ _associated conformance 16CoreTransparency26AetTlsSerializationVersionVSHAASQ
+ _associated conformance 16CoreTransparency26AetTlsSerializationVersionVs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 16CoreTransparency29SignedObjectVerificationErrorO10Foundation13CustomNSErrorAAs0F0
+ _associated conformance 16CoreTransparency34PatInclusionProofVerificationErrorO10Foundation13CustomNSErrorAAs0G0
+ _associated conformance 16CoreTransparency35AETEscapableProofVerificationResultVAA08AETProofeF8ProtocolAA12SignedObjectAaDP_AA0ijH0
+ _associated conformance 16CoreTransparency35AETEscapableProofVerificationResultVAA08AETProofeF8ProtocolAA7LogHeadAaDP_AA0ijH0
+ _get_enum_tag_for_layout_string 16CoreTransparency16AETVerifierErrorO
+ _get_enum_tag_for_layout_string 16CoreTransparency16CTConfigBagErrorO
+ _get_enum_tag_for_layout_string 16CoreTransparency17PublicKeyBagErrorO
+ _get_enum_tag_for_layout_string 16CoreTransparency25LogEntryVerificationErrorO
+ _get_enum_tag_for_layout_string 16CoreTransparency25MapProofVerificationErrorO
+ _get_enum_tag_for_layout_string 16CoreTransparency27AETEventVerificationOutcomeO
+ _get_enum_tag_for_layout_string 16CoreTransparency34PatInclusionProofVerificationErrorO
+ _kCFAllocatorDefault
+ _kCFAllocatorNull
+ _kSecKeyAlgorithmRSASignatureMessagePKCS1v15SHA256
+ _objc_opt_self
+ _objc_release_x19
+ _objc_release_x20
+ _objc_release_x22
+ _objc_release_x23
+ _objc_release_x24
+ _objc_release_x27
+ _objc_release_x8
+ _objc_retain_x26
+ _objc_retain_x8
+ _swift_getForeignTypeMetadata
+ _swift_getObjCClassMetadata
+ _swift_initStackObject
+ _swift_makeBoxUnique
+ _swift_release_x19
+ _swift_release_x26
+ _swift_release_x8
+ _symbolic $s16CoreTransparency0aB8AETErrorP
+ _symbolic $s16CoreTransparency19AETVerifierProtocolP
+ _symbolic $s16CoreTransparency19CTVerificationErrorP
+ _symbolic $s16CoreTransparency26AETVerifiableEventProtocolP
+ _symbolic $s16CoreTransparency34AETProofVerificationResultProtocolP
+ _symbolic 12SignedObject_____Qz 16CoreTransparency34AETProofVerificationResultProtocolP
+ _symbolic 17MetadataHashBytes_____Qz 16CoreTransparency26AETVerifiableEventProtocolP
+ _symbolic 26AETProofVerificationResult_____Qz 16CoreTransparency19AETVerifierProtocolP
+ _symbolic 7LogHead_____Qz 16CoreTransparency34AETProofVerificationResultProtocolP
+ _symbolic SDy_____Say_____GG 16CoreTransparency9CTMapTypeO AA11AetTlsEventV
+ _symbolic SDy__________G 16CoreTransparency14AetTlsEventKeyV AA0cdE0V
+ _symbolic SS10keySetName_Si5indexSS26underlyingErrorDescriptiont
+ _symbolic SS10keySetName_Si5index_____4codet s5Int32V
+ _symbolic SS10keySetName_t
+ _symbolic SS7eventId______11insertionMs_____0A4Typet s6UInt64V 16CoreTransparency15AetTlsEventTypeV
+ _symbolic Say_____G 16CoreTransparency11AetTlsEventV
+ _symbolic Say_____G 16CoreTransparency15AetTlsEventTypeV
+ _symbolic Say_____G 16CoreTransparency15AetTlsExtensionO
+ _symbolic Say_____G 16CoreTransparency26AetTlsSerializationVersionV
+ _symbolic Say_____G 16CoreTransparency27AETEventVerificationOutcomeO
+ _symbolic Say_____G17proofMetadataHash_t s5UInt8V
+ _symbolic Say_____y__________GG 16CoreTransparency11VerifiedSLHV AA23CTEscapableSignedObjectV AA10CTELogHeadV
+ _symbolic Say_____y__________GG 16CoreTransparency11VerifiedSMHV AA23CTEscapableSignedObjectV AA10CTEMapHeadV
+ _symbolic _____ 16CoreTransparency11AetTlsEventV
+ _symbolic _____ 16CoreTransparency12AETErrorCodeO
+ _symbolic _____ 16CoreTransparency13AetTlsMapLeafV
+ _symbolic _____ 16CoreTransparency14AetTlsEventKeyV
+ _symbolic _____ 16CoreTransparency15AetTlsEventTypeV
+ _symbolic _____ 16CoreTransparency15AetTlsExtensionO
+ _symbolic _____ 16CoreTransparency16AETVerifierErrorO
+ _symbolic _____ 16CoreTransparency16VerifiedLogEntryV
+ _symbolic _____ 16CoreTransparency16VerifiedMapProofV
+ _symbolic _____ 16CoreTransparency19AetTlsExtensionTypeV
+ _symbolic _____ 16CoreTransparency20AETEscapableVerifierV
+ _symbolic _____ 16CoreTransparency23CTVerificationErrorCodeO
+ _symbolic _____ 16CoreTransparency23MerkleLogInclusionErrorO
+ _symbolic _____ 16CoreTransparency25LogEntryVerificationErrorO
+ _symbolic _____ 16CoreTransparency25MapProofVerificationErrorO
+ _symbolic _____ 16CoreTransparency25VerifiedPatInclusionProofV
+ _symbolic _____ 16CoreTransparency26AetTlsSerializationVersionV
+ _symbolic _____ 16CoreTransparency27AETEventVerificationOutcomeO
+ _symbolic _____ 16CoreTransparency34PatInclusionProofVerificationErrorO
+ _symbolic _____ 16CoreTransparency35AETEscapableProofVerificationResultV
+ _symbolic _____Sg 16CoreTransparency11AetTlsEventV
+ _symbolic _____Sg_ABt 16CoreTransparency11AetTlsEventV
+ _symbolic ______AAt 16CoreTransparency16AETVerifierErrorO
+ _symbolic ___________t 16CoreTransparency19AetTlsExtensionTypeV AA0B10ByteBufferV
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _symbolic _____ySnySiGG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 16CoreTransparency11AetTlsEventV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 16CoreTransparency15AetTlsExtensionO
+ _symbolic _____y_____Say_____GG s17_NativeDictionaryV 16CoreTransparency9CTMapTypeO AC11AetTlsEventV
+ _symbolic _____y__________G 16CoreTransparency11VerifiedSLHV AA23CTEscapableSignedObjectV AA10CTELogHeadV
+ _symbolic _____y__________G 16CoreTransparency11VerifiedSMHV AA23CTEscapableSignedObjectV AA10CTEMapHeadV
+ _symbolic _____y__________G s17_NativeDictionaryV 16CoreTransparency14AetTlsEventKeyV AC0efG0V
+ _symbolic _____y__________GSg 16CoreTransparency11VerifiedSLHV AA23CTEscapableSignedObjectV AA10CTELogHeadV
+ _symbolic _____y_______________Say_____GG 16CoreTransparency16VerifiedMapProofV AA23CTEscapableSignedObjectV AA10CTELogHeadV AA06CTEMapJ0V s5UInt8V
+ _symbolic _____y_____y__________GG s23_ContiguousArrayStorageC 16CoreTransparency11VerifiedSLHV AC23CTEscapableSignedObjectV AC10CTELogHeadV
+ _symbolic _____y_____y__________GG s23_ContiguousArrayStorageC 16CoreTransparency11VerifiedSMHV AC23CTEscapableSignedObjectV AC10CTEMapHeadV
+ _symbolic _____yxq0_G 16CoreTransparency11VerifiedSMHV
+ _symbolic _____yxq_G 16CoreTransparency11VerifiedSLHV
+ _symbolic _____yxq_GSg 16CoreTransparency11VerifiedSLHV
+ _symbolic _____yxq_q0_G 16CoreTransparency16VerifiedLogEntryV
+ _symbolic _____yxq_q1_G 16CoreTransparency16VerifiedLogEntryV
+ _symbolic _____yxq_q1_GSg 16CoreTransparency16VerifiedLogEntryV
+ _symbolic q0_
+ _symbolic q1_
+ _type_layout_string 16CoreTransparency11AetTlsEventV
+ _type_layout_string 16CoreTransparency13AetTlsMapLeafV
+ _type_layout_string 16CoreTransparency14AetTlsEventKeyV
+ _type_layout_string 16CoreTransparency15AetTlsExtensionO
+ _type_layout_string 16CoreTransparency16AETVerifierErrorO
+ _type_layout_string 16CoreTransparency17PublicKeyBagErrorO
+ _type_layout_string 16CoreTransparency19AetTlsExtensionTypeV
+ _type_layout_string 16CoreTransparency25LogEntryVerificationErrorO
+ _type_layout_string 16CoreTransparency25MapProofVerificationErrorO
+ _type_layout_string 16CoreTransparency27AETEventVerificationOutcomeO
+ _type_layout_string 16CoreTransparency34PatInclusionProofVerificationErrorO
+ _type_layout_string 16CoreTransparency35AETEscapableProofVerificationResultV
CStrings:
+ "AetTlsEventType.DT_EVENT("
+ "AetTlsEventType.P_EVENT("
+ "AetTlsEventType.S_EVENT("
+ "AetTlsEventType.TestEvent("
+ "AetTlsEventType.TestLLEvent("
+ "AetTlsEventType.UNKNOWN("
+ "AetTlsEventType.UNSET("
+ "AetTlsExtensionType(rawValue: "
+ "Failed to parse log head from map proof: "
+ "SecKeyVerifySignature returned false"
+ "SecTrustCreateWithCertificates failed: "
+ "SecTrustEvaluateWithError failed"
+ "SerializationVerions(rawValue: "
+ "aet"
+ "com.apple.CoreTransparency.AET"
+ "com.apple.CoreTransparency.Verification"
+ "failed to create SecCertificate from leaf"
+ "failed to wrap inputs as CFData"
+ "underlying error: "
```
