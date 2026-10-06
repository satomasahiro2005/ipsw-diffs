## IdentityLookup

> `/System/Library/Frameworks/IdentityLookup.framework/IdentityLookup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x258f0` | `0x28588` | **`+0x2c98`** |
| `__TEXT.__const` | `0xbe0` | `0xda0` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x985` | `0xad1` | **`+0x14c`** |
| `__AUTH_CONST.__const` | `0x8c8` | `0x9c8` | **`+0x100`** |
| `__DATA.__bss` | `0xad0` | `0xbd0` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0xdbd` | `0xe7d` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0xb80` | `0xc20` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x46e` | `0x4f2` | **`+0x84`** |
| `__TEXT.__swift5_reflstr` | `0x258` | `0x2d8` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x3ac` | `0x408` | **`+0x5c`** |
| `__AUTH_CONST.__auth_got` | `0x850` | `0x8a8` | **`+0x58`** |
| `__DATA.__data` | `0x770` | `0x7b8` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0xad0` | `0xb10` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x6cc` | `0x708` | **`+0x3c`** |
| `__DATA_CONST.__objc_selrefs` | `0x840` | `0x878` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x250` | `0x278` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x50` | **`+0x14`** |
| `__DATA.__common` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x530` | `0x538` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0xc` | `0x10` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x58` | `0x5c` | **`+0x4`** |

### Other Changes

```diff

-1392.100.3.0.0
+1394.100.1.0.0

+  - /System/Library/PrivateFrameworks/FTServices.framework/FTServices

+  - /usr/lib/swift/libswiftCompression.dylib

-  Functions: 925
-  Symbols:   1094
-  CStrings:  148
+  Functions: 952
+  Symbols:   1110
+  CStrings:  159
Symbols:
+ _OBJC_CLASS_$_FTServerBag
+ _OBJC_CLASS_$_NSUserDefaults
+ ___swift_memcpy25_8
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_IdentityLookup
+ _associated conformance 14IdentityLookup20PlistValidationErrorO10Foundation09LocalizedE0AAs0E0
+ _bzero
+ _get_enum_tag_for_layout_string 14IdentityLookup20PlistValidationErrorO
+ _symbolic $s14IdentityLookup18ServerBagProvidingP
+ _symbolic SDySSypG
+ _symbolic SS10identifier_SaySSG4keyst
+ _symbolic SS______t 10Foundation3URLV
+ _symbolic SaySSG
+ _symbolic _____ 14IdentityLookup20PlistValidationErrorO
+ _symbolic _____ySS_____G s18_DictionaryStorageC 10Foundation3URLV
+ _symbolic ypSg
+ _type_layout_string 14IdentityLookup20PlistValidationErrorO
- _swift_retain_x28
CStrings:
+ " has values that are not valid URLs for keys: "
+ " missing required plist keys: "
+ "Cannot read info dictionary for extension: "
+ "Error found while validating plist for extension: "
+ "Extension %s, failed plist validation: %@ marking as uninstalled"
+ "Extension not found: "
+ "PIRConfiguration"
+ "liveCallerIDPlistValidationDisabled"
+ "livecalleridProfileEnabled"
+ "not re-enabling extension %s, failed plist validation: %@"
+ "plist validated successfully for extension %s"
```
