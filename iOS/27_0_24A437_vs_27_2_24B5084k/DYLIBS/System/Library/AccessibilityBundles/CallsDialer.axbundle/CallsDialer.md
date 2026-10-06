## CallsDialer

> `/System/Library/AccessibilityBundles/CallsDialer.axbundle/CallsDialer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e3c` | `0x2e20` | **`-0x1c`** |
| `__TEXT.__unwind_info` | `0x1a8` | `0x1a0` | **`-0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0
Symbols:
+ -[PHHandsetDialerViewAccessibility _axAnnotateCallButton:]
+ ___58-[PHHandsetDialerViewAccessibility _axAnnotateCallButton:]_block_invoke
- -[PHHandsetDialerViewAccessibility _axAnnotateCallButton]
- ___57-[PHHandsetDialerViewAccessibility _axAnnotateCallButton]_block_invoke
Functions:
~ -[PHHandsetDialerViewAccessibility _accessibilityLoadAccessibilityInformation] : 76 -> 108
~ -[PHHandsetDialerViewAccessibility newCallButton] : 84 -> 88
~ -[PHHandsetDialerViewAccessibility _axAnnotateCallButton] -> -[PHHandsetDialerViewAccessibility _axAnnotateCallButton:] : 80 -> 16
```
