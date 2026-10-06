## LocationAuthorizationFramework

> `/System/Library/PrivateFrameworks/LocationAuthorizationFramework.framework/LocationAuthorizationFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66624` | `0x67730` | **`+0x110c`** |
| `__TEXT.__oslogstring` | `0x6ff4` | `0x7277` | **`+0x283`** |
| `__AUTH_CONST.__cfstring` | `0x14c0` | `0x1560` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x2891` | `0x292d` | **`+0x9c`** |
| `__TEXT.__objc_methlist` | `0x12b8` | `0x1330` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0xe88` | `0xed0` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x101c` | `0x1060` | **`+0x44`** |
| `__AUTH_CONST.__objc_const` | `0x1c50` | `0x1c80` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x348` | `0x368` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1650` | `0x1668` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x860` | `0x870` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xd20` | `0xd18` | **`-0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x848` | `0x850` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xa58` | `0xa60` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x94` | `0x98` | **`+0x4`** |

### Other Changes

```diff

-3176.0.0.0.0
+3183.0.0.0.0

-  Functions: 1912
-  Symbols:   435
-  CStrings:  555
+  Functions: 1922
+  Symbols:   439
+  CStrings:  562
Symbols:
+ _CLAuthorizationDatabaseErrorDomain
+ _NSLocalizedDescriptionKey
+ _OBJC_CLASS_$_CLSettingsDictionary
+ _OBJC_CLASS_$_NSError
+ ___kCFBooleanTrue
+ _memset
+ _swift_retain_x25
- __os_feature_enabled_impl
- _swift_retain_x26
- _swift_retain_x27
CStrings:
+ "#AuthorizationDatabase promote: not a known system service"
+ "%@ is already a bellwether or standalone; nothing to promote"
+ "%@ is not a known system service"
+ "Attempting to remove System Service from #AuthorizationDatabase! Refusing removal, since it's not a symlink'd or quarantine'd system service."
+ "Quarantined"
+ "QuarantinedClients"
+ "com.apple.locationd.authorizationdatabase.errorDomain"
+ "{\"msg%{public}.0s\":\"#AuthorizationDatabase promote: already a bellwether/standalone\", \"BundlePath\":%{public, location:escape_only}@}"
+ "{\"msg%{public}.0s\":\"#AuthorizationDatabase promote: not a known system service\", \"BundlePath\":%{public, location:escape_only}@}"
+ "{\"msg%{public}.0s\":\"#AuthorizationDatabase promoted innate system service to standalone\", \"BundlePath\":%{public, location:escape_only}@, \"StandaloneKey\":%{public, location:escape_only}@}"
+ "{\"msg%{public}.0s\":\"Attempting to remove System Service from #AuthorizationDatabase! Refusing removal, since it's not a symlink'd or quarantine'd system service.\", \"System Service\":%{public, location:escape_only}@}"
- "Attempting to remove System Service from #AuthDatabase! Refusing removal."
- "AuthSync2"
- "CoreLocation"
- "{\"msg%{public}.0s\":\"Attempting to remove System Service from #AuthDatabase! Refusing removal.\", \"System Service\":%{public, location:escape_only}@}"
```
