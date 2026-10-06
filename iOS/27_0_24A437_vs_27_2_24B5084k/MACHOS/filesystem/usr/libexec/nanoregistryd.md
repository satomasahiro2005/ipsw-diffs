## nanoregistryd

> `/usr/libexec/nanoregistryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10080c` | `0x101134` | **`+0x928`** |
| `__TEXT.__oslogstring` | `0x16281` | `0x164d9` | **`+0x258`** |
| `__TEXT.__objc_methname` | `0x1c603` | `0x1c7f1` | **`+0x1ee`** |
| `__TEXT.__cstring` | `0xe174` | `0xe299` | **`+0x125`** |
| `__DATA_CONST.__cfstring` | `0xc120` | `0xc1e0` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0x11000` | `0x110a0` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x1a380` | `0x1a400` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x1cc0` | `0x1d30` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x4bc0` | `0x4c20` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xdadc` | `0xdb14` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x5e90` | `0x5ec0` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x4bc9` | `0x4be2` | **`+0x19`** |
| `__TEXT.__auth_stubs` | `0x1110` | `0x1120` | **`+0x10`** |
| `__TEXT.__const` | `0x69a` | `0x6aa` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x11e0` | `0x11ec` | **`+0xc`** |
| `__DATA.__data` | `0x19d8` | `0x19e0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x898` | `0x8a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1075.1.4.0.0
+1075.11.0.0.0

-  Functions: 5830
-  Symbols:   707
-  CStrings:  8661
+  Functions: 5834
+  Symbols:   708
+  CStrings:  8683
Symbols:
+ _os_eligibility_get_domain_answer
CStrings:
+ "\n\""
+ "-[NRPairingDaemon remoteObject:receivedUnpairRequestWithAdvertisedName:shouldObliterate:shouldBrick:shouldPreserveESim:shouldOverwriteStorage:withPairingFailureCode:withAbortReason:withRequestIdentifier:fromIDSBTUUID:]"
+ "-[NRPairingDaemon unpairDeviceWithPairingID:obliterationString:shouldBrick:storeUnpair:migrationUnpair:shouldPreserveESim:shouldOverwriteStorage:pairingReport:remoteUnpairRequestUUID:shouldConnectionWithDevice:]"
+ "-overwriteStorage"
+ "71ae426b-1f25-4ade-a61d-f0676b93be1f"
+ "F47B90E6-F2D5-49D0-A8F2-C880AA3FED19"
+ "NanoRegistry-1075.11"
+ "SEABORGIUM eligible: %{bool}d"
+ "T@\"NSData\",&,N,V_additionalPairingData"
+ "TB,R,N,V_supportsSecurePairing"
+ "[obliterateGizmo] receivedUnpairRequest: advertisedName=%{public}@ shouldObliterate=%{BOOL}d shouldBrick=%{BOOL}d shouldPreserveESim=%{BOOL}d shouldOverwriteStorage=%{BOOL}d abortReason=%{public}@ idsBTUUID=%{public}@"
+ "[obliterateGizmo] xpcUnpairWithDeviceID parsed: shouldOverwriteStorage=%{BOOL}d shouldPreserveESim=%{BOOL}d shouldObliterate=%{BOOL}d shouldBrick=%{BOOL}d shouldStore=%{BOOL}d"
+ "[obliterateGizmo] xpcUnpairWithDeviceID raw options dict from caller %{public}@: %@"
+ "_additionalPairingData"
+ "_pairWithCandidate:withPreSharedAuthData:isAltAccountPairing:additionalPairingData:"
+ "_pairingOptionsFromPairedDevice:"
+ "_pendingAdditionalPairingData"
+ "_supportsSecurePairing"
+ "additionalPairingData"
+ "com.apple.NanoRegistry.watchsetuppayload.extendedMetadata.supportsSecurePairing"
+ "extensiblePairingAdditionalPairingData"
+ "f90f4d4f-f87c-41a0-b174-ad80e6d8214a"
+ "initWithPairingVersion:productVersionMajor:productVersionMinor:postFailSafeObliteration:encodedSystemVersion:supportsSecurePairing:"
+ "os_eligibility_get_domain_answer for SEABORGIUM returned %d"
+ "passPINAuthDataToPairingCandidate:isAltAccountPairing:additionalPairingData:"
+ "remoteObject:receivedUnpairRequestWithAdvertisedName:shouldObliterate:shouldBrick:shouldPreserveESim:shouldOverwriteStorage:withPairingFailureCode:withAbortReason:withRequestIdentifier:fromIDSBTUUID:"
+ "requestPreSharedAuthForCandidateWithIdentifier:preSharedAuthData:isAltAccountPairing:additionalPairingData:"
+ "sendUnpairMessageWithAdvertisedName:btUUID:shouldObliterate:shouldBrick:shouldPreserveESim:shouldOverwriteStorage:withPairingFailureCode:withAbortReason:withRequestIdentifier:responseBlock:"
+ "setAdditionalPairingData:"
+ "setSupportsSecurePairing:"
+ "startPairingDevice:additionalData:withCompletion:resultBlock:"
+ "supportsSecurePairing"
+ "unpairDeviceWithPairingID:obliterationString:shouldBrick:storeUnpair:migrationUnpair:shouldPreserveESim:shouldOverwriteStorage:pairingReport:remoteUnpairRequestUUID:shouldConnectionWithDevice:"
+ "v80@0:8@\"NRRemoteObjectClassD\"16@\"NSString\"24B32B36B40B44@\"NSNumber\"48@\"NSString\"56@64@\"NSUUID\"72"
+ "v80@0:8@16@24B32B36B40B44@48@56@64@72"
+ "v92@0:8@\"NSUUID\"16@\"NSString\"24@\"NSNumber\"32@\"NSNumber\"40@\"NSNumber\"48@\"NSNumber\"56@\"NSNumber\"64@\"NRPairingReport\"72@\"NSUUID\"80B88"
+ "v92@0:8@16@24@32@40@48@56@64@72@80B88"
+ "v96@0:8@16@24@32@40@48@56@64@72@80@?88"
+ "xpcUnpairWithDeviceID: deviceID=%{public}@ shouldObliterate=%{BOOL}d shouldBrick=%{BOOL}d shouldStore=%{BOOL}d shouldPreserveESim=%{BOOL}d shouldOverwriteStorage=%{BOOL}d unlockedSinceBoot=%{BOOL}d, pairingReport=%{BOOL}d"
- "\n!"
- "-[NRPairingDaemon remoteObject:receivedUnpairRequestWithAdvertisedName:shouldObliterate:shouldBrick:shouldPreserveESim:withPairingFailureCode:withAbortReason:withRequestIdentifier:fromIDSBTUUID:]"
- "-[NRPairingDaemon unpairDeviceWithPairingID:obliterationString:shouldBrick:storeUnpair:migrationUnpair:shouldPreserveESim:pairingReport:remoteUnpairRequestUUID:shouldConnectionWithDevice:]"
- "NanoRegistry-1075.1.4"
- "_pairWithCandidate:withPreSharedAuthData:isAltAccountPairing:"
- "initWithPairingVersion:productVersionMajor:productVersionMinor:postFailSafeObliteration:encodedSystemVersion:"
- "passPINAuthDataToPairingCandidate:isAltAccountPairing:"
- "remoteObject:receivedUnpairRequestWithAdvertisedName:shouldObliterate:shouldBrick:shouldPreserveESim:withPairingFailureCode:withAbortReason:withRequestIdentifier:fromIDSBTUUID:"
- "requestPreSharedAuthForCandidateWithIdentifier:preSharedAuthData:isAltAccountPairing:"
- "sendUnpairMessageWithAdvertisedName:btUUID:shouldObliterate:shouldBrick:shouldPreserveESim:withPairingFailureCode:withAbortReason:withRequestIdentifier:responseBlock:"
- "unpairDeviceWithPairingID:obliterationString:shouldBrick:storeUnpair:migrationUnpair:shouldPreserveESim:pairingReport:remoteUnpairRequestUUID:shouldConnectionWithDevice:"
- "v76@0:8@\"NRRemoteObjectClassD\"16@\"NSString\"24B32B36B40@\"NSNumber\"44@\"NSString\"52@60@\"NSUUID\"68"
- "v76@0:8@16@24B32B36B40@44@52@60@68"
- "v84@0:8@\"NSUUID\"16@\"NSString\"24@\"NSNumber\"32@\"NSNumber\"40@\"NSNumber\"48@\"NSNumber\"56@\"NRPairingReport\"64@\"NSUUID\"72B80"
- "v84@0:8@16@24@32@40@48@56@64@72B80"
- "v88@0:8@16@24@32@40@48@56@64@72@?80"
- "xpcUnpairWithDeviceID: deviceID=%{public}@ shouldObliterate=%{BOOL}d shouldBrick=%{BOOL}d shouldStore=%{BOOL}d shouldPreserveESim=%{BOOL}d unlockedSinceBoot=%{BOOL}d, pairingReport=%{BOOL}d"
```
