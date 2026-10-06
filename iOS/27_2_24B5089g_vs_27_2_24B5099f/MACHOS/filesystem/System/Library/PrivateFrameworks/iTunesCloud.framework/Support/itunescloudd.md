## itunescloudd

> `/System/Library/PrivateFrameworks/iTunesCloud.framework/Support/itunescloudd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x178258` | `0x179ddc` | **`+0x1b84`** |
| `__TEXT.__oslogstring` | `0x32109` | `0x3289b` | **`+0x792`** |
| `__TEXT.__objc_methname` | `0x25f17` | `0x2619b` | **`+0x284`** |
| `__TEXT.__objc_stubs` | `0x17ea0` | `0x18040` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x12217` | `0x1231b` | **`+0x104`** |
| `__DATA.__objc_const` | `0x18248` | `0x18320` | **`+0xd8`** |
| `__TEXT.__objc_methlist` | `0xcae4` | `0xcb64` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0xcf80` | `0xcfe0` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x7090` | `0x70e8` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x5114` | `0x516c` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x68c0` | `0x6910` | **`+0x50`** |
| `__DATA_CONST.__objc_arraydata` | `0x288` | `0x2b8` | **`+0x30`** |
| `__DATA_CONST.__objc_arrayobj` | `0x270` | `0x2a0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x4258` | `0x4288` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0xfe0` | `0xff8` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x1008` | `0x1020` | **`+0x18`** |
| `__TEXT.__const` | `0x610` | `0x620` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.200.17.0.0
+4026.200.21.0.0

-  Functions: 5766
+  Functions: 5783

-  CStrings:  10325
+  CStrings:  10363
Symbols:
+ _ML3TrackPropertyStoreCloudInMyLibrary
- _ICCloudChannelRegistrationAvailabilityDidChangeNotification
CStrings:
+ "5 `"
+ "Boosted artwork download has not started after %.1fs (identifier = '%{public}@' type = %{public}@ source = %{public}@ hasResolvedAssetLocation=%{BOOL}u); artworkDownloadOperationQueue.maxConcurrentOperationCount=%ld operationCount=%lu reservedSlots=%lu"
+ "Could not clear cloud channel name for released/completed albums. Error=%{public}@"
+ "Could not set sagaIDs for trackPersistentIDs"
+ "Could not update cloudInMyLibrary for trackPersistentIDs"
+ "ICDCloudAPNSChannelPersistenceManager - failed to overwrite stale metadata path=%{public}@ err=%{public}@"
+ "ICDCloudAPNSChannelPersistenceManager - failed to remove cloud channel metadata; falling back to empty write path=%{public}@ err=%{public}@"
+ "ICDCloudAPNSChannelPersistenceManager - removing all cloud channel metadata path=%{public}@"
+ "ICDCloudAPNSChannelRegistry - evicting client channels to make room evicted=%{public}@ forChannelID=%{public}@"
+ "ICDCloudAPNSChannelRegistry - failed to drop unclaimed registrations channels=%{public}@ err=%{public}@"
+ "ICDCloudAPNSChannelRegistry - failed to release client pool slots channels=%{public}@ err=%{public}@"
+ "ICDCloudAPNSChannelRegistry - giving up channels with no registrations given=%{public}@ forChannelID=%{public}@"
+ "ICDCloudAPNSChannelRegistry - giving up unclaimed registrations given=%{public}@ forChannelID=%{public}@"
+ "ICDCloudAPNSChannelRegistry - invalidating all registrations connection=%{public}@ channelCount=%lu"
+ "ICDCloudAPNSChannelRegistry - max allowed channel subscription counts changed old=%lu, new=%lu, catalog budget=%lu, library budget=%lu"
+ "ICDCloudAPNSChannelRegistry - not enforcing the catalog budget as the culled channels could not be read"
+ "ICDCloudAPNSChannelRegistry - not invalidating all registrations; unsupported off macOS connection=%{public}@"
+ "ICDCloudAPNSChannelRegistry - not unsubscribing from APS during invalidation err=%{public}@"
+ "ICDCloudAPNSChannelRegistry - reconciling channels after grace, keeping library=%{public}@ client=%{public}@ durable=%{public}@"
+ "ICDCloudChannelRegistrationConfigurationChangedNotification"
+ "Migrating to version 810000"
+ "Migrating to version 810010"
+ "Not setting cloud in my library for trackPIDS=%{public}@ for operationType=%d, behavior=%d"
+ "Releasing reserved download slot for artwork operation (identifier = '%{public}@'); lowering artworkDownloadOperationQueue.maxConcurrentOperationCount from %ld to %ld"
+ "Releasing the client pool slots for channels=%{public}@"
+ "Removing %d unclaimed registration(s) for channels=%{public}@"
+ "Reserving a download slot for boosted artwork operation (identifier = '%{public}@'); raising artworkDownloadOperationQueue.maxConcurrentOperationCount from %ld to %ld"
+ "SagaCloudUtilsCloudLibraryIDsKey"
+ "SagaCloudUtilsTrackPIDsToUpdateCloudInLibraryKey"
+ "SagaCloudUtilsUnmappedCloudIDsKey"
+ "Setting cloud in my library for trackPIDS=%{public}@"
+ "T@\"NSMutableSet\",&,N,V_reservedSlotOperationIdentifiers"
+ "Track with persistentID=%lld, cloudID=%lld inMyLibrary=%{BOOL}u cloudInMyLibrary=%{BOOL}u is not in the library"
+ "UPDATE album SET cloud_channel_name=? WHERE (cloud_channel_name !=? AND is_followed=? AND release_event_aux_info=? AND is_prerelease=?)"
+ "_baseMaxConcurrentOperationCount"
+ "_isPriority"
+ "_maxAllowedCatalogChannelSubscriptions"
+ "_maxAllowedChannelSubscriptions"
+ "_maxAllowedLibraryChannelSubscriptions"
+ "_releaseClientPoolSlotsForChannelIDs:"
+ "_releaseReservedDownloadSlotForOperationIdentifierIfNeeded:"
+ "_reserveDownloadSlotForBoostedOperation:identifier:"
+ "_reservedSlotOperationIdentifiers"
+ "_scheduleStalledBoostWarningForOperation:identifier:"
+ "cloudChannelSubscriptionsConfigurationChanged:"
+ "invalidateAllRegistrationsForConnection:completion:"
+ "invalidateAllRegistrationsWithCompletion:"
+ "maxAllowedCloudChannelRegistrations"
+ "prioritizeDownload"
+ "releaseClientPoolSlotsForChannelIDs:"
+ "removeUnclaimedRegistrationsForChannelIDs:"
+ "reservedSlotOperationIdentifiers"
+ "setPrioritize:"
+ "setReservedSlotOperationIdentifiers:"
+ "\xf02"
- "4`"
- "ICDCloudAPNSChannelRegistry - evicting a client channel to make room evicted=%{public}@ forChannelID=%{public}@"
- "ICDCloudAPNSChannelRegistry - failed to drop an unclaimed registration channelID=%{public}@ err=%{public}@"
- "ICDCloudAPNSChannelRegistry - failed to release a client pool slot channelID=%{public}@ err=%{public}@"
- "ICDCloudAPNSChannelRegistry - giving up a channel with no registrations given=%{public}@ forChannelID=%{public}@"
- "ICDCloudAPNSChannelRegistry - giving up an unclaimed registration given=%{public}@ forChannelID=%{public}@"
- "ICDCloudAPNSChannelRegistry - reconciling channels after grace channels=%{public}@"
- "Releasing the client pool slot for channel=%{public}@"
- "Removing %d unclaimed registration(s) for channel=%{public}@"
- "Removing all cloud channel registrations for a disabled feature"
- "SagaCloudUtilsSagaIDsKey"
- "SagaCloudUtilsUnmappedIDsKey"
- "_releaseClientPoolSlotForChannelID:"
- "cloudChannelSubscriptionsRegistrationOffsetsChanged:"
- "releaseClientPoolSlotForChannelID:"
- "removeUnclaimedRegistrationForChannelID:"
- "\xf2"
```
