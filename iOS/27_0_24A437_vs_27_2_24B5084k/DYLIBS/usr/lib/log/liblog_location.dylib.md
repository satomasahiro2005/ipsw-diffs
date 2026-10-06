## liblog_location.dylib

> `/usr/lib/log/liblog_location.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6940` | `0x69f8` | **`+0xb8`** |
| `__AUTH_CONST.__cfstring` | `0x54e0` | `0x5580` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x4874` | `0x48d0` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0xae0` | `0xae8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x390` | `0x398` | **`+0x8`** |

### Other Changes

```diff

-3185.0.6.0.3
+3186.0.12.0.0

-  CStrings:  686
+  CStrings:  691
Functions:
~ -[CLLogFormatter JSONObjectWith_CLLocationDictionaryUtilitiesAuthorizationMask:info:] : 236 -> 420
CStrings:
+ " | "
+ "Always"
+ "CLLocationProvider_Type::kNotificationClientActivityTypeMaritime"
+ "Never"
+ "WhenInUse"
```
