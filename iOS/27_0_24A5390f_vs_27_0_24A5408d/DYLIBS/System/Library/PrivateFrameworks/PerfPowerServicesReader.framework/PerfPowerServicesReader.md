## PerfPowerServicesReader

> `/System/Library/PrivateFrameworks/PerfPowerServicesReader.framework/PerfPowerServicesReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14ae04` | `0x14b03c` | **`+0x238`** |
| `__TEXT.__gcc_except_tab` | `0x4a8c` | `0x4adc` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0xd5f` | `0xda1` | **`+0x42`** |
| `__AUTH_CONST.__cfstring` | `0xf0a0` | `0xf0c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xd106` | `0xd0f4` | **`-0x12`** |
| `__TEXT.__const` | `0x5fe2` | `0x5fd2` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x49b8` | `0x49b0` | **`-0x8`** |

### Other Changes

```diff

-3486.0.81.502.4
+3486.2.4.0.0

-  Functions: 7904
+  Functions: 7905

-  CStrings:  2142
+  CStrings:  2144
Functions:
~ ___60-[PPSSQLiteTimeSeriesIngester parseDataForRequest:outError:]_block_invoke : 900 -> 1120
- ___87-[PPSSQLiteTimeSeriesIngester _convertSQLiteDataFromQuery:withMetricDefinitions:error:]_block_invoke.46
~ -[PPSSQLiteTimeSeriesIngester parseDataForRequest:outError:] : 2824 -> 2840
~ -[PPSSQLiteDatabase _statementForSQL:shouldCache:error:] : 544 -> 812
+ ___87-[PPSSQLiteTimeSeriesIngester _convertSQLiteDataFromQuery:withMetricDefinitions:error:]_block_invoke.49
+ -[PPSSQLiteDatabase _statementForSQL:shouldCache:error:].cold.1
CStrings:
+ "Exception during query execution"
+ "SQL string contains more than one statement."
+ "SQL string contains more than one statement; refusing to execute."
- "SQL strings must contain only a single statement; remaining statements will not be executed: %s"
```
