## securityd

> `/usr/libexec/securityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26a0f0` | `0x26b4bc` | **`+0x13cc`** |
| `__TEXT.__oslogstring` | `0x2fa77` | `0x2fbe2` | **`+0x16b`** |
| `__TEXT.__cstring` | `0x225ba` | `0x226e5` | **`+0x12b`** |
| `__TEXT.__objc_methname` | `0x2e4ab` | `0x2e54b` | **`+0xa0`** |
| `__DATA_CONST.__cfstring` | `0x1c400` | `0x1c480` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x148b8` | `0x14920` | **`+0x68`** |
| `__TEXT.__gcc_except_tab` | `0x9ebc` | `0x9f10` | **`+0x54`** |
| `__DATA_CONST.__objc_intobj` | `0x13e0` | `0x1410` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xaf90` | `0xafbe` | **`+0x2e`** |
| `__DATA.__objc_const` | `0x23c18` | `0x23c40` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x4330` | `0x4350` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1d860` | `0x1d880` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6a38` | `0x6a50` | **`+0x18`** |
| `__DATA.__bss` | `0xec0` | `0xed0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x9838` | `0x9848` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x21a8` | `0x21b8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x13d8` | `0x13e0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x15e50` | `0x15e48` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1ae4` | `0x1ae8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__thread_vars`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-62426.0.0.0.4
+62460.0.22.0.0

-  Functions: 9906
-  Symbols:   1886
-  CStrings:  16359
+  Functions: 9908
+  Symbols:   1889
+  CStrings:  16378
Symbols:
+ __OctagonSignpostLogMetricDeltas
+ _kSecurityRTCFieldIsDemoAccount
+ _os_release
CStrings:
+ "-[CuttlefishXPCWrapper joinWithSpecificUser:voucherData:voucherSig:ckksKeys:tlkShares:preapprovedKeys:flowID:deviceSessionID:canSendMetrics:distrustEveryoneOnJoin:reply:]_block_invoke"
+ "Disable walrus failed due to test scenario"
+ "Distrusting all other peers + recovery factors in subsequent join post CKKS reset"
+ "EnableWalrus failed due to test scenario"
+ "FailDisableWalrus"
+ "FailEnableWalrus"
+ "Failing walrus disablement due to test scenario (%@)"
+ "Failing walrus enablement due to test scenario (%@)"
+ "OctagonAuthenticatedRKJoin"
+ "OctagonAuthenticatedRKJoin is %s"
+ "OctagonStateJoinAsOnlyPeer"
+ "RerollJoinUpdateDeviceList"
+ "SecDbConnectionRelease"
+ "TB,V_distrustEveryoneOnJoin"
+ "_distrustEveryoneOnJoin"
+ "com.apple.securityd.idle-dbconnections-cleanup"
+ "distrustEveryoneOnJoin"
+ "fetchStableTrustedDeviceID: demo-account lookup failed: %@"
+ "fetched MID/StableID pair is %@"
+ "idle connections more than baseline, kicking off cleanup"
+ "idle read dbconnections cleanup timer fired: %ld idle, baseline %d"
+ "idle read dbconnections cleanup: reached baseline, stopping timer"
+ "idle read dbconnections cleanup: starting timer (idle=%ld > baseline=%d)"
+ "idle read dbconnections cleanup: trimmed %ld, %ld remaining"
+ "initWithDependencies:intendedState:ckksConflictState:errorState:distrustEveryoneOnJoin:"
+ "join-but-distrust-everyone"
+ "joinAfterCKKSResetPathDictionary"
+ "joinWithSpecificUser:voucherData:voucherSig:ckksKeys:tlkShares:preapprovedKeys:flowID:deviceSessionID:canSendMetrics:distrustEveryoneOnJoin:reply:"
+ "join_but_distrust_everyone"
+ "no need to cleanup"
+ "onQueueScheduleIdleReadConnectionsCleanupIfNeeded"
+ "setDistrustEveryoneOnJoin:"
+ "v52@?0@\"NSData\"8@\"NSData\"16@\"NSArray\"24B32@\"TrustedPeersHelperTLKRecoveryResult\"36@\"NSError\"44"
+ "v56@0:8@\"TPSpecificUser\"16@\"NSString\"24@\"NSString\"32@\"NSArray\"40@?<v@?@\"NSData\"@\"NSData\"@\"NSArray\"B@\"TrustedPeersHelperTLKRecoveryResult\"@\"NSError\">48"
+ "v96@0:8@\"TPSpecificUser\"16@\"NSData\"24@\"NSData\"32@\"NSArray\"40@\"NSArray\"48@\"NSArray\"56@\"NSString\"64@\"NSString\"72B80B84@?<v@?@\"NSString\"@\"NSArray\"@\"TPSyncingPolicy\"@\"NSError\">88"
+ "v96@0:8@16@24@32@40@48@56@64@72B80B84@?88"
+ "will be distrusting all other peers and recovery factors on join"
- "-[CuttlefishXPCWrapper joinWithSpecificUser:voucherData:voucherSig:ckksKeys:tlkShares:preapprovedKeys:flowID:deviceSessionID:canSendMetrics:reply:]_block_invoke"
- "Device is locked! Cannot check reroll status"
- "Error checking stable device ID reroll status: %@"
- "Feature not enabled: %@"
- "OctagonActivityRerollForStableTrustedDeviceID"
- "OctagonEventRerollForStableTrustedDeviceID"
- "Rejecting a rerollForStableTrustedDeviceID RPC for arguments (%@): %@"
- "Stable device ID already up to date, no reroll needed"
- "Stable device ID needs update, proceeding with reroll"
- "Stable trusted device ID feature is not enabled"
- "joinWithSpecificUser:voucherData:voucherSig:ckksKeys:tlkShares:preapprovedKeys:flowID:deviceSessionID:canSendMetrics:reply:"
- "octagon-stable-device-id-reroll"
- "reroll-stable-device-id"
- "rerollForStableTrustedDeviceID invoked for arguments (%@)"
- "rerollForStableTrustedDeviceID:reply:"
- "rerollForStableTrustedDeviceIDWithReply:"
- "v56@0:8@\"TPSpecificUser\"16@\"NSString\"24@\"NSString\"32@\"NSArray\"40@?<v@?@\"NSData\"@\"NSData\"@\"NSArray\"@\"TrustedPeersHelperTLKRecoveryResult\"@\"NSError\">48"
- "v92@0:8@\"TPSpecificUser\"16@\"NSData\"24@\"NSData\"32@\"NSArray\"40@\"NSArray\"48@\"NSArray\"56@\"NSString\"64@\"NSString\"72B80@?<v@?@\"NSString\"@\"NSArray\"@\"TPSyncingPolicy\"@\"NSError\">84"
```
