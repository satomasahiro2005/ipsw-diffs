## searchpartyd

> `/usr/libexec/searchpartyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1937a4c` | `0x19550bc` | **`+0x1d670`** |
| `__TEXT.__eh_frame` | `0xf9494` | `0xfac54` | **`+0x17c0`** |
| `__TEXT.__oslogstring` | `0x4ed5e` | `0x500ee` | **`+0x1390`** |
| `__TEXT.__unwind_info` | `0x4bdd0` | `0x4b5a8` | **`-0x828`** |
| `__DATA.__data` | `0x43930` | `0x43c30` | **`+0x300`** |
| `__TEXT.__const` | `0x985d8` | `0x98348` | **`-0x290`** |
| `__TEXT.__swift5_capture` | `0x1aba0` | `0x1adbc` | **`+0x21c`** |
| `__DATA_CONST.__const` | `0x72a00` | `0x72c08` | **`+0x208`** |
| `__TEXT.__cstring` | `0x3282c` | `0x32a2c` | **`+0x200`** |
| `__TEXT.__swift_as_cont` | `0xe154` | `0xe2e4` | **`+0x190`** |
| `__TEXT.__swift5_typeref` | `0x2511f` | `0x25227` | **`+0x108`** |
| `__TEXT.__swift5_reflstr` | `0x25a31` | `0x25b21` | **`+0xf0`** |
| `__TEXT.__swift_as_ret` | `0x7f60` | `0x8048` | **`+0xe8`** |
| `__TEXT.__auth_stubs` | `0x9bf0` | `0x9cd0` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x22a0c` | `0x22ab8` | **`+0xac`** |
| `__TEXT.__swift5_fieldmd` | `0x26ebc` | `0x26f5c` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x1ed78` | `0x1ee10` | **`+0x98`** |
| `__DATA_CONST.__auth_got` | `0x4e00` | `0x4e70` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x3c10` | `0x3c70` | **`+0x60`** |
| `__DATA.__common` | `0x34a0` | `0x34d8` | **`+0x38`** |
| `__DATA_CONST.__auth_ptr` | `0x4c08` | `0x4c40` | **`+0x38`** |
| `__TEXT.__swift_as_entry` | `0x3cb8` | `0x3cf0` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x4a54` | `0x4a34` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x5bee` | `0x5bce` | **`-0x20`** |
| `__DATA.__objc_data` | `0x4560` | `0x4548` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x988` | `0x974` | **`-0x14`** |
| `__TEXT.__swift5_types` | `0x2074` | `0x2070` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-449.30.6.14.26
+449.31.6.16.16

+  - /System/Library/Frameworks/AppIntents.framework/AppIntents

+  - /System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight

+  - /System/Library/PrivateFrameworks/SPMirrorEntities.framework/SPMirrorEntities

