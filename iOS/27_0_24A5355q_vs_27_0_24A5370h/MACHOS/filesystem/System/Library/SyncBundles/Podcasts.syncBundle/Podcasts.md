## Podcasts

> `/System/Library/SyncBundles/Podcasts.syncBundle/Podcasts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x95e8` | `0x9178` | **`-0x470`** |
| `__TEXT.__oslogstring` | `0x1345` | `0x128f` | **`-0xb6`** |
| `__TEXT.__objc_methname` | `0x1ec9` | `0x1f51` | **`+0x88`** |
| `__TEXT.__objc_stubs` | `0x1480` | `0x14e0` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x1a0` | `0x1e0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x380` | `0x3a8` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x8d8` | `0x8f0` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x902` | `0x913` | **`+0x11`** |
| `__TEXT.__auth_stubs` | `0x470` | `0x460` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2f0` | `0x2e0` | **`-0x10`** |
| `__TEXT.__cstring` | `0x322` | `0x32e` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x248` | `0x240` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x96c` | `0x974` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-4027.100.59.0.0
+4027.100.70.0.0

-  Functions: 153
-  Symbols:   122
-  CStrings:  537
+  Functions: 151
+  Symbols:   121
+  CStrings:  541
Symbols:
+ _OBJC_CLASS_$_MTEpisode
+ _kEpisodeMediaEnclosures
- _OBJC_CLASS_$_MTStoreIdentifier
- _kMTEpisodeEntityName
- _objc_retain_x27
CStrings:
+ "Cleanup task will clear assetURL %@"
+ "PSUB"
+ "Requesting secure deletion for episode asset at path %@"
+ "Will remove asset for <%@ - %@> at path %@ with adam id %lld"
+ "_deleteEpisodesMatchingPredicate:"
+ "_deleteEpisodesMatchingPredicate:clearDownloadBehavior:"
+ "_deleteEpisodesMatchingPredicate:fetchLimit:clearDownloadBehavior:"
+ "byteSize"
+ "episode"
+ "mediaEnclosures"
+ "movpkg"
+ "predicateForEpisodeUuid:"
+ "priceType"
+ "setFetchLimit:"
+ "setRelationshipKeyPathsForPrefetching:"
+ "v36@0:8@16Q24B32"
- "Cleanup task will clear assetURL for episode %@"
- "Deleted fully played manual download (%@ - %@) at path %@"
- "Deleted unpinned episode <%@ - %@> at path %@ with adam id %lld"
- "Failed to remove episode asset at path for fully played manual download (%@ - %@) at path %@ - %@"
- "Requesting secure deletion for episode <%@ - %@> with adam id %lld"
- "_clearAssetURLForEpisode:"
- "_deleteEpisodesNotInUUIDs:"
- "isNotEmpty:"
- "keyEnumerator"
- "objectEnumerator"
- "removeObjectForKey:"
- "setReturnsObjectsAsFaults:"
```
