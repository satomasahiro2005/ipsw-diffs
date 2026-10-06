## Transparency

> `/System/Library/PrivateFrameworks/Transparency.framework/Transparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6fe24` | `0x786a4` | **`+0x8880`** |
| `__DATA.__bss` | `0x6620` | `0x6e90` | **`+0x870`** |
| `__TEXT.__eh_frame` | `0x26a8` | `0x2f00` | **`+0x858`** |
| `__TEXT.__const` | `0x3d44` | `0x4580` | **`+0x83c`** |
| `__AUTH_CONST.__const` | `0x39e8` | `0x3d38` | **`+0x350`** |
| `__TEXT.__unwind_info` | `0x27f0` | `0x2a40` | **`+0x250`** |
| `__TEXT.__swift5_typeref` | `0xd2c` | `0xf32` | **`+0x206`** |
| `__TEXT.__constg_swiftt` | `0x954` | `0xa5c` | **`+0x108`** |
| `__TEXT.__swift5_fieldmd` | `0xab8` | `0xbb8` | **`+0x100`** |
| `__DATA.__data` | `0xf70` | `0x1050` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x2f41` | `0x2fec` | **`+0xab`** |
| `__AUTH.__data` | `0x420` | `0x4b0` | **`+0x90`** |
| `__TEXT.__swift5_acfuncs` | `0x78` | `0xf0` | **`+0x78`** |
| `__TEXT.__swift_as_cont` | `0x128` | `0x194` | **`+0x6c`** |
| `__TEXT.__oslogstring` | `0x1e12` | `0x1e5b` | **`+0x49`** |
| `__TEXT.__swift5_proto` | `0x34c` | `0x38c` | **`+0x40`** |
| `__TEXT.__swift_as_entry` | `0xa8` | `0xe4` | **`+0x3c`** |
| `__TEXT.__swift5_reflstr` | `0x88f` | `0x8ca` | **`+0x3b`** |
| `__TEXT.__swift5_assocty` | `0x230` | `0x260` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x9c` | `0xcc` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x4a50` | `0x4a78` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0xb4` | `0xdc` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0xc58` | `0xc78` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x618` | `0x638` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2010` | `0x2028` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0xd0` | `0xe8` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x8018` | `0x8020` | **`+0x8`** |

### Other Changes

```diff

-1766.0.27.0.0
+1766.0.39.0.2

-  Functions: 3550
-  Symbols:   3504
-  CStrings:  761
+  Functions: 3694
+  Symbols:   3542
+  CStrings:  765
Symbols:
+ +[TransparencySettings setSharedSettings:]
+ -[KTVerifierResult supportConditionalEnforcementWithSettings:]
+ -[TransparencySettings idsKeyTransparencyEnforcementShouldApplyForService:]
+ ___swift_memcpy24_8
+ _associated conformance 12Transparency20CKVPeerOverrideEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOSHAASQ
+ _associated conformance 12Transparency20CKVPeerOverrideEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency20CKVPeerOverrideEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12Transparency21CKVPeerOverrideDeviceV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOSHAASQ
+ _associated conformance 12Transparency21CKVPeerOverrideDeviceV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency21CKVPeerOverrideDeviceV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance So10KTUIStatusVs12CaseIterable12Transparency8AllCasessACP_Sl
+ _associated conformance So8KTResultVs12CaseIterable12Transparency8AllCasessACP_Sl
+ _sSharedOverride
+ _swift_getForeignTypeMetadata
+ _swift_release_x27
+ _symbolic S2SSiSgAASay_____Gx______p_____Rz_____RzlIetMHgTgTyTyTgTgzo_ 12Transparency21CKVPeerOverrideDeviceV s5ErrorP 11Distributed01_F9ActorStubP AA21CKVDiagnosticsServiceP
+ _symbolic S2SSiSgAASay_____Gx______p_____RzlIetWHgTgTyTyTgTgzo_ 12Transparency21CKVPeerOverrideDeviceV s5ErrorP AA21CKVDiagnosticsServiceP
+ _symbolic S2Sx______p_____Rz_____RzlIetMHgTgTgzo_ s5ErrorP 11Distributed01_B9ActorStubP 12Transparency21CKVDiagnosticsServiceP
+ _symbolic S2Sx______p_____RzlIetWHgTgTgzo_ s5ErrorP 12Transparency21CKVDiagnosticsServiceP
+ _symbolic Say_____G 12Transparency20CKVPeerOverrideEntryV
+ _symbolic Say_____G 12Transparency21CKVPeerOverrideDeviceV
+ _symbolic Say_____G So10KTUIStatusV
+ _symbolic Say_____G So8KTResultV
+ _symbolic SiSg
+ _symbolic _____ 12Transparency20CKVPeerOverrideEntryV
+ _symbolic _____ 12Transparency20CKVPeerOverrideEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____ 12Transparency21CKVPeerOverrideDeviceV
+ _symbolic _____ 12Transparency21CKVPeerOverrideDeviceV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____ So10KTUIStatusV
+ _symbolic _____ So8KTResultV
+ _symbolic _____ySay_____GG 11Distributed18RemoteCallArgumentV 12Transparency21CKVPeerOverrideDeviceV
+ _symbolic _____ySiSgG 11Distributed18RemoteCallArgumentV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency20CKVPeerOverrideEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency21CKVPeerOverrideDeviceV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency20CKVPeerOverrideEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency21CKVPeerOverrideDeviceV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic xSay_____G______p_____Rz_____RzlIetMHgozo_ 12Transparency20CKVPeerOverrideEntryV s5ErrorP 11Distributed01_F9ActorStubP AA21CKVDiagnosticsServiceP
+ _symbolic xSay_____G______p_____RzlIetWHgozo_ 12Transparency20CKVPeerOverrideEntryV s5ErrorP AA21CKVDiagnosticsServiceP
+ _type_layout_string 12Transparency21CKVPeerOverrideDeviceV
- -[KTVerifierResult supportConditionalEnforcement]
CStrings:
+ "injectFailureClear(application:uri:)"
+ "injectFailureList()"
+ "injectFailureSet(application:uri:ktResult:ktUIStatus:deviceFailures:)"
+ "verifyProof: rejecting empty proof, skipping XPC dispatch"
```
