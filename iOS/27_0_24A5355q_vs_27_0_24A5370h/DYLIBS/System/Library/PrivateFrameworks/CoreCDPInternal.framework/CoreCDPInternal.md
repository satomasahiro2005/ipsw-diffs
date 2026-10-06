## CoreCDPInternal

> `/System/Library/PrivateFrameworks/CoreCDPInternal.framework/CoreCDPInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xd995` | `0xe035` | **`+0x6a0`** |
| `__TEXT.__text` | `0x8cf5c` | `0x8d5a0` | **`+0x644`** |
| `__AUTH_CONST.__cfstring` | `0x8fc0` | `0x94a0` | **`+0x4e0`** |
| `__TEXT.__oslogstring` | `0x1488e` | `0x1494e` | **`+0xc0`** |
| `__DATA_CONST.__objc_arraydata` | `0x1b8` | `0x220` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x2578` | `0x25c8` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0xb68` | `0xb94` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0xab0` | `0xad0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x5644` | `0x5664` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1dc0` | `0x1de0` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xa8` | `0xc0` | **`+0x18`** |
| `__DATA.__bss` | `0x4b0` | `0x4c0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x38e0` | `0x38f0` | **`+0x10`** |

### Other Changes

```diff

-440.1.0.0.0
+442.0.0.0.0

-  Functions: 3142
-  Symbols:   4133
-  CStrings:  2760
+  Functions: 3151
+  Symbols:   4143
+  CStrings:  2802
Symbols:
+ +[CDPDAnalyticsTransport getAllowedTransparencyAETEvents]
+ -[CDPDPCSController _renewAndRetryGeneratePDPBlob:authError:completion:]
+ GCC_except_table38
+ GCC_except_table43
+ GCC_except_table65
+ ___57+[CDPDAnalyticsTransport getAllowedTransparencyAETEvents]_block_invoke
+ ___72-[CDPDPCSController _renewAndRetryGeneratePDPBlob:authError:completion:]_block_invoke
+ ___block_descriptor_56_e8_32s40bs48w_e28_v24?0"NSData"8"NSError"16lw48l8s40l8s32l8
+ ___block_descriptor_64_e8_32s40s48bs56w_e17_v16?0"NSError"8lw56l8s32l8s48l8s40l8
+ _getAllowedTransparencyAETEvents.approvedEvents
+ _getAllowedTransparencyAETEvents.onceToken
+ _swift_retain_x25
- GCC_except_table63
- _swift_release_x26
CStrings:
+ "AppleAccountTransparency.AATError"
+ "CDPDPCSController found nil, generatePDPBlob failed with error: %@"
+ "CoreTransparency.AETVerifierError"
+ "CoreTransparency.CTConfigBagError"
+ "CoreTransparency.PublicKeyBagError"
+ "CoreTransparency.SignedObjectError"
+ "Generate PDP Blob retry completed with blob length=%lu error=%@"
+ "com.apple.CoreTransparency.AET"
+ "com.apple.CoreTransparency.TransparencyTLSError"
+ "com.apple.CoreTransparency.Verification"
+ "com.apple.KTSwiftDBError"
+ "com.apple.Transparency.AETransparencyError"
+ "com.apple.Transparency.ConfigBagManagerError"
+ "com.apple.Transparency.CoreTransparencyEnumShimError"
+ "com.apple.Transparency.PublicKeyBagManagerError"
+ "com.apple.Transparency.TransparencyProtobufClientError"
+ "com.apple.TransparencyFallbackError"
+ "com.apple.appleaccounttransparency.storage"
+ "com.apple.authkit.StableIDAvailability"
+ "com.apple.authkit.TDIDAvailability"
+ "com.apple.authkit.TDIDAvailability.signin"
+ "com.apple.authkit.TDIDAvailability.upgrade"
+ "com.apple.security.allowedStableIDMIDHashMismatch"
+ "com.apple.security.ckks.tlkOwnershipProofsGenerated"
+ "com.apple.security.fetchStableTrustedDeviceID"
+ "com.apple.security.fetchTDLInTPH"
+ "com.apple.security.prepareVouchAndJoinTPH"
+ "com.apple.security.supportsTLKOwnershipProofSetinStableInfo"
+ "com.apple.transparency.aet.dutyCycle.finish"
+ "com.apple.transparency.aet.dutyCycle.start"
+ "com.apple.transparency.aet.fetchRevisions"
+ "com.apple.transparency.aet.garbageCollect"
+ "com.apple.transparency.aet.getConfigBag"
+ "com.apple.transparency.aet.getPublicKeyBag"
+ "com.apple.transparency.aet.makeProofRequestPayload.finish"
+ "com.apple.transparency.aet.makeProofRequestPayload.start"
+ "com.apple.transparency.aet.treeRollSelfHeal"
+ "com.apple.transparency.aet.verification.eventMatchOnly"
+ "com.apple.transparency.aet.verification.fullProof"
+ "com.apple.transparency.aet.verifyProof.finish"
+ "com.apple.transparency.aet.verifyProof.start"
+ "generatePDPBlob failed with authentication error: %@"
```
