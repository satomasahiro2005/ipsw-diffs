## QuickLookThumbnailingDaemon

> `/System/Library/PrivateFrameworks/QuickLookThumbnailingDaemon.framework/QuickLookThumbnailingDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5460c` | `0x54afc` | **`+0x4f0`** |
| `__AUTH_CONST.__objc_const` | `0x5368` | `0x5478` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x5555` | `0x5645` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x3204` | `0x326c` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x24d0` | `0x2518` | **`+0x48`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x20` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x490` | `0x4ac` | **`+0x1c`** |
| `__AUTH_CONST.__objc_arrayobj` | `—` | `0x18` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1008` | `0x1018` | **`+0x10`** |
| `__TEXT.__const` | `0x1004` | `0x1014` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-218.1.1.0.0
+218.1.3.200.0

-  Functions: 2030
-  Symbols:   2722
-  CStrings:  876
+  Functions: 2040
+  Symbols:   2739
+  CStrings:  878
Symbols:
+ +[QLDiskCache prepareCacheAtLocation:]
+ -[QLDiskCache lastOpenErrno]
+ -[QLServerThread locationCacheLock]
+ -[QLServerThread locationsToCaches]
+ -[QLServerThread setLocationsToCaches:]
+ -[QLThumbnailAdditionIndex _protectDatabaseFiles]
+ -[_QLCacheThread _allowCacheOpenRetries]
+ -[_QLCacheThread _clearCacheOpenThrottleForTesting]
+ -[_QLCacheThread _reopenCacheIfDue]
+ GCC_except_table41
+ GCC_except_table43
+ GCC_except_table45
+ GCC_except_table54
+ GCC_except_table71
+ GCC_except_table75
+ GCC_except_table80
+ GCC_except_table84
+ GCC_except_table90
+ GCC_except_table92
+ OBJC_IVAR_$_QLDiskCache._lastOpenErrno
+ OBJC_IVAR_$__QLCacheThread._failedOpenAttempts
+ OBJC_IVAR_$__QLCacheThread._gaveUpOpeningCache
+ OBJC_IVAR_$__QLCacheThread._lastCacheOpenAttempt
+ OBJC_IVAR_$__QLCacheThread._resetDeferred
+ _OBJC_CLASS_$_NSConstantArray
+ _OBJC_IVAR_$_QLServerThread._locationCacheLock
+ _OBJC_IVAR_$_QLServerThread._locationsToCaches
+ _QLTProtectCacheAtLocation
+ _QLTProtectCacheItemAtPath
+ _QLTThumbnailCacheProtectionAttributes
- GCC_except_table40
- GCC_except_table42
- GCC_except_table44
- GCC_except_table47
- GCC_except_table51
- GCC_except_table53
- GCC_except_table68
- GCC_except_table72
- GCC_except_table77
- GCC_except_table81
- GCC_except_table87
- GCC_except_table89
- _fcntl
CStrings:
+ "Could not fully protect the thumbnail cache at '%@' yet"
+ "Could not open the cache; will retry on a later request"
+ "Giving up on the cache after %lu failed opens (errno %d); -reset will re-enable it"
+ "Not opening the cache at '%@' yet: it is not fully protected, so the device is still locked"
+ "\xf0\xf0\xb1"
- "Problem to open the cache, so we disabled it"
- "\xf0\xf0\x81"
- "\xf1"
```
