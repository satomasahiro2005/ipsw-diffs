## BackBoardHIDEventFoundation

> `/System/Library/PrivateFrameworks/BackBoardHIDEventFoundation.framework/BackBoardHIDEventFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3cdc4` | `0x3cf84` | **`+0x1c0`** |
| `__AUTH.__objc_data` | `0x4f0` | `0x400` | **`-0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0xc80` | `0xd70` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x6098` | `0x6100` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x32e0` | `0x3308` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1480` | `0x14a0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x22c8` | `0x22e8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3392` | `0x33af` | **`+0x1d`** |
| `__DATA.__objc_ivar` | `0x45c` | `0x468` | **`+0xc`** |
| `__DATA.__data` | `0xca0` | `0xca8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x400` | `0x408` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc28` | `0xc30` | **`+0x8`** |

### Other Changes

```diff

-868.0.0.0.0
+873.100.0.0.0

-  Functions: 1086
-  Symbols:   2416
-  CStrings:  686
+  Functions: 1089
+  Symbols:   2426
+  CStrings:  688
Symbols:
+ -[BKIOHIDServiceMatcher _notifyObserver:servicesDidMatch:]
+ -[BKIOHIDServiceMatcher setSessionID:]
+ -[BKIOHIDServicePersistentPropertyController unregisterHandler:]
+ GCC_except_table336
+ GCC_except_table394
+ GCC_except_table407
+ GCC_except_table410
+ GCC_except_table416
+ GCC_except_table419
+ GCC_except_table664
+ GCC_except_table667
+ GCC_except_table702
+ GCC_except_table751
+ GCC_except_table812
+ GCC_except_table824
+ GCC_except_table856
+ _OBJC_CLASS_$_NSMapTable
+ _OBJC_IVAR_$_BKIOHIDServiceMatcher._dataProviderSupportsSessionHoisting
+ _OBJC_IVAR_$_BKIOHIDServiceMatcher._matcherID
+ _OBJC_IVAR_$_BKIOHIDServiceMatcher._sessionID
+ __BKHIDServiceMatcherMap
+ __BKHIDServiceMatcherMapLock
+ __BKHIDServiceMatcherNextID
+ ___58-[BKIOHIDServiceMatcher _notifyObserver:servicesDidMatch:]_block_invoke
+ ___58-[BKIOHIDServiceMatcher _notifyObserver:servicesDidMatch:]_block_invoke_2
- GCC_except_table334
- GCC_except_table392
- GCC_except_table405
- GCC_except_table408
- GCC_except_table414
- GCC_except_table417
- GCC_except_table662
- GCC_except_table665
- GCC_except_table699
- GCC_except_table748
- GCC_except_table809
- GCC_except_table821
- GCC_except_table853
- ___40-[BKIOHIDServiceMatcher _servicesAdded:]_block_invoke
- ___56-[BKIOHIDServiceMatcher _lock_asyncNotifyServicesAdded:]_block_invoke_2
CStrings:
+ "Matcher with ID %ld not found; ignoring"
+ "dealloc without invalidation matching %d invalidated %d"
+ "r"
- "dealloc without invalidation"
```
