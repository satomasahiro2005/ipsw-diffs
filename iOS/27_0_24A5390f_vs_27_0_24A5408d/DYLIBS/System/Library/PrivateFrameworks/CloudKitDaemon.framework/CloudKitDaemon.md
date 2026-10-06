## CloudKitDaemon

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/CloudKitDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3dacf0` | `0x3dce8c` | **`+0x219c`** |
| `__TEXT.__oslogstring` | `0x32470` | `0x3275f` | **`+0x2ef`** |
| `__AUTH_CONST.__objc_const` | `0x4ab70` | `0x4ad60` | **`+0x1f0`** |
| `__TEXT.__objc_methlist` | `0x3156c` | `0x316d4` | **`+0x168`** |
| `__DATA_CONST.__objc_selrefs` | `0x12ff0` | `0x130b0` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x5300` | `0x53a0` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x23820` | `0x238c0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0xce78` | `0xcf10` | **`+0x98`** |
| `__TEXT.__gcc_except_tab` | `0xc7dc` | `0xc86c` | **`+0x90`** |
| `__TEXT.__cstring` | `0x2b130` | `0x2b0d5` | **`-0x5b`** |
| `__AUTH_CONST.__const` | `0x51c8` | `0x51e8` | **`+0x20`** |
| `__DATA.__data` | `0x1da8` | `0x1dc8` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0xcc0` | `0xcd8` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x14d8` | `0x14e8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x13b8` | `0x13c8` | **`+0x10`** |
| `__DATA_DIRTY.__objc_ivar` | `0x1964` | `0x1970` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x2038` | `0x2040` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1a88` | `0x1a8c` | **`+0x4`** |

### Other Changes

```diff

-2710.116.0.0.0
+2710.119.0.0.0

-  Functions: 20633
-  Symbols:   2947
-  CStrings:  8460
+  Functions: 20664
+  Symbols:   2949
+  CStrings:  8475
Symbols:
+ _OBJC_CLASS_$_CKDMMCSRequestOptions
+ _OBJC_METACLASS_$_CKDMMCSRequestOptions
CStrings:
+ "(%@) addZoneID:withParentZoneID: failed with SQLite database error: %@"
+ "(%@) addZoneID:withParentZoneID: ignoring self-parent relation for zone %@"
+ "(%@) ancestorZoneShareIDsForZoneID failed with SQLite database error: %@"
+ "(%@) ancestorZoneShareIDsForZoneID: cycle detected at rowID %@"
+ "(%@) ancestorZoneShareIDsForZoneID: walk exceeded max depth %lu"
+ "(%@) hasParentRecordForRecordID failed with SQLite database error: %@"
+ "(%@) hasParentZoneForZoneID failed with SQLite database error: %@"
+ "(%@) removeParentForZoneID failed with SQLite database error: %@"
+ ", governingShareRecordID=%@"
+ "Couldn't serialize rolled zone PCS for zone %@. Error: %@"
+ "Couldn't serialize rolled zoneish PCS for zone %@. Error: %@"
+ "Error removing previous parent PCS from zone %@. Error: %@"
+ "Error rolling zonePCS for zone %@"
+ "GoverningShareRecordID"
+ "Rolled zone PCS for zone %@ during zone save (ancestor PCS processing was skipped)."
+ "Rolling existing zone %@ due to reparenting to %@ (shared on either side; re-keying to revoke any cached access)"
+ "Self got deallocated while determining ancestor PCS processing"
+ "Skipping key rolling for zone %@: unshared before and after reparent"
+ "Zone-wide share fetch completed without returning every requested record"
+ "ZoneHierarchyTable"
+ "childZoneRowID"
+ "parentZoneRowID"
+ "removeChildrenWithParentZoneRowID"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CloudKitTools/Sources/CloudKitDaemon/Accounts/CKDAccountDataSecurityObserver.m"
- "Attempted to fetch manatee status on incorrect persona. expected: %@, got: %@"
- "Attempted to fetch walrus status on incorrect persona. expected: %@, got: %@"
- "Could not fetch parent PCS for zone %@ while checking whether reparent rolling is needed."
- "Error removing previous parent PCS from zone %@: %@"
- "Rolling existing zone %@ due to reparenting to %@"
- "Self got deallocated while fetching PCS for zone %@"
- "Self got deallocated while fetching parent PCS for zone %@"
```
