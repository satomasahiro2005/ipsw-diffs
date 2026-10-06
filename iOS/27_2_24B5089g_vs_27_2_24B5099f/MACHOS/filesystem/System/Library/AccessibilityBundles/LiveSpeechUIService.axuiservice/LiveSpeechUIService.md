## LiveSpeechUIService

> `/System/Library/AccessibilityBundles/LiveSpeechUIService.axuiservice/LiveSpeechUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdca70` | `0xdea28` | **`+0x1fb8`** |
| `__TEXT.__oslogstring` | `0x2987` | `0x2c67` | **`+0x2e0`** |
| `__TEXT.__swift5_typeref` | `0x18514` | `0x185aa` | **`+0x96`** |
| `__TEXT.__objc_stubs` | `0x21c0` | `0x2240` | **`+0x80`** |
| `__TEXT.__const` | `0x8e28` | `0x8e98` | **`+0x70`** |
| `__TEXT.__auth_stubs` | `0x3ed0` | `0x3f30` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x29a4` | `0x2a04` | **`+0x60`** |
| `__DATA.__data` | `0x57e8` | `0x5838` | **`+0x50`** |
| `__DATA.__objc_const` | `0x2e08` | `0x2e48` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x218f` | `0x21cf` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x1f78` | `0x1fa8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2320` | `0x2350` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x53b8` | `0x53e0` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x5149` | `0x5161` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x1d24` | `0x1d3c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2bc8` | `0x2be0` | **`+0x18`** |
| `__DATA.__objc_data` | `0x1dd0` | `0x1de0` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x1812` | `0x1822` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x1668` | `0x1678` | **`+0x10`** |
| `__DATA.__common` | `0x268` | `0x270` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x1088` | `0x1090` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xe78` | `0xe80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3245.8.2.0.0
+3245.8.4.2.0

-  Functions: 4093
+  Functions: 4102

-  CStrings:  1354
+  CStrings:  1367
CStrings:
+ "AXLSForeignTextInputDidBecomeActive"
+ "Text entry field ended editing. isFirstResponder=%{bool,public}d isEditable=%{bool,public}d"
+ "cannot move native focus; handing back the keyboard anyway"
+ "foreign text input notification had no usable payload: %{public}s"
+ "foreign text input pid=%{public}d bundle=%{public}s scene=%{public}s inputMode=%{public}s presentTextField=%{bool,public}d hudResponder=%{public}s"
+ "foreignTextInputObserver"
+ "handed keyboard to pid=%{public}d stillFirstResponder=%{bool,public}d"
+ "keyboardDidShowRelayoutObserver"
+ "not relinquishing: HUD does not hold first responder"
+ "not relinquishing: HUD is not in keyboard mode"
+ "not relinquishing: report came from our own process"
+ "observing foreign text input"
+ "stopped observing foreign text input"
+ "switchNativeFocusedApplicationToProcessIdentifier:sceneIdentifier:"
- "removeObserver:name:object:"
```
