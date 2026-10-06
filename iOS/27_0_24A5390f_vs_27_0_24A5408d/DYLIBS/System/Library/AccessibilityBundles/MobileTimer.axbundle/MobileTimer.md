## MobileTimer

> `/System/Library/AccessibilityBundles/MobileTimer.axbundle/MobileTimer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8d28` | `0x8eb0` | **`+0x188`** |
| `__AUTH_CONST.__cfstring` | `0x2520` | `0x2580` | **`+0x60`** |
| `__TEXT.__cstring` | `0x17ae` | `0x17d9` | **`+0x2b`** |
| `__DATA_CONST.__objc_selrefs` | `0x758` | `0x770` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xfa8` | `0xfb8` | **`+0x10`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 304
-  Symbols:   863
-  CStrings:  321
+  Functions: 305
+  Symbols:   864
+  CStrings:  324
Symbols:
+ -[MTATimerButtonsControllerAccessibility _axUpdateCancelButtonState]
+ -[MTATimerButtonsControllerAccessibility _axUpdateStartStopButtonState]
+ GCC_except_table174
+ GCC_except_table218
+ GCC_except_table246
+ ___block_descriptor_48_e8_32s40w_e15_"NSString"8?0lw40l8s32l8
- -[MTATimerButtonsControllerAccessibility _updateCancelButtonState]
- GCC_except_table173
- GCC_except_table217
- GCC_except_table245
- ___block_descriptor_48_e8_32s40w_e15_"NSString"8?0ls32l8w40l8
CStrings:
+ "MTDTVC"
+ "_startStopButton"
+ "sunriseSunsetLabel"
+ "timer.cancel"
+ "timer.start"
- "sunriseLabel"
- "sunsetLabel"
```
