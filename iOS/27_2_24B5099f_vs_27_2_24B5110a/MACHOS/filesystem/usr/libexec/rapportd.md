## rapportd

> `/usr/libexec/rapportd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a6bec` | `0x1a92d0` | **`+0x26e4`** |
| `__TEXT.__cstring` | `0x3d716` | `0x3e016` | **`+0x900`** |
| `__TEXT.__objc_methname` | `0x1e7c0` | `0x1eac0` | **`+0x300`** |
| `__DATA_CONST.__cfstring` | `0xa180` | `0xa400` | **`+0x280`** |
| `__TEXT.__objc_stubs` | `0x14400` | `0x145c0` | **`+0x1c0`** |
| `__DATA_CONST.__const` | `0x86f8` | `0x88a0` | **`+0x1a8`** |
| `__DATA.__bss` | `0x47f0` | `0x4980` | **`+0x190`** |
| `__TEXT.__const` | `0x6640` | `0x6700` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x2550` | `0x2600` | **`+0xb0`** |
| `__DATA.__objc_selrefs` | `0x6570` | `0x6600` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0xada8` | `0xae28` | **`+0x80`** |
| `__DATA.__objc_const` | `0x12cb0` | `0x12d18` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x5ca8` | `0x5d10` | **`+0x68`** |
| `__TEXT.__eh_frame` | `0x4c44` | `0x4c84` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0xf3c` | `0xf70` | **`+0x34`** |
| `__TEXT.__swift5_reflstr` | `0xfc4` | `0xff4` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0xe60` | `0xe84` | **`+0x24`** |
| `__TEXT.__auth_stubs` | `0x3a30` | `0x3a50` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x3662` | `0x3682` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x190` | `0x1a8` | **`+0x18`** |
| `__DATA.__data` | `0x3e08` | `0x3e18` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1d28` | `0x1d38` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x17ca` | `0x17d8` | **`+0xe`** |
| `__TEXT.__swift5_proto` | `0x1cc` | `0x1d8` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x11f8` | `0x1200` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xfc` | `0x100` | **`+0x4`** |

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
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-751.200.74.0.0
+751.200.92.0.0

-  Functions: 8975
-  Symbols:   1462
-  CStrings:  11868
+  Functions: 9010
+  Symbols:   1464
+  CStrings:  11947
Symbols:
+ _nw_parameters_get_advertise_wake_to_peer_to_peer_responder
+ _nw_parameters_get_high_power_peer_to_peer_discovery
CStrings:
+ " homeAccessory"
+ "### Failed to find multi-user device for identifier %@\n"
+ "### Received multi-user device add event without identifier: %@\n"
+ "### Received multi-user device removed event without identifier: %@\n"
+ "### Reject message for multi-user device on unauthenticated connection: %@"
+ "%s unexpected in %s phase"
+ "-[RPCompanionLinkDaemon _multiUserDevice:receivedRequestID:request:options:responseHandler:cnx:]"
+ "-[RPCompanionLinkDaemon _multiUserDeviceAdded:connection:responseHandler:]"
+ "-[RPCompanionLinkDaemon _multiUserDeviceAdded:connection:responseHandler:]_block_invoke"
+ "-[RPCompanionLinkDaemon _multiUserDeviceRemoved:connection:]"
+ "-[RPCompanionLinkDaemon registerForDaemonEvents]_block_invoke_4"
+ "-[RPCompanionLinkXPCConnection _effectiveMultiUserDestinationForDestination:]"
+ "Add multi-user active device: %@ from connection %@ altDSID %@\n"
+ "AudioAccessory11,1"
+ "B525ish"
+ "Connection to %@ is to multi-user destination %@"
+ "DeviceEnclosureColor"
+ "Found better matching multi-user device='%@'\n"
+ "HasHomeAccessoryForce: %d -> %d\n"
+ "HomeAccessory"
+ "HomeAccessory17,1"
+ "HomeAccessory17,2"
+ "J490Setup"
+ "J491Setup"
+ "Multi-user device identifier missing"
+ "Multi-user device not found"
+ "Received EventID '%@' for multi-user device '%@'\n"
+ "Received requestID '%@' for multi-user device %@"
+ "Remove multi-user active device ( %@ ) from connection ( %@ )\n"
+ "Replacing existing multi-user device ( %@ ) with new ( %@ ) on %@\n"
+ "Unable to map DirectPeer to destination ID"
+ "_aaltDSID"
+ "_destinationID:matchesMultiUserDeviceOnCnx:"
+ "_effectiveMultiUserDestinationForDestination:"
+ "_handleFirstUnlock"
+ "_idHKU"
+ "_idsHasHomeAccessoryCache"
+ "_isAccountCheckedDevice:"
+ "_muDI"
+ "_multiUserDevice:receivedRequestID:request:options:responseHandler:cnx:"
+ "_multiUserDeviceAdded:connection:responseHandler:"
+ "_multiUserDeviceRemoved:connection:"
+ "_multiUserUpdateOptions:withDestination:"
+ "_prefHasHomeAccessoryForce"
+ "_sigHKU"
+ "_sigPD"
+ "_sigRP"
+ "accountOwnerCheckApplies"
+ "com.apple.callservicesd.audioRouteTransfer"
+ "com.apple.callservicesd.requestCallDisplayDetails"
+ "com.apple.callservicesd.requestRingtoneConfiguration"
+ "com.apple.callservicesd.transferActiveConversation"
+ "com.apple.callservicesd.transferContinuityCall"
+ "com.apple.callservicesd.updateBlockedState"
+ "com.apple.nearbyd.perception.generic.data"
+ "exchangePAKEIdentities(clientIdentity:deviceName:givenName:familyName:)"
+ "hasHomeAccessoryForce"
+ "homeAccessoryVariant"
+ "homeDidSetHasOwnerAcknowledgedHomePodSiriOnboarding:"
+ "iPhoneDuo"
+ "idsHasHomeAccessory"
+ "localAccountUpdated"
+ "multiUserDevID"
+ "multiUserDevices"
+ "pairAndReceiveIdentity(pairingData:)"
+ "pairAndReceiveTemporaryIdentities(pairingData:)"
+ "pairing"
+ "phase"
+ "prePairing"
+ "resolveBonjour(clientPublicKey:)"
+ "resolveBonjourCompleted()"
+ "resolveBonjourEncryptedWithSessionID(encryptedRequest:sessionID:)"
+ "setMultiUserDevices:"
+ "shareIdentity(_:)"
+ "shareTemporaryIdentities(_:)"
+ "startPairVerifyWithSessionID(createEncryptionStream:)"
+ "updateMultiUserDeviceWithPeer:"
+ "v16@?0Q8"
+ "verifyIdentityProof:accountAltDSID:"
+ "verifyMUHomeKitIdentityProof:identifier:accountAltDSID:completion:"
- "DeviceColor"
```
