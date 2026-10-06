## APFoundation

> `/System/Library/PrivateFrameworks/APFoundation.framework/APFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ec5c8` | `0x1ef57c` | **`+0x2fb4`** |
| `__AUTH_CONST.__objc_const` | `0x99a8` | `0x9fb0` | **`+0x608`** |
| `__AUTH_CONST.__cfstring` | `0x3820` | `0x3b80` | **`+0x360`** |
| `__TEXT.__objc_methlist` | `0x46bc` | `0x4924` | **`+0x268`** |
| `__DATA.__bss` | `0x5c60` | `0x5eb0` | **`+0x250`** |
| `__TEXT.__cstring` | `0x462d` | `0x47fd` | **`+0x1d0`** |
| `__TEXT.__oslogstring` | `0x49e6` | `0x4ba6` | **`+0x1c0`** |
| `__DATA_CONST.__objc_selrefs` | `0x25b8` | `0x2718` | **`+0x160`** |
| `__AUTH.__objc_data` | `0x540` | `0x680` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x2b20` | `0x2bf8` | **`+0xd8`** |
| `__AUTH_CONST.__const` | `0xa3a0` | `0xa460` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x13a0` | `0x1450` | **`+0xb0`** |
| `__TEXT.__const` | `0xb480` | `0xb520` | **`+0xa0`** |
| `__DATA.__data` | `0x21a8` | `0x2208` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0x394` | `0x3e8` | **`+0x54`** |
| `__DATA_CONST.__got` | `0x9d0` | `0xa20` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x23f0` | `0x2438` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x1c74` | `0x1c9a` | **`+0x26`** |
| `__DATA_CONST.__objc_classlist` | `0x3b8` | `0x3d8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1620` | `0x1638` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x198` | `0x1b0` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x148` | `0x160` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x188` | `0x1a0` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x2bcc` | `0x2bb4` | **`-0x18`** |
| `__DATA_CONST.__objc_protorefs` | `0x78` | `0x88` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1678` | `0x1688` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x2560` | `0x2570` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x428` | `0x438` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x197c` | `0x1988` | **`+0xc`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-557.1.33.0.0
+557.2.8.0.0

-  Functions: 3945
-  Symbols:   774
-  CStrings:  1040
+  Functions: 4029
+  Symbols:   792
+  CStrings:  1074
Symbols:
+ _APDatabaseTransactionQueryPrefix
+ _APDiagnosticThrottleDefaultsKey
+ _APSimulateCrashNoKillProcessWithoutABCReport
+ _APSimulateCrashWithoutABCReport
+ _CreateDiagnosticReportSubtypeCrashSynchronously
+ _OBJC_CLASS_$_APDatabaseQueryInfo
+ _OBJC_CLASS_$_APDatabaseTelemetry
+ _OBJC_CLASS_$_APDatabaseTimingLock
+ _OBJC_CLASS_$_APDiagnosticThrottle
+ _OBJC_CLASS_$_NSCharacterSet
+ _OBJC_METACLASS_$_APDatabaseQueryInfo
+ _OBJC_METACLASS_$_APDatabaseTelemetry
+ _OBJC_METACLASS_$_APDatabaseTimingLock
+ _OBJC_METACLASS_$_APDiagnosticThrottle
+ _clock_gettime_nsec_np
+ _kSymptomDiagnosticReplyRateLimitExpiresIn
+ _kSymptomDiagnosticReplySuccess
+ _objc_setProperty_atomic_copy
CStrings:
+ " (DEFERRED)"
+ " (EXCLUSIVE)"
+ "%08x"
+ "%@|%@|%@"
+ "();,"
+ "(transaction)"
+ "(unknown)"
+ "APDiagnosticThrottle.suppressedUntil"
+ "DELETE"
+ "Database lock held for %llu ms"
+ "Database.CoreAnalyticsThresholdMs"
+ "Database.SlowQueryThresholdMs"
+ "DatabaseSlowQuery"
+ "Diagnostic Reporter skipped a report from excluded process %{public}@"
+ "Diagnostic Reporter suppressed a repeated report, subtype:%{public}@, key:%{public}@, description:\"%{public}@\""
+ "FROM"
+ "INSERT"
+ "INTO"
+ "OR"
+ "QueryDuration"
+ "QueryType"
+ "REPLACE"
+ "SELECT"
+ "SearchAdsSettings"
+ "TRANSACTION"
+ "TableName"
+ "ThresholdMs"
+ "UPDATE"
+ "[APDatabaseTelemetry]: Database lock held for %{public}llu ms (threshold %{public}llu ms). Type: %{public}ld, Table: %{public}@, Database: %{public}@, Version: %{public}ld, Query: %{public}@"
+ "[APDatabaseTelemetry]: Skipping Core Analytics for unmapped database: %{public}@"
+ "`\"'[]"
+ "com.apple.ap.database.telemetry"
+ "com.apple.ap.diagnosticreport"
+ "q24@?0@\"NSNumber\"8@\"NSNumber\"16"
+ "sqlite_master"
- "!"
```
