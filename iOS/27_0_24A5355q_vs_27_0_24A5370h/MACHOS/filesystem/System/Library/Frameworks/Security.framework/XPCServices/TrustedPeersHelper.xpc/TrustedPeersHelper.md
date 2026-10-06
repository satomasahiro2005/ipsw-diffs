## TrustedPeersHelper

> `/System/Library/Frameworks/Security.framework/XPCServices/TrustedPeersHelper.xpc/TrustedPeersHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29197c` | `0x2a0864` | **`+0xeee8`** |
| `__TEXT.__oslogstring` | `0xc917` | `0xd2f7` | **`+0x9e0`** |
| `__TEXT.__cstring` | `0x17377` | `0x17a67` | **`+0x6f0`** |
| `__DATA_CONST.__const` | `0x14fb0` | `0x14c70` | **`-0x340`** |
| `__TEXT.__eh_frame` | `0x7d38` | `0x7f60` | **`+0x228`** |
| `__TEXT.__swift5_typeref` | `0x3e20` | `0x3fbc` | **`+0x19c`** |
| `__TEXT.__const` | `0xd390` | `0xd4a0` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x4eb0` | `0x4f70` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x3b74` | `0x3c1c` | **`+0xa8`** |
| `__TEXT.__objc_methname` | `0x9041` | `0x90e1` | **`+0xa0`** |
| `__DATA.__bss` | `0x12da0` | `0x12e20` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x2250` | `0x22d0` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x25c7` | `0x2647` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x2b0c` | `0x2b80` | **`+0x74`** |
| `__DATA.__objc_const` | `0x6e18` | `0x6e78` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x295f` | `0x29bf` | **`+0x60`** |
| `__DATA.__objc_data` | `0x2c38` | `0x2c90` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x9b8` | `0xa10` | **`+0x58`** |
| `__DATA.__data` | `0x8450` | `0x84a0` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x1138` | `0x1178` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x6020` | `0x6060` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x50bc` | `0x5090` | **`-0x2c`** |
| `__DATA.__common` | `0xa18` | `0xa28` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1eb8` | `0x1ec0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x6e8` | `0x6f0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2c0` | `0x2c8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x988` | `0x98c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-62426.0.0.0.4
+62460.0.22.0.0

