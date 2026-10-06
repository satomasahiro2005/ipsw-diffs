## LoginKit

> `/System/Library/PrivateFrameworks/LoginKit.framework/LoginKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf5d4` | `0xf570` | **`-0x64`** |
| `__TEXT.__unwind_info` | `0x478` | `0x470` | **`-0x8`** |

### Other Changes

```diff

-3030.0.0.0.0
+3031.0.0.0.0
Functions:
~ ___83-[LKAttentionAwareIdleTimer startMonitoringAttentionAwareIdleWithDelegate:timeout:]_block_invoke : 676 -> 672
~ ___82-[LKAttentionAwareIdleTimer stopMonitoringAttentionAwareIdleWithDelegate:timeout:]_block_invoke : 432 -> 428
~ -[LKLoginController recentUsers] : 376 -> 372
~ -[LKClassGroup initWithClassGroupDictionary:classesDictionaryByClassID:] : 608 -> 604
~ +[LKLoginSupport findLeastRecentlyUsedCleanUser] : 388 -> 384
~ +[LKLoginSupport hasCleanUser] : 284 -> 280
~ -[LKClass initWithClassDictionary:usersByUserIdentifier:] : 812 -> 804
~ -[LKClassConfiguration initWithDictionary:] : 2120 -> 2108
~ -[LKClassConfiguration studentForStudentIdentifier:inClass:] : 428 -> 424
~ -[LKClassConfiguration studentForUsername:inClass:] : 428 -> 424
~ -[LKClassConfiguration classesByClassGroupNameDictionary] : 384 -> 380
~ -[LKBacktraceLogger _getBacktraceFromThread:] : 868 -> 856
~ -[LKBacktraceLogger _symbolicateBuffer:symbolsBuffer:count:] : 132 -> 112
~ -[LKUniversalDiskStorage clearKeys:] : 668 -> 664
~ -[LKSwitchOperation dictionary] : 592 -> 588
~ ___43-[LKLogoutSupport _syncPreferencesIfNeeded]_block_invoke : 908 -> 904
```
