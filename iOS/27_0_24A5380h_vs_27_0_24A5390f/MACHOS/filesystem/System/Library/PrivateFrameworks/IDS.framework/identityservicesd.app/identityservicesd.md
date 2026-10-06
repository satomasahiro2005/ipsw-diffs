## identityservicesd

> `/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/identityservicesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xac2d88` | `0xac9158` | **`+0x63d0`** |
| `__TEXT.__oslogstring` | `0x88a8d` | `0x8906d` | **`+0x5e0`** |
| `__TEXT.__cstring` | `0x59a3e` | `0x59e2e` | **`+0x3f0`** |
| `__TEXT.__const` | `0x6e590` | `0x6e930` | **`+0x3a0`** |
| `__TEXT.__objc_methname` | `0x7bac5` | `0x7be45` | **`+0x380`** |
| `__TEXT.__objc_stubs` | `0x4a120` | `0x4a380` | **`+0x260`** |
| `__TEXT.__eh_frame` | `0x1281c` | `0x129e4` | **`+0x1c8`** |
| `__DATA_CONST.__const` | `0x30dd0` | `0x30f00` | **`+0x130`** |
| `__TEXT.__objc_methlist` | `0x2c414` | `0x2c53c` | **`+0x128`** |
| `__DATA_CONST.__cfstring` | `0x365c0` | `0x366e0` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x17018` | `0x17110` | **`+0xf8`** |
| `__TEXT.__swift5_reflstr` | `0x9085` | `0x9175` | **`+0xf0`** |
| `__DATA.__objc_const` | `0x52520` | `0x525f8` | **`+0xd8`** |
| `__DATA.__bss` | `0x24dd0` | `0x24ea0` | **`+0xd0`** |
| `__DATA.__objc_selrefs` | `0x16dd0` | `0x16e88` | **`+0xb8`** |
| `__TEXT.__gcc_except_tab` | `0x2434c` | `0x243f8` | **`+0xac`** |
| `__TEXT.__constg_swiftt` | `0x7f50` | `0x7fcc` | **`+0x7c`** |
| `__TEXT.__auth_stubs` | `0x7700` | `0x7770` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x99e8` | `0x9a58` | **`+0x70`** |
| `__DATA.__objc_data` | `0xf7a8` | `0xf810` | **`+0x68`** |
| `__DATA_CONST.__objc_dictobj` | `0x50` | `0xa0` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0xa1a8` | `0xa1f6` | **`+0x4e`** |
| `__DATA_CONST.__got` | `0x45d0` | `0x4618` | **`+0x48`** |
| `__DATA_CONST.__objc_arraydata` | `0x588` | `0x5c8` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x3b90` | `0x3bc8` | **`+0x38`** |
| `__DATA.__data` | `0x167f0` | `0x16820` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0xed8` | `0xf00` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x4c0` | `0x4dc` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x2f0` | `0x30c` | **`+0x1c`** |
| `__DATA_CONST.__objc_intobj` | `0x1ab8` | `0x1ad0` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x2180` | `0x2198` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x2d0` | `0x2e8` | **`+0x18`** |
| `__TEXT.__swift5_acfuncs` | `0xb4` | `0xc8` | **`+0x14`** |
| `__TEXT.__swift5_builtin` | `0x21c` | `0x230` | **`+0x14`** |
| `__TEXT.__objc_methtype` | `0x143e9` | `0x143f9` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x70` | `0x80` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x3508` | `0x3510` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x100c` | `0x1010` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x948` | `0x94c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__ustring`

### Other Changes

```diff

-1998.100.2.0.0
+2000.100.2.2.1

