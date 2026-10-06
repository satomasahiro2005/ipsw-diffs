## ServiceDiscovery

> `/System/Library/PrivateFrameworks/ServiceDiscovery.framework/ServiceDiscovery`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x191f54` | `0x1a1ffc` | **`+0x100a8`** |
| `__TEXT.__eh_frame` | `0xc12c` | `0xcf44` | **`+0xe18`** |
| `__TEXT.__const` | `0xa1ac` | `0xa94c` | **`+0x7a0`** |
| `__DATA.__bss` | `0x8a30` | `0x8f40` | **`+0x510`** |
| `__TEXT.__unwind_info` | `0x4420` | `0x4708` | **`+0x2e8`** |
| `__TEXT.__swift5_capture` | `0x1508` | `0x134c` | **`-0x1bc`** |
| `__AUTH_CONST.__const` | `0x5b10` | `0x5980` | **`-0x190`** |
| `__TEXT.__swift5_typeref` | `0x31e5` | `0x336b` | **`+0x186`** |
| `__TEXT.__constg_swiftt` | `0x230c` | `0x2440` | **`+0x134`** |
| `__TEXT.__swift5_fieldmd` | `0x1e24` | `0x1f44` | **`+0x120`** |
| `__AUTH_CONST.__objc_const` | `0x3380` | `0x3488` | **`+0x108`** |
| `__TEXT.__cstring` | `0x2965` | `0x2a65` | **`+0x100`** |
| `__TEXT.__swift5_reflstr` | `0x1859` | `0x1949` | **`+0xf0`** |
| `__TEXT.__swift_as_cont` | `0x9a8` | `0xa70` | **`+0xc8`** |
| `__DATA.__data` | `0x1878` | `0x1908` | **`+0x90`** |
| `__DATA_DIRTY.__data` | `0x3108` | `0x3188` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x1578` | `0x15e0` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x6cc6` | `0x6c66` | **`-0x60`** |
| `__TEXT.__swift5_assocty` | `0x2d0` | `0x330` | **`+0x60`** |
| `__TEXT.__swift_as_ret` | `0x538` | `0x594` | **`+0x5c`** |
| `__TEXT.__swift_as_entry` | `0x4c4` | `0x518` | **`+0x54`** |
| `__DATA_DIRTY.__objc_data` | `0x638` | `0x5f8` | **`-0x40`** |
| `__TEXT.__swift5_acfuncs` | `0x294` | `0x2d0` | **`+0x3c`** |
| `__TEXT.__swift5_proto` | `0x684` | `0x6ac` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x204` | `0x21c` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x708` | `0x6f8` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x920` | `0x928` | **`+0x8`** |

### Other Changes

