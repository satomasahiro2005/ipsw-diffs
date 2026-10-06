## findmydeviced

> `/usr/libexec/findmydeviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4de508` | `0x4f57ec` | **`+0x172e4`** |
| `__TEXT.__eh_frame` | `0x26244` | `0x2741c` | **`+0x11d8`** |
| `__TEXT.__oslogstring` | `0x1cbe9` | `0x1d669` | **`+0xa80`** |
| `__TEXT.__const` | `0x463b6` | `0x469e6` | **`+0x630`** |
| `__DATA_CONST.__const` | `0x1d770` | `0x1dd50` | **`+0x5e0`** |
| `__DATA.__data` | `0xad68` | `0xb2d0` | **`+0x568`** |
| `__DATA.__bss` | `0x28a70` | `0x28fa0` | **`+0x530`** |
| `__TEXT.__unwind_info` | `0xfb58` | `0xfeb8` | **`+0x360`** |
| `__DATA.__objc_const` | `0x1e9b0` | `0x1ecc8` | **`+0x318`** |
| `__TEXT.__constg_swiftt` | `0x5990` | `0x5c7c` | **`+0x2ec`** |
| `__TEXT.__swift5_fieldmd` | `0x6ca4` | `0x6ee8` | **`+0x244`** |
| `__TEXT.__swift5_capture` | `0x1d10` | `0x1e60` | **`+0x150`** |
| `__TEXT.__swift5_reflstr` | `0x563e` | `0x578e` | **`+0x150`** |
| `__TEXT.__cstring` | `0xdede` | `0xdfde` | **`+0x100`** |
| `__TEXT.__swift_as_cont` | `0x1ff0` | `0x20f0` | **`+0x100`** |
| `__TEXT.__auth_stubs` | `0x4d80` | `0x4e70` | **`+0xf0`** |
| `__TEXT.__objc_classname` | `0x2a56` | `0x2b46` | **`+0xf0`** |
| `__TEXT.__swift5_typeref` | `0x4d1c` | `0x4df4` | **`+0xd8`** |
| `__TEXT.__objc_methname` | `0x20479` | `0x20519` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x18a80` | `0x18b20` | **`+0xa0`** |
| `__TEXT.__swift_as_ret` | `0x13e8` | `0x1478` | **`+0x90`** |
| `__DATA_CONST.__auth_got` | `0x26d0` | `0x2748` | **`+0x78`** |
| `__DATA.__common` | `0x978` | `0x9e8` | **`+0x70`** |
| `__DATA.__objc_data` | `0x5570` | `0x55c0` | **`+0x50`** |
| `__TEXT.__swift_as_entry` | `0xd30` | `0xd80` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x1b68` | `0x1ba8` | **`+0x40`** |
| `__TEXT.__swift5_types` | `0x804` | `0x838` | **`+0x34`** |
| `__TEXT.__swift5_builtin` | `0x1e0` | `0x208` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x13ec` | `0x1414` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x7168` | `0x7188` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x1e18` | `0x1e38` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x8f0` | `0x910` | **`+0x20`** |
| `__TEXT.__swift5_mpenum` | `0x124` | `0x138` | **`+0x14`** |
| `__TEXT.__objc_methtype` | `0x3e1c` | `0x3e2c` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1093c` | `0x10944` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-482.30.6.14.19
+482.31.6.16.10

+  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 16288
-  Symbols:   2699
-  CStrings:  10329
+  Functions: 16506
+  Symbols:   2719
+  CStrings:  10371
Symbols:
+ _$s10FindMyBase12TimeoutErrorVACycfC
+ _$s10FindMyBase12TimeoutErrorVMa
+ _$s10FindMyBase12TimeoutErrorVs0E0AAMc
+ _$s10Foundation4DateV2eeoiySbAC_ACtFZ
+ _$s15FindMyBluetooth18PeripheralProtocolP11isConnectedSbvgTj
+ _$s7ElementSTTl
+ _$s8IteratorSTTl
+ _$sS2cEycfC
+ _$sST12makeIterator0B0QzyFTj
+ _$sST8IteratorST_StTn
+ _$sSTTL
+ _$sScEMa
+ _$sScEs5ErrorsMc
+ _$sSt4next7ElementQzSgyFTj
+ _$ss15ContiguousArrayV6appendyyxnF
+ _$ss15ContiguousArrayVAByxGycfC
+ _$ss15ContiguousArrayVMa
+ _$ss8DurationV11descriptionSSvg
+ __swift_FORCE_LOAD_$_swiftIntents
+ _swift_task_addCancellationHandler
+ _swift_task_deinitOnExecutor
+ _swift_task_isCurrentExecutor
+ _swift_task_removeCancellationHandler
+ _swift_task_reportUnexpectedExecutor
- _$s10FindMyBase18AsyncKeyedThrottleC16throttleIntervalACyxGSd_tcfC
- _$s10FindMyBase18AsyncKeyedThrottleC8throttle3key5blockyx_SbyYaYbctFTj
- _$s10FindMyBase18AsyncKeyedThrottleCMn
- _$s10FindMyBase18AsyncKeyedThrottleCyxGScAAAMc
CStrings:
+ " connectionType: "
+ "%s %{public}s Invalid OOB MAC address, %ld bytes: %{private,mask.hash}s!"
+ "%s %{public}s Unexpected authStatus: %{public}s (%u) on %{public}s connection, dropping this delivery"
+ "%s %{public}s Unsupported connection type: %{public}s (%u)"
+ "%s Failed to resolve accessory record for %{private,mask.hash}s: %{public}@"
+ "%s Found record %{private,mask.hash}s matching peripheral %{private,mask.hash}s"
+ "%{public}s for local findable %{private,mask.hash}s timeout %s"
+ "Accessory connection detached for untracked connection %{public}s, nothing to report the detach with"
+ "Could not find owned accessory for identifier %{private,mask.hash}s, when trying to store device event. Trying to resolve a shared accessory…"
+ "Dropping %{public}s for accessory %{public}s: %ld owned accessories last reported %{public}s, so the %{public}s cannot be attributed to one"
+ "Dropping %{public}s for accessory %{public}s: no owned accessory record and no peripheral for its address"
+ "Error reading the reported attachment of %{private,mask.hash}s: %{public}@"
+ "Error resolving owned accessory for %{public}s of %{public}s: %{public}@"
+ "Error resolving peripheral for %{public}s of %{public}s: %{public}@"
+ "Error resolving the reported %{public}s for %{public}s of %{public}s: %{public}@"
+ "Error storing detach event for accessory %{public}s: %{public}@"
+ "Found a shared accessory with owner identifier %{private,mask.hash}s"
+ "Marking pairing session for device %{public}s detached"
+ "No owned accessory record for %{public}s of %{public}s, resolving its peripheral over bluetooth"
+ "No pairing session for device %{public}s at detach, reporting it without one"
+ "Relayed device event %{public}s for device %{private,mask.hash}s"
+ "Relaying device event %{public}s for device %{private,mask.hash}s, observed at %{public}s, attached to %{private,mask.hash}s"
+ "Resolved %{public}s of %{public}s to owned accessory %{private,mask.hash}s from its record"
+ "Resolved %{public}s of %{public}s to owned accessory %{private,mask.hash}s, the %{public}s this daemon last reported"
+ "Resolved %{public}s of %{public}s to peripheral %{private,mask.hash}s"
+ "Resolved owned accessory %{private,mask.hash}s from peripheral identifier %{private,mask.hash}s via MAC address"
+ "Saving detected-nearby already in progress, return"
+ "Saving detected-nearby is being throttled, return"
+ "Starting detected-nearby save from coming out of throttle"
+ "Starting detected-nearby save from idle"
+ "Storing device event %{public}s for device %{private,mask.hash}s observed at %{public}s"
+ "[ATTACH] %{public}s"
+ "[ATTACH] %{public}s OOB pairing info is not an address, %ld bytes: %{private,mask.hash}s, no attach event will be reported"
+ "[ATTACH] %{public}s delivered no OOB pairing info, resolving it from the detach this daemon reported"
+ "[ATTACH] %{public}s is not pairable, no attach event will be reported"
+ "[DETACH] %{public}s"
+ "[DETACH] %{public}s OOB pairing info is not an address, %ld bytes: %{private,mask.hash}s, no detach event will be reported"
+ "[DETACH] %{public}s delivered no OOB pairing info, resolving it from the attach this daemon reported"
+ "[DETACH] %{public}s on a %{public}s connection carries no findable attachment, no detach event will be reported"
+ "[UPDATE] %{public}s"
+ "[UPDATE] %{public}s is not pairable, no attach event will be reported"
+ "_TtC13findmydeviced20UnifiedBeaconFetcher"
+ "_TtC13findmydeviced21AttachmentReportQueue"
+ "_TtC13findmydeviced32LocalBluetoothConnectableAddress"
+ "_TtCC13findmydeviced20UnifiedBeaconFetcher21SendableUnifiedBeacon"
+ "_execute(command:connectionOptions:executeOnlyIfConnected:)"
+ "advertisingAddressDataConnectable"
+ "beacon"
+ "capabilities"
+ "com.apple.icloud.searchpartyuseragent"
+ "connectUsingLTK(beaconId:connectUseCase:searchIfNeeded:)"
+ "connectableAddressProvider"
+ "execute(command:connectionOptions:executeOnlyIfConnected:)"
+ "executeAndReturnRawResponse(command:connectionOptions:executeOnlyIfConnected:)"
+ "fetch(identifier:timeout:)"
+ "findmydeviced/LocalBluetoothConnectableAddress.swift"
+ "initWithFetchProperties:matchingBeaconUUIDs:"
+ "pendingReports"
+ "peripheral(for:searchIfNeeded:)"
+ "sendLocalFindable(centralManager:discovery:config:record:command:executeOnlyIfConnected:)"
+ "soundPlayingInitiated"
+ "storeDetectedNearby()"
- "%s %{public}s Invalid MAC address %s!"
- "%s %{public}s Unexpected authStatus: %u"
- "%s %{public}s Unsupported connection type: %u"
- "%s Failed to resolve accessory record for %{public}s: %{public}@"
- "%s Found record %{public}s matching peripheral %{public}s"
- "Could not find owned accessory for identifier %{public}s, when trying to store device event. Trying to resolve a shared accessory…"
- "FindingSession-DeviceEvent"
- "Found a shared accessory with owner identifier %{public}s"
- "Marking pairing session for device %s detached"
- "Relaying device event %{public}s for device %{public}s, attached to %s"
- "Resolved owned accessory %{public}s from peripheral identifier %{public}s via MAC address"
- "Saving detected-nearby event with throttle"
- "Storing device event %{public}s for device %{public}s"
- "_execute(command:connectionOptions:)"
- "connectUsingLTK(beaconId:connectUseCase:)"
- "deviceEventQueue"
- "execute(command:connectionOptions:)"
- "executeAndReturnRawResponse(command:connectionOptions:)"
- "peripheral(for:)"
- "sendLocalFindable(centralManager:discovery:config:record:command:)"
```
