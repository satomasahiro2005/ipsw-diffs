## AnnounceDaemon

> `/System/Library/PrivateFrameworks/AnnounceDaemon.framework/AnnounceDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x2584` | `0x25a4` | **`+0x20`** |
| `__TEXT.__text` | `0x6a8a4` | `0x6a8b0` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xd10` | `0xd18` | **`+0x8`** |

### Other Changes

```diff

-  Symbols:   3061
-  CStrings:  868
+  Symbols:   3062
+  CStrings:  870
Symbols:
+ __os_feature_enabled_impl
Functions:
~ -[ANAnnouncementCoordinator supportsHomeKitGroupBroadcastingForCompanionConnection:] : 8 -> 20
CStrings:
+ "Home"
+ "HomeTheaterSurround"
```
