## SiriUI

> `/System/Library/AccessibilityBundles/SiriUI.axbundle/SiriUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1404` | `0x1294` | **`-0x170`** |
| `__AUTH_CONST.__cfstring` | `0x820` | `0x760` | **`-0xc0`** |
| `__TEXT.__cstring` | `0x5b9` | `0x54d` | **`-0x6c`** |
| `__DATA_CONST.__const` | `0xd8` | `0xb0` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x180` | `0x170` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x100` | `0xf8` | **`-0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 64
-  Symbols:   228
-  CStrings:  75
+  Functions: 63
+  Symbols:   226
+  CStrings:  69
Symbols:
- ___69-[SiriUISiriStatusViewAccessibility accessibilityElementDidLoseFocus]_block_invoke
- ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
Functions:
~ +[SiriUISiriStatusViewAccessibility _accessibilityPerformValidations:] : 288 -> 184
~ -[SiriUISiriStatusViewAccessibility accessibilityElementDidLoseFocus] : 128 -> 60
- ___69-[SiriUISiriStatusViewAccessibility accessibilityElementDidLoseFocus]_block_invoke
CStrings:
- "AFUISiriSession"
- "AFUISiriView"
- "AFUISiriViewController"
- "VoiceOverCancelRequestInProgress"
- "_session"
- "cancelRequest"
```
