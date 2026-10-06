## TrustedPeersHelper

> `/System/Library/Frameworks/Security.framework/XPCServices/TrustedPeersHelper.xpc/TrustedPeersHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a0864` | `0x2a3ccc` | **`+0x3468`** |
| `__TEXT.__oslogstring` | `0xd2f7` | `0xd4a4` | **`+0x1ad`** |
| `__DATA_CONST.__const` | `0x14c70` | `0x14d88` | **`+0x118`** |
| `__TEXT.__swift5_capture` | `0x5090` | `0x516c` | **`+0xdc`** |
| `__TEXT.__eh_frame` | `0x7f60` | `0x7ef0` | **`-0x70`** |
| `__TEXT.__objc_methname` | `0x90e1` | `0x9141` | **`+0x60`** |
| `__TEXT.__cstring` | `0x17a67` | `0x17ab7` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x29bf` | `0x29f0` | **`+0x31`** |
| `__DATA_CONST.__got` | `0xa10` | `0xa40` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x2647` | `0x2677` | **`+0x30`** |
| `__TEXT.__const` | `0xd4a0` | `0xd4c0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x6060` | `0x6080` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x22d0` | `0x22e0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2b80` | `0x2b8c` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x3fbc` | `0x3fc6` | **`+0xa`** |
| `__DATA.__objc_selrefs` | `0x1ec0` | `0x1ec8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1178` | `0x1180` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x292c` | `0x2934` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4f70` | `0x4f78` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-62460.0.22.0.0
+62460.0.38.0.1

+  - /System/Library/PrivateFrameworks/StorageContainersPrivate.framework/StorageContainersPrivate

-  Functions: 8885
-  Symbols:   570
-  CStrings:  3187
+  Functions: 8898
+  Symbols:   578
+  CStrings:  3195
Symbols:
+ _kSecurityRTCEventNameRKSponsorSelection
+ _kSecurityRTCEventNameRecoverRKTLKShares
+ _kSecurityRTCEventNameTLKProofInvalid
+ _kSecurityRTCFieldAuthenticatedRKSponsorSelected
+ _kSecurityRTCFieldNumRKTLKShares
+ _kSecurityRTCFieldNumRKTLKSharesRecovered
+ _kSecurityRTCFieldPotentialRKSponsorsWithStableInfoFlagSet
+ _swift_projectBox
CStrings:
+ "@28@0:8@16B24"
+ "B52@0:8@16@24@32B40^@44"
+ "Couldn't verify signature of TLKShare (%@) that includes tlkOwnershipProof as part of dataForSigning; trying again without tlkOwnershipProof"
+ "No protected Container "
+ "UpdateTrust: failed to find ego peer information"
+ "couldn't generate stableInfo for walrus disable retry, cannot disable walrus"
+ "dataForSigning:includeProof:"
+ "disableWalrus retry failed: %{public}s"
+ "disableWalrus returned indicating that stableInfo contains extra modifications, trying fetch"
+ "v84@0:8@\"TPSpecificUser\"16@\"NSString\"24@\"NSString\"32@\"NSArray\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64B72@?<v@?@\"NSData\"@\"NSData\"@\"NSArray\"B@\"TrustedPeersHelperTLKRecoveryResult\"@\"NSError\">76"
+ "verifySignature:verifyingPeer:ckrecord:acceptProoflessSig:error:"
+ "vouchWithRecoveryKey(recoveryKey:salt:tlkShares:altDSID:flowID:deviceSessionID:canSendMetrics:reply:)"
+ "vouchWithRecoveryKeyWithSpecificUser:recoveryKey:salt:tlkShares:altDSID:flowID:deviceSessionID:canSendMetrics:reply:"
- "B48@0:8@16@24@32^@40"
- "v56@0:8@\"TPSpecificUser\"16@\"NSString\"24@\"NSString\"32@\"NSArray\"40@?<v@?@\"NSData\"@\"NSData\"@\"NSArray\"B@\"TrustedPeersHelperTLKRecoveryResult\"@\"NSError\">48"
- "verifySignature:verifyingPeer:ckrecord:error:"
- "vouchWithRecoveryKey(recoveryKey:salt:tlkShares:reply:)"
- "vouchWithRecoveryKeyWithSpecificUser:recoveryKey:salt:tlkShares:reply:"
```
