## ecosystemanalyticsd

> `/System/Library/PrivateFrameworks/EcosystemAnalytics.framework/Support/ecosystemanalyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5ebc` | `0x64c0` | **`+0x604`** |
| `__TEXT.__oslogstring` | `0xc6` | `0x297` | **`+0x1d1`** |
| `__TEXT.__auth_stubs` | `0x830` | `0x8f0` | **`+0xc0`** |
| `__DATA_CONST.__auth_got` | `0x420` | `0x480` | **`+0x60`** |
| `__TEXT.__const` | `0x22a` | `0x28a` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x6e1` | `0x739` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x14c` | `0x198` | **`+0x4c`** |
| `__DATA.__data` | `0x338` | `0x378` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0xa0` | `0xe0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1016` | `0x1046` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x2e9` | `0x319` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0xc8` | `0xf0` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x100` | `0x128` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x12b` | `0x14d` | **`+0x22`** |
| `__DATA.__objc_const` | `0x270` | `0x290` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x120` | `0x140` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x11c` | `0x108` | **`-0x14`** |
| `__DATA.__objc_selrefs` | `0xc8` | `0xd8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x110` | `0x120` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xd7` | `0xe6` | **`+0xf`** |
| `__TEXT.__unwind_info` | `0x160` | `0x168` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xc` | `0x10` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-38.0.0.0.0
+39.0.1.0.0

-  Functions: 118
-  Symbols:   215
-  CStrings:  141
+  Functions: 121
+  Symbols:   234
+  CStrings:  152
Symbols:
+ _$s18EcosystemAnalytics21SystemPressureMonitorO07isUnderD020thermalStateProviderSbSo020NSProcessInfoThermalI0VyXE_tFZ
+ _$s2os21OSAllocatedUnfairLockVMn
+ _$ss13ManagedBufferCMn
+ _$ss5Int32VMn
+ _$ss6UInt32VMn
+ _$ss6UInt64VMn
+ _OBJC_CLASS_$_NSProcessInfo
+ ___stack_chk_fail
+ ___stack_chk_guard
+ _notify_cancel
+ _notify_get_state
+ _notify_register_dispatch
+ _objc_retain_x19
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_endAccess
+ _swift_getForeignTypeMetadata
+ _swift_release_n
+ _swift_release_x19
+ _swift_release_x28
+ _swift_retain_x24
+ _swift_retain_x28
- _$sSo17OS_dispatch_queueC8DispatchE4sync7executexxyKXE_tKlF
- _dispatch_sync
- _swift_isEscapingClosureAtFileLocation
CStrings:
+ "com.apple.ecosystem.gameModeNotify"
+ "com.apple.system.game_mode_status_changed"
+ "ecosystemanalyticsd: Game Mode notification received, active: %{bool}d"
+ "ecosystemanalyticsd: Seeded initial Game Mode state, active: %{bool}d"
+ "ecosystemanalyticsd: gameModeActive value set to: %{bool}d"
+ "ecosystemanalyticsd: memoryPressureDetected value set to: %{bool}d"
+ "ecosystemanalyticsd: notify_get_state failed for Game Mode (status %u)"
+ "ecosystemanalyticsd: notify_get_state failed seeding Game Mode (status %u)"
+ "ecosystemanalyticsd: notify_register_dispatch failed for Game Mode (status %u)"
+ "gameModeLock"
+ "gameModeNotificationToken"
+ "memoryPressureLock"
+ "processInfo"
+ "thermalState"
+ "v12@?0i8"
- "_memoryPressureDetected"
- "com.apple.ecosystem.memoryPressureQueue"
- "ecosystemanalyticsd: _memoryPressureDetected value set to: %{bool}d"
- "memoryPressureQueue"
```
