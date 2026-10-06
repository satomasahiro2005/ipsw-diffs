## CloudKitDaemon

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/CloudKitDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ec364` | `0x3ede34` | **`+0x1ad0`** |
| `__TEXT.__cstring` | `0x2b11e` | `0x2b395` | **`+0x277`** |
| `__TEXT.__oslogstring` | `0x32f64` | `0x330f8` | **`+0x194`** |
| `__AUTH_CONST.__cfstring` | `0x238e0` | `0x23a20` | **`+0x140`** |
| `__TEXT.__gcc_except_tab` | `0xc894` | `0xc988` | **`+0xf4`** |
| `__AUTH_CONST.__objc_const` | `0x4ae60` | `0x4af20` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x3177c` | `0x31834` | **`+0xb8`** |
| `__DATA_CONST.__objc_selrefs` | `0x13100` | `0x13180` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0xd1b8` | `0xd210` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x9a18` | `0x9a68` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x53a8` | `0x5388` | **`-0x20`** |
| `__DATA_DIRTY.__objc_ivar` | `0x1978` | `0x1984` | **`+0xc`** |
| `__TEXT.__const` | `0x4e08` | `0x4e10` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1a90` | `0x1a94` | **`+0x4`** |

### Other Changes

```diff

-2720.14.0.0.0
+2720.15.0.0.0

-  Functions: 20972
+  Functions: 20995

-  CStrings:  8514
+  CStrings:  8528
CStrings:
+ "Couldn't decrypt ancestor share %@: %@"
+ "Couldn't decrypt the share PCS for fetched zone %@: %@"
+ "Couldn't decrypt the share PCS of zone %@"
+ "Couldn't decrypt the zone PCS for fetched zone %@"
+ "Couldn't decrypt the zone PCS for fetched zone %@: %@"
+ "Couldn't decrypt the zoneish PCS for zone %@"
+ "Couldn't spawn an operation to decrypt fetched ancestor shares"
+ "Decrypting record %@ with the zone PCS supplied for zone %@ instead of fetching it"
+ "FailFirstDecryptWithSuppliedZonePCS"
+ "FailIfZonePCSFetchNeededToDecryptRecord"
+ "Failed to decrypt publicPCS for share %@ on zone %@ using invitedPCS"
+ "Fetch operation was deallocated before its ancestor chain could be wired"
+ "Fetch operation was deallocated before its ancestor shares could be decrypted"
+ "Fetch operation was deallocated before zone %@ could be decrypted"
+ "Fetched an ancestor zone without a zoneID"
+ "Fetched discontinuous ancestors for zone %@: zone %@ has parent %@, which is not the next zone returned, %@"
+ "Missing decrypted share PCS for fetched zone %@; rolling its parent requires the share's invitedPCS"
+ "Missing decrypted share PCS for zone %@"
+ "Missing decrypted zonePCS for fetched zone %@; rolling requires every ancestor zone's PCS"
+ "Missing decrypted zonePCS for zone %@"
+ "Record %@ needed a zone PCS fetch to decrypt, which this test forbids"
+ "Record %@ was failed on its supplied zone PCS by a test hook"
+ "Skipping ancestor PCS processing for zones %@ because encryption is disabled"
+ "Supplied zone PCS for zone %@ has no zoneish PCS but record %@ needs one. Fetching instead"
+ "v40@?0@\"CKRecordZoneID\"8@\"NSArray\"16@\"NSDictionary\"24@\"NSError\"32"
- "Could not decrypt zonePCS for zone %@"
- "Could not decrypt zoneishPCS for zone %@. "
- "Failed to decrypt invitedPCS for share %@ on zone %@ using parent zonePCS. Error:%@"
- "Failed to decrypt publicPCS for share %@ using invitedPCS %@"
- "Failed to decrypt publicPCS for share %@ using invitedPCS %@. Error %@."
- "Fetched ancestor zone is not continuous. Last zone: %@. Last zone's parent ID %@ does not match the current zoneID %@"
- "Fetched discontinuous ancestor array for leaf zone %@. Ancestors:%@"
- "Fetched zone %@ lacks protectionData."
- "We don't have zone PCS data to decrypt for zone %@"
- "Zone:%@. Parent:%@"
- "com.apple.cloudkit.processAncestors"
```