-  Functions: 67827
-  Symbols:   5020
-  CStrings:  14145
+  Functions: 68029
+  Symbols:   5049
+  CStrings:  14217
Symbols:
+ _$s10AppIntents12IntentPersonV10IdentifierO18applicationDefinedyAESScAEmFWC
+ _$s10AppIntents12IntentPersonV10IdentifierO7unknownyA2EmFWC
+ _$s10AppIntents12IntentPersonV10IdentifierOMa
+ _$s10AppIntents12IntentPersonV10identifier4name6handle7aliases4isMe5imageA2C10IdentifierO_AC4NameOAC6HandleVSgSayAOGSbAA21DisplayRepresentationV5ImageVSgtcfC
+ _$s10AppIntents12IntentPersonV4NameO7unknownyA2EmFWC
+ _$s10AppIntents12IntentPersonV4NameOMa
+ _$s10AppIntents12IntentPersonV6HandleV11phoneNumber5labelAESS_AE5LabelOtcfC
+ _$s10AppIntents12IntentPersonV6HandleV12emailAddress5labelAESS_AE5LabelOtcfC
+ _$s10AppIntents12IntentPersonV6HandleV5LabelO5otheryA2GmFWC
+ _$s10AppIntents12IntentPersonV6HandleV5LabelOMa
+ _$s10AppIntents12IntentPersonV6HandleVMa
+ _$s10AppIntents12IntentPersonV6HandleVMn
+ _$s10AppIntents12IntentPersonVMa
+ _$s10AppIntents12IntentPersonVMn
+ _$s10AppIntents21DisplayRepresentationV5ImageVMa
+ _$s10AppIntents21DisplayRepresentationV5ImageVMn
+ _$s12FindMyLocate12ClientTargetVMa
+ _$s12FindMyLocate12ClientTargetVMn
+ _$s12FindMyLocate13RequestOriginV_12clientTargetAcA06ClientE0O_AA0hG0VSgtcfC
+ _$s16SPMirrorEntities25IntentSessionEntityMirrorO04ItemE0V10AppIntents07IndexedE0AAMc
+ _$s16SPMirrorEntities25IntentSessionEntityMirrorO04ItemE0V2id4name10customName07productK05owner8categoryAESS_S2SSgSS10AppIntents0C6PersonVSgALtcfC
+ _$s16SPMirrorEntities25IntentSessionEntityMirrorO04ItemE0VMa
+ _$s16SPMirrorEntities25IntentSessionEntityMirrorO04ItemE0VMn
+ _$sSi10FindMyBase17PropertyListValueAAWP
+ _$sSo17CSSearchableIndexC10AppIntentsE05indexC8Entities_8priorityySayxG_SitYaKAC13IndexedEntityRzlF
+ _$sSo17CSSearchableIndexC10AppIntentsE05indexC8Entities_8priorityySayxG_SitYaKAC13IndexedEntityRzlFTu
+ _$sSo17CSSearchableIndexC10AppIntentsE06deleteC8Entities12identifiedBy6ofTypeySay2IDQzG_xmtYaKAC13IndexedEntityRzlF
+ _$sSo17CSSearchableIndexC10AppIntentsE06deleteC8Entities12identifiedBy6ofTypeySay2IDQzG_xmtYaKAC13IndexedEntityRzlFTu
+ _$sSo17CSSearchableIndexC10AppIntentsE06deleteC8Entities6ofTypeyxm_tYaKAC13IndexedEntityRzlF
+ _$sSo17CSSearchableIndexC10AppIntentsE06deleteC8Entities6ofTypeyxm_tYaKAC13IndexedEntityRzlFTu
+ _OBJC_CLASS_$_CSSearchableIndex
- _$s12FindMyLocate13RequestOriginVyAcA06ClientE0OcfC
- _$ss8DurationV12millisecondsyABSdFZ
CStrings:
+ "%s - subscribing."
+ "%s: Failed to get BeaconStoreActor"
+ "%s: proximityPairing → RemoteUI color=%lu"
+ "%s: queueing re-donation of %ld beacon(s)"
+ "%{public}s: Failed to get BeaconStore"
+ "%{public}s: Failed to get FindMyServiceDeviceStoreService: %{public}@"
+ "%{public}s: failed %{public}@, retrying on the next launch"
+ "%{public}s: nothing buildable, retrying on the next launch"
+ "%{public}s: store not available, retrying on the next launch"
+ ", bootSessionUUID: "
+ "Already observing sound state for %{private,mask.hash}s, not handing out another stream."
+ "Attach state for beacon %{private,mask.hash}s changed connected %{bool,public}d -> %{bool,public}d via %{public}s, appActive %{bool,public}d."
+ "BeaconSharing companion findable accessory paired: true."
+ "BeaconStore unavailable, cannot check attachment identity for beacon %{private,mask.hash}s."
+ "Cannot create destination from %{private,mask.hash}s in circle %{private,mask.hash}s."
+ "Checking if we need a companion share."
+ "Companion device identifier is not a uuid"
+ "Correlation map unavailable for family/follower intersection; falling back to raw handles: %@"
+ "Could not make MessageDestination from AppleID: %@"
+ "Device List update pending, not creating a new task."
+ "Device has no companion device identifier."
+ "Did not find companion device identifier for findMyDevice for beacon %{private,mask.hash}s."
+ "Donating %{public}ld of %{public}ld beacon(s)"
+ "EnableUnifiedDevicesRefresh"
+ "Ended Item Entity Donation"
+ "Entities changed: %ld"
+ "Entities removed: %ld"
+ "Failed to register simple beacon subscription for entity donation."
+ "Failed to update device list: %{public}@."
+ "Failure in fetching latest attached to device. Error: %{public}@"
+ "Failure in fetching latest attached to device. No attached device found for identifier: %{private,mask.hash}s."
+ "Failure sending circleTrust share. sharingCircle=%{private,mask.hash}s peerTrust=%{private,mask.hash}s shareType=%{public}s error=%{public}@. Marking member acceptance state as .failed; propagating idsMessageSendingFailure to caller."
+ "Failure sending local-findable circleTrust share. sharingCircle=%{private,mask.hash}s peerTrust=%{private,mask.hash}s shareType=%{public}s error=%{public}@. Marking member acceptance state as .failed; propagating idsMessageSendingFailure to caller."
+ "Failure to reevaluate companion sharing on me device change: %{public}@"
+ "Found companion device identifier %{private,mask.hash}s for beacon %{private,mask.hash}s."
+ "Imported share has non-canonicalizable displayIdentifier; aborting createImportedShare. shareIdentifier=%{private,mask.hash}s beaconIdentifier=%{private,mask.hash}s"
+ "Injecting device event source: %{public}s timestamp: %{public}s for beacon: %{private,mask.hash}s."
+ "Item Entity Donation failed: %{public}@"
+ "LocalFindable cache expired, will re-fetch beacons. (initiated from cache path)"
+ "LocalFindable cache hit, returning %{public}ld beacons. (initiated from cache path)"
+ "LocalFindable cache ongoing, returning current %{public}ld beacons. (initiated from cache path)"
+ "LocalFindable first load, will fetch beacons. (initiated from cache path)"
+ "LocalFindable kept %ld beacons after failure."
+ "LocalFindable stale, will fetch beacons."
+ "LocalFindable stale, will fetch beacons. (initiated from cache path)"
+ "Location sharing device changed to %{public}s."
+ "MessagingDestination(email:) could not canonicalize input; using best-effort handle. input=%{private,mask.hash}s"
+ "MessagingDestination(phoneNumber:) could not canonicalize input; using best-effort handle. input=%{private,mask.hash}s"
+ "MessagingDestination(string:) rejected non-canonicalizable input. kind=%{public}s input=%{private,mask.hash}s"
+ "No attachment identity for device event for beacon: %{private,mask.hash}s. The device has neither an own-device beacon record nor a stable identifier."
+ "No attachment identity for device event for beacon: %{private,mask.hash}s. The device has neither an own-device beacon record nor a stable identifier. Storing the event without attachment info."
+ "No findMyDevice found for beacon %{private,mask.hash}s."
+ "Not buildable yet, skipping: %{private,mask.hash}s"
+ "Publish delay: policy:%{public}s onBattery: %{bool}d, onWiFi: %{bool}d, powerMode: %s, next publish date: %{public}s, delay: %lld."
+ "Refreshed attach state for beacon %{private,mask.hash}s."
+ "Registering observer for me device state changes"
+ "Reusing LocalFindablePlaySoundManager for %{private,mask.hash}s. CommandId %{public}s"
+ "Scheduling next device list update."
+ "Sharee has no IDS-registered devices; proceeding with local unshare. (shareIdentifier: %@)"
+ "Skipping Find My service device %{private,mask.hash}s: a beacon record already owns key %{private,mask.hash}s."
+ "Skipping peer trust with non-canonicalizable displayIdentifier. peerTrust=%{private,mask.hash}s displayIdentifier=%{private,mask.hash}s"
+ "Sound playing (state=%{public}s) is already stopped for %{private,mask.hash}s, returning."
+ "Started Item Entity Donation"
+ "Withholding synthetic attachment identity from published device event for beacon: %{private,mask.hash}s."
+ "_beaconUpdateStream(context:)"
+ "_receivedSimpleBeacons(identifiers:beaconStore:origin:)"
+ "accountScopedDestination: could not strip token URI; returning token-scoped destination. %{private,mask.hash}s"
+ "beaconUpdateContext"
+ "beaconUpdateSubscriptionTask"
+ "buildSpotlightChanges(for:)"
+ "changes: %s"
+ "com.apple.searchpartyd.syntheticBeacon.v1"
+ "createUserInfo()"
+ "defaultSearchableIndex"
+ "deleteAppEntities failed: %{public}@"
+ "donatedItemEntityFormatVersion"
+ "entityUpdateStream"
+ "forceBreakAllShares: non-canonicalizable userHandle; cannot resolve peer trusts."
+ "hasStateStreamSubscriber"
+ "indexAppEntities failed: %{public}@"
+ "playSound(commandIdentifier:timeout:)"
+ "postBeaconEntitiesChanged(changes:)"
+ "redonateAllItemEntities()"
+ "redonateItemEntities()"
+ "refreshAttachEvent could not get the ObservationStoreService for beacon: %{private,mask.hash}s."
+ "simpleBeacon.updateAllBeacons.beaconUpdateStream"
+ "stateStreamProvider"
+ "stopSound(commandIdentifier:)"
+ "submitDeviceEvent:source:timestamp:attachedTo:completion:"
+ "subscribeToEntityDonation()"
+ "task revision previousRecords "
+ "v52@0:8@\"NSUUID\"16I24@\"NSDate\"28@\"NSUUID\"36@?<v@?@\"NSError\">44"
+ "v52@0:8@16I24@28@36@?44"
+ "waitForAvailableBeaconStore()"
+ "waitForSpotlightReadiness: Failed to get FirstUnlockService"
- " to account-scoped!"
- "BeaconObservationStore.latestObservation(for:)"
- "ClientTrampoline.latestObservation(for:) XPC error: %@"
- "Error could not get self-beacon UUID for device event for beacon: %{private,mask.hash}s."
- "Error reading latest observation: %@"
- "Failure on share sending: %{public}@"
- "LocalFindable cached 0 beacons due to failure."
- "New local findable accessory paired. Checking if we need a companion share."
- "Publish delay: policy:%{public}s onBattery: %{bool}d, onWiFi: %{bool}d, powerMode: %s, next publish date: %{public}s, eligible delay: %lld, delay: %lld."
- "Sound playing is already stopped for %{private,mask.hash}s, returning."
- "Unknown MessagingDestination case!"
- "_receivedSimpleBeacons(identifiers:beaconStore:)"
- "connected() limit-1 fetch for %{private,mask.hash}s: rows=%ld."
- "latestObservation(for:) failed: %{public}@"
- "latestObservation(for:types:)"
- "latestObservationWithBeaconIdentifier:typeRawValues:completion:"
- "playSound(timeout:)"
- "searchpartyd/MessagingDestination.swift"
- "submitDeviceEvent:source:attachedTo:completion:"
- "task revision "
- "v40@0:8@\"NSUUID\"16@\"NSArray\"24@?<v@?@\"NSData\"@\"NSError\">32"
- "v44@0:8@\"NSUUID\"16I24@\"NSUUID\"28@?<v@?@\"NSError\">36"
- "v44@0:8@16I24@28@?36"
```
