## UserProfilesCore

> `/System/Library/PrivateFrameworks/UserProfilesCore.framework/UserProfilesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb48c` | `0xb460` | **`-0x2c`** |
| `__TEXT.__const` | `0x2b6` | `0x2c6` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x400` | `0x3f8` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-299.10.18.0.0
+299.10.20.0.1

-  Symbols:   819
-  CStrings:  144
+  Symbols:   818
+  CStrings:  143
Symbols:
- __os_feature_enabled_impl
Functions:
~ -[UPPlatform _initWithDeviceClass:systemVersion:buildVersion:productType:] : 508 -> 464
CStrings:
- "homePod"
```
