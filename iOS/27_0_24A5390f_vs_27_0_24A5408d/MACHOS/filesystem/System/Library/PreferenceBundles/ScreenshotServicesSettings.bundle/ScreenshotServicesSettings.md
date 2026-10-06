## ScreenshotServicesSettings

> `/System/Library/PreferenceBundles/ScreenshotServicesSettings.bundle/ScreenshotServicesSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2d4` | `0x97a0` | **`-0xb34`** |
| `__TEXT.__const` | `0xb20` | `0xa60` | **`-0xc0`** |
| `__DATA.__data` | `0x670` | `0x600` | **`-0x70`** |
| `__TEXT.__constg_swiftt` | `0x3f0` | `0x390` | **`-0x60`** |
| `__TEXT.__auth_stubs` | `0xc30` | `0xbe0` | **`-0x50`** |
| `__DATA.__bss` | `0x7f0` | `0x7b0` | **`-0x40`** |
| `__DATA.__objc_const` | `0x2b8` | `0x278` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x22e` | `0x1f8` | **`-0x36`** |
| `__TEXT.__objc_methname` | `0x18b` | `0x15b` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1c5` | `0x195` | **`-0x30`** |
| `__DATA_CONST.__auth_got` | `0x620` | `0x5f8` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x360` | `0x338` | **`-0x28`** |
| `__TEXT.__cstring` | `0x3c5` | `0x3a5` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x188` | `0x170` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0x76e` | `0x762` | **`-0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x2d0` | `0x2c8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-444.0.0.0.0
+447.100.0.0.0

-  Functions: 270
-  Symbols:   157
-  CStrings:  55
+  Functions: 254
+  Symbols:   152
+  CStrings:  52
Symbols:
- __SSEnableVisualLookUpInScreenshots
- __SSVisualIntelligenceV2EnabledIgnoringOrientation
- __SSVisualLookUpInScreenshotsEnabled
- _objc_retain_x28
- _swift_release_x23
CStrings:
+ "update settings, fullScreenPreviewEnabled: %{bool}d, hdrEnabled: %{bool}d, highQualityEnabled: %{bool}d"
- "ENABLE_VI_FOOTER_TEXT"
- "_viSupported"
- "_visualLookUpEnabled"
- "update settings, fullScreenPreviewEnabled: %{bool}d, hdrEnabled: %{bool}d, visualLookUpEnabled: %{bool}d, viSupported: %{bool}d, highQualityEnabled: %{bool}d"
```
