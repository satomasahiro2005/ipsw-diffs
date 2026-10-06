## DeviceRecovery

> `/System/Library/PrivateFrameworks/DeviceRecovery.framework/DeviceRecovery`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x104ec` | `0x10c08` | **`+0x71c`** |
| `__TEXT.__cstring` | `0x2779` | `0x2889` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x1145` | `0x11e7` | **`+0xa2`** |
| `__TEXT.__objc_methlist` | `0x768` | `0x7c0` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0xf40` | `0xf80` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x8e8` | `0x928` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x538` | `0x560` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x468` | `0x480` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x520` | `0x528` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x60` | `0x64` | **`+0x4`** |

### Other Changes

```diff

-150.40.7.0.0
+150.40.9.0.0

-  Functions: 525
-  Symbols:   544
-  CStrings:  313
+  Functions: 539
+  Symbols:   553
+  CStrings:  322
Symbols:
+ -[DeviceRecoveryController addEraseAndUpdateRestrictionForClient:completion:]
+ -[DeviceRecoveryController eraseAndUpdateRestricted]
+ -[DeviceRecoveryController removeEraseAndUpdateRestrictionForClient:completion:]
+ -[DeviceRecoveryController setEraseAndUpdateRestricted:]
+ -[DeviceRecoveryController setEraseAndUpdateRestriction:forClient:completion:]
+ _DRServiceAttributeEraseAndUpdateRestricted
+ _OBJC_IVAR_$_DeviceRecoveryController._eraseAndUpdateRestricted
+ _OUTLINED_FUNCTION_33
+ ___78-[DeviceRecoveryController setEraseAndUpdateRestriction:forClient:completion:]_block_invoke
CStrings:
+ "%{public}s: Could not update EACS / Software Update restriction: %{public}@"
+ "%{public}s: Framework: %{public}s EACS / Software Update restriction for '%{public}@'"
+ "-[DeviceRecoveryController setEraseAndUpdateRestriction:forClient:completion:]"
+ "-[DeviceRecoveryController setEraseAndUpdateRestriction:forClient:completion:]_block_invoke"
+ "EraseAndUpdateRestricted"
+ "adding"
+ "clientIdentifier.length > 0"
+ "no client identifier provided"
+ "removing"
```
