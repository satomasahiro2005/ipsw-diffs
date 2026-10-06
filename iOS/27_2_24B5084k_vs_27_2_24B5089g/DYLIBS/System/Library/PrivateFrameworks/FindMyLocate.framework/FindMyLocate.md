## FindMyLocate

> `/System/Library/PrivateFrameworks/FindMyLocate.framework/FindMyLocate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16927c` | `0x16c12c` | **`+0x2eb0`** |
| `__TEXT.__swift5_typeref` | `0x4087` | `0x4157` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0xc1e0` | `0xc298` | **`+0xb8`** |
| `__DATA.__data` | `0x22f0` | `0x23a0` | **`+0xb0`** |
| `__TEXT.__const` | `0x12ee0` | `0x12f80` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0xf5a4` | `0xf634` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x2e50` | `0x2ed8` | **`+0x88`** |
| `__TEXT.__cstring` | `0x32a3` | `0x3303` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x6450` | `0x64a8` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x32d0` | `0x3320` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x28b6` | `0x2906` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x27ea` | `0x283a` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0xff8` | `0x1040` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x3d40` | `0x3d80` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x158` | `0x180` | **`+0x28`** |
| `__DATA.__common` | `0x58` | `0x68` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x32f8` | `0x3308` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x1c00` | `0x1bf8` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x11e8` | `0x11e0` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x470` | `0x474` | **`+0x4`** |

### Other Changes

```diff

-141.31.6.16.16
+141.31.6.16.17

-  Functions: 7507
-  Symbols:   1997
-  CStrings:  563
+  Functions: 7533
+  Symbols:   2007
+  CStrings:  568
Symbols:
+ __IVARS__TtCC12FindMyLocate7Session12TimeoutQueue
+ _symbolic _____ 12FindMyLocate7SessionC12TimeoutQueueC
+ _symbolic _____ s8DurationV
+ _symbolic _____9timestamp______5eventt s15SuspendingClockV7InstantV 12FindMyLocate18DeviceStreamChangeO
+ _symbolic _____9timestamp______5eventt s15SuspendingClockV7InstantV 12FindMyLocate22PreferenceStreamChangeO
+ _symbolic _____ySay_____9timestamp_x5eventtGG 15Synchronization5MutexVAARi_zrlE s15SuspendingClockV7InstantV
+ _symbolic _____y_____9timestamp______5eventtG s23_ContiguousArrayStorageC s15SuspendingClockV7InstantV 12FindMyLocate18DeviceStreamChangeO
+ _symbolic _____y_____9timestamp______5eventtG s23_ContiguousArrayStorageC s15SuspendingClockV7InstantV 12FindMyLocate22PreferenceStreamChangeO
+ _symbolic _____y______G 12FindMyLocate7SessionC12TimeoutQueueC AA18DeviceStreamChangeO
+ _symbolic _____y______G 12FindMyLocate7SessionC12TimeoutQueueC AA22PreferenceStreamChangeO
CStrings:
+ "Adding continuation for %s late execution queue"
+ "DeviceStreamChange"
+ "Executing late continuations for %s"
+ "Missing %s continuation!"
+ "PreferenceStreamChange"
+ "Starting stream %s"
+ "timestamp event "
- "Missing meDeviceCountinuation for %s"
- "Missing preferenceContinuation!"
```
