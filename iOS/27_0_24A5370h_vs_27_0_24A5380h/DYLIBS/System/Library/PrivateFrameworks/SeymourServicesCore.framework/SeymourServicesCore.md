## SeymourServicesCore

> `/System/Library/PrivateFrameworks/SeymourServicesCore.framework/SeymourServicesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59690` | `0x5a8dc` | **`+0x124c`** |
| `__DATA_DIRTY.__data` | `0x998` | `0x1498` | **`+0xb00`** |
| `__AUTH.__data` | `0x948` | `0x2b0` | **`-0x698`** |
| `__DATA.__bss` | `0x58a0` | `0x52a0` | **`-0x600`** |
| `__DATA_DIRTY.__bss` | `0x480` | `0xa80` | **`+0x600`** |
| `__DATA.__data` | `0xd60` | `0x998` | **`-0x3c8`** |
| `__AUTH.__objc_data` | `0xf0` | `—` | **`-0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0x140` | **`+0xf0`** |
| `__AUTH_CONST.__const` | `0x3810` | `0x38f8` | **`+0xe8`** |
| `__TEXT.__const` | `0x4a88` | `0x4b70` | **`+0xe8`** |
| `__TEXT.__eh_frame` | `0x3540` | `0x3628` | **`+0xe8`** |
| `__AUTH_CONST.__objc_const` | `0xbb8` | `0xc90` | **`+0xd8`** |
| `__TEXT.__oslogstring` | `0x1e7d` | `0x1f4d` | **`+0xd0`** |
| `__TEXT.__constg_swiftt` | `0x14b0` | `0x1528` | **`+0x78`** |
| `__DATA.__common` | `0x70` | `—` | **`-0x70`** |
| `__DATA_DIRTY.__common` | `—` | `0x70` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x1bf8` | `0x1c60` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x17b8` | `0x1810` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x11a4` | `0x11ec` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0xe80` | `0xe90` | **`+0x10`** |
| `__TEXT.__cstring` | `0xbd3` | `0xbe3` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x8fc` | `0x90c` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xb73` | `0xb83` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x334` | `0x33c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x164` | `0x16c` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x274` | `0x26c` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x148` | `0x150` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x168` | `0x170` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x5c` | `0x60` | **`+0x4`** |

### Other Changes

```diff

-2027.0.117.0.2
+2027.0.124.0.3

-  Functions: 1951
-  Symbols:   844
-  CStrings:  189
+  Functions: 1974
+  Symbols:   852
+  CStrings:  190
Symbols:
+ __DATA__TtC19SeymourServicesCore33ProcessLimitMemoryPressureMonitor
+ __IVARS__TtC19SeymourServicesCore33ProcessLimitMemoryPressureMonitor
+ __METACLASS_DATA__TtC19SeymourServicesCore33ProcessLimitMemoryPressureMonitor
+ ___swift_closure_destructor.39Tm
+ _symbolic $s19SeymourServicesCore24MemoryPressureMonitoringP
+ _symbolic _____ 19SeymourServicesCore25NullMemoryPressureMonitorV
+ _symbolic _____ 19SeymourServicesCore33ProcessLimitMemoryPressureMonitorC
+ _symbolic _____y______pSgG 2os21OSAllocatedUnfairLockV So33OS_dispatch_source_memorypressureP
+ _symbolic _____y______pSg_____G s13ManagedBufferCsRi__rlE So33OS_dispatch_source_memorypressureP So16os_unfair_lock_sV
- _os_proc_available_memory
CStrings:
+ "[%{public}s] %{public}s begin footprint=%{public}fKB"
+ "[footprint-measurement] grace-compaction phys_footprint beforeDrop=%{public}s afterHandlers=%{public}s afterRelief=%{public}s dropReclaimedBytes=%{public}s reliefReclaimedBytes=%{public}s"
+ "validateHandshake(requiredVersion:dataProtectionMonitor:platform:)"
- "[%{public}s] %{public}s begin mem=%{public}fKB"
- "validateHandshake(dataProtectionMonitor:platform:)"
```
