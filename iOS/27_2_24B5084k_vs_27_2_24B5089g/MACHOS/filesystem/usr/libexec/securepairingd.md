## securepairingd

> `/usr/libexec/securepairingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7db5c` | `0x4c52c` | **`-0x31630`** |
| `__DATA.__bss` | `0x19720` | `0xe8a0` | **`-0xae80`** |
| `__TEXT.__const` | `0xe158` | `0x7ea8` | **`-0x62b0`** |
| `__DATA_CONST.__const` | `0x7b50` | `0x46d0` | **`-0x3480`** |
| `__TEXT.__eh_frame` | `0x4890` | `0x2d38` | **`-0x1b58`** |
| `__DATA.__data` | `0x46c2` | `0x3242` | **`-0x1480`** |
| `__TEXT.__swift5_fieldmd` | `0x273c` | `0x1828` | **`-0xf14`** |
| `__TEXT.__oslogstring` | `0x21ad` | `0x129d` | **`-0xf10`** |
| `__TEXT.__swift5_typeref` | `0x26e9` | `0x17f3` | **`-0xef6`** |
| `__TEXT.__unwind_info` | `0x2298` | `0x1640` | **`-0xc58`** |
| `__TEXT.__constg_swiftt` | `0x2bdc` | `0x1fd0` | **`-0xc0c`** |
| `__TEXT.__cstring` | `0x1970` | `0x1060` | **`-0x910`** |
| `__TEXT.__swift5_proto` | `0xdac` | `0x7c8` | **`-0x5e4`** |
| `__TEXT.__swift5_capture` | `0x950` | `0x4a4` | **`-0x4ac`** |
| `__TEXT.__swift5_reflstr` | `0xcf2` | `0x874` | **`-0x47e`** |
| `__TEXT.__swift5_assocty` | `0x530` | `0x2d8` | **`-0x258`** |
| `__DATA.__objc_const` | `0x1ba8` | `0x1978` | **`-0x230`** |
| `__TEXT.__objc_methname` | `0x3f5` | `0x1ef` | **`-0x206`** |
| `__TEXT.__swift5_types` | `0x3d4` | `0x27c` | **`-0x158`** |
| `__TEXT.__objc_methlist` | `0x104` | `—` | **`-0x104`** |
| `__DATA_CONST.__auth_ptr` | `0x4c8` | `0x3e0` | **`-0xe8`** |
| `__TEXT.__objc_methtype` | `0xde` | `0x2e` | **`-0xb0`** |
| `__DATA.__objc_selrefs` | `0xd0` | `0x30` | **`-0xa0`** |
| `__TEXT.__swift_as_cont` | `0x130` | `0x94` | **`-0x9c`** |
| `__TEXT.__auth_stubs` | `0x1800` | `0x1770` | **`-0x90`** |
| `__DATA.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__TEXT.__objc_classname` | `0x707` | `0x6b7` | **`-0x50`** |
| `__DATA_CONST.__auth_got` | `0xc08` | `0xbc0` | **`-0x48`** |
| `__TEXT.__swift_as_entry` | `0x84` | `0x4c` | **`-0x38`** |
| `__DATA.__common` | `0x88` | `0x68` | **`-0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `—` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x2f8` | `0x2e0` | **`-0x18`** |
| `__TEXT.__swift5_mpenum` | `0x18` | `0x30` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x40` | `0x28` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x28` | **`-0x14`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `—` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x118` | `0x110` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-67.3.0.0.0
+67.5.0.0.0

-  Functions: 2937
-  Symbols:   589
-  CStrings:  422
+  Functions: 1857
+  Symbols:   577
+  CStrings:  265
Symbols:
- _$s13SecurePairing0aB5ErrorV4CodeO21audioListeningFailureyA2EmFWC
- _$s19SecureAudioPasscode0A20PairingInputRecorderC4stopSbyFTj
- _$s19SecureAudioPasscode0A20PairingInputRecorderC5startSbyFTj
- _$s19SecureAudioPasscode0A20PairingInputRecorderCACyKcfc
- _$s19SecureAudioPasscode0A20PairingInputRecorderCMa
- _$s19SecureAudioPasscode0A20PairingInputRecorderCMn
- _$s9Tightbeam0A7EncoderV6encodeyys6UInt32VF
- _$sScTss5NeverORszABRs_rlE11isCancelledSbvgZ
- _$ss6UInt32VSEsWP
- _$ss6UInt32VSesWP
- _swift_release_x9
- _swift_updateClassMetadata2
CStrings:
+ "Cleaning up session: %llu"
- "#16@0:8"
- ".domainKeysLeadExchange("
- ".domainKeysPeerExchange("
- ".sigmaPeerPairing("
- "@\"NSString\"16@0:8"
- "@16@0:8"
- "@24@0:8:16"
- "@32@0:8:16@24"
- "@40@0:8:16@24@32"
- "Attempted SecurePairingInputRecorder.start() with result: %{bool}d"
- "Attempted SecurePairingInputRecorder.stop() with result: %{bool}d"
- "B16@0:8"
- "B24@0:8#16"
- "B24@0:8:16"
- "B24@0:8@\"Protocol\"16"
- "B24@0:8@16"
- "Cleaning up session: %s"
- "Conclave initialization with resource com.apple.securepairingd.sigmapeerservice failed: %@. That is either build configuration error or given device does not support exclaves. Clients should check SecurePairing.supported property before attempting to call any framework SPI."
- "Creating ACM context from user provided externalized form"
- "Creating service: com.apple.securepairingd.sigmapeerservice"
- "Ignoring suspicious attempt to stop listening from ownerId=%llu, current=%s"
- "Invalid key value while decoding result type for cancelDomainPairing"
- "Invalid key value while decoding result type for completeAttestation"
- "Invalid key value while decoding result type for getAttestation"
- "Invalid key value while decoding result type for handleDomainKeys"
- "Invalid key value while decoding result type for handleDomainKeysAck"
- "Invalid key value while decoding result type for handleMissingKeyTypesAck"
- "Invalid key value while decoding result type for handleMissingKeyTypesCont"
- "Invalid key value while decoding result type for handleStartKeyTransfer"
- "Invalid key value while decoding result type for startDomainPairing"
- "Invalid key value while decoding result type for startListening"
- "Invalid key value while decoding result type for testSetProximityInfo"
- "Invalid key value while decoding result type for verifyRandomK"
- "NSObject"
- "OS_os_transaction"
- "Q16@0:8"
- "T#,R"
- "T@\"NSString\",?,R,C"
- "T@\"NSString\",R,C"
- "TQ,R"
- "Using legacy ACM context creation. Please switch to using the SecurePairingContext"
- "Vv16@0:8"
- "^{_NSZone=}16@0:8"
- "_TtC14securepairingd19SecureAudioListener"
- "autorelease"
- "cancelDomainPairing"
- "class"
- "com.apple.securepairing.audioListen"
- "com.apple.securepairing.domainKeysExchange.lead."
- "com.apple.securepairing.domainKeysExchange.peer."
- "com.apple.securepairing.pairingSession.peer."
- "com.apple.securepairingd.sigmapeerservice"
- "completeAttestation"
- "conformsToProtocol:"
- "debugDescription"
- "description"
- "domainCancelPairing"
- "domainCancelPairing error: %@"
- "domainHandleDomainKeys"
- "domainHandleDomainKeys error: %@"
- "domainHandleDomainKeysAck"
- "domainHandleDomainKeysAck error: %@"
- "domainHandleMissingKeyTypesAck"
- "domainHandleMissingKeyTypesAck error: %@"
- "domainPeerCancelPairing"
- "domainPeerCancelPairing error: %@"
- "domainPeerHandleDomainKeys"
- "domainPeerHandleDomainKeys error: %@"
- "domainPeerHandleDomainKeysAck"
- "domainPeerHandleDomainKeysAck error: %@"
- "domainPeerHandleMissingKeyTypes"
- "domainPeerHandleMissingKeyTypes error: %@"
- "domainPeerHandleMissingKeyTypesCont"
- "domainPeerHandleMissingKeyTypesCont error: %@"
- "domainPeerHandleStartKeyTransfer"
- "domainPeerHandleStartKeyTransfer error: %@"
- "domainPeerSessionEnded"
- "domainSessionEnded"
- "domainStartKeyTransfer"
- "domainStartKeyTransfer error: %@"
- "domainStartPairing"
- "domainStartPairing error: %@"
- "domainStartPeerPairing"
- "externalizedACMContext"
- "getAttestation (peer)"
- "handleDomainKeys"
- "handleDomainKeysAck"
- "handleMissingKeyTypes"
- "handleMissingKeyTypesAck"
- "handleMissingKeyTypesCont"
- "handleStartKeyTransfer"
- "hash"
- "initSecureIntent"
- "inputRecorder"
- "invalid rawValue for TransferEncoding: "
- "isEqual:"
- "isKindOfClass:"
- "isMemberOfClass:"
- "isProxy"
- "osTransaction"
- "ownerId"
- "parkedAudioBoostContinuation"
- "performSelector:"
- "performSelector:withObject:"
- "performSelector:withObject:withObject:"
- "preferedEncoding"
- "processing XPC request domainCancelPairing"
- "processing XPC request domainHandleDomainKeys"
- "processing XPC request domainHandleDomainKeysAck"
- "processing XPC request domainHandleMissingKeyTypesAck"
- "processing XPC request domainPeerCancelPairing"
- "processing XPC request domainPeerHandleDomainKeys"
- "processing XPC request domainPeerHandleDomainKeysAck"
- "processing XPC request domainPeerHandleMissingKeyTypes"
- "processing XPC request domainPeerHandleMissingKeyTypesCont"
- "processing XPC request domainPeerHandleStartKeyTransfer"
- "processing XPC request domainPeerSessionEnded for pairingID=%llu"
- "processing XPC request domainSessionEnded for pairingID=%llu"
- "processing XPC request domainStartKeyTransfer"
- "processing XPC request domainStartPairing"
- "processing XPC request sigmaPeerCancelPairing for pairingID=%llu"
- "processing XPC request sigmaPeerSessionEnded for pairingID=%llu"
- "processing XPC request sigmaSessionInit (POR)"
- "processing XPC request sigmaStartListening"
- "release"
- "respondsToSelector:"
- "retain"
- "retainCount"
- "securepairingd/SecureAudioSupport.swift"
- "self"
- "sigmaCompleteAttestation"
- "sigmaCompleteAttestation (peer)"
- "sigmaCompleteAttestation error: %@"
- "sigmaPeerCancelPairing"
- "sigmaPeerCancelPairing conclave error: %@"
- "sigmaPeerCancelPairing: context cleared for pairingID=%llu"
- "sigmaPeerSessionEnded"
- "sigmaProximityBypass"
- "sigmaProximityBypass error: %@"
- "sigmaSessionInit"
- "sigmaSessionInit error: %@"
- "sigmaSetRandomK"
- "sigmaSetRandomK error: %@"
- "sigmaStartListening"
- "sigmaStartListening error: %@"
- "sigmaVerifyRandomK"
- "sigmaVerifyRandomK error: %@"
- "startDomainPairing"
- "startListening (peer)"
- "startListening(ownerId:timeout:)"
- "startPairing (peer)"
- "stopListening(ownerId:)"
- "superclass"
- "testSetProximityInfo (peer)"
- "timeoutTask"
- "unexpected randomK data size"
- "unexpected wka passcode data size"
- "zone"
```
