## CalendarDatabase

> `/System/Library/PrivateFrameworks/CalendarDatabase.framework/CalendarDatabase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdc2a0` | `0xdc30c` | **`+0x6c`** |
| `__TEXT.__cstring` | `0x1fa88` | `0x1fa45` | **`-0x43`** |
| `__AUTH_CONST.__cfstring` | `0xca80` | `0xca40` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x1f0c` | `0x1f24` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2d20` | `0x2d30` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x18dc` | `0x18e4` | **`+0x8`** |

### Other Changes

```diff

-1291.0.0.0.0
+1291.1.3.0.0

-  Functions: 4248
-  Symbols:   6556
-  CStrings:  3123
+  Functions: 4251
+  Symbols:   6560
+  CStrings:  3121
Symbols:
+ -[CalSingleDatabaseInMemoryChangeTimestamp hash]
+ -[CalSingleDatabaseInMemoryChangeTimestamp isEqual:]
+ GCC_except_table149
+ GCC_except_table30
+ _CalDatabaseSaveWithOptionsAndOutSelfTimestamp
- GCC_except_table148
CStrings:
+ "commit at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4338"
+ "rollback at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalDatabase.m:5068"
+ "write at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4315"
- "SiriCanLearnFromAppBlacklist"
- "com.apple.suggestions.settingsChanged"
- "commit at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4339"
- "rollback at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalDatabase.m:5055"
- "write at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4316"
```
