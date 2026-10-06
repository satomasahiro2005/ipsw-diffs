## ComputeSafeguards

> `/System/Library/PrivateFrameworks/ComputeSafeguards.framework/ComputeSafeguards`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5aeec` | `0x5b188` | **`+0x29c`** |
| `__TEXT.__cstring` | `0x6075` | `0x6144` | **`+0xcf`** |
| `__TEXT.__oslogstring` | `0xf32a` | `0xf3aa` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x6300` | `0x6340` | **`+0x40`** |
| `__DATA_CONST.__objc_arraydata` | `0x2200` | `0x21e0` | **`-0x20`** |
| `__DATA.__bss` | `0xc0` | `0xd0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x4634` | `0x4644` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1088` | `0x1098` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a20` | `0x2a28` | **`+0x8`** |

### Other Changes

```diff

-177.0.8.502.1
+177.0.16.0.0

-  Functions: 2065
-  Symbols:   2692
-  CStrings:  1872
+  Functions: 2069
+  Symbols:   2696
+  CStrings:  1876
Symbols:
+ -[CSIssueDetector isDriverCoalitionName:]
+ ___41-[CSIssueDetector isDriverCoalitionName:]_block_invoke
+ _isDriverCoalitionName:.driverRegex
+ _isDriverCoalitionName:.onceToken
CStrings:
+ "(p.processName = '%@' OR p.processName = '%@' OR %@)"
+ "SELECT m.* FROM (SELECT m.* FROM XPCMetrics_OngoingRestore_14_2 AS m JOIN XPCMetrics_OngoingRestore_14_2_Array_processName AS p ON m.ID = p.FK_ID WHERE %@ AND m.timestamp < %f ORDER BY m.timestamp DESC LIMIT 1) AS m UNION SELECT m.* FROM XPCMetrics_OngoingRestore_14_2 AS m JOIN XPCMetrics_OngoingRestore_14_2_Array_processName AS p ON m.ID = p.FK_ID WHERE %@ AND m.timestamp >= %f AND m.timestamp < %f ORDER BY timestamp"
+ "Skipping coalition '%@' (CID: %@) - kernel driver coalition"
+ "^(com\\.apple\\.)?[Dd]river(Kit)?\\."
+ "isDriverCoalitionName: failed to compile driver coalition regex: %@"
+ "m.fastPassName IN (SELECT DISTINCT Name FROM PLDuetService_EventNone_DASActivityLifecycle WHERE ',' || REPLACE(InvolvedProcesses, ' ', '') || ',' LIKE '%%,%@,%%' OR ',' || REPLACE(InvolvedProcesses, ' ', '') || ',' LIKE '%%,%@,%%')"
- "SELECT m.* FROM (SELECT m.* FROM XPCMetrics_OngoingRestore_14_2 AS m JOIN XPCMetrics_OngoingRestore_14_2_Array_processName AS p ON m.ID = p.FK_ID WHERE (p.processName = '%@' OR p.processName = '%@') AND m.timestamp < %f ORDER BY m.timestamp DESC LIMIT 1) AS m UNION SELECT m.* FROM XPCMetrics_OngoingRestore_14_2 AS m JOIN XPCMetrics_OngoingRestore_14_2_Array_processName AS p ON m.ID = p.FK_ID WHERE (p.processName = '%@' OR p.processName = '%@') AND m.timestamp >= %f AND m.timestamp < %f ORDER BY timestamp"
- "com.apple.hybridsearchd"
```
