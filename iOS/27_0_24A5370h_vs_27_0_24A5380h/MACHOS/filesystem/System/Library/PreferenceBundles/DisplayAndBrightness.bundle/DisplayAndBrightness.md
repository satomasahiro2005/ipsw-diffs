## DisplayAndBrightness

> `/System/Library/PreferenceBundles/DisplayAndBrightness.bundle/DisplayAndBrightness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26b0` | `0x22fc` | **`-0x3b4`** |
| `__TEXT.__objc_stubs` | `0x3e0` | `0x320` | **`-0xc0`** |
| `__TEXT.__objc_methname` | `0x2ce` | `0x24b` | **`-0x83`** |
| `__DATA_CONST.__const` | `0x308` | `0x2a8` | **`-0x60`** |
| `__DATA.__objc_selrefs` | `0x128` | `0xf8` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x128` | `0xf8` | **`-0x30`** |
| `__TEXT.__auth_stubs` | `0x580` | `0x550` | **`-0x30`** |
| `__DATA.__data` | `0x140` | `0x120` | **`-0x20`** |
| `__TEXT.__cstring` | `0x107` | `0xe7` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x2c8` | `0x2b0` | **`-0x18`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1205.0.0.0.0
+1208.0.0.0.0

-  Symbols:   112
-  CStrings:  57
+  Symbols:   104
+  CStrings:  48
Symbols:
+ _objc_release_x26
+ _objc_retain_x27
+ _swift_release_x27
- _OBJC_CLASS_$_DBSDeviceAppearanceScheduleController
- _OBJC_CLASS_$_DBSDisplayZoomSelectionListController
- _OBJC_CLASS_$_DBSLargeTextController
- _OBJC_CLASS_$_DBSLiquidGlassLegacyController
- _OBJC_CLASS_$_UIDevice
- _OBJC_CLASS_$_UISUserInterfaceStyleMode
- _UISUserInterfaceStyleModeValueIsAutomatic
- _objc_release_x25
- _objc_retain_x25
- _objc_retain_x28
- _swift_release_x26
Functions:
~ sub_250c : 3772 -> 2944
~ sub_34c0 -> sub_3184 : 644 -> 524
CStrings:
- "LIQUID_GLASS"
- "MAGNIFY"
- "TEXT_SIZE"
- "currentDevice"
- "initWithDelegate:"
- "modeValue"
- "setSpecifierIdentifierToScrollAndSelect:"
- "sf_deviceSupportsDisplayZoom"
- "userInterfaceIdiom"
```
