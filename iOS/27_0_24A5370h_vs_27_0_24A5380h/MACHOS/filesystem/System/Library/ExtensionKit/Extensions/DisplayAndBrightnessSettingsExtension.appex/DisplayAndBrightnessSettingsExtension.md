## DisplayAndBrightnessSettingsExtension

> `/System/Library/ExtensionKit/Extensions/DisplayAndBrightnessSettingsExtension.appex/DisplayAndBrightnessSettingsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1175c` | `0x10d1c` | **`-0xa40`** |
| `__TEXT.__cstring` | `0x3863` | `0x3453` | **`-0x410`** |
| `__DATA_CONST.__const` | `0xc18` | `0xb98` | **`-0x80`** |
| `__TEXT.__swift5_reflstr` | `0x527` | `0x4e7` | **`-0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x3cc` | `0x390` | **`-0x3c`** |
| `__TEXT.__auth_stubs` | `0x790` | `0x770` | **`-0x20`** |
| `__DATA.__data` | `0x5e8` | `0x5d8` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x3d0` | `0x3c0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xd0` | `0xc0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x6e0` | `0x6d0` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
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

### Other Changes

```diff

-1205.0.0.0.0
+1208.0.0.0.0

-  - /System/Library/Frameworks/SwiftUI.framework/SwiftUI

-  Functions: 551
+  Functions: 547

-  CStrings:  209
+  CStrings:  200
CStrings:
- "#DEVICE_APPEARANCE"
- "Description text for the Bold Text control in the Display & Brightness Settings pane"
- "Description text for the Display Zoom control in the Display & Brightness Settings pane"
- "Description text for the Light and Dark mode control in the Display & Brightness Settings pane"
- "Description text for the Text Size control in the Display & Brightness Settings pane"
- "This is the Bold Text control in the Display & Brightness Settings pane. When enabled, text will appear thicker and bolder on your device."
- "This is the Display Zoom control of the Display & Brightness Settings pane. Use this control to choose between showing larger controls or more space."
- "This is the Light and Dark mode control of the Display & Brightness Settings pane where the user can set the appearance of the device as either Light Mode or Dark Mode."
- "This is the Text Size control in the Display & Brightness Settings pane. Use this control to adjust the size of text in apps that support Dynamic Type."
```
