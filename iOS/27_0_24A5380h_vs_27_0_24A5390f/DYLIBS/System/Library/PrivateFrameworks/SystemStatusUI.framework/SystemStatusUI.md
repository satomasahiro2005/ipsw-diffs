## SystemStatusUI

> `/System/Library/PrivateFrameworks/SystemStatusUI.framework/SystemStatusUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa123c` | `0xa1fa4` | **`+0xd68`** |
| `__TEXT.__const` | `0x3420` | `0x3870` | **`+0x450`** |
| `__AUTH.__objc_data` | `0x1350` | `0x1238` | **`-0x118`** |
| `__DATA_DIRTY.__objc_data` | `0x2c60` | `0x2d78` | **`+0x118`** |
| `__AUTH_CONST.__const` | `0x1348` | `0x1408` | **`+0xc0`** |
| `__DATA.__bss` | `0x1d38` | `0x1d98` | **`+0x60`** |
| `__DATA_DIRTY.__data` | `—` | `0x50` | **`+0x50`** |
| `__AUTH.__data` | `0x2b0` | `0x280` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x13af8` | `0x13b28` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x25c0` | `0x25d8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xbc0` | `0xbd0` | **`+0x10`** |
| `__DATA.__data` | `0x16f0` | `0x16e0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0xaf34` | `0xaf24` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x520` | `0x528` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x530` | `0x52c` | **`-0x4`** |

### Other Changes

```diff

-282.0.0.0.0
+284.1.0.0.0

-  Functions: 4174
-  Symbols:   6910
+  Functions: 4182
+  Symbols:   6922
Symbols:
+ -[STUIStatusBarDisplayableContainerView forceAllowCrossfade]
+ -[STUIStatusBarDisplayableContainerView setForceAllowCrossfade:]
+ -[STUIStatusBarDisplayableContainerView wantsCrossfade]
+ -[STUIStatusBarWirelessChargerView _drawChargingInRect:capacityColor:boltColor:level:]
+ -[STUIStatusBarWirelessChargerView _drawDeviceEnabledInRect:]
+ -[STUIStatusBarWirelessChargerView _drawErrorInRect:]
+ -[STUIStatusBarWirelessChargerView _drawOutlineInRect:]
+ _BoltTemplate
+ _CGContextRestoreGState
+ _CGContextSaveGState
+ _OBJC_IVAR_$_STUIStatusBarDisplayableContainerView._forceAllowCrossfade
+ _OBJC_IVAR_$_STUIStatusBarWirelessChargerView._styleAttributes
+ _OuterPillTemplate
+ _PathAt
+ ___45-[STUIStatusBarWirelessChargerView drawRect:]_block_invoke
+ ___BoltTemplate_block_invoke
+ ___ExclamationTemplate_block_invoke
+ ___InnerPillTemplate_block_invoke
+ ___OuterPillTemplate_block_invoke
+ ___SlashCutTemplate_block_invoke
+ ___SlashMarkTemplate_block_invoke
- -[STUIStatusBarWirelessChargerView _drawBodyOutlineInRect:color:]
- -[STUIStatusBarWirelessChargerView _drawBoltInRect:color:]
- -[STUIStatusBarWirelessChargerView _drawExclamationInRect:color:]
- -[STUIStatusBarWirelessChargerView _drawFillInRect:level:color:displayScale:]
- -[STUIStatusBarWirelessChargerView _drawTerminalInRect:color:]
- -[STUIStatusBarWirelessChargerView _fillColor]
- -[STUIStatusBarWirelessChargerView _outlineColor]
- -[STUIStatusBarWirelessChargerView _shouldShowExclamation]
- -[STUIStatusBarWirelessChargerView _shouldShowFill]
```
