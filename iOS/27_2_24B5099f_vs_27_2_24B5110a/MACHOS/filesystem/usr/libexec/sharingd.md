## sharingd

> `/usr/libexec/sharingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6b7d44` | `0x6b88f0` | **`+0xbac`** |
| `__TEXT.__oslogstring` | `0x3d683` | `0x3d973` | **`+0x2f0`** |
| `__TEXT.__cstring` | `0x3f4b1` | `0x3f541` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x1ce18` | `0x1ce58` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0xb200` | `0xb230` | **`+0x30`** |
| `__DATA.__objc_const` | `0x38840` | `0x38860` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x19960` | `0x19940` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x4ef65` | `0x4ef85` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x5910` | `0x5928` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x79c0` | `0x79c8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x294c` | `0x2950` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
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
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2131.21.21.0.0
+2131.21.31.2.4

-  Functions: 26483
-  Symbols:   5086
-  CStrings:  27657
+  Functions: 26486
+  Symbols:   5089
+  CStrings:  27667
Symbols:
+ _SFIsDeviceHomeAccessory
+ _SFStringForSensitiveData
+ _SFStringsForSensitiveData
CStrings:
+ "    %@ = %@\n"
+ "%@ %{public}@ (%@)"
+ "%@ advertising: advertisingEnabled %{public}@, currentConsoleUser %{public}@, state %s, shouldNotAdvertiseRequestersCount %lu, shouldStart %{public}@"
+ "%@ enabled: %{public}@, state: %s, shouldStart: %{public}@, scanForCopyPaste: %{public}@, scanForHandoff: %{public}@"
+ "%{public}@ %{public}@ %@ %d"
+ "%{public}@ goodbyeTimeoutFired"
+ "%{public}@ invalidateGoodbyeTimer"
+ "%{public}@ startGoodbyeTimer with time interval %.2f"
+ "%{public}@: Encryption key request - Already have request for key %@. Replacing completion block"
+ "%{public}@: Preventing encryption key request - Auto Unlock in progress"
+ "Activity Service: %@, devices: %@\n"
+ "Activity payload received via %@ for requestIdentifier %@ not/no longer wanted from %{public}@"
+ "Attempting to use unrequested encryption key with requestIdentifier %@ from %{public}@"
+ "Auth tag verified against none of %ld ad-hoc paired identities, last error: %s"
+ "B525ish"
+ "Device Identifier To Device Record:\n"
+ "Device Identifier To Lost Device Timer:\n"
+ "Discarding unrequested encryption key as it is missing the requestIdentifier %@ or device %{public}@"
+ "Encryption key: No device found for identifier %{public}@ (Devices: %@)"
+ "Failed to decrypt advertisement from %{public}@ with rawAdvertisementData %@. New key is same. Replay?"
+ "Failed to decrypt advertisement from %{public}@ with rawAdvertisementData %@. Requesting new key"
+ "Failed to decrypt advertisement with new key from %{public}@ with rawAdvertisementData %@. Discarding advertisement"
+ "Failed to retrieve new key from %{public}@"
+ "Failed to update with raw advertisementData %@ from %{public}@ (%@)"
+ "Forcing this device to identify as a B525\n"
+ "Got payload to send of size %d with activityIdentifier:%@ for advertisementPayload:%{public}@"
+ "Handoff active for device %{public}@ : %{public}s"
+ "HomeAccessory"
+ "HomePod identifying as B525: %s -> %s\n"
+ "Ignoring request from %{public}@ via %@ for key with requestIdentifier %@ as we replied only %@ ago"
+ "Lost IDS device %{public}@"
+ "New counter %d is not greater than previous %d from %{public}@ with rawAdvertisementData %@. New key is same. Replay!"
+ "New counter %d is not greater than previous %d from %{public}@ with rawAdvertisementData %@. Requesting new key"
+ "No IDS device found for identifier %{public}@ (Devices: %@)"
+ "No current key to decrypt advertisement from %{public}@ with rawAdvertisementData %@. Requesting key"
+ "No device ID generated for device %{public}@ (Devices: %@) for requestIdentifier %@"
+ "No device found for identifier %{public}@ (Devices: %@)"
+ "Ready to respond to handoff request via %@ from \"%{public}@\" (%{public}@) with requestIdentifier %@ for advertisementPayload %{public}@, command: %@. RTT:%@"
+ "Received Handoff encryption key request from \"%{public}@\" via IDS with requestIdentifier %@"
+ "Received Handoff encryption key request from \"%{public}@\" via Rapport with requestIdentifier %@, xid %@"
+ "Received Handoff payload reply from \"%{public}@\" via IDS with requestIdentifier %@"
+ "Received Handoff payload reply from \"%{public}@\" via Rapport (%s) with requestIdentifier %@, xid %@"
+ "Received Handoff payload request from \"%{public}@\" via Rapport with requestIdentifier %@, xid %@"
+ "Received a new Handoff encryption key from \"%{public}@\" via IDS with requestIdentifier %@"
+ "Received a new Handoff encryption key from \"%{public}@\" via Rapport (%s) with requestIdentifier %@, xid %@"
+ "Received a new advertisement %{public}@"
+ "Received a new rawAdvertisementData %@ from %{public}@ (isReplay:%{public}@, disabledDuplicateFilter:%{public}@)"
+ "Received handoff payload request via %@ from \"%{public}@\" (%{public}@) with requestIdentifier %@ command=%@ for advertisementPayload %{public}@"
+ "Received requested Handoff payload via %@ from \"%{public}@\" (%{public}@) for %{public}@ with activity payload of size %ld for requestIdentifier %@ (%@). RTT:%@"
+ "Request to advertise %{public}@ with options %@"
+ "Requesting Encryption key via IDS from \"%{public}@\" %{public}@ with message GUID: %@ and timeout: %f"
+ "Requesting Encryption key via Rapport from \"%{public}@\" %{public}@ with message GUID: %@ and timeout: %d"
+ "Requesting payload from %{public}@ for %{public}@"
+ "Responding to Handoff encryption key request from \"%{public}@\" via IDS"
+ "Responding to Handoff encryption key request from \"%{public}@\" via Rapport"
+ "Responding to Handoff payload request from \"%{public}@\" via IDS"
+ "Responding to Handoff payload request from \"%{public}@\" via Rapport"
+ "Responding to request via %@ from %{public}@ with requestIdentifier %@ for advertisementPayload %{public}@ with an empty payload"
+ "Responding to request via %@ from %{public}@ with requestIdentifier %@ for advertisementPayload %{public}@ with payload of size %d"
+ "Saw IDS device %{public}@ with mismatched version %d, expected %d"
+ "Saw device %{public}@ but cannot find mathing IDSDevice"
+ "Starting%{public}@%{public}@%{public}@ scanning with duplicates:%{public}@ for peers [%{public}@]"
+ "Unique ID To Key Reply Date:\n"
+ "_homePodIdentifiesAsB525"
+ "deviceIdentifier %{public}@ does not match %{public}@"
+ "from %{public}@, is final:%{public}@, %{public}@"
+ "homePodIdentifiesAsB525"
+ "iPhoneDuo"
+ "nearbyServiceDevicesChanged: %{public}@"
- "%@ %@ %@ %d"
- "%@ advertising: advertisingEnabled %@, currentConsoleUser %@, state %s, shouldNotAdvertiseRequestersCount %lu, shouldStart %@"
- "%@ enabled: %@, state: %s, shouldStart: %@, scanForCopyPaste: %@, scanForHandoff: %@"
- "%@ goodbyeTimeoutFired"
- "%@ invalidateGoodbyeTimer"
- "%@ startGoodbyeTimer with time interval %.2f"
- "%@: Encryption key request - Already have request for key %@. Replacing completion block"
- "%@: Preventing encryption key request - Auto Unlock in progress"
- "Activity Service: %@, devices: \n"
- "Activity payload received via %@ for requestIdentifier %@ not/no longer wanted from %@"
- "Attempting to use unrequested encryption key with requestIdentifier %@ from %@"
- "Device Identifier To Device Record: %@\n"
- "Device Identifier To Lost Device Timer: %@\n"
- "Discarding unrequested encryption key as it is missing the requestIdentifier %@ or device %@"
- "Encryption key: No device found for identifier %@ (Devices: %@)"
- "Failed to decrypt advertisement from %@ with rawAdvertisementData %@. New key is same. Replay?"
- "Failed to decrypt advertisement from %@ with rawAdvertisementData %@. Requesting new key"
- "Failed to decrypt advertisement with new key from %@ with rawAdvertisementData %@. Discarding advertisement"
- "Failed to retrieve new key from %@"
- "Failed to update with raw advertisementData %@ from %@ (%@)"
- "Got payload to send of size %d with activityIdentifier:%@ for advertisementPayload:%@"
- "Handoff active for device %@ : %s"
- "Ignoring request from %@ via %@ for key with requestIdentifier %@ as we replied only %@ ago"
- "Lost IDS device %@"
- "New counter %d is not greater than previous %d from %@ with rawAdvertisementData %@. New key is same. Replay!"
- "New counter %d is not greater than previous %d from %@ with rawAdvertisementData %@. Requesting new key"
- "No IDS device found for identifier %@ (Devices: %@)"
- "No current key to decrypt advertisement from %@ with rawAdvertisementData %@. Requesting key"
- "No device ID generated for device %@ (Devices: %@) for requestIdentifier %@"
- "No device found for identifier %@ (Devices: %@)"
- "Ready to respond to handoff request via %@ from \"%@\" (%@) with requestIdentifier %@ for advertisementPayload %@, command: %@. RTT:%@"
- "Received Handoff encryption key request from \"%@\" via IDS with requestIdentifier %@"
- "Received Handoff encryption key request from \"%@\" via Rapport with requestIdentifier %@, xid %@"
- "Received Handoff payload reply from \"%@\" via IDS with requestIdentifier %@"
- "Received Handoff payload reply from \"%@\" via Rapport (%s) with requestIdentifier %@, xid %@"
- "Received Handoff payload request from \"%@\" via Rapport with requestIdentifier %@, xid %@"
- "Received a new Handoff encryption key from \"%@\" via IDS with requestIdentifier %@"
- "Received a new Handoff encryption key from \"%@\" via Rapport (%s) with requestIdentifier %@, xid %@"
- "Received a new advertisement %@"
- "Received a new rawAdvertisementData %@ from %@ (isReplay:%@, disabledDuplicateFilter:%@)"
- "Received handoff payload request via %@ from \"%@\" (%@) with requestIdentifier %@ command=%@ for advertisementPayload %@"
- "Received requested Handoff payload via %@ from \"%@\" (%@) for %@ with activity payload of size %ld for requestIdentifier %@ (%@). RTT:%@"
- "Request to advertise %@ with options %@"
- "Requesting Encryption key via IDS from \"%@\" %@ with message GUID: %@ and timeout: %f"
- "Requesting Encryption key via Rapport from \"%@\" %@ with message GUID: %@ and timeout: %d"
- "Requesting payload from %@ for %@"
- "Responding to Handoff encryption key request from \"%@\" via IDS"
- "Responding to Handoff encryption key request from \"%@\" via Rapport"
- "Responding to Handoff payload request from \"%@\" via IDS"
- "Responding to Handoff payload request from \"%@\" via Rapport"
- "Responding to request via %@ from %@ with requestIdentifier %@ for advertisementPayload %@ with an empty payload"
- "Responding to request via %@ from %@ with requestIdentifier %@ for advertisementPayload %@ with payload of size %d"
- "Saw IDS device %@ with mismatched version %d, expected %d"
- "Saw device %@ but cannot find mathing IDSDevice"
- "Starting%@%@%@ scanning with duplicates:%@ for peers [%@]"
- "Unique ID To Key Reply Date: %@\n"
- "deviceIdentifier %@ does not match %@"
- "from %@, is final:%@, %@"
- "nearbyServiceDevicesChanged: %@"
```
