## NanoHealthBalanceBridgeSettings

> `/System/Library/NanoPreferenceBundles/Applications/NanoHealthBalanceBridgeSettings.bundle/NanoHealthBalanceBridgeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x1c0` | `0x240` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x1fb` | `0x230` | **`+0x35`** |
| `__TEXT.__text` | `0x3698` | `0x36c4` | **`+0x2c`** |
| `__DATA.__objc_selrefs` | `0xc0` | `0xe0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1c6` | `0x1e6` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x128` | `0x138` | **`+0x10`** |
| `__DATA.__objc_data` | `0x108` | `0x110` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x118` | `0x120` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x118` | `0x120` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

+  - /System/Library/PrivateFrameworks/HealthUI.framework/HealthUI
+  - /System/Library/PrivateFrameworks/IconServices.framework/IconServices

-  Symbols:   112
-  CStrings:  50
+  Symbols:   113
+  CStrings:  54
Symbols:
+ _OBJC_CLASS_$_HKIconServicesImage
+ _OBJC_CLASS_$_ISImageDescriptor
- _OBJC_CLASS_$_UIImage
CStrings:
+ "com.apple.application-icon.vitals"
+ "displayScale"
+ "initWithSize:scale:"
+ "setAppearance:"
+ "setShape:"
+ "traitCollection"
- "imageNamed:inBundle:"
- "vitals_glass_icon"
```