-  Functions: 8841
-  Symbols:   552
-  CStrings:  3126
+  Functions: 8885
+  Symbols:   570
+  CStrings:  3187
Symbols:
+ _IsOctagonAuthenticatedRKJoinEnabled
+ _SecSignpostMetricsSnapshot
+ _kSecurityRTCEventNameTDLDuplicateMIDRecord
+ _kSecurityRTCEventNameTDLDuplicateStableID
+ _kSecurityRTCEventNameTDLMembershipCheckFailed
+ _kSecurityRTCEventNameTDLMembershipMultipleRecords
+ _kSecurityRTCEventNameTDLSilentDrop
+ _kSecurityRTCEventNameTDLStableIDDivergenceDisallow
+ _kSecurityRTCFieldLookupKeyType
+ _kSecurityRTCFieldRecordCount
+ _mach_port_deallocate
+ _mach_task_self_
+ _mach_thread_self
+ _swift_deallocUninitializedObject
+ _swift_retain_x1
+ _swift_stdlib_random
+ _task_info
+ _thread_info
CStrings:
+ " enableTelemetry=YES "
+ "%s: error calling statusOfPeer: %{public}@"
+ "%s: unable to compute syncing policy: %{public}s"
+ "; stableID divergence: TDL stableID="
+ "Could not find a sponsor for RK join"
+ "Disallowing machineID present on TDL with diverging stableID"
+ "END [%lld] %fs: %{public}@ success=%d rss_delta=%lldKB peak=%lldKB task_cpu=%lldus thread_cpu=%lldus"
+ "Error creating voucher on behalf of sponsor (%s) using recovery key set: %{public}s"
+ "Errored generating TLK Ownership proof for %s, exiting early: %@"
+ "Errored while trying to find a sponsor for RK"
+ "Failed to get peer that trust RK: %{public}@"
+ "Failed to recover TLKs for self, errors ahead: %{public}@"
+ "Hurrah! found a sponsor %s for peer joining with RK"
+ "Loop 1"
+ "Loop 2 silent drop due to stableID collision"
+ "Loop 2 skipping TDL pair: TDL MID=%{public}s shares stableID=%{public}s with knownMachine MID=%{public}s; not creating"
+ "Loop 3"
+ "Loop 3 created second MachineMO with same MID"
+ "Loop 3 creating second MachineMO with same MID: MID=%{public}s, new stableID=%{public}s, prior record stableID=%{public}s, prior status=%{public}lld"
+ "Machine ID %{public}s matched TDL by MID; local stable ID not yet populated, will adopt TDL stableID=%{public}s"
+ "Multiple MachineMO records share one machineID"
+ "Peer machineID: %{public}s, Stable ID:  %{public}s, is unknown, making it disallowed%{public}s"
+ "Potential sponsor %s does not have a self-TLKShare for this view, skipping"
+ "Sponsor (%s has a TLK Ownership proof that doesn't match our knowledge, exiting early"
+ "TDL contains duplicate stableID across multiple MIDs"
+ "TDL contains duplicate stableID: %{public}ld MIDs share stableID %{public}s; MIDs=[%{public}s]"
+ "TDL has %{public}ld distinct stableIDs each shared by multiple MIDs"
+ "TRUST_STATE: account_non_primary"
+ "TRUST_STATE: account_primary"
+ "TRUST_STATE: peers"
+ "TRUST_STATE: preapprovals"
+ "TRUST_STATE: recovery_key_no"
+ "TRUST_STATE: recovery_key_yes"
+ "TRUST_STATE: totals"
+ "Updating machine ID from %{public}s to %{public}s (matched stableID=%{public}s, MID rolled)"
+ "User initiated removal! machine ID last modified %{public}s; distrusting Machine ID: %{public}s, Stable ID: %{public}s, Status: %{public}lld%{public}s"
+ "We haven't recovered the TLKs, so we can't generate TLK Ownership proofs. Exiting"
+ "baselineMetrics"
+ "couldn't find a potential sponsor for RK that can prove ownership of all TLKs, we'll have to choose a random sponsor and distrust everyone on join"
+ "dynamicInfoForJoiningPeerID:peerPermanentInfo:peerStableInfo:sponsorID:preapprovedKeys:signingKeyPair:currentMachineIDs:requiresTDLFetch:distrustEveryoneOnJoin:error:"
+ "fetchAndPersistChanges"
+ "fetchCuttlefishAfterReset: fetch failed (non-fatal): %{public}s"
+ "fetchCuttlefishAfterReset: refreshed Cuttlefish opinion successfully"
+ "fetchRecoverableTlkshares for peer %s failed: %{public}s"
+ "included=%{public,signpost.telemetry:number1,name=included}d excluded=%{public,signpost.telemetry:number2,name=excluded}d enableTelemetry=YES "
+ "join(voucherData:voucherSig:ckksKeys:tlkShares:preapprovedKeys:altDSID:flowID:deviceSessionID:canSendMetrics:distrustEveryoneOnJoin:reply:)"
+ "joinWithSpecificUser:voucherData:voucherSig:ckksKeys:tlkShares:preapprovedKeys:flowID:deviceSessionID:canSendMetrics:distrustEveryoneOnJoin:reply:"
+ "machineID=%{public}s %{public}s: matched record MID=%{public}s, stableID=%{public}s, status=%{public}lld, requested stableTrustedDeviceID=%{public}s"
+ "machineID=%{public}s not found on list, requested stableTrustedDeviceID=%{public}s, knownMachines.count=%{public}ld"
+ "metrics_cpu"
+ "metrics_memory"
+ "not enforcing idms list changes; allowing machineID=%{public}s, stableTrustedDeviceID=%{public}s"
+ "not explicitly allowed"
+ "onDeallocation"
+ "onqueueMachineAllowedByIDMS returned false"
+ "onqueueMachineAllowedByIDMS: multiple (%{public}ld) records for machineID=%{public}s; records=[%{public}s]"
+ "onqueueMachineAllowedByIDMS: requested machineID=%{public}s, stableTrustedDeviceID=%{public}s"
+ "peerIDsThatTrustRecoveryKeys:canIntroducePeer:stableInfo:error:"
+ "perform(updateTrust)"
+ "perform(updateTrust): error getting ego peer: %{public}@"
+ "perform(updateTrust): response contains only ego peer echo, skipping re-evaluation"
+ "preapprovals=%{public,signpost.telemetry:number1,name=preapprovals}d enableTelemetry=YES "
+ "prepare: dropping stable trusted device ID because the feature is not enabled"
+ "prepareInheritancePeer: dropping stable trusted device ID because the feature is not enabled"
+ "rss_delta_kb=%{public,signpost.telemetry:number1,name=rss_delta_kb}lld peak_kb=%{public,signpost.telemetry:number2,name=peak_kb}lld enableTelemetry=YES "
+ "self peer disallowed via %{public}s: machineID=%{public}s, stableID=%{public}s%{public}s"
+ "success=%{public,signpost.telemetry:number1,name=success}d enableTelemetry=YES "
+ "task_cpu_us=%{public,signpost.telemetry:number1,name=task_cpu_us}lld thread_cpu_us=%{public,signpost.telemetry:number2,name=thread_cpu_us}lld enableTelemetry=YES "
+ "testOnlyEgoPeerEchoShortCircuitTaken"
+ "total_peers=%{public,signpost.telemetry:number1,name=total_peers}d vouchers=%{public,signpost.telemetry:number2,name=vouchers}d enableTelemetry=YES "
+ "updateTrustIfNeeded"
+ "v56@0:8@\"TPSpecificUser\"16@\"NSString\"24@\"NSString\"32@\"NSArray\"40@?<v@?@\"NSData\"@\"NSData\"@\"NSArray\"B@\"TrustedPeersHelperTLKRecoveryResult\"@\"NSError\">48"
+ "v96@0:8@\"TPSpecificUser\"16@\"NSData\"24@\"NSData\"32@\"NSArray\"40@\"NSArray\"48@\"NSArray\"56@\"NSString\"64@\"NSString\"72B80B84@?<v@?@\"NSString\"@\"NSArray\"@\"TPSyncingPolicy\"@\"NSError\">88"
+ "v96@0:8@16@24@32@40@48@56@64@72B80B84@?88"
- "Error creating voucher using recovery key set: %{public}s"
- "Failed to get peer that trusts RK: %{public}@"
- "Peer machineID: %{public}s, Stable ID:  %{public}s, is unknown, making it disallowed"
- "Updating machine ID from %{public}s to %{public}s (stable ID matched, MID rolled)"
- "User initiated removal! machine ID last modified %{public}s; distrusting Machine ID: %{public}s, Stable ID: %{public}s, Status: %{public}lld"
- "dynamicInfoForJoiningPeerID:peerPermanentInfo:peerStableInfo:sponsorID:preapprovedKeys:signingKeyPair:currentMachineIDs:requiresTDLFetch:error:"
- "join(voucherData:voucherSig:ckksKeys:tlkShares:preapprovedKeys:altDSID:flowID:deviceSessionID:canSendMetrics:reply:)"
- "joinWithSpecificUser:voucherData:voucherSig:ckksKeys:tlkShares:preapprovedKeys:flowID:deviceSessionID:canSendMetrics:reply:"
- "machineID %{public}s not found on list"
- "not enforcing idms list changes; allowing %{public}s"
- "updateTrustIfNeeded: unable to compute a new syncing policy: %{public}s"
- "v56@0:8@\"TPSpecificUser\"16@\"NSString\"24@\"NSString\"32@\"NSArray\"40@?<v@?@\"NSData\"@\"NSData\"@\"NSArray\"@\"TrustedPeersHelperTLKRecoveryResult\"@\"NSError\">48"
- "v92@0:8@\"TPSpecificUser\"16@\"NSData\"24@\"NSData\"32@\"NSArray\"40@\"NSArray\"48@\"NSArray\"56@\"NSString\"64@\"NSString\"72B80@?<v@?@\"NSString\"@\"NSArray\"@\"TPSyncingPolicy\"@\"NSError\">84"
```
