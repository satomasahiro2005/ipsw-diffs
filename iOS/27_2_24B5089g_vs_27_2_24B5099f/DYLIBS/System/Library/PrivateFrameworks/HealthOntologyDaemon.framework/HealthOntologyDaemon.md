## HealthOntologyDaemon

> `/System/Library/PrivateFrameworks/HealthOntologyDaemon.framework/HealthOntologyDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f59c` | `0x2f74c` | **`+0x1b0`** |
| `__TEXT.__oslogstring` | `0x208a` | `0x212a` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x34ec` | `0x354c` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x4010` | `0x4050` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x2420` | `0x2440` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x226c` | `0x2254` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x18e8` | `0x18d8` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x1f4` | `0x1fc` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xf08` | `0xf00` | **`-0x8`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 1138
-  Symbols:   2196
-  CStrings:  476
+  Functions: 1137
+  Symbols:   2198
+  CStrings:  479
Symbols:
+ -[HDOntologyUpdateCoordinator _callWillTriggerGatedActivityTestHookWithMaximumDelay:gatedTask:]
+ -[HDOntologyUpdateCoordinator _configureBackgroundTasksInProfile:]
+ GCC_except_table48
+ GCC_except_table70
+ GCC_except_table83
+ _OBJC_IVAR_$_HDOntologyUpdateCoordinator._lock_didConfigureBackgroundTasks
+ _OBJC_IVAR_$_HDOntologyUpdateCoordinator._lock_invalidated
- -[HDOntologyUpdateCoordinator _callWillTriggerGatedActivityTestHookWithMaximumDelay:]
- -[HDOntologyUpdateCoordinator initWithDaemon:scheduler:]
- -[HDOntologyUpdateCoordinator initWithDaemon:scheduler:medicalHistoryDefaults:]
- GCC_except_table71
- GCC_except_table84
CStrings:
+ "%{public}@: No fallback background task available (primary profile not ready, or coordinator invalidated)"
+ "%{public}@: Unable to trigger gated update: %{public}@"
+ "No gated ontology background task available (primary profile not ready, or coordinator invalidated)"
```
