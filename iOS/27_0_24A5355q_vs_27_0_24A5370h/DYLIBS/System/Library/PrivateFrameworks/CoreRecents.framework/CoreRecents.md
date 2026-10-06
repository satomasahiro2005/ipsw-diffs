## CoreRecents

> `/System/Library/PrivateFrameworks/CoreRecents.framework/CoreRecents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc610` | `0xc5fc` | **`-0x14`** |

### Other Changes

```text
Functions:
~ +[CRRecentContactSorting sortRecents:forQuery:] : 600 -> 596
~ -[CRRecentContactsLibrary _recordContactEvents:recentsDomain:sendingAddress:source:userInitiated:completion:] : 932 -> 928
~ -[CRRecentContact description] : 428 -> 424
~ -[NSString(CoreRecentsUtilities) cr_rangeOfAddressDomain] : 956 -> 964
~ -[NSString(CoreRecentsUtilities) cr_uniqueFilenameWithRespectToFilenames:] : 424 -> 420
~ -[NSArray(CoreRecentsUtilities) cr_firstObjectPassingTest:] : 268 -> 264
~ -[NSArray(CoreRecentsUtilities) cr_map:] : 316 -> 312
~ -[NSArray(CoreRecentsUtilities) cr_insertionSortedArrayUsingComparator:] : 284 -> 280
```
