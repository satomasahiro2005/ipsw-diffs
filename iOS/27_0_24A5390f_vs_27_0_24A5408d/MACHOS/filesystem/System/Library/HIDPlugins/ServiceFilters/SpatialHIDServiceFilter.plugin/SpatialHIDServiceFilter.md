## SpatialHIDServiceFilter

> `/System/Library/HIDPlugins/ServiceFilters/SpatialHIDServiceFilter.plugin/SpatialHIDServiceFilter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2640` | `0x29f8` | **`+0x3b8`** |
| `__DATA.__objc_const` | `0x510` | `0x5f8` | **`+0xe8`** |
| `__TEXT.__objc_methname` | `0x81a` | `0x8d5` | **`+0xbb`** |
| `__TEXT.__auth_stubs` | `0x3a0` | `0x420` | **`+0x80`** |
| `__DATA_CONST.__auth_got` | `0x1e0` | `0x220` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x796` | `0x7b8` | **`+0x22`** |
| `__DATA_CONST.__const` | `0xb8` | `0xd8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x44` | `0x60` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x3d8` | `0x3f0` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x91c` | `0x92e` | **`+0x12`** |
| `__DATA.__bss` | `0x10` | `0x20` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xf8` | `0x108` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x2d0` | `0x2d8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__const` | `0x40` | `0x48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-14.0.21.0.0
+14.0.24.0.0

-  Functions: 70
-  Symbols:   81
-  CStrings:  233
+  Functions: 79
+  Symbols:   90
+  CStrings:  244
Symbols:
+ __dispatch_source_type_timer
+ _dispatch_assert_queue$V2
+ _dispatch_resume
+ _dispatch_source_cancel
+ _dispatch_source_create
+ _dispatch_source_set_event_handler
+ _dispatch_source_set_timer
+ _mach_absolute_time
+ _mach_timebase_info
CStrings:
+ "@\"NSObject<OS_dispatch_source>\""
+ "End Haptics"
+ "[%#llx] Commit continuous waveform failed: %@"
+ "[%#llx] End haptics failed: %@"
+ "_hapticActiveContinuousIntensity"
+ "_hapticActiveContinuousWaveform"
+ "_hapticPendingIntensity"
+ "_hapticPendingWaveform"
+ "_hapticPumpDirty"
+ "_hapticPumpTimer"
+ "_lastHapticCommitTime"
+ "_onqueue_pumpHaptic"
+ "endHaptics"
+ "q"
- "Stop Haptics"
- "[%#llx] Set haptic motor [%zu] (sequence=%llu) failed: %@"
- "stopHaptics"
```
