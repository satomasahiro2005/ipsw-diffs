## CarCamera

> `/Applications/CarCamera.app/CarCamera`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28a70` | `0x281e8` | **`-0x888`** |
| `__TEXT.__oslogstring` | `0xd7d` | `0xf6d` | **`+0x1f0`** |
| `__TEXT.__objc_stubs` | `0x600` | `0x680` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x1cdd` | `0x1d2d` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x1620` | `0x15f0` | **`-0x30`** |
| `__TEXT.__eh_frame` | `0x488` | `0x4b8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xd68` | `0xd90` | **`+0x28`** |
| `__DATA.__data` | `0x1bf0` | `0x1bd0` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x598` | `0x5b8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x767` | `0x787` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x888` | `0x8a8` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xb18` | `0xb00` | **`-0x18`** |
| `__DATA.__objc_data` | `0x9e0` | `0x9f0` | **`+0x10`** |
| `__TEXT.__const` | `0x20b4` | `0x20a4` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0xfb4` | `0xfc4` | **`+0x10`** |
| `__TEXT.__cstring` | `0x32b` | `0x31b` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x1c0` | `0x1d0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x24c8` | `0x24c0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-342.1.0.0.0
+351.2.0.0.0

-  Functions: 778
-  Symbols:   656
-  CStrings:  470
+  Functions: 783
+  Symbols:   653
+  CStrings:  479
Symbols:
+ _swift_bridgeObjectRelease_n
- _$s10CAFCombine25CAFCameraButtonObservableC12buttonActionSo09CAFButtonF0VSgvgTj
- _$s10CAFCombine25CAFCameraButtonObservableC12buttonActionSo09CAFButtonF0VSgvsTj
- _$s10CAFCombine25CAFCameraButtonObservableC16contentURLActionSSSgvgTj
- _$s10CAFCombine25CAFCameraButtonObservableC8disabledSbSgvgTj
CStrings:
+ "[CAMERAMODEL] CAFCameraButtonObserver %s didUpdateButtonAction %hhu"
+ "[CAMERAMODEL] CAFCameraButtonObserver %s didUpdateDisabled %{bool}d"
+ "[CAMERAMODEL] RequestContent URL button pressed (URL: %s)"
+ "[CAMERAMODEL] RequestContent failed, missing window scene."
+ "[CAMERAMODEL] RequestContent opening url %s was not successful"
+ "[CAMERAMODEL] nothing to do for %s"
+ "[CAMERAMODEL] performAction %s"
+ "[CAMERAMODEL] performAction failed, no service for %s"
+ "[CAMERAMODEL] sendAction to vehicle with .performAction"
+ "[CAMERAMODEL] submenu %s has no actionable entry, returning to top level"
+ "[CameraActionButton] submenu %s has no exit path, staying at top level"
+ "[CameraButtonGroup] no selected action resolved for %s"
+ "[CameraButtonGroup] no service for selected entry %s in %s, falling back to parent"
+ "[CameraButtonGroup] selectedEntryIndex %ld out of range for %ld entries in %s, falling back to parent"
+ "_submenuParentIdentifier"
+ "buttonAction"
+ "contentURLAction"
+ "disabled"
+ "entering submenu (using identifier)"
+ "setButtonAction:"
+ "sink submenuParentIdentifier"
+ "submenuParentIdentifier"
- "[CameraActionButton] %s sending action"
- "[CameraActionButton] RequestContent URL button pressed (URL: %s)"
- "[CameraActionButton] RequestContent failed, missing window scene."
- "[CameraActionButton] equestContent opening url %s was not successful"
- "[CameraActionButton] nothing to do"
- "[CameraActionButton] sendAction to vehicle with .performAction"
- "[are these buttons correct] %s"
- "_submenuParent"
- "entering submenu (using parent)"
- "sink submenuParent"
- "subItems"
- "submenuButtons update: static sort (active not at front)"
- "submenuParent"
```
