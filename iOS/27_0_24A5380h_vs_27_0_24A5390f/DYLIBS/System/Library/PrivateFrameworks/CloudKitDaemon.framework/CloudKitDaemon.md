## CloudKitDaemon

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/CloudKitDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d8d80` | `0x3dacf0` | **`+0x1f70`** |
| `__DATA_DIRTY.__objc_data` | `0x7c48` | `0x83c8` | **`+0x780`** |
| `__AUTH.__objc_data` | `0x5a30` | `0x5300` | **`-0x730`** |
| `__AUTH_CONST.__objc_const` | `0x4a9b0` | `0x4ab70` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0x322e8` | `0x32470` | **`+0x188`** |
| `__TEXT.__gcc_except_tab` | `0xc664` | `0xc7dc` | **`+0x178`** |
| `__TEXT.__objc_methlist` | `0x31444` | `0x3156c` | **`+0x128`** |
| `__DATA_CONST.__objc_selrefs` | `0x12f40` | `0x12ff0` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x237a0` | `0x23820` | **`+0x80`** |
| `__TEXT.__cstring` | `0x2b0de` | `0x2b130` | **`+0x52`** |
| `__DATA.__data` | `0x1df8` | `0x1da8` | **`-0x50`** |
| `__DATA_DIRTY.__data` | `0x2218` | `0x2268` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xce40` | `0xce78` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x99c0` | `0x99e8` | **`+0x28`** |
| `__TEXT.__const` | `0x4bf8` | `0x4c18` | **`+0x20`** |
| `__DATA_DIRTY.__objc_ivar` | `0x1950` | `0x1964` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x2168` | `0x2178` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x14d0` | `0x14d8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x13b0` | `0x13b8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1a84` | `0x1a88` | **`+0x4`** |

### Other Changes

```diff

-2710.114.0.0.0
+2710.116.0.0.0

-  Functions: 20606
-  Symbols:   2944
-  CStrings:  8446
+  Functions: 20633
+  Symbols:   2947
+  CStrings:  8460
Symbols:
+ _CKDPCSExistingFetchOptionsCanSatisfyRequestedOptions
+ _CKLinkCheck67c944b220f944039d015d402e20c1e8
+ _CKStringFromParticipantPermission
+ _OBJC_METACLASS_$_NSFileHandle
- _CKDPCSFetchOptionsCanSatisfyOptions
CStrings:
+ "Clearing only the SQL PCS cache for container %p"
+ "Clearing only the record cache for container %p"
+ "Clearing the SQL PCS cache, leaving the in-memory caches intact"
+ "Could not fetch parent PCS for zone %@ while checking whether reparent rolling is needed."
+ "End traffic log for operation"
+ "Failed to register push token for %@: %@"
+ "Fetch for zone %@ %@ the zone parentPCS"
+ "Missing PCS for zone %@ while aligning parent PCS"
+ "No parent identity found on updated child zone PCS for zone %@ while preparing share %@"
+ "Parent %@ of zone %@ PCS not found in cache, attempting to decrypt via direct share"
+ "Self got deallocated while fetching PCS for zone %@"
+ "Self got deallocated while fetching parent PCS for zone %@"
+ "Skipping ancestor PCS prepping. Operation uses encryption: %@. Container uses zone-wide PCS: %@. Database scope is %@. Save PCS only: %@."
+ "Skipping dependent zone PCS fetch for share %@ to avoid a share/zone fetch cycle"
+ "Skipping parent PCS prep for PCS only zone save."
+ "Skipping push token registration for test container tuple %@"
+ "Skipping push token removal for test container tuple %@"
+ "Skipping push token unregister for test container tuple %@"
+ "Skipping share PCS prep for PCS only zone save."
+ "Skipping zone PCS prep for PCS only zone save."
+ "Traffic log for request "
+ "Updating permission for %@ participant %@ from %{public}@ -> %{public}@ to match the public permission on share %@"
+ "did not request"
+ "requested"
+ "skip-dependent-zone"
- "Detected zone PCS oplock for zone %@ with missing local parent and parent-tagged PCS. Fetching full zone metadata before retry."
- "Failed to fetch zone %@ while recovering from parent-tagged PCS oplock. Continuing with standard retry path. Error: %@"
- "Fetched zone %@ for parent-tagged PCS oplock recovery did not include usable protection data. Falling back to PCS reset and re-fetch."
- "Fetched zone %@ while recovering from parent-tagged PCS oplock did not have a repairable parent. Continuing with standard retry path."
- "Parent %@ of zone %@ PCS not found in cache, attempting share-based decryption"
- "Skipping ancestor PCS prepping. Operation uses encryption: %@. Container uses zone-wide PCS: %@. Database scope is %@. Operation originator is %lu."
- "Unable to fetch zone %@ while recovering from zone PCS oplock"
- "Warn: Failed to register push token for %@: %@"
- "ck26eecl"
- "pcs sharee is incorrectly tagged as parent pcs key"
- "v24@?0@\"CKRecordZone\"8@\"NSError\"16"
```
