## seserviced

> `/usr/libexec/seserviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4883f8` | `0x488f80` | **`+0xb88`** |
| `__TEXT.__cstring` | `0x226f9` | `0x22a31` | **`+0x338`** |
| `__TEXT.__oslogstring` | `0x31e42` | `0x320f9` | **`+0x2b7`** |
| `__DATA_CONST.__cfstring` | `0x88c0` | `0x8ac0` | **`+0x200`** |
| `__TEXT.__const` | `0x14e68` | `0x15038` | **`+0x1d0`** |
| `__DATA.__bss` | `0x13f00` | `0x14000` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x1962d` | `0x196ed` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0xe7e0` | `0xe8a0` | **`+0xc0`** |
| `__TEXT.__objc_methtype` | `0x7f37` | `0x7fe6` | **`+0xaf`** |
| `__TEXT.__swift5_typeref` | `0x58f2` | `0x5990` | **`+0x9e`** |
| `__DATA_CONST.__const` | `0x15b38` | `0x15bc8` | **`+0x90`** |
| `__DATA.__data` | `0xe4c4` | `0xe534` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x6390` | `0x63fc` | **`+0x6c`** |
| `__TEXT.__unwind_info` | `0xaba8` | `0xabf8` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x5e48` | `0x5e88` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x16064` | `0x1609c` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x4b00` | `0x4b30` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x64fa` | `0x652a` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x33e8` | `0x33c4` | **`-0x24`** |
| `__DATA.__objc_const` | `0x19228` | `0x19208` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x5120` | `0x5100` | **`-0x20`** |
| `__DATA.__common` | `0x848` | `0x838` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x28a8` | `0x2898` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0xfd8` | `0xfe8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x7194` | `0x71a4` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x658` | `0x664` | **`+0xc`** |
| `__DATA.__objc_data` | `0x6c10` | `0x6c08` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xcf0` | `0xcf8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2118` | `0x2120` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xad8` | `0xae0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x32dc` | `0x32e0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-70.37.0.0.0
+70.39.1.0.0

-  Functions: 13155
+  Functions: 13195

-  CStrings:  11601
+  CStrings:  11639
Symbols:
+ _$s15Synchronization5MutexVMa
+ _$s15Synchronization5_CellVMn
+ _SESEndPointRevokeWithReason
+ __SESEndPointDeleteWithReason
- _SESEndPointDelete
- _SESEndPointRevoke
- __SESEndPointDeleteWithSession
- _kmlUtilUserVisibleLen
CStrings:
+ "  Will create EP %{public}s in DB (active %{bool}d)"
+ "  Will delete EP %{public}s from DB (reason %{public}s)"
+ "  Will delete EP %{public}s from SE (reason %{public}s)"
+ "  Will revoke EP %{public}s in DB (reason %{public}s)"
+ "%s : %i : Clearing pending pairing creation block and recent removals"
+ "%s : %i : Not creating pending pairing; creation is blocked (too many pending pairings removed without a key)"
+ "%s : %i : Not recording pending pairing removal; ignoring creation block per set UD"
+ "%s : %i : Overriding creation block due to debug user default!"
+ "%s : %i : Pending pairing block strategy changed (%ld -> %ld); unblocking and resetting removal tracking"
+ "%s : %i : Pending pairing removal threshold reached; blocking further pending pairing creation (strategy %ld)"
+ "%s : %i : Pending pairing removed without a key (%lu/%lu within %lu-day window)"
+ "%s : %i : Pruned %lu expired pending pairing removal(s) from the creation-block window"
+ "-[KmlEndpointManager localDeleteKey:]"
+ "-[KmlEndpointManager revokeOrDeleteKeyWithReason:error:]"
+ "-[KmlFriendSharingManager deleteKey:]"
+ "-[KmlKeyManagementSession deleteKey:reason:callback:]_block_invoke"
+ "-[KmlKeyManagementSession localDeleteKey:reason:callback:]_block_invoke"
+ "-[KmlKeySharingSession createSharingInvitationsForKeyIdentifier:friendIdentifier:auth:deviceTransfer:ourBindingAttestation:config:completionHandler:]_block_invoke"
+ "-[KmlOwnerSharingManager startSharingKeyWithAuth:deviceTransfer:ourBindingAttestation:config:]_block_invoke"
+ "-[KmlPendingPairingRecordsUpdater cleanupExpiredRemovalsWithoutKey_sync:]"
+ "-[KmlPendingPairingRecordsUpdater clearPendingPairingCreationBlock_sync]"
+ "-[KmlPendingPairingRecordsUpdater isPendingPairingCreationBlocked_sync]"
+ "-[KmlPendingPairingRecordsUpdater recordRemovalWithoutKey_sync]"
+ "-[SESEndpointAndKeyXPCServer(SEEndPointXPC) deleteEndPointWithProxy:identifier:mustBeTerminated:reason:reply:]"
+ "-[SESEndpointAndKeyXPCServer(SEEndPointXPC) listEndPointsWithProxy:reconciliation:reply:]"
+ "-[SESEndpointAndKeyXPCServer(SEEndPointXPC) revokeEndPointWithIdentifier:nonce:metaData:reason:reply:]"
+ "B32@?0@\"NSDate\"8Q16^B24"
+ "Database reconciled %d required %d proxy %d skip %d"
+ "FailedAlishaCreation"
+ "FailedCreation"
+ "FailedHydraCreation"
+ "FailedLocalCreation"
+ "FailedLyonCreation"
+ "FailedLyonHydraCreation"
+ "KMLPairDanglingKey"
+ "KMLPairFailed"
+ "KMLShareCancelled"
+ "KMLShareDanglingKey"
+ "KMLShareFailed"
+ "PTA%d Sunsprite%d"
+ "Queuing server connection for revoked endpoint (success %d)"
+ "RevokedInSEActiveInDB"
+ "RevokedInSENotInDB"
+ "RevokedInSERevokedInDB"
+ "SESEndPointListWithSession (skip reconciliation) hung during general stats reporting"
+ "TaskID %@"
+ "Vv40@0:8@\"<SEProxyInterface>\"16q24@?<v@?@\"NSArray\"@\"NSError\">32"
+ "Vv40@0:8@\"NSString\"16@\"NSString\"24@?<v@?@\"NSData\"@\"NSError\">32"
+ "Vv40@0:8@16q24@?32"
+ "Vv52@0:8@\"<SEProxyInterface>\"16@\"NSString\"24B32@\"NSString\"36@?<v@?B@\"NSError\">44"
+ "Vv52@0:8@16@24B32@36@?44"
+ "Vv56@0:8@\"NSString\"16@\"NSData\"24@\"NSData\"32@\"NSString\"40@?<v@?@\"NSData\"@\"NSError\">48"
+ "Vv68@0:8@\"NSString\"16@\"NSString\"24@\"NSData\"32B40@\"NSData\"44@\"NSArray\"52@?<v@?@\"NSArray\"@\"NSError\">60"
+ "Vv68@0:8@16@24@32B40@44@52@?60"
+ "_deviceTransfer"
+ "_endPointsForClientInfo:handle:error:"
+ "_recentRemovalsWithoutKey"
+ "counters"
+ "createSharingInvitationsForKeyIdentifier:friendIdentifier:auth:deviceTransfer:ourBindingAttestation:config:completionHandler:"
+ "creationBlockParamsForStrategy:threshold:windowInDays:"
+ "databaseServiceWithProxy:reconciliation:reason:reply:"
+ "deleteEndPointWithProxy:identifier:mustBeTerminated:reason:reply:"
+ "deleteKey:reason:callback:"
+ "elapsedTimeEvents"
+ "iOS (27.0) - SecureElementService-70.39.1"
+ "ignorePendingPairingCreationBlock"
+ "indexesOfObjectsPassingTest:"
+ "kmlPendingPairingCreationBlockedStrategy"
+ "kmlPendingPairingRecentRemovalsWithoutKey"
+ "listEndPointsWithProxy:reconciliation:reply:"
+ "localDeleteKey:reason:callback:"
+ "logDeleteWithKeyID:useCase:trigger:reason:"
+ "logRevokeWithKeyID:useCase:trigger:reason:"
+ "pendingPairingCreationBlockStrategy"
+ "revocationReason"
+ "revokeEndPointWithIdentifier:nonce:metaData:reason:reply:"
+ "setRevocationReason:"
+ "terminationReason"
+ "v48@0:8@16q24@32@40"
+ "\xf0\x81"
- "  Will create EP %{public}s in DB (active: %{bool}d)"
- "  Will delete EP %{public}s from DB"
- "  Will delete EP %{public}s from SE"
- "  Will revoke EP %{public}s in DB"
- "%s : %i : Asking seld to initiate delete with TSM"
- "%s : %i : Using car brand as vehicle name: %@"
- "%s : %i : Using car model as vehicle name: %@"
- "-[KmlEndpointManager localDeleteKey]"
- "-[KmlEndpointManager revokeOrDeleteKeyWithError:]"
- "-[KmlFriendSharingManager deleteKey]"
- "-[KmlKeyManagementSession deleteKey:callback:]_block_invoke"
- "-[KmlKeyManagementSession localDeleteKey:callback:]_block_invoke"
- "-[KmlKeySharingSession createSharingInvitationsForKeyIdentifier:friendIdentifier:auth:ourBindingAttestation:config:completionHandler:]_block_invoke"
- "-[KmlOwnerSharingManager startSharingKeyWithAuth:ourBindingAttestation:config:]_block_invoke"
- "-[SESEndpointAndKeyXPCServer(SEEndPointXPC) deleteEndPointWithProxy:identifier:mustBeTerminated:reply:]"
- "-[SESEndpointAndKeyXPCServer(SEEndPointXPC) listEndPointsWithProxy:mandatoryReconciliation:reply:]"
- "-[SESEndpointAndKeyXPCServer(SEEndPointXPC) revokeEndPointWithIdentifier:nonce:metaData:reply:]"
- "Database reconciled %d required %d proxy %d"
- "SESEndPointListWithSession hung during general stats reporting"
- "Vv32@0:8@\"NSString\"16@?<v@?@\"NSData\"@\"NSError\">24"
- "Vv36@0:8@\"<SEProxyInterface>\"16B24@?<v@?@\"NSArray\"@\"NSError\">28"
- "Vv36@0:8@16B24@?28"
- "Vv44@0:8@\"<SEProxyInterface>\"16@\"NSString\"24B32@?<v@?B@\"NSError\">36"
- "Vv64@0:8@\"NSString\"16@\"NSString\"24@\"NSData\"32@\"NSData\"40@\"NSArray\"48@?<v@?@\"NSArray\"@\"NSError\">56"
- "carModel"
- "countsKeyedByCountEvents"
- "createSharingInvitationsForKeyIdentifier:friendIdentifier:auth:ourBindingAttestation:config:completionHandler:"
- "currentElapsedTimeEvent"
- "databaseServiceWithProxy:isReconcileRequired:reason:reply:"
- "deleteEndPointWithProxy:identifier:mustBeTerminated:reply:"
- "deleteKey:callback:"
- "elapsedTimesKeyedByEvents"
- "iOS (27.0) - SecureElementService-70.37"
- "invalidationReason"
- "listEndPointsWithProxy:mandatoryReconciliation:reply:"
- "localDeleteKey:callback:"
- "logDeleteWithKeyID:useCase:trigger:"
- "logRevokeWithKeyID:useCase:trigger:"
- "revokeEndPointWithIdentifier:nonce:metaData:reply:"
- "sessionElapsedTimeEvent"
- "v44@0:8@16B24@28@?36"
- "\xf0q"
```
