## intelligencetasksd

> `/System/Library/PrivateFrameworks/IntelligenceTasksEngine.framework/Support/intelligencetasksd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x170` | `0x2e8` | **`+0x178`** |
| `__DATA.__bss` | `—` | `0x80` | **`+0x80`** |
| `__TEXT.__const` | `0x52` | `0xb2` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0xc0` | `0x100` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `—` | `0x28` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x60` | `0x80` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x38` | `0x58` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1f` | `0x3f` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x8` | `0x18` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x10` | **`+0x10`** |
| `__DATA.__data` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `—` | `0x6` | **`+0x6`** |
| `__TEXT.__swift5_proto` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__swift5_types` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_entry`

### Other Changes

```diff

-239.0.2.0.0
+243.0.0.0.0

+  - /System/Library/PrivateFrameworks/IntelligenceTasks.framework/IntelligenceTasks

-  Functions: 2
-  Symbols:   22
-  CStrings:  2
+  Functions: 6
+  Symbols:   29
+  CStrings:  3
Symbols:
+ _$s17IntelligenceTasks7LoggingO6Engine2os6LoggerVvgZ
+ _$s23IntelligenceTasksEngine010BackgroundB0O5startyyFZ
+ _$s23IntelligenceTasksEngine10XPCServersO5startyyFZ
+ _$s23IntelligenceTasksEngine6DaemonMp
+ _$s23IntelligenceTasksEngine6DaemonP5startyyFZTq
+ _$s23IntelligenceTasksEngine6DaemonPAAE12enterSandbox10identifierySS_tFZ
+ _$s23IntelligenceTasksEngine9XPCEventsO5startyyFZ
+ _$sytWV
+ _objc_release_x20
+ _objc_release_x23
+ _swift_getWitnessTable
- _$s23IntelligenceTasksEngine6DaemonV12enterSandbox10identifierySS_tFZ
- _$s23IntelligenceTasksEngine6DaemonV5startyyFZ
- _$s23IntelligenceTasksEngine7LoggingO0C02os6LoggerVvgZ
- _objc_release_x22
CStrings:
+ "intelligencetasksd started"
```
