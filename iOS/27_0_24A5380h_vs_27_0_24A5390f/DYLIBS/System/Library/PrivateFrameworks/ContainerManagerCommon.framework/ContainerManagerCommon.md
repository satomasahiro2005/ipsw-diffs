## ContainerManagerCommon

> `/System/Library/PrivateFrameworks/ContainerManagerCommon.framework/ContainerManagerCommon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf1ad0` | `0xf2ffc` | **`+0x152c`** |
| `__TEXT.__oslogstring` | `0xe509` | `0xe701` | **`+0x1f8`** |
| `__AUTH.__objc_data` | `0xed8` | `0xd70` | **`-0x168`** |
| `__DATA_DIRTY.__objc_data` | `0x2f08` | `0x3070` | **`+0x168`** |
| `__DATA_DIRTY.__data` | `0x308` | `0x448` | **`+0x140`** |
| `__TEXT.__gcc_except_tab` | `0x22e0` | `0x240c` | **`+0x12c`** |
| `__AUTH.__data` | `0x198` | `0xd0` | **`-0xc8`** |
| `__DATA_CONST.__got` | `0x438` | `0x500` | **`+0xc8`** |
| `__TEXT.__objc_methlist` | `0xac8c` | `0xad2c` | **`+0xa0`** |
| `__DATA_DIRTY.__bss` | `0x618` | `0x6b0` | **`+0x98`** |
| `__DATA.__bss` | `0xf88` | `0xef8` | **`-0x90`** |
| `__AUTH_CONST.__objc_const` | `0x17050` | `0x170d0` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1880` | `0x18f8` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x3700` | `0x3750` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x4ca0` | `0x4ce0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x94b9` | `0x94f0` | **`+0x37`** |
| `__DATA.__common` | `0x18` | `—` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0x40` | `0x58` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2518` | `0x2530` | **`+0x18`** |
| `__DATA.__data` | `0x3ba0` | `0x3bb0` | **`+0x10`** |
| `__TEXT.__const` | `0x1320` | `0x1330` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xc0c` | `0xc14` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x520` | `0x528` | **`+0x8`** |

### Other Changes

```diff

-833.0.0.0.0
+833.0.3.0.0

