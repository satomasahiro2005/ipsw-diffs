## AppManagedFeaturesDeveloperSettings

> `/System/Library/PreferenceBundles/AppManagedFeaturesDeveloperSettings.bundle/AppManagedFeaturesDeveloperSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17774` | `0x1b174` | **`+0x3a00`** |
| `__TEXT.__swift5_typeref` | `0x23f1` | `0x2e33` | **`+0xa42`** |
| `__TEXT.__cstring` | `0xa5c` | `0xc5c` | **`+0x200`** |
| `__TEXT.__auth_stubs` | `0xe60` | `0xfc0` | **`+0x160`** |
| `__DATA.__data` | `0x7c8` | `0x920` | **`+0x158`** |
| `__TEXT.__eh_frame` | `0xa34` | `0xb74` | **`+0x140`** |
| `__TEXT.__const` | `0x928` | `0x9f8` | **`+0xd0`** |
| `__DATA_CONST.__auth_got` | `0x738` | `0x7e8` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x185` | `0x235` | **`+0xb0`** |
| `__DATA_CONST.__got` | `0x258` | `0x2d8` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x218` | `0x284` | **`+0x6c`** |
| `__TEXT.__unwind_info` | `0x4d8` | `0x528` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0x318` | `0x360` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0x1c9` | `0x209` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x930` | `0x958` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x18c` | `0x1b0` | **`+0x24`** |
| `__TEXT.__objc_stubs` | `0x20` | `0x40` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x334` | `0x348` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x88` | `0x98` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0xb` | `0x19` | **`+0xe`** |
| `__DATA.__objc_selrefs` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x3c` | `0x44` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x44` | `0x4c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-43.0.0.0.0
+46.0.1.0.0

+  - /System/Library/Frameworks/CoreTransferable.framework/CoreTransferable

+  - /System/Library/Frameworks/PhotosUI.framework/PhotosUI

+  - /System/Library/Frameworks/_PhotosUI_SwiftUI.framework/_PhotosUI_SwiftUI

-  Functions: 369
-  Symbols:   135
-  CStrings:  66
+  Functions: 398
+  Symbols:   140
+  CStrings:  79
Symbols:
+ _objc_allocWithZone
+ _objc_retain
+ _objc_retain_x20
+ _objc_retain_x24
+ _swift_release_x27
CStrings:
+ "Accessibility label for the rendered logo preview"
+ "Button that opens the photo picker to preview a logo image"
+ "Choose an image from your photo library to see how the logo will appear as a circular badged icon during enrollment."
+ "Could not load photo: "
+ "Could not render the logo preview."
+ "Failed to load selected photo: %{public}s"
+ "Failed to load selected photo: no transferable image data"
+ "Failed to render badged logo preview from selected photo"
+ "Footer explaining the logo preview"
+ "Section header for the logo preview"
+ "Select a Provider App"
+ "Select a Provider App for testing. Disable App Managed Features to change the selected app."
+ "The selected photo could not be loaded."
+ "info.circle.fill"
+ "initWithData:"
- "Select Provider App"
- "Select Provider App for testing. Disable App Managed Features to change the selected app."
```
