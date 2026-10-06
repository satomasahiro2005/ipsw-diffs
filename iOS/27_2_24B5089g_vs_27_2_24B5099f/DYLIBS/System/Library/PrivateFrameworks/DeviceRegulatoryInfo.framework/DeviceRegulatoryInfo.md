## DeviceRegulatoryInfo

> `/System/Library/PrivateFrameworks/DeviceRegulatoryInfo.framework/DeviceRegulatoryInfo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b588` | `0x1b05c` | **`-0x52c`** |
| `__DATA.__bss` | `0xa00` | `0x880` | **`-0x180`** |
| `__TEXT.__const` | `0xd14` | `0xc04` | **`-0x110`** |
| `__TEXT.__eh_frame` | `0xb30` | `0xc28` | **`+0xf8`** |
| `__DATA_DIRTY.__data` | `—` | `0xd0` | **`+0xd0`** |
| `__AUTH.__data` | `0x530` | `0x490` | **`-0xa0`** |
| `__AUTH_CONST.__const` | `0xa10` | `0x998` | **`-0x78`** |
| `__DATA.__data` | `0x370` | `0x328` | **`-0x48`** |
| `__TEXT.__cstring` | `0x507` | `0x4c7` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x6e0` | `0x6b8` | **`-0x28`** |
| `__AUTH_CONST.__objc_const` | `0x4f0` | `0x510` | **`+0x20`** |
| `__DATA.__common` | `0xa0` | `0x80` | **`-0x20`** |
| `__DATA_DIRTY.__common` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x3aa` | `0x38a` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x3ac` | `0x390` | **`-0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x180` | `0x170` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x30d` | `0x31d` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x50` | `0x44` | **`-0xc`** |
| `__TEXT.__swift5_fieldmd` | `0x2ec` | `0x2f4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5d8` | `0x5e0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x58` | `0x54` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-2027.0.4.0.0
+2027.1.2.0.0

-  Functions: 420
-  Symbols:   321
-  CStrings:  83
+  Functions: 413
+  Symbols:   320
+  CStrings:  82
Symbols:
+ _MobileGestalt_get_iPadCapability
+ _MobileGestalt_get_mainScreenScale
+ ___swift_memcpy24_8
+ _symbolic _____ 20DeviceRegulatoryInfo09AccessoryB12ImageLocatorC0A6TraitsV
+ _symbolic _____ySiG s23_ContiguousArrayStorageC
+ _symbolic _____ySnySiGG s23_ContiguousArrayStorageC
+ _type_layout_string 20DeviceRegulatoryInfo09AccessoryB12ImageLocatorC0A6TraitsV
- _associated conformance 20DeviceRegulatoryInfo0abC11EditorErrorOSHAASQ
- _objc_retain_x28
- _symbolic SS_ypt
- _symbolic SayypG
- _symbolic _____ 20DeviceRegulatoryInfo0abC11EditorErrorO
- _symbolic _____ 20DeviceRegulatoryInfo0abC6EditorO
- _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
- _symbolic _____ySSypG s18_DictionaryStorageC
CStrings:
+ "Found regulatory image for model %{public}s at %{public}s"
+ "No regulatory image found for model %{public}s"
- "Found default regulatory image at %{public}s"
- "No default regulatory image found for model %{public}s"
- "regulatory plist not found — is this an AppleInternal device?"
```
