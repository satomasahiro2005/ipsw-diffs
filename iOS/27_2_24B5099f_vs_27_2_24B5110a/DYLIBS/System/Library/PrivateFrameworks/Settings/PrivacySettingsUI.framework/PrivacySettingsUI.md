## PrivacySettingsUI

> `/System/Library/PrivateFrameworks/Settings/PrivacySettingsUI.framework/PrivacySettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6a6e4` | `0x6ad10` | **`+0x62c`** |
| `__AUTH_CONST.__objc_const` | `0x6850` | `0x68d0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x4444` | `0x448c` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x3480` | `0x34a8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x18e8` | `0x1908` | **`+0x20`** |
| `__DATA.__data` | `0x5f8` | `0x610` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xaf8` | `0xb08` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x490` | `0x4a0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xab8` | `0xac8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x87c4` | `0x87d4` | **`+0x10`** |

### Other Changes

```diff

-2027.1.9.0.0
+2027.1.10.0.0

-  Functions: 2189
-  Symbols:   3789
+  Functions: 2200
+  Symbols:   3803
Symbols:
+ -[PUIMotionSensorsRestrictController .cxx_destruct]
+ -[PUIMotionSensorsRestrictController forceReloadIgnoringGuards]
+ -[PUIMotionSensorsRestrictController performReloadNow]
+ -[PUIMotionSensorsRestrictController requestReload]
+ -[PUIMotionSensorsRestrictController restartReloadThrottleWindow]
+ -[PUIMotionSensorsRestrictController tableView:didEndEditingRowAtIndexPath:]
+ -[PUIMotionSensorsRestrictController tableView:willBeginEditingRowAtIndexPath:]
+ _OBJC_IVAR_$_PUIMotionSensorsRestrictController._interactingSettleBlock
+ _OBJC_IVAR_$_PUIMotionSensorsRestrictController._reloadPending
+ _OBJC_IVAR_$_PUIMotionSensorsRestrictController._reloadThrottleActive
+ _OBJC_IVAR_$_PUIMotionSensorsRestrictController._reloadThrottleBlock
+ _OBJC_IVAR_$_PUIMotionSensorsRestrictController._userIsInteracting
+ ___65-[PUIMotionSensorsRestrictController restartReloadThrottleWindow]_block_invoke
+ ___76-[PUIMotionSensorsRestrictController tableView:didEndEditingRowAtIndexPath:]_block_invoke
+ _dispatch_block_cancel
+ _dispatch_block_create
- -[PUIMotionSensorsRestrictController reloadRestrictedApps]
- _OBJC_IVAR_$_PUIMotionSensorsRestrictController._ignoringNextAccessChangedNotification
```
