## DisplayAndBrightnessSettingsExtension

> `/System/Library/ExtensionKit/Extensions/DisplayAndBrightnessSettingsExtension.appex/DisplayAndBrightnessSettingsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3453` | `0x35d3` | **`+0x180`** |
| `__TEXT.__text` | `0x10dcc` | `0x10f24` | **`+0x158`** |
| `__TEXT.__swift5_reflstr` | `0x4e7` | `0x507` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xb98` | `0xbb0` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x390` | `0x39c` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1215.1.5.0.0
+1215.1.6.0.0

-  CStrings:  200
+  CStrings:  204
Functions:
~ sub_100001ecc : 5028 -> 5328
~ sub_100003270 -> sub_10000339c : 56 -> 60
~ sub_100004494 -> sub_1000045c4 : 468 -> 504
~ sub_100004668 -> sub_1000047bc : 56 -> 60
CStrings:
+ "/DoubleTapTopOfWindowToZoom"
+ "Description text for the Double-tap Top of Window to Zoom control of the Multitasking & Gestures Settings pane"
+ "Double-tap Top of Window to Zoom"
+ "This is the Double-tap Top of Window to Zoom control of the Multitasking & Gestures Settings pane. When enabled, double-tapping the top of a window zooms the window to fill the screen."
```
