## ReplayKit

> `/System/Library/Frameworks/ReplayKit.framework/ReplayKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35f3c` | `0x361a8` | **`+0x26c`** |
| `__AUTH_CONST.__objc_const` | `0x66c8` | `0x66e8` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x56af` | `0x569a` | **`-0x15`** |
| `__AUTH_CONST.__auth_got` | `0x5c8` | `0x5c0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x4c8` | `0x4d0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2110` | `0x2118` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x35f8` | `0x3600` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2e0` | `0x2e4` | **`+0x4`** |
| `__TEXT.__cstring` | `0x8009` | `0x800a` | **`+0x1`** |

### Other Changes

```diff

-740.44.1.0.0
+740.48.1.0.0

-  Symbols:   2219
+  Symbols:   2221
Symbols:
+ -[RPControlCenterClient cacheImageIfNeededForBundleID:extensionInfo:]
+ _OBJC_CLASS_$_NSCache
+ _OBJC_IVAR_$_RPControlCenterClient._availableExtensionsLock
+ _SBSGetScreenLockStatus
- _objc_opt_new
- _objc_unsafeClaimAutoreleasedReturnValue
CStrings:
+ " [INFO] %{public}s:%d Screen lock status=%d"
- " [ERROR] %{public}s:%d imageForBundleID called with nil bundleID"
```
