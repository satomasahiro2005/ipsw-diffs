## IMTransferAgent

> `/System/Library/PrivateFrameworks/IMTransferAgent.framework/IMTransferAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16140` | `0x16c14` | **`+0xad4`** |
| `__TEXT.__oslogstring` | `0x25d7` | `0x2a69` | **`+0x492`** |
| `__TEXT.__gcc_except_tab` | `0x1688` | `0x1720` | **`+0x98`** |
| `__TEXT.__cstring` | `0xb62` | `0xbb3` | **`+0x51`** |
| `__DATA_CONST.__const` | `0x7e0` | `0x830` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0xd60` | `0xda0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xd50` | `0xd70` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x570` | `0x588` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xa74` | `0xa84` | **`+0x10`** |
| `__TEXT.__const` | `0x118` | `0x110` | **`-0x8`** |

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4

-  Symbols:   261
-  CStrings:  338
+  Symbols:   263
+  CStrings:  352
Symbols:
+ _objc_release_x2
+ _os_activity_apply
CStrings:
+ "%@ Dispatching CloudKit operation, retryInterval: %f"
+ "%@ Failed CloudKit operation. Too many retries."
+ "%@ Going to delete nicknames from public db %@ and save nickname to public db %@"
+ "%@ Have some wallpaper tag: %i, knownSender: %i, shouldFetchWallpaperRecord: %i, wallpaperRecordID: %@"
+ "%@ Public Nickname record found %@"
+ "%@ Public Nickname retrieval completed with error %@"
+ "%@ Public Nickname with recordID Publish completed with error %@"
+ "%@ Public Wallpaper record found %@"
+ "%@ Public nickname retrieval errors %@"
+ "%@ Transfer agent sending back nickname: %@"
+ "%@ We should not retry the ck operation on this error %@"
+ "%@ We should retry the ck operation"
+ "B16@?0@\"NSError\"8"
+ "Device does not support name and photo."
+ "Going to delete recordIDs %@, with error: %@"
+ "Nicknames CloudKit attempt"
+ "No nicknames to delete (fetch error: %@)"
+ "Transfer_Nicknames - %@ Failed to create nickname from record {error: %@, preKey: %@, nicknameRecord: %@}"
+ "Transfer_Nicknames - %@ Failed to generate preKey from data -- failed to fetch public nickname record {error: %@, recordID: %@}"
+ "Transfer_Nicknames - %@ We did not have success deleting the records, not retrying"
+ "Transfer_Nicknames - %@ We got a conflict error while trying to upload to CK, we should not overwrite the record %@"
+ "Transfer_Nicknames - %@ We got a server rejected request, this is unrecoverable so we shouldn't retry"
+ "Transfer_Nicknames - %@ We got an error modifying the records {error: %@, saved records: %@, deleted records: %@}"
+ "Transfer_Nicknames - %@ We got an unique index constraint violation, we should clear the existing records and then retry"
+ "Transfer_Nicknames - Failed to create public nickname record -- saving public nickname failed {error: %@, preKey: %@}"
+ "Transfer_Nicknames - Failed to generate publicNicknameEncryptionPreKey -- saving public nickname failed {error: %@}"
+ "Transfer_Nicknames - Failed to update nickname with recordID: %@ with error: %@"
+ "[retry %lu/%lu]"
+ "v24@?0@?<B@?@\"NSError\">8Q16"
- "B8@?0"
- "Dispatching CloudKit operation with retry: %lu and retryInterval: %f"
- "Failed CloudKit operation. Too many retries."
- "Going to delete nicknames from public db %@ and save nickname to public db %@"
- "Going to delete recordIDs %@, with error"
- "Have some wallpaper tag: %i, knownSender: %i, shouldFetchWallpaperRecord: %i, wallpaperRecordID: %@"
- "Public Nickname record found %@"
- "Public Nickname retrieval completed with error %@"
- "Public Nickname with recordID Publish completed with error %@"
- "Public Wallpaper record found %@"
- "Public nickname retrieval errors %@"
- "Transfer agent sending back nickname: %@"
- "We should not retry the ck operation on this error %@"
- "We should retry the ck operation %@"
- "v16@?0@?<B@?>8"
```
