## CloudKit

> `/System/Library/Frameworks/CloudKit.framework/CloudKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x367004` | `0x3698bc` | **`+0x28b8`** |
| `__TEXT.__oslogstring` | `0x16f52` | `0x17326` | **`+0x3d4`** |
| `__AUTH_CONST.__cfstring` | `0x1df00` | `0x1e060` | **`+0x160`** |
| `__TEXT.__cstring` | `0x21086` | `0x211da` | **`+0x154`** |
| `__AUTH_CONST.__const` | `0x11f08` | `0x11ff8` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x218dc` | `0x2197c` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x105cc` | `0x10654` | **`+0x88`** |
| `__AUTH_CONST.__objc_const` | `0x39b30` | `0x39bb0` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0xbf98` | `0xbff0` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0xabc4` | `0xac14` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x11158` | `0x111a0` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x3b14` | `0x3b54` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x6f58` | `0x6f90` | **`+0x38`** |
| `__AUTH.__data` | `0x1908` | `0x1928` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1d7f` | `0x1d9f` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x6bc2` | `0x6be0` | **`+0x1e`** |
| `__AUTH_CONST.__objc_intobj` | `0xc60` | `0xc78` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x2924` | `0x293c` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0xb98` | `0xba8` | **`+0x10`** |
| `__TEXT.__const` | `0xe3b0` | `0xe3c0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2538` | `0x2544` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0xe74` | `0xe80` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x197c` | `0x1984` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xe78` | `0xe80` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x764` | `0x768` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x884` | `0x888` | **`+0x4`** |

### Other Changes

```diff

-2710.116.0.0.0
+2710.119.0.0.0

-  Functions: 24283
-  Symbols:   6515
-  CStrings:  6248
+  Functions: 24333
+  Symbols:   6520
+  CStrings:  6277
Symbols:
+ _$sSo11CKContainerC8CloudKitE25fetchOrgAdminUserRecordIDSo08CKRecordI0CSgyYaKF
+ _$sSo11CKContainerC8CloudKitE25fetchOrgAdminUserRecordIDSo08CKRecordI0CSgyYaKFTu
+ _CKCurrentProcessIsContainerized
+ _CKDataFromFileAtPathWithAttributes
+ _CKSQLiteContainerAttribution_AgentSessionStoreSecure
CStrings:
+ "%s credentials are valid again. Scheduling sync."
+ "%s setting isWaitingForValidCredentials from last error"
+ "AccountInfoCache.archive"
+ "AgentSessionStoreSecure"
+ "CKSQLiteContainerAttribution_AgentSessionStoreSecure"
+ "Cleared in-memory account info cache after auth failure."
+ "Cleared in-memory account info cache."
+ "Containers"
+ "Could not locate caches directory for account info cache: %@"
+ "Could not read account info validation counter. (This is a potential performance issue.)"
+ "Failed to read account info cache file %@: %@"
+ "Failed to remove account info cache directory %@: %@"
+ "Failed to remove account info cache file %@: %@"
+ "Failed to unarchive account info cache (archive length %lu): %@"
+ "Failed to write account info cache file %@ %@ after recreating its directory with error %@"
+ "Failed to write account info cache file %@ %@: %@"
+ "Failed to write account info cache file %@ with error %@ %@. Could not recreate its directory: %@"
+ "FrameworkCachesDirectory"
+ "Malformed package archive"
+ "Missing package archive"
+ "Obsolete package archive"
+ "Read account info from %{public}@ cache."
+ "Received updated framework cache directory from cloudd %@"
+ "Removed account info cache directory %@"
+ "Removed legacy CloudKitAccountInfoCache user-defaults entry."
+ "Skipping account info cache write: setup hash is nil or empty."
+ "Waiting for valid credentials"
+ "Wrote account info cache file %@ %@"
+ "Wrote account info cache file %@ %@ after recreating its directory"
+ "com.apple.agentsessionstore.secure"
+ "com.apple.cloudkit.CKAccountInfoFIOQueue"
+ "fetchOrgAdminUserRecordID()"
+ "globally"
+ "in the data container"
+ "in-memory"
+ "on-disk"
- "CKAccountInfoCacheReset"
- "Cleared account info cache."
- "Clearing in-memory account info cache after auth failure."
- "Could not validate account info cache. (This is a potential performance issue.)"
- "Failed to unarchive account info cache: %@"
- "Unknown error unarchiving CKPackage"
- "a"
```
