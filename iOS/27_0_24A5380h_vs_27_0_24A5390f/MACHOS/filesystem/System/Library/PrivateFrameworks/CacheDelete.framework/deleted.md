## deleted

> `/System/Library/PrivateFrameworks/CacheDelete.framework/deleted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a8a4` | `0x5b558` | **`+0xcb4`** |
| `__TEXT.__oslogstring` | `0xabe3` | `0xacf0` | **`+0x10d`** |
| `__TEXT.__objc_stubs` | `0x6880` | `0x6920` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x7d7f` | `0x7e16` | **`+0x97`** |
| `__DATA_CONST.__cfstring` | `0x4b40` | `0x4b80` | **`+0x40`** |
| `__TEXT.__cstring` | `0x493b` | `0x4977` | **`+0x3c`** |
| `__DATA.__objc_selrefs` | `0x1ee0` | `0x1f08` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x2fcc` | `0x2ff4` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1d08` | `0x1d28` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0xe7b` | `0xe8c` | **`+0x11`** |
| `__TEXT.__unwind_info` | `0xe00` | `0xe08` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-904.0.5.0.0
+904.0.7.0.0

-  Functions: 1236
-  Symbols:   3030
-  CStrings:  3154
+  Functions: 1240
+  Symbols:   3039
+  CStrings:  3165
Symbols:
+ +[CacheDeleteAnalytics appStatsBatchForFairPurgeResult:purgeAttempt:]
+ +[CacheDeleteAnalytics individualAppStatsForAppInfo:phase:purgeAttempt:]
+ +[CacheDeleteAnalytics isThirdPartyAppInfo:]
+ GCC_except_table64
+ GCC_except_table67
+ ___69+[CacheDeleteAnalytics appStatsBatchForFairPurgeResult:purgeAttempt:]_block_invoke
+ _objc_msgSend$appStatsBatchForFairPurgeResult:purgeAttempt:
+ _objc_msgSend$developerType
+ _objc_msgSend$individualAppStatsForAppInfo:phase:purgeAttempt:
+ _objc_msgSend$isThirdPartyAppInfo:
+ _objc_msgSend$sortUsingComparator:
- GCC_except_table56
- GCC_except_table63
CStrings:
+ ", "
+ "@40@0:8@16Q24Q32"
+ "Fair Purge Analytics: classified %lu first-party, %lu third-party apps"
+ "Fair Purge Analytics: first-party app bundles=[%@] visible=%d weight=%f purgeable=%llu purged=%llu"
+ "Fair Purge Analytics: third-party app bundles=[%@] visible=%d weight=%f purgeable=%llu purged=%llu"
+ "appStatsBatchForFairPurgeResult:purgeAttempt:"
+ "com.apple.cache_delete.fair_purge.aggregated_third_party"
+ "developerType"
+ "individualAppStatsForAppInfo:phase:purgeAttempt:"
+ "isThirdPartyAppInfo:"
+ "sortUsingComparator:"
```
