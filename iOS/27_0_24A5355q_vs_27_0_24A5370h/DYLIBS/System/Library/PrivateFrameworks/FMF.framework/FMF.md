## FMF

> `/System/Library/PrivateFrameworks/FMF.framework/FMF`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ff28` | `0x1ff00` | **`-0x28`** |

### Other Changes

```text
Functions:
~ +[FMFSchedule firstDateFromDates:order:] : 316 -> 312
~ ___47-[FMFSession(Admin) getThisDeviceAndCompanion:]_block_invoke : 464 -> 460
~ ___59-[FMFHandle correlationIdentifierForHandle:withCompletion:]_block_invoke : 300 -> 296
~ -[FMFSessionDataManager setLocations:] : 668 -> 664
~ -[FMFMapCache pruneCacheIfNeeded] : 1048 -> 1044
~ ___27-[FMFSession setLocations:]_block_invoke : 292 -> 288
~ +[FMFSession isAnyAccountManaged] : 368 -> 364
~ _GEOSouthKoreaRegion : 404 -> 400
~ -[FMFFence handlesForArray:] : 352 -> 348
~ -[FMFContactUtility findOptimalContactInContacts:] : 448 -> 444
```
