## CalendarDaemon

> `/System/Library/PrivateFrameworks/CalendarDaemon.framework/CalendarDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76ebc` | `0x77890` | **`+0x9d4`** |
| `__TEXT.__gcc_except_tab` | `0x1b20` | `0x1bcc` | **`+0xac`** |
| `__DATA_CONST.__const` | `0x2200` | `0x2250` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0xce80` | `0xcec0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xa70` | `0xa98` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x6954` | `0x697c` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1c68` | `0x1c70` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x860` | `0x868` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1d48` | `0x1d50` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1246.0.0.0.0
+1246.1.4.0.0

-  Functions: 2347
-  Symbols:   5599
+  Functions: 2350
+  Symbols:   5612
Symbols:
+ -[CADInMemoryChangeTimestamp hash]
+ -[CADInMemoryChangeTimestamp isEqual:]
+ -[CADStatsCalendars accountTypeForStore:]
+ -[CADStatsReminders eventDictionaries]
+ -[CADXPCImplementation(CADDatabaseOperationGroup) insert:deletes:updates:insertedObjectIDMap:inDatabase:selfTimestamp:]
+ _ACAccountTypeIdentifierAppleAccount
+ _ACAccountTypeIdentifierExchange
+ _ACAccountTypeIdentifierGmail
+ _ACAccountTypeIdentifierYahoo
+ _CalDatabaseSaveWithOptionsAndOutSelfTimestamp
+ _OBJC_IVAR_$_CADStatsCalendarInfo._accountType
+ _OBJC_IVAR_$_CADStatsCalendarInfo._storeType
+ ___block_descriptor_112_e8_32s40s48s56s64s72s80s88s96s104r_e340_v20?0i8^{CalDatabase={__CFRuntimeBase=QAQ}Q^{CPRecordStore}^{CalEventOccurrenceCache}^{CalScheduledTaskCache}^v^v^{__CFDictionary}^{__CFDictionary}{os_unfair_lock_s=I}II^{__CFArray}^{__CFString}^{__CFArray}ii^{__CFString}^{__CFURL}^{__CFString}^{__CFString}Qiii?{_opaque_pthread_mutex_t=q[56c]}B^{__CFArray}B^{__CFSet}*IIiQBBBBBBB}12lr104l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8
+ ___block_descriptor_112_e8_32s40s48s56s64s72s80s88s96s104r_e340_v20?0i8^{CalDatabase={__CFRuntimeBase=QAQ}Q^{CPRecordStore}^{CalEventOccurrenceCache}^{CalScheduledTaskCache}^v^v^{__CFDictionary}^{__CFDictionary}{os_unfair_lock_s=I}II^{__CFArray}^{__CFString}^{__CFArray}ii^{__CFString}^{__CFURL}^{__CFString}^{__CFString}Qiii?{_opaque_pthread_mutex_t=q[56c]}B^{__CFArray}B^{__CFSet}*IIiQBBBBBBB}12ls32l8s40l8s48l8s56l8r104l8s64l8s72l8s80l8s88l8s96l8
+ ___block_descriptor_64_e8_32s40s48r56r_e352_v28?0i8"NSArray"12^{CalDatabase={__CFRuntimeBase=QAQ}Q^{CPRecordStore}^{CalEventOccurrenceCache}^{CalScheduledTaskCache}^v^v^{__CFDictionary}^{__CFDictionary}{os_unfair_lock_s=I}II^{__CFArray}^{__CFString}^{__CFArray}ii^{__CFString}^{__CFURL}^{__CFString}^{__CFString}Qiii?{_opaque_pthread_mutex_t=q[56c]}B^{__CFArray}B^{__CFSet}*IIiQBBBBBBB}20ls32l8s40l8r48l8r56l8
+ ___block_descriptor_72_e8_32s40s48s56s64r_e340_v20?0i8^{CalDatabase={__CFRuntimeBase=QAQ}Q^{CPRecordStore}^{CalEventOccurrenceCache}^{CalScheduledTaskCache}^v^v^{__CFDictionary}^{__CFDictionary}{os_unfair_lock_s=I}II^{__CFArray}^{__CFString}^{__CFArray}ii^{__CFString}^{__CFURL}^{__CFString}^{__CFString}Qiii?{_opaque_pthread_mutex_t=q[56c]}B^{__CFArray}B^{__CFSet}*IIiQBBBBBBB}12ls32l8r64l8s40l8s48l8s56l8
+ ___block_descriptor_80_e8_32s40r48r56r64r72r_e76_v40?0i8"NSDictionary"12"NSDictionary"20"CADInMemoryChangeTimestamp"28B36lr40l8r48l8r56l8r64l8s32l8r72l8
+ ___block_descriptor_92_e8_32s40s48s56s64s72s80r_e340_v20?0i8^{CalDatabase={__CFRuntimeBase=QAQ}Q^{CPRecordStore}^{CalEventOccurrenceCache}^{CalScheduledTaskCache}^v^v^{__CFDictionary}^{__CFDictionary}{os_unfair_lock_s=I}II^{__CFArray}^{__CFString}^{__CFArray}ii^{__CFString}^{__CFURL}^{__CFString}^{__CFString}Qiii?{_opaque_pthread_mutex_t=q[56c]}B^{__CFArray}B^{__CFSet}*IIiQBBBBBBB}12lr80l8s32l8s40l8s48l8s56l8s64l8s72l8
+ _kCalDatabaseSaveOptionsDefaultOptions
- -[CADStatsReminders reminderDictionaries]
- -[CADXPCImplementation(CADDatabaseOperationGroup) insert:deletes:updates:insertedObjectIDMap:inDatabase:]
- ___block_descriptor_104_e8_32s40s48s56s64s72s80s88s96r_e340_v20?0i8^{CalDatabase={__CFRuntimeBase=QAQ}Q^{CPRecordStore}^{CalEventOccurrenceCache}^{CalScheduledTaskCache}^v^v^{__CFDictionary}^{__CFDictionary}{os_unfair_lock_s=I}II^{__CFArray}^{__CFString}^{__CFArray}ii^{__CFString}^{__CFURL}^{__CFString}^{__CFString}Qiii?{_opaque_pthread_mutex_t=q[56c]}B^{__CFArray}B^{__CFSet}*IIiQBBBBBBB}12lr96l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8
- ___block_descriptor_104_e8_32s40s48s56s64s72s80s88s96r_e340_v20?0i8^{CalDatabase={__CFRuntimeBase=QAQ}Q^{CPRecordStore}^{CalEventOccurrenceCache}^{CalScheduledTaskCache}^v^v^{__CFDictionary}^{__CFDictionary}{os_unfair_lock_s=I}II^{__CFArray}^{__CFString}^{__CFArray}ii^{__CFString}^{__CFURL}^{__CFString}^{__CFString}Qiii?{_opaque_pthread_mutex_t=q[56c]}B^{__CFArray}B^{__CFSet}*IIiQBBBBBBB}12ls32l8s40l8s48l8s56l8r96l8s64l8s72l8s80l8s88l8
- ___block_descriptor_64_e8_32r40r48r56r_e76_v40?0i8"NSDictionary"12"NSDictionary"20"CADInMemoryChangeTimestamp"28B36lr32l8r40l8r48l8r56l8
- ___block_descriptor_80_e8_32s40s48s56s64s72r_e340_v20?0i8^{CalDatabase={__CFRuntimeBase=QAQ}Q^{CPRecordStore}^{CalEventOccurrenceCache}^{CalScheduledTaskCache}^v^v^{__CFDictionary}^{__CFDictionary}{os_unfair_lock_s=I}II^{__CFArray}^{__CFString}^{__CFArray}ii^{__CFString}^{__CFURL}^{__CFString}^{__CFString}Qiii?{_opaque_pthread_mutex_t=q[56c]}B^{__CFArray}B^{__CFSet}*IIiQBBBBBBB}12lr72l8s32l8s40l8s48l8s56l8s64l8
CStrings:
+ "integration:reminders"
- "integration.reminders"
```
