## Compass

> `/private/var/staged_system_apps/Compass.app/Compass`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd31c` | `0xd258` | **`-0xc4`** |
| `__TEXT.__objc_methname` | `0x3aec` | `0x3a84` | **`-0x68`** |
| `__TEXT.__objc_stubs` | `0x2b80` | `0x2b20` | **`-0x60`** |
| `__DATA.__objc_const` | `0x2878` | `0x2858` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x1018` | `0xff8` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x1040` | `0x1028` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x2a0` | `0x290` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x408` | `0x410` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x150` | `0x14c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_floatobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-367.30.6.12.9
+367.31.6.17.4

+  - /usr/lib/swift/libswiftAccelerate.dylib

-  Functions: 327
-  Symbols:   259
-  CStrings:  900
+  Functions: 325
+  Symbols:   258
+  CStrings:  895
Symbols:
+ __swift_FORCE_LOAD_$_swiftAccelerate
- _OBJC_CLASS_$_UIDevice
- _UIDeviceOrientationDidChangeNotification
CStrings:
- "_isDeviceLandscape"
- "currentDevice"
- "deviceOrientationDidChange:"
- "orientation"
- "updateDeviceOrientation"
```
