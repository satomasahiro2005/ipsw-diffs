## securityd

> `/usr/libexec/securityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26b4bc` | `0x26c4bc` | **`+0x1000`** |
| `__TEXT.__oslogstring` | `0x2fbe2` | `0x2fe5c` | **`+0x27a`** |
| `__TEXT.__gcc_except_tab` | `0x9f10` | `0xa074` | **`+0x164`** |
| `__DATA_CONST.__got` | `0x13e0` | `0x1528` | **`+0x148`** |
| `__TEXT.__objc_methname` | `0x2e54b` | `0x2e5af` | **`+0x64`** |
| `__TEXT.__objc_methtype` | `0xafbe` | `0xb01a` | **`+0x5c`** |
| `__TEXT.__cstring` | `0x226e5` | `0x2273b` | **`+0x56`** |
| `__TEXT.__objc_stubs` | `0x1d880` | `0x1d8c0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x14920` | `0x14948` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x1c480` | `0x1c4a0` | **`+0x20`** |
| `__TEXT.__const` | `0x920` | `0x910` | **`-0x10`** |
| `__DATA.__data` | `0x3158` | `0x3150` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x9848` | `0x9850` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x15e48` | `0x15e50` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6a50` | `0x6a58` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x378` | `0x372` | **`-0x6`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__thread_vars`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-62460.0.22.0.0
+62460.0.38.0.1

-  Functions: 9908
-  Symbols:   1889
-  CStrings:  16378
+  Functions: 9910
+  Symbols:   1890
+  CStrings:  16391
Symbols:
+ _kSecurityRTCEventNameVouchWithRK
+ _kSecurityRTCFieldDistrustEveryoneOnJoin
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "-[CuttlefishXPCWrapper vouchWithRecoveryKeyWithSpecificUser:recoveryKey:salt:tlkShares:altDSID:flowID:deviceSessionID:canSendMetrics:reply:]_block_invoke"
+ "@\"OTCheckHealthOperation\""
+ "B52@0:8@16@24@32B40^@44"
+ "Couldn't verify signature of TLKShare (%@) that includes tlkOwnershipProof as part of dataForSigning; trying again without tlkOwnershipProof"
+ "Existing TLKShare's ownership proof for peer %@ from self %@ is invalid. Will update TLK Share %@"
+ "Existing TLKShare's signature for peer %@ from self %@ is invalid. Will update TLK Share %@"
+ "Finishing vouching with recovery key with %@"
+ "Proposed TLKShare(%@) supercedes existing TLKShare(%@)"
+ "Unable to generate TLK ownership proof: %@"
+ "_currentHealthCheckOp"
+ "active user: %d"
+ "com.apple.FileProvider.usermanager.sync"
+ "dataForSigning:includeProof:"
+ "onlyDelete: %{BOOL}d, copyCloudAuthToken: %{BOOL}d, copyMobileMail: %{BOOL}d, copyNSURLSession: %{BOOL}d, copyPCS: %{BOOL}d"
+ "unknown service: %@"
+ "v84@0:8@\"TPSpecificUser\"16@\"NSString\"24@\"NSString\"32@\"NSArray\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64B72@?<v@?@\"NSData\"@\"NSData\"@\"NSArray\"B@\"TrustedPeersHelperTLKRecoveryResult\"@\"NSError\">76"
+ "verifySignature:verifyingPeer:acceptProoflessSig:error:"
+ "verifySignature:verifyingPeer:ckrecord:acceptProoflessSig:error:"
+ "vouchWithRecoveryKeyWithSpecificUser:recoveryKey:salt:tlkShares:altDSID:flowID:deviceSessionID:canSendMetrics:reply:"
- "-[CuttlefishXPCWrapper vouchWithRecoveryKeyWithSpecificUser:recoveryKey:salt:tlkShares:reply:]_block_invoke"
- "_healthCheckResults"
- "v56@0:8@\"TPSpecificUser\"16@\"NSString\"24@\"NSString\"32@\"NSArray\"40@?<v@?@\"NSData\"@\"NSData\"@\"NSArray\"B@\"TrustedPeersHelperTLKRecoveryResult\"@\"NSError\">48"
- "verifySignature:verifyingPeer:ckrecord:error:"
- "verifySignature:verifyingPeer:error:"
- "vouchWithRecoveryKeyWithSpecificUser:recoveryKey:salt:tlkShares:reply:"
```