```diff

-747.100.2.0.0
+751.100.2.0.0

-  Functions: 4740
-  Symbols:   1720
-  CStrings:  880
+  Functions: 4926
+  Symbols:   1758
+  CStrings:  881
Symbols:
+ ___swift_closure_destructor.11Tm
+ ___swift_closure_destructor.158Tm
+ ___swift_closure_destructor.16Tm
+ ___swift_closure_destructor.26Tm
+ ___swift_closure_destructor.31Tm
+ ___swift_closure_destructor.33Tm
+ ___swift_closure_destructor.39Tm
+ ___swift_closure_destructor.6Tm
+ ___swift_closure_destructor.82Tm
+ ___swift_memcpy153_8
+ ___swift_memcpy56_8
+ ___swift_memcpy65_8
+ _associated conformance 16ServiceDiscovery0aB6ClientC15ActivationState33_731BA4132486D8DFB119317E4A74F756LLOSHAASQ
+ _associated conformance 16ServiceDiscovery16DeviceChangeTypeVSHAASQ
+ _associated conformance 16ServiceDiscovery16DeviceChangeTypeVs10SetAlgebraAASQ
+ _associated conformance 16ServiceDiscovery16DeviceChangeTypeVs10SetAlgebraAAs25ExpressibleByArrayLiteral
+ _associated conformance 16ServiceDiscovery16DeviceChangeTypeVs9OptionSetAASY
+ _associated conformance 16ServiceDiscovery16DeviceChangeTypeVs9OptionSetAAs0G7Algebra
+ _get_enum_tag_for_layout_string 16ServiceDiscovery0aB6ClientC18XPCConnectionState33_731BA4132486D8DFB119317E4A74F756LLO
+ _get_enum_tag_for_layout_string 16ServiceDiscovery16MemberIdentifierVSg05localD0_ShyACG7memberstSg
+ _get_witness_table SlRzlSay16ServiceDiscovery16MemberIdentifierV11ContactInfoOGSlHPyHC
+ _swift_getAtKeyPath
+ _swift_getKeyPath
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _symbolic SS________________pIetMHgTnTgzo_ 16ServiceDiscovery16DeviceChangeTypeV AA15XPCServiceActorC s5ErrorP
+ _symbolic SS_____x______p_____Rz_____RzlIetMHgTnTgzo_ 16ServiceDiscovery16DeviceChangeTypeV s5ErrorP 11Distributed01_G9ActorStubP AA19XPCServiceInterfaceP
+ _symbolic SS_____x______p_____RzlIetWHgTnTgzo_ 16ServiceDiscovery16DeviceChangeTypeV s5ErrorP AA19XPCServiceInterfaceP
+ _symbolic ScCySb_____G s5NeverO
+ _symbolic _____ 16ServiceDiscovery0aB6ClientC15ActivationState33_731BA4132486D8DFB119317E4A74F756LLO
+ _symbolic _____ 16ServiceDiscovery0aB6ClientC18XPCConnectionState33_731BA4132486D8DFB119317E4A74F756LLO
+ _symbolic _____ 16ServiceDiscovery16DeviceChangeTypeV
+ _symbolic _____ 16ServiceDiscovery26CloudKitTrustCircleManagerC15LocalShareStateV
+ _symbolic _____ 16ServiceDiscovery26CloudKitTrustCircleManagerC16RemoteShareStateV
+ _symbolic _____ 16ServiceDiscovery28TrustCircleMembershipTrackerV
+ _symbolic _____7service______7sessiont 16ServiceDiscovery20$XPCServiceInterfaceC 14XPCDistributed9XPCSystemC7SessionC
+ _symbolic _____Sg 16ServiceDiscovery16MemberIdentifierV11ContactInfoO
+ _symbolic _____Sg 16ServiceDiscovery26CloudKitTrustCircleManagerC15LocalShareStateV
+ _symbolic _____Sg15localIdentifier_ShyAAG7memberstSg 16ServiceDiscovery16MemberIdentifierV
+ _symbolic ______SSt 16ServiceDiscovery0A8ProviderV
+ _symbolic _____ySo10CKRecordIDCSo0A0C_G SD5IndexV
+ _symbolic _____y_____G 11Distributed18RemoteCallArgumentV 16ServiceDiscovery16DeviceChangeTypeV
+ _symbolic _____y______SStG s23_ContiguousArrayStorageC 16ServiceDiscovery0D8ProviderV
+ _type_layout_string 16ServiceDiscovery0aB6ClientC18XPCConnectionState33_731BA4132486D8DFB119317E4A74F756LLO
+ _type_layout_string 16ServiceDiscovery16DeviceChangeTypeV
+ _type_layout_string 16ServiceDiscovery26CloudKitTrustCircleManagerC15LocalShareStateV
+ _type_layout_string 16ServiceDiscovery26CloudKitTrustCircleManagerC16RemoteShareStateV
+ _type_layout_string 16ServiceDiscovery28TrustCircleMembershipTrackerV
- ___swift_closure_destructor.201Tm
- ___swift_closure_destructor.22Tm
- ___swift_closure_destructor.25Tm
- ___swift_closure_destructor.5Tm
- ___swift_closure_destructor.65Tm
- ___swift_closure_destructor.9Tm
- ___swift_memcpy144_8
- _os_unfair_lock_assert_owner
- _symbolic _____Sg 16ServiceDiscovery20$XPCServiceInterfaceC
CStrings:
+ "$s16ServiceDiscovery20$XPCServiceInterfaceC13deviceChanged_7changesySS_AA16DeviceChangeTypeVtYaKFTE"
+ "%s is newer than %s"
+ "%s is newer than %s - equal"
+ "%s is not newer than %s"
+ "%s is not strictly newer than %s"
+ "%s is strictly newer than %s"
+ "Activation failed"
+ "Cannot process device %s change %s: not activated"
+ "Cannot process lost device %s: not activated"
+ "Deferring share participant sync for %s till server state is received"
+ "Did not find device info"
+ "INVALID_DEVICE_ID"
+ "Inconsistent ServiceDirectory: invalid device ID"
+ "Invitation #%hhu was rejected by %{sensitive}s in scope %s, cannot retry: local invitation: #%hhu, current: #%hhu"
+ "Invitation #%hhu was rejected by %{sensitive}s in scope %s, retrying (current: #%hhu)"
+ "Membership unchanged, skipping update"
+ "Membership updated for %s: %ld member(s), +%ld -%ld"
+ "Missing membership update for %s, skipping share participant sync"
+ "No delegate to forward device change"
+ "No known remote share for corrupted zone %s, ignoring local reset"
+ "Queued local record delete %s at index %ld schema %ld"
+ "Queueing corrupted %s share in %s for deletion, awaiting re-invitation"
+ "Received stale rejection (#%hhu < #%hhu) from %{sensitive}s in scope %s, re-sending current invitation"
+ "Remote payload contains invalid device ID"
+ "Service Directory for %s is newer than existing discovered peer %s, received via %s:%s"
+ "Skipping %s from %{sensitive}s in %s, token regeneration request exists"
+ "Unable to consume Service Directory for %s: existing discovered peer %s has newer payload"
+ "Updating local device ID from %s to %s"
+ "[%s] Cannot process change %s to device %s: no service provider"
+ "[%s] Cannot process change %s to device %s: not activated"
+ "[%s] Cannot process lost device %s: no service provider"
+ "[%s] Cannot process lost device %s: not activated"
+ "[%s] Processing change %s for device %s"
+ "deviceChanged(_:changes:)"
+ "leaveCorruptedShares(_:)"
+ "remoteappintents"
- "%s is newer than %s - ordering"
- "%s is newer than %s - rollover"
- "%s is not newer than %s - ordering"
- "%s is not newer than %s - surpassed"
- "Cannot process lost device: not activated"
- "Deferring share participant sync till server state is received"
- "Deleted local payload for %s at index %ld schema %ld"
- "Did not find device ID"
- "Expiration timer cancelled"
- "Expiration timer fired"
- "Failed to determine home member %{sensitive}s, skipping"
- "IDSCopyLocalDeviceUniqueID returned nil, skipping update"
- "Ignoring stale rejection (%hhu < %hhu) from %{sensitive}s in scope %s"
- "Invitation #%hhu was rejected by %{sensitive}s in scope %s, retrying"
- "Local invitation #%hhu is older than rejected invitation #%hhu from %{sensitive}s in scope %s, requesting regeneration"
- "Membership updated for %s: %ld member(s)"
- "Missing membership update for scope %s, skipping share participant sync"
- "Missing state for scope %s, skipping invitation sync"
- "Missing state for scope %s, skipping remote shares sync"
- "Missing state for scope %s, skipping share participant sync"
- "Missing state for scope %s, skipping share sync"
- "MockA2DPActivity"
- "No known remote share for corrupted zone %s, ignoring"
- "Personal scope update: %ld peer(s)"
- "Queueing %s share from %{sensitive}s for deletion, awaiting re-invitation"
- "Scope %s removed during invitation processing, aborting remote share sync"
- "Scope %s removed during participant lookup, aborting share participant sync"
- "Scope %s removed during processing of incoming invitation, aborting"
- "Scope %s removed during remote share sync, aborting"
- "Share already has invitation state for %{sensitive}s, overwriting"
- "Starting expiration timer"
- "Stopping expiration timer"
- "Unable to delete local payloads as there is no confirmed registration index"
- "[%s] Cannot process lost device: no service provider"
- "[%s] Cannot process lost device: not activated"
```
