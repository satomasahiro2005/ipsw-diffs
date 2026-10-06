## SoftwareUpdateUIMobileSettingsPlugin

> `/System/Library/PreferenceBundles/SoftwareUpdateUIMobileSettingsPlugin.bundle/SoftwareUpdateUIMobileSettingsPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6566c` | `0x65250` | **`-0x41c`** |
| `__TEXT.__const` | `0x2934` | `0x2864` | **`-0xd0`** |
| `__TEXT.__swift5_typeref` | `0x20a7` | `0x2171` | **`+0xca`** |
| `__TEXT.__auth_stubs` | `0x1910` | `0x1860` | **`-0xb0`** |
| `__TEXT.__constg_swiftt` | `0x984` | `0x8d8` | **`-0xac`** |
| `__DATA.__data` | `0xfe0` | `0xf40` | **`-0xa0`** |
| `__DATA_CONST.__const` | `0x4c18` | `0x4c88` | **`+0x70`** |
| `__TEXT.__cstring` | `0x1265` | `0x1205` | **`-0x60`** |
| `__DATA_CONST.__auth_got` | `0xc90` | `0xc38` | **`-0x58`** |
| `__TEXT.__swift5_capture` | `0x1dac` | `0x1dec` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x845` | `0x875` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x4d0` | `0x4a8` | **`-0x28`** |
| `__DATA.__bss` | `0xf28` | `0xf08` | **`-0x20`** |
| `__DATA.__objc_const` | `0x510` | `0x530` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x485` | `0x465` | **`-0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x738` | `0x728` | **`-0x10`** |
| `__DATA.__objc_data` | `0x168` | `0x170` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xb0` | `0xa8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1460` | `0x1468` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xc4` | `0xc8` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x4c` | `0x50` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x40` | `0x44` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-772.0.0.0.0
+772.0.3.0.0

-  Functions: 2147
-  Symbols:   135
-  CStrings:  288
+  Functions: 2128
+  Symbols:   134
+  CStrings:  286
Symbols:
- _swift_retain_x8
CStrings:
+ "%s.%s: Settings Experience Plugin - Initiating Deep Linking resolution request for URL: %s"
+ "Attempting to perform update action \"%s\" to resolve the deep link action: %s"
+ "deepLinkRequest"
- "%s.%s: Settings Experience - Initiating Deep Linking resolution request for URL:  %s"
- ":"
- "Atempting to perform update action \"%s\" to resolve the deep link action: %s"
- "SoftwareUpdateUIMobileSettingsPlugin/SoftwareUpdateSettings.swift"
- "View.task @ "
```
