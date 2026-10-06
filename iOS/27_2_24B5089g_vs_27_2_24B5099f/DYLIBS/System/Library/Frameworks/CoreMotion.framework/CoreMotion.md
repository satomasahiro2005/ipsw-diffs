## CoreMotion

> `/System/Library/Frameworks/CoreMotion.framework/CoreMotion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d0b34` | `0x3d0e64` | **`+0x330`** |
| `__TEXT.__cstring` | `0x47a46` | `0x47ac5` | **`+0x7f`** |
| `__TEXT.__gcc_except_tab` | `0xd4dc` | `0xd50c` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xbcd8` | `0xbcf8` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x2fcb7` | `0x2fcd1` | **`+0x1a`** |
| `__TEXT.__objc_methlist` | `0xd994` | `0xd9ac` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x1dd68` | `0x1dd78` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x5718` | `0x5728` | **`+0x10`** |

### Other Changes

```diff

-3186.0.17.0.1
+3186.0.21.0.0

-  Functions: 12717
+  Functions: 12720

-  CStrings:  11439
+  CStrings:  11441
CStrings:
+ "#Spi, _CLInternalClearLocationAuthorizationLoctool failed"
+ "-[CLLocationInternalClient_CoreMotion clearLocationAuthorizationForLoctoolWithBundleId:orBundlePath:]_block_invoke"
+ "22:22:50"
+ "CLMotionTypeAngleEventPhase toCLMotionType(CMAngleReportEventPhase)"
+ "Sep 28 2026"
+ "[CLAngleNotifier] Unrecognized phase 0x%{public}x"
+ "[CMAngleManager] Unrecognized phase 0x%{public}x"
+ "const char *toString(CMAngleReportEventPhase)"
- "-[CMDeviceStateManager queryDeviceStateBlocking]"
- "-[CMDeviceStateManager queryDeviceStateWithHandler:]"
- "21:39:32"
- "Sep 15 2026"
- "queryDeviceStateBlocking is unsupported and should not be used."
- "queryDeviceStateWithHandler is unsupported and should not be used."
```
