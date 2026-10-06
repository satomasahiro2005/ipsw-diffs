## HomeKitDiagnosticExtension

> `/System/Library/Frameworks/HomeKit.framework/PlugIns/HomeKitDiagnosticExtension.appex/HomeKitDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x4e9e` | `0x4cd3` | **`-0x1cb`** |
| `__TEXT.__text` | `0x246b4` | `0x24734` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x2360` | `0x23a0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1bc2` | `0x1be7` | **`+0x25`** |
| `__TEXT.__objc_stubs` | `0x3a80` | `0x3aa0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x910` | `0x8fc` | **`-0x14`** |
| `__TEXT.__auth_stubs` | `0x980` | `0x990` | **`+0x10`** |
| `__TEXT.__const` | `0xd0` | `0xe0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x3ec8` | `0x3ed3` | **`+0xb`** |
| `__DATA.__objc_selrefs` | `0x12f0` | `0x12f8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x4d0` | `0x4d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1484.2.0.0.0
+1490.2.0.1.1

-  Symbols:   300
-  CStrings:  1601
+  Symbols:   301
+  CStrings:  1598
Symbols:
+ _objc_retain_x27
Functions:
~ sub_100019984 : 13764 -> 1556
~ sub_10001cf48 -> sub_100019f98 : 812 -> 13764
~ sub_10001d274 -> sub_10001d55c : 1372 -> 812
~ sub_10001d7d0 -> sub_10001d888 : 240 -> 1372
~ sub_10001d8c0 -> sub_10001dde4 : 556 -> 240
~ sub_10001daec -> sub_10001ded4 : 1832 -> 556
~ sub_10001e214 -> sub_10001e100 : 7804 -> 7452
~ sub_1000228c0 -> sub_10002264c : 5596 -> 6352
CStrings:
+ "/Home.app/Home"
+ "Could not find %s process"
+ "Dumping '%@'"
+ "Dumping objects and history for %lu database(s)"
+ "Found %s process: PID %d, start time: %.0f"
+ "[%{public}@] Could not find %s process"
+ "[%{public}@] Dumping '%@'"
+ "[%{public}@] Dumping objects and history for %lu database(s)"
+ "[%{public}@] Found %s process: PID %d, start time: %.0f"
+ "[%{public}@] [LogArchive] Most recent quarantine: %.0f (homed: %.0f, Home.app: %.0f)"
+ "[%{public}@] [LogArchive] No recent quarantine for either process, skipping log archive collection"
+ "[%{public}@] [LogArchive] Process start times — homed: %.0f, Home.app: %.0f; statistics: %.0f"
+ "[%{public}@] [LogArchive] Quarantine is recent (homed: %d, Home.app: %d), will collect log archive"
+ "[LogArchive] Most recent quarantine: %.0f (homed: %.0f, Home.app: %.0f)"
+ "[LogArchive] No recent quarantine for either process, skipping log archive collection"
+ "[LogArchive] Process start times — homed: %.0f, Home.app: %.0f; statistics: %.0f"
+ "[LogArchive] Quarantine is recent (homed: %d, Home.app: %d), will collect log archive"
+ "hasSuffix:"
+ "sysdiagnose_de_home_quarantine_logarchive"
+ "system_logs.logarchive"
- "Could not find homed process"
- "DE_homed_quarantine_log_archive.logarchive"
- "Found homed process: PID %d, start time: %.0f"
- "[%{public}@] Could not find homed process"
- "[%{public}@] Found homed process: PID %d, start time: %.0f"
- "[%{public}@] [LogArchive] Failed to get homed start time, using statistics-based comparison"
- "[%{public}@] [LogArchive] Most recent quarantine: %.0f"
- "[%{public}@] [LogArchive] Most recent statistics: %.0f"
- "[%{public}@] [LogArchive] No statistics records found, skipping log archive collection"
- "[%{public}@] [LogArchive] Quarantine is older than %.0f hours, skipping log archive collection"
- "[%{public}@] [LogArchive] Quarantine is within %.0f hours, will collect log archive"
- "[%{public}@] [LogArchive] Quarantine occurred after homed started, will collect log archive"
- "[%{public}@] [LogArchive] Quarantine occurred before homed started, skipping log archive collection"
- "[%{public}@] [LogArchive] homed started at: %.0f"
- "[LogArchive] Failed to get homed start time, using statistics-based comparison"
- "[LogArchive] Most recent quarantine: %.0f"
- "[LogArchive] Most recent statistics: %.0f"
- "[LogArchive] No statistics records found, skipping log archive collection"
- "[LogArchive] Quarantine is older than %.0f hours, skipping log archive collection"
- "[LogArchive] Quarantine is within %.0f hours, will collect log archive"
- "[LogArchive] Quarantine occurred after homed started, will collect log archive"
- "[LogArchive] Quarantine occurred before homed started, skipping log archive collection"
- "[LogArchive] homed started at: %.0f"
```