-  Functions: 32339
-  Symbols:   2949
-  CStrings:  32993
+  Functions: 32383
+  Symbols:   2951
+  CStrings:  33048
Symbols:
+ _IDSGroupSessionCapabilityTerminateAutomatically
+ _OBJC_CLASS_$_NSISO8601DateFormatter
CStrings:
+ " staticKeyEnforced="
+ "%@ - Could not find session with uniqueID %@ to request media key material, ignoring..."
+ "%@ Not prompting TTR because isNearby:NO"
+ "%@, Error in queue stats: {pendingOutgoingBytes:%lu} -> {fixedPendingOutgoingBytes:%lu}, {maxQueueSize:%lu}, {inflightMessageCount:%lu}"
+ "-[IDSDSession link:didFinishConvergenceForRelaySessionID:]_block_invoke"
+ "22:11:10"
+ "B20@0:8C16"
+ "IDSDSession.OutgoingBlob"
+ "IDSNWSocketPairConnection: _startOutgoingStallTimer: %@ stall time: %f seconds"
+ "Jul 14 2026"
+ "Not re-adding user-disabled alias from registered URIs {alias: %@}"
+ "Not re-selecting user-disabled alias on vetted refresh {alias: %@, reason: %ld}"
+ "Preserving user-intent unselect reason, not downgrading {alias: %@, keeping: %ld, ignoring: %ld}"
+ "RPOptionStatusFlags"
+ "TB,N,V_terminateAutomatically"
+ "Throttling session setup after %lu seconds"
+ "Validation Results"
+ "_connectQRDirectlyToClientChannel: strongSelf: %p, terminateAutomatically: %@, not ending session because we have not been told to."
+ "_connectSocketDescriptor: strongSelf: %p, terminateAutomatically: %@, not ending session because we have not been told to"
+ "_fixPendingOutgoingBytesForClass:"
+ "_getThrottleDelaySeconds"
+ "_isAliasUserDisabled:"
+ "_isUserIntentUnselectReason:"
+ "_setupNWConnectionReadWrite: strongSelf: %p, terminateAutomatically: %@, not ending session because we have not been told to"
+ "_terminateAutomatically"
+ "_userIntentKeyForAlias:"
+ "fixPendingStatistics:forDataProtectionClass:"
+ "getThrottlingThresholdForUTunTTR"
+ "identityservicesd detected an issue with a UTun connection %@.\n\nissue time (local): %@\n\nissue type: %d\n\n%@\n\nPlease attach a sysdiagnose of both *phone and watch* taken near the time of this prompt."
+ "ids-throttle-delay-seconds"
+ "ids-utun-ttr-throttling-threshold"
+ "ignoring didDisconnectOverCloud for %@ from stale link (no longer the current GlobalLink for this session)."
+ "ignoring didFailToConnectOverCloud for %@ from stale link (no longer the current GlobalLink for this session)."
+ "initWithQueryID:uris:fromURI:service:eventTrace:"
+ "invalidateMediaKeyMaterialInFrameworkCache:"
+ "ktQueryOperation"
+ "ktValidationOperation"
+ "localTimeZone"
+ "noteIDSQueryStartWithUris:fromURI:service:parentEventTrace:"
+ "noteItemWithCount:count:shouldLog:"
+ "recvMediaKeyMaterialForFrameworkCache for session %@. MKM count=%lu"
+ "recvMediaKeyMaterialForFrameworkCache:"
+ "requestMediaKeyMaterialForGroup %@, for %lu participants %@"
+ "requestMediaKeyMaterialForGroup:participants:"
+ "requestMediaKeyMaterialForGroup:participants:messageContext:"
+ "requestMediaKeyMaterialForParticipantIDs:"
+ "session:didReceiveMediaKeyMaterial:"
+ "session:shouldInvalidateMediaKeyMaterialByKeyIndexes:"
+ "setFormatOptions:"
+ "setTerminateAutomatically:"
+ "shouldThrottleUTunTTRAfterDiceRoll"
+ "shouldThrottleUTunTTRAfterDiceRoll: currentServerBagPercentage (%lu), diceRoll (%u)"
+ "terminateAutomatically"
+ "triggerUTunTTR: shouldThrottleUTunTTRAfterDiceRoll: %@"
+ "updateAVCPlainBlob:"
+ "updateAVCPlainBlob: new blob: %@"
+ "updateCapabilities: clientChannelDisabled=%{bool}d, lightweight=%{bool}d, managedMediaKeys=%{bool}d, terminateAutomatically=%{bool}d, channelAction=%s"
+ "updateMirageHandshakeBlob:"
+ "updateMirageHandshakeBlob: new blob: %@"
+ "updateOutgoingBlob(_:)"
+ "updateOutgoingBlob: avcPlain, byteCount=%ld"
+ "updateOutgoingBlob: mirageHandshake, byteCount=%ld"
+ "updateOutgoingBlob: participantData, byteCount=%ld"
+ "updateOutgoingBlob: participantInfo, byteCount=%ld"
+ "updateOutgoingBlob: unknown blob kind '%{public}s', ignoring"
- "16:49:52"
- "IDSNWSocketPairConnection: _startOutgoingStallTimer: stall time: %f seconds"
- "Jun 27 2026"
- "Throttling session setup after %d seconds"
- "_connectQRDirectlyToClientChannel: strongSelf: %p, not ending session because we have not been told to."
- "_connectSocketDescriptor: strongSelf: %p, not ending session because we have not been told to"
- "_setupNWConnectionReadWrite: strongSelf: %p, not ending session because we have not been told to"
- "identityservicesd detected an issue with a UTun connection %@.\n\nissue type: %d\n\n%@\n\nPlease attach a sysdiagnose of both *phone and watch* taken near the time of this prompt."
- "noteItemWithCount:count:"
- "updateCapabilities: clientChannelDisabled=%{bool}d, lightweight=%{bool}d, managedMediaKeys=%{bool}d, channelAction=%s"
```
