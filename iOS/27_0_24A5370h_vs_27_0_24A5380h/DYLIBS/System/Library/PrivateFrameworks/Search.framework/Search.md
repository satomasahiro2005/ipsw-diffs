## Search

> `/System/Library/PrivateFrameworks/Search.framework/Search`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__bss` | `0x6b0` | `0x788` | **`+0xd8`** |
| `__TEXT.__gcc_except_tab` | `0x550` | `0x484` | **`-0xcc`** |
| `__DATA_DIRTY.__data` | `0x150` | `0x88` | **`-0xc8`** |
| `__TEXT.__text` | `0x24aa0` | `0x24b5c` | **`+0xbc`** |
| `__TEXT.__cstring` | `0x2d6f` | `0x2e0f` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x5a0` | `0x5c8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x9e8` | `0x9f8` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x16bf` | `0x16cc` | **`+0xd`** |

### Other Changes

```diff

-2448.100.0.0.0
+2451.1.101.0.0

-  Functions: 1066
-  Symbols:   2116
-  CStrings:  712
+  Functions: 1067
+  Symbols:   2122
+  CStrings:  713
Symbols:
+ __SPPublishApplications
+ __db_rwlock_init
+ __db_write_lock
+ _db_read_lock
+ _db_read_unlock
+ _db_write_unlock
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Spotlight_Search/spotlight/SearchFramework/SPApplication.m"
+ "Finished getting %ld applications, took %f seconds, published1:%@ published2:%@"
- "Finished getting %ld applications, took %f seconds updateApps ? %@"
```
