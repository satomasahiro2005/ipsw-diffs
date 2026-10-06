## AXHapticMusicServer

> `/System/Library/AccessibilityBundles/AXHapticMusicServer.axuiservice/AXHapticMusicServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b6c8` | `0x2bccc` | **`+0x604`** |
| `__DATA_CONST.__const` | `0x1ae0` | `0x1b30` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x1368` | `0x1398` | **`+0x30`** |
| `__TEXT.__cstring` | `0x5cb` | `0x5eb` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x10e0` | `0x10f0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x718` | `0x728` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5e0` | `0x5f0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x880` | `0x888` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2d8` | `0x2e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

+  - /System/Library/Frameworks/Accessibility.framework/Accessibility

-  Functions: 647
-  Symbols:   267
-  CStrings:  419
+  Functions: 654
+  Symbols:   269
+  CStrings:  421
Symbols:
+ _AXApplicationAccessibilityEnabled
+ _kAXSHapticMusicPreferenceDidChangeNotification
CStrings:
+ "Haptic Music enabled state changed to: %{bool}d"
+ "haptic music enabled change"
```
