## TelephonyPreferences

> `/System/Library/PrivateFrameworks/TelephonyPreferences.framework/TelephonyPreferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30c4c` | `0x30bf4` | **`-0x58`** |
| `__AUTH_CONST.__objc_const` | `0x75c8` | `0x75b8` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2358` | `0x2350` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x4000` | `0x3ff8` | **`-0x8`** |

### Other Changes

```diff

-401.100.1.0.0
+405.100.1.0.0

-  Functions: 1428
-  Symbols:   2675
+  Functions: 1427
+  Symbols:   2674
Symbols:
+ -[TPSWiFiCallingController canEnableThumperCalling]
- -[TPSCloudCallingThumperController supportsThumperCalling]
- -[TPSWiFiCallingController supportsThumperCalling]
Functions:
~ -[TPSCloudCallingThumperProvisioningURLController shouldShowUpgradeToThumperButton] : 152 -> 136
- -[TPSCloudCallingThumperController supportsThumperCalling]
~ -[TPSWiFiCallingController isThumperCallingEnabled] : 96 -> 80
```
