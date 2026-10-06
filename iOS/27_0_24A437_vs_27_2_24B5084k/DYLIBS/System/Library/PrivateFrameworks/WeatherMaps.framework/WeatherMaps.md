## WeatherMaps

> `/System/Library/PrivateFrameworks/WeatherMaps.framework/WeatherMaps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c5fc4` | `0x1c94e0` | **`+0x351c`** |
| `__AUTH_CONST.__const` | `0x12101` | `0x11f29` | **`-0x1d8`** |
| `__TEXT.__oslogstring` | `0x695d` | `0x6b2d` | **`+0x1d0`** |
| `__TEXT.__swift5_reflstr` | `0x86de` | `0x87be` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0x3538` | `0x3474` | **`-0xc4`** |
| `__AUTH.__data` | `0x39a8` | `0x3a68` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0xed90` | `0xee50` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x8c8c` | `0x8d2c` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x875c` | `0x87e4` | **`+0x88`** |
| `__TEXT.__cstring` | `0x64c1` | `0x6541` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x6ff0` | `0x7070` | **`+0x80`** |
| `__DATA.__data` | `0x3600` | `0x3650` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x8058` | `0x8098` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x90a2` | `0x90dc` | **`+0x3a`** |
| `__AUTH_CONST.__auth_got` | `0x2930` | `0x2960` | **`+0x30`** |
| `__TEXT.__const` | `0x14a24` | `0x14a44` | **`+0x20`** |
| `__DATA_DIRTY.__objc_data` | `0x17c8` | `0x17e0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2618` | `0x2628` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1040` | `0x1048` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x794` | `0x798` | **`+0x4`** |

### Other Changes

```diff

-1454.1.0.0.0
+1470.0.0.0.0

-  Functions: 11605
-  Symbols:   3888
-  CStrings:  856
+  Functions: 11651
+  Symbols:   3905
+  CStrings:  862
Symbols:
+ _OBJC_CLASS_$_NSThread
+ _OUTLINED_FUNCTION_190
+ _OUTLINED_FUNCTION_191
+ _OUTLINED_FUNCTION_192
+ _OUTLINED_FUNCTION_193
+ _OUTLINED_FUNCTION_194
+ _OUTLINED_FUNCTION_195
+ _OUTLINED_FUNCTION_196
+ _OUTLINED_FUNCTION_197
+ ___swift_closure_destructor.139Tm
+ ___swift_closure_destructor.15Tm
+ ___swift_closure_destructor.56Tm
+ ___swift_closure_destructor.88Tm
+ ___swift_memcpy132_8
+ _swift_deallocBox
+ _swift_task_getMainExecutor
+ _swift_task_isCurrentExecutor
+ _symbolic So12UIUpdateLinkCIegg_
+ _symbolic _____ 11WeatherMaps010UpdateLinka10MapOverlayC17TimingCoordinator33_8066BAF2812C05BACFDB45544C66DA4BLLC5StateV
+ _symbolic _____Sg 11WeatherMaps15SnapshotManagerC11RunningTask016_747971E0A3A4FA0G15F6CC4069E04E8CBLLV
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 11WeatherMaps010UpdateLinke10MapOverlayG17TimingCoordinator33_8066BAF2812C05BACFDB45544C66DA4BLLC5StateV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 11WeatherMaps010UpdateLinkc10MapOverlayE17TimingCoordinator33_8066BAF2812C05BACFDB45544C66DA4BLLC5StateV So16os_unfair_lock_sV
+ _symbolic yt______pIgrzo_ s5ErrorP
+ _type_layout_string 11WeatherMaps010UpdateLinka10MapOverlayC17TimingCoordinator33_8066BAF2812C05BACFDB45544C66DA4BLLC5StateV
- ___swift_closure_destructor.16Tm
- ___swift_closure_destructor.53Tm
- ___swift_closure_destructor.76Tm
- ___swift_memcpy124_8
- _symbolic So6UIViewCSgz_Xx
- _symbolic _____z_Xx So7CGPointV
- _type_layout_string 11WeatherMaps15SnapshotManagerC11RunningTask016_747971E0A3A4FA0G15F6CC4069E04E8CBLLV
CStrings:
+ "Incorrect actor executor assumption; Expected same executor as "
+ "Snapshot Manager: %{public}s: Clear out running task after error. error=%{public}s"
+ "Snapshot Manager: %{public}s: Running task entry already replaced - nothing to clear."
+ "Snapshot View Controller: %s: Keeping rendered snapshot visible while reloading."
+ "Snapshot View Controller: %s: Repeated unrequested cancellations - showing error. location=%{private,mask.hash}s"
+ "Snapshot View Controller: %s: Unrequested cancellation - retrying (%ld/%ld). location=%{private,mask.hash}s"
+ "Snapshot View Controller: Refresh snapshot - suspended while the layout animates. location=%{private,mask.hash}s, overlayKind=%s"
+ "WeatherMaps/WeatherMapOverlayUpdateTimingCoordinator.swift"
- "Snapshot Manager: %{public}s: Clear out running task after error. error=%s"
- "Snapshot View Controller: Refresh snapshot - requested to skip updates. location=%{private,mask.hash}s, overlayKind=%s"
```
