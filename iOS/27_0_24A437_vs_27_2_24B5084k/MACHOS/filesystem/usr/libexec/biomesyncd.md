## biomesyncd

> `/usr/libexec/biomesyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a748` | `0x4c598` | **`+0x1e50`** |
| `__TEXT.__oslogstring` | `0x6468` | `0x6b00` | **`+0x698`** |
| `__TEXT.__objc_methname` | `0xa3f4` | `0xa7b1` | **`+0x3bd`** |
| `__TEXT.__objc_stubs` | `0x8900` | `0x8bc0` | **`+0x2c0`** |
| `__TEXT.__objc_methlist` | `0x3c44` | `0x3d04` | **`+0xc0`** |
| `__DATA.__objc_selrefs` | `0x28e0` | `0x2990` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x59f8` | `0x5aa2` | **`+0xaa`** |
| `__TEXT.__gcc_except_tab` | `0x89c` | `0x900` | **`+0x64`** |
| `__DATA_CONST.__cfstring` | `0x4740` | `0x47a0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x10d8` | `0x1130` | **`+0x58`** |
| `__DATA_CONST.__objc_arrayobj` | `0x8a0` | `0x8d0` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x1733` | `0x1760` | **`+0x2d`** |
| `__DATA_CONST.__objc_dictobj` | `0x78` | `0xa0` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x5a0` | `0x5c0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1160` | `0x1148` | **`-0x18`** |
| `__TEXT.__auth_stubs` | `0xd00` | `0xd10` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x690` | `0x698` | **`+0x8`** |
| `__TEXT.__const` | `0x134a` | `0x1352` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__linkguard`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-250.0.0.3.0
+255.0.2.0.0

-  Functions: 1627
-  Symbols:   356
-  CStrings:  3072
+  Functions: 1656
+  Symbols:   357
+  CStrings:  3122
Symbols:
+ __os_feature_enabled_impl
CStrings:
+ "%@%@_%@"
+ "-[BMSyncServiceServer cascadeRapportSyncWithReply:]"
+ "B32@0:8d16@24"
+ "Biome"
+ "Dropping malformed deleted location from peer for stream %{public}@"
+ "Failed to clear the local device flag for %@: %@"
+ "HighestPostedEventTimestamp_"
+ "RetiredLocalSiteIdentifiers"
+ "TimeTravelDeviceRotation"
+ "TimeTravelPoolCleanup"
+ "Tombstone segment %@ in stream %@ is already gone; assuming the store's configured version %u for bookmark ordering"
+ "addRetiredLocalSiteIdentifier:"
+ "anySyncStreamHoldsFutureDatedEvents"
+ "anySyncStreamIsFrozenForSiteIdentifier:database:"
+ "arrayByAddingObject:"
+ "cascadeRapportSync called"
+ "clearLocalDeviceFlagForDeviceWithIdentifier:"
+ "configDatastoreVersion"
+ "could not open a transaction to rotate the local device identifier"
+ "d32@0:8@16@24"
+ "failed to retire site %@ in stream %{public}@"
+ "failed to rotate the local device identifier while sync was frozen"
+ "handleHighestDeletedLocationDidFetchRecord: can't build location from stream:%{public}@ site:%{public}@ day:%ld"
+ "handleHighestDeletedLocationDidFetchRecord: no location row for stream:%{public}@ site:%{public}@ day:%ld; not recording it as the highest deleted location"
+ "hasElapsed:sinceDate:"
+ "highestLocationForSiteIdentifier:inStream:"
+ "highestPostedEventTimestampForSiteIdentifier:inStream:"
+ "highestPostedEventTimestampKeyForSiteIdentifier:inStream:"
+ "isTimeTravelStreamResetEnabledForConfig:"
+ "newEnumeratorFromStartTime:endTime:maxEvents:options:"
+ "newEnumeratorStartingAfterBookmark:reader:notBefore:"
+ "newestEventTimestampForStreamConfiguration:"
+ "not rotating the local device identifier: stream %{public}@ still holds future dated events"
+ "not rotating the local device identifier: there is no identified local device to retire"
+ "populateAtomBatch could not open a reader for bookmark %@, adding a placeholder append: %@"
+ "refusing to record an unusable retired local site identifier %@"
+ "resetImmediateSyncBudget"
+ "retireLocationsForRetiredLocalSiteIdentifiersInManagers:database:"
+ "retireSiteIdentifier:"
+ "retiredLocalSiteIdentifiers"
+ "retiring site %@ in stream %{public}@ up to and including %@; peers will prune everything that site contributed"
+ "rolling back a failed local device identifier rotation"
+ "rotateLocalDeviceIdentifier"
+ "rotateLocalDeviceIdentifierIfFrozenAndEveryStreamRecovered:database:"
+ "rotated the local device identifier because sync was frozen and every sync stream is free of future dated events"
+ "seedHighestPostedEventTimestampIfLastPostedEventIsGone:reader:"
+ "setHighestPostedEventTimestamp:forSiteIdentifier:inStream:"
+ "stream %{public}@ has posted atoms whose events are gone from disk; seeding the highest posted timestamp to %f so no earlier event is posted to peers"
+ "stream %{public}@ retracted %lu atoms in %@ whose events are no longer on disk; peers will prune their copies"
+ "stream %{public}@ withheld %lu events at or below the highest already posted timestamp %f; sync for this stream stays frozen until the clock passes it"
+ "syncAllPersonasNowWithReason:activity:completionHandler:"
+ "v40@0:8d16@24@32"
- "activity \"%s\" not supported on this platform"
- "newEnumeratorFromBookmark:options:"
```
