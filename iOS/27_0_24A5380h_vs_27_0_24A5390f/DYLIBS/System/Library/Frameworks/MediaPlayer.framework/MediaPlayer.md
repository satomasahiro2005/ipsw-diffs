## MediaPlayer

> `/System/Library/Frameworks/MediaPlayer.framework/MediaPlayer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38cbb4` | `0x38cebc` | **`+0x308`** |
| `__TEXT.__oslogstring` | `0x1a1d5` | `0x1a251` | **`+0x7c`** |
| `__TEXT.__cstring` | `0x319fa` | `0x31a3f` | **`+0x45`** |
| `__DATA_CONST.__objc_selrefs` | `0x13988` | `0x139b8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x28b04` | `0x28b1c` | **`+0x18`** |
| `__DATA.__bss` | `0xe90` | `0xe88` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xd1d8` | `0xd1e0` | **`+0x8`** |

### Other Changes

```diff

-4026.100.76.0.0
+4026.100.79.0.0

-  Functions: 17156
-  Symbols:   32350
+  Functions: 17158
+  Symbols:   32352
Symbols:
+ -[MPRouteButton _accessoryImageForRoute:]
+ -[MPRouteButton largeContentTitle]
+ GCC_except_table16657
+ GCC_except_table16737
+ GCC_except_table16743
+ GCC_except_table16841
- GCC_except_table16655
- GCC_except_table16735
- GCC_except_table16741
- GCC_except_table16839
Functions:
~ ___91-[MPMediaLibraryDataProviderML3 setValue:forProperty:ofItemWithIdentifier:completionBlock:]_block_invoke : 1776 -> 1924
~ ___110-[MPMediaLibraryDataProviderML3 setValue:forProperty:ofCollectionWithIdentifier:groupingType:completionBlock:]_block_invoke.195 : 2316 -> 2656
~ ___126-[MPMediaLibraryDataProviderML3 setValuesForProperties:trackList:andEntryProperties:ofPlaylistWithIdentifier:completionBlock:]_block_invoke.205 : 2280 -> 2364
~ ___129-[MPModelStorePlatformMetadataGenericObjectBuilder genericObjectForStorePlatformMetadata:radioStationContainsVideo:userIdentity:]_block_invoke_4 : 3648 -> 3644
~ -[MPRouteButton initWithFrame:] : 440 -> 464
+ -[MPRouteButton largeContentTitle]
~ -[MPRouteButton _updateAccessoryIcon] : 572 -> 144
+ -[MPRouteButton _accessoryImageForRoute:]
CStrings:
+ " SELECT child.rowid, child.explicit, r.suborder FROM object_relationships r INNER JOIN objects parent   ON parent.identifier = r.parent_identifier AND parent.person_id = r.person_id INNER JOIN objects child   ON child.identifier = r.child_identifier AND child.person_id = r.person_id WHERE parent.rowid = @id   AND r.child_key = @childKey   AND r.parent_version_hash = COALESCE(@parentVersionHash, r.parent_version_hash) ORDER BY r.suborder"
+ "%{public}@ imageForRoute image: %{public}@ | routes: %{public}@"
+ "Not propagating favorite state change for album (likedState=%{public}@, timeStamp=%{public}@) with persistentID=%lld as cloudLibrary is not enabled and it's missing store identifiers"
+ "Not propagating favorite state change for album (likedState=%{public}@, timeStamp=%{public}@) with persistentID=%lld as it's missing store identifiers"
+ "Not propagating favorite state change for album (likedState=%{public}@, timeStamp=%{public}@) with persistentID=%lld as the request is not valid"
+ "Not propagating favorite state change for album artist (likedState=%{public}@, timeStamp=%{public}@) with persistentID=%lld as cloudLibrary is not enabled and it's missing store identifiers"
+ "Not propagating favorite state change for album artist (likedState=%{public}@, timeStamp=%{public}@) with persistentID=%lld as it's missing store identifiers"
+ "Not propagating favorite state change for album artist (likedState=%{public}@, timeStamp=%{public}@) with persistentID=%lld as the request is not valid"
+ "Not propagating favorite state change for playlist (likedState=%{public}@, timeStamp=%{public}@) with persistentID=%lld as it's missing store identifiers"
+ "Not propagating favorite state change for playlist (likedState=%{public}@, timeStamp=%{public}@) with persistentID=%lld as the request is not valid"
+ "Not propagating favorite state change for track (likedState=%{public}@, timeStamp=%{public}@) with persistentID=%lld as cloudLibrary is not enabled and it's missing store identifiers"
+ "Not propagating favorite state change for track (likedState=%{public}@, timeStamp=%{public}@) with persistentID=%lld as it's missing store identifiers"
+ "Not propagating favorite state change for trackPID=%lld as the request is not valid (likedState=%{public}@, timeStamp=%{public}@"
+ "Not propagating liked state=%{public}@ for album=%{public}@"
- " SELECT child.rowid, child.explicit, r.suborder FROM object_relationships r INNER JOIN objects parent   ON parent.identifier = r.parent_identifier INNER JOIN objects child   ON child.identifier = r.child_identifier WHERE parent.rowid = @id   AND r.child_key = @childKey   AND r.parent_version_hash = COALESCE(@parentVersionHash, r.parent_version_hash) ORDER BY r.suborder"
- "%{public}@ imageForRoute routes: %{public}@"
- "Not propagating favorite state change for album (likedState=%d, timeStamp=%{public}@) with persistentID=%lld as cloudLibrary is not enabled and it's missing store identifiers"
- "Not propagating favorite state change for album (likedState=%d, timeStamp=%{public}@) with persistentID=%lld as it's missing store identifiers"
- "Not propagating favorite state change for album (likedState=%d, timeStamp=%{public}@) with persistentID=%lld as the request is not valid"
- "Not propagating favorite state change for album artist (likedState=%d, timeStamp=%{public}@) with persistentID=%lld as cloudLibrary is not enabled and it's missing store identifiers"
- "Not propagating favorite state change for album artist (likedState=%d, timeStamp=%{public}@) with persistentID=%lld as it's missing store identifiers"
- "Not propagating favorite state change for album artist (likedState=%d, timeStamp=%{public}@) with persistentID=%lld as the request is not valid"
- "Not propagating favorite state change for playlist (likedState=%d, timeStamp=%{public}@) with persistentID=%lld as it's missing store identifiers"
- "Not propagating favorite state change for playlist (likedState=%d, timeStamp=%{public}@) with persistentID=%lld as the request is not valid"
- "Not propagating favorite state change for track (likedState=%d, timeStamp=%p) with persistentID=%lld as it's missing store identifiers"
- "Not propagating favorite state change for track (likedState=%d, timeStamp=%{public}@) with persistentID=%lld as cloudLibrary is not enabled and it's missing store identifiers"
- "Not propagating favorite state change for trackPID=%lld as the request is not valid (likedState=%d, timeStamp=%{public}@"
- "Not propagating liked state=%d for album=%{public}@"
```
