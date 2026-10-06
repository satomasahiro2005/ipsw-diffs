## AppConduit

> `/System/Library/PrivateFrameworks/AppConduit.framework/AppConduit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x62e1` | `0x633e` | **`+0x5d`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x230` | `0x280` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x1474` | `0x14a4` | **`+0x30`** |
| `__TEXT.__text` | `0x1dff0` | `0x1e01c` | **`+0x2c`** |
| `__AUTH_CONST.__cfstring` | `0x29c0` | `0x29e0` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x1be8` | `0x1c08` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xfc0` | `0xfe0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x8e8` | `0x8f0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x7c8` | `0x7c0` | **`-0x8`** |

### Other Changes

```diff

-405.0.0.0.0
+408.0.0.0.0

-  Functions: 568
-  Symbols:   1097
-  CStrings:  539
+  Functions: 571
+  Symbols:   1103
+  CStrings:  541
Symbols:
+ +[ACXFeatureFlags restrictedDistributedNotificationsEnabled]
+ -[LSApplicationRecord(AppConduitAdditions) ACX_isDeletableSystemApp]
+ -[LSApplicationRecord(AppConduitAdditions) ACX_isDeletable]
+ __OBJC_$_CLASS_METHODS_ACXFeatureFlags
+ __os_feature_enabled_impl
+ _kACXRemoteAppNotificationReadEntitlement
CStrings:
+ "com.apple.appconduit.remote-app-notifications.read"
+ "restrictedDistributedNotificationsEnabled"
```