-  Functions: 3639
-  Symbols:   6880
-  CStrings:  2000
+  Functions: 3653
+  Symbols:   6905
+  CStrings:  2012
Symbols:
+ +[MCMPOSIXUser _getCachedUID:GID:name:flush:onCacheMiss:]
+ +[MCMPOSIXUser _posixUserWithUID:GID:name:]
+ -[MCMContainerClassPath _readPendingHints]
+ -[MCMContainerClassPath _writePendingHints:]
+ -[MCMContainerClassPath decrementPendingHint:]
+ -[MCMContainerClassPath incrementPendingHint:]
+ -[MCMContainerClassPath pendingHint:]
+ -[MCMContainerClassPath resetPendingHint:]
+ -[MCMPOSIXPermission initWithUID:GID:mode:posixUser:isNull:]
+ -[MCMPOSIXUser naturalized]
+ -[MCMUserIdentity naturalized]
+ GCC_except_table1564
+ GCC_except_table1714
+ GCC_except_table1718
+ GCC_except_table1878
+ GCC_except_table1884
+ GCC_except_table1986
+ GCC_except_table2120
+ GCC_except_table2261
+ GCC_except_table2278
+ GCC_except_table2279
+ GCC_except_table2344
+ GCC_except_table2402
+ GCC_except_table2423
+ GCC_except_table2492
+ GCC_except_table2504
+ GCC_except_table2573
+ GCC_except_table2583
+ GCC_except_table2608
+ GCC_except_table2631
+ GCC_except_table2641
+ GCC_except_table2667
+ GCC_except_table2670
+ GCC_except_table2675
+ GCC_except_table2721
+ GCC_except_table2725
+ GCC_except_table2890
+ GCC_except_table2893
+ GCC_except_table2970
+ _OBJC_IVAR_$_MCMContainerClassPath._lock
+ _OBJC_IVAR_$_MCMContainerClassPath._lock_caseSensitive
+ _OBJC_IVAR_$_MCMContainerClassPath._lock_caseSensitiveDetermined
+ _OBJC_IVAR_$_MCMContainerClassPath._lock_classURLCreated
+ _OBJC_IVAR_$_MCMContainerClassPath._lock_supportsDataProtection
+ _OBJC_IVAR_$_MCMContainerClassPath._lock_supportsDataProtectionDetermined
+ _OBJC_IVAR_$_MCMContainerClassPath._lock_symlinkClassURLCreated
+ _OBJC_IVAR_$_MCMContainerClassPath._pendingHintsLock
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MCMContainerPathHasPendingHints
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MCMContainerPathHasPendingHints
+ __OBJC_$_PROTOCOL_REFS_MCMContainerPathHasPendingHints
+ __OBJC_LABEL_PROTOCOL_$_MCMContainerPathHasPendingHints
+ __OBJC_PROTOCOL_$_MCMContainerPathHasPendingHints
+ ___34+[MCMPOSIXUser posixUserWithName:]_block_invoke
+ ___37+[MCMPOSIXUser posixUserWithUID:GID:]_block_invoke
+ ___42-[MCMContainerClassPath _readPendingHints]_block_invoke
+ ___43+[MCMPOSIXUser _posixUserWithUID:GID:name:]_block_invoke
+ ___44-[MCMContainerClassPath _writePendingHints:]_block_invoke
+ ___57+[MCMPOSIXUser _getCachedUID:GID:name:flush:onCacheMiss:]_block_invoke
+ ___block_descriptor_48_e19_"MCMPOSIXUser"8?0l
+ ___block_descriptor_48_e8_32s_e19_"MCMPOSIXUser"8?0ls32l8
+ ___block_descriptor_56_e8_32s40r48r_e17_B16?0"NSError"8lr40l8r48l8s32l8
+ ___block_descriptor_60_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56r_e17_B16?0"NSError"8lr56l8s32l8s40l8s48l8
+ __getCachedUID:GID:name:flush:onCacheMiss:.cacheByName
+ __getCachedUID:GID:name:flush:onCacheMiss:.cacheByUID
+ __getCachedUID:GID:name:flush:onCacheMiss:.cacheByUIDGID
+ __getCachedUID:GID:name:flush:onCacheMiss:.onceToken
- +[MCMPOSIXUser _getCachedUID:flush:onCacheMiss:]
- +[MCMPOSIXUser _posixUserWithUID:name:useUID:]
- GCC_except_table1563
- GCC_except_table1713
- GCC_except_table1717
- GCC_except_table1877
- GCC_except_table1883
- GCC_except_table1984
- GCC_except_table2118
- GCC_except_table2259
- GCC_except_table2276
- GCC_except_table2277
- GCC_except_table2342
- GCC_except_table2400
- GCC_except_table2421
- GCC_except_table2490
- GCC_except_table2502
- GCC_except_table2571
- GCC_except_table2581
- GCC_except_table2606
- GCC_except_table2629
- GCC_except_table2639
- GCC_except_table2663
- GCC_except_table2668
- GCC_except_table2673
- GCC_except_table2731
- GCC_except_table2877
- GCC_except_table2880
- GCC_except_table2956
- _OBJC_IVAR_$_MCMContainerClassPath._caseSensitive
- _OBJC_IVAR_$_MCMContainerClassPath._caseSensitiveDetermined
- _OBJC_IVAR_$_MCMContainerClassPath._classURLCreated
- _OBJC_IVAR_$_MCMContainerClassPath._supportsDataProtection
- _OBJC_IVAR_$_MCMContainerClassPath._supportsDataProtectionDetermined
- _OBJC_IVAR_$_MCMContainerClassPath._symlinkClassURLCreated
- ___33+[MCMPOSIXUser posixUserWithUID:]_block_invoke
- ___46+[MCMPOSIXUser _posixUserWithUID:name:useUID:]_block_invoke
- ___48+[MCMPOSIXUser _getCachedUID:flush:onCacheMiss:]_block_invoke
- ___block_descriptor_40_e22_"MCMPOSIXUser"12?0I8l
- ___block_descriptor_52_e8_32s40s_e5_v8?0ls32l8s40l8
- __getCachedUID:flush:onCacheMiss:.cache
- __getCachedUID:flush:onCacheMiss:.onceToken
CStrings:
+ "02:13:54"
+ "@\"MCMPOSIXUser\"8@?0"
+ "Attempted to look up posix user with nil name."
+ "B16@?0@\"NSError\"8"
+ "Could not read pending hints, JSON decode failed; classPath = %@, error = %@"
+ "Could not read pending hints; classPath = %@, error = %@"
+ "Could not write pending hints, JSON encode failed; classPath = %@, error = %@"
+ "Could not write pending hints; classPath = %@, error = %@"
+ "Failed to naturalize POSIX user; user = %@"
+ "Jul  8 2026"
+ "MobileContainerManager-833.0.3~136"
+ "Pending hints xattr did not decode to a dictionary; classPath = %@, top-level type = %@"
+ "Removing [%@] xattr on [%@]"
+ "Unable to get user (%u/[%@]); error = %{public}s"
+ "Writing [%@] xattr to [%@]; value = %@"
+ "com.apple.containermanager.hints"
+ "dp"
- "02:57:11"
- "@\"MCMPOSIXUser\"12@?0I8"
- "Jun 23 2026"
- "MobileContainerManager-833~402"
- "Unable to get user (%u/[%@]/%{public}d); error = %{public}s"
```
