## ManagedAppsCore

> `/System/Library/PrivateFrameworks/ManagedAppsCore.framework/ManagedAppsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7eb74` | `0x7ec6c` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0x1682` | `0x16c2` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1520` | `0x1550` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x49ec` | `0x4a14` | **`+0x28`** |
| `__TEXT.__const` | `0x4cc0` | `0x4ca0` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x1928` | `0x1910` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0xbc0` | `0xbb0` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x163f` | `0x1635` | **`-0xa`** |

### Other Changes

```diff

-105.0.0.0.0
+107.0.0.0.0

-  Symbols:   702
-  CStrings:  239
+  Symbols:   698
+  CStrings:  241
Symbols:
- _objc_retain_x27
- _swift_deallocPartialClassInstance
- _swift_release_x9
- _symbolic SDySSyXlG
CStrings:
+ "%s - failed to copy path for managed preferences"
+ "%{public}s - managementKey: %{public}s, appCodeIdentity: %s extensions: [ %s ]"
+ "CFPrefsPathForManagedDomain(bundleID:)"
- "%{public}s - managementKey: %{public}s, appCodeIdentity: %s extensions: %ld"
```
