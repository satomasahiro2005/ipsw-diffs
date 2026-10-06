## AccessibilitySettings

> `/System/Library/NanoPreferenceBundles/General/AccessibilitySettings.bundle/AccessibilitySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38b20` | `0x38cc4` | **`+0x1a4`** |
| `__TEXT.__objc_methlist` | `0x2988` | `0x2998` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xcf8` | `0xd08` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bb8` | `0x1bc0` | **`+0x8`** |

### Other Changes

```diff

-3050.3.1.0.0
+3050.3.5.0.0

-  Functions: 1054
-  Symbols:   2046
+  Functions: 1057
+  Symbols:   2049
Symbols:
+ -[AccessibilityBridgeSettingsController _appSwitcherAutoSelectIsSupported]
+ GCC_except_table142
+ GCC_except_table192
+ GCC_except_table452
+ GCC_except_table603
+ GCC_except_table704
+ GCC_except_table827
+ _AXActivePairedDeviceIsOrchidBOrLater
+ _AXActivePairedDeviceSupportsAppSwitcher
- GCC_except_table141
- GCC_except_table189
- GCC_except_table449
- GCC_except_table600
- GCC_except_table701
- GCC_except_table824
```
