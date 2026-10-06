## AppManagedFeaturesUI

> `/Applications/LimitedModeShieldApp.app/Frameworks/AppManagedFeaturesUI.framework/AppManagedFeaturesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23450` | `0x23914` | **`+0x4c4`** |
| `__TEXT.__cstring` | `0xbb1` | `0xc71` | **`+0xc0`** |
| `__DATA.__common` | `0x8` | `0x28` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1640` | `0x1660` | **`+0x20`** |
| `__TEXT.__const` | `0x1238` | `0x1258` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xb28` | `0xb38` | **`+0x10`** |
| `__DATA.__data` | `0x748` | `0x758` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3c8` | `0x3b8` | **`-0x10`** |
| `__AUTH.__objc_data` | `0x830` | `0x838` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x838` | `0x840` | **`+0x8`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_selrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-46.0.7.0.0
+46.0.15.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 707
-  Symbols:   640
-  CStrings:  327
+  Functions: 711
+  Symbols:   642
+  CStrings:  329
Symbols:
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_wapiCapability
CStrings:
+ " may restrict access to most of your apps on this iPhone. \n\nYou’ll still be able to use “"
+ "Choose WLAN Network"
+ "Information needed to set up this device couldn't load. Check your internet connection and try again.  If that doesn’t work, contact the store where you bought the device."
+ "” from requesting access to sensitive personal information, such as your Photo Library or Precise Location."
+ "” may collect other personal data directly in this app with your permission.  \n\niOS prevents “"
+ "” will have access to device identifiers such as the serial number of your device. \n\n“"
- " may block access to most of your apps and their associated subscriptions on this iPhone. \n\nYou’ll still be able to use “"
- "Provider information is needed to set up this device and couldn't be loaded. Check your internet connection and try again."
- "” is restricted from requesting access to sensitive personal information like your Photo Library or Location."
- "” will not be able to access your personal data. \n\n“"
```
