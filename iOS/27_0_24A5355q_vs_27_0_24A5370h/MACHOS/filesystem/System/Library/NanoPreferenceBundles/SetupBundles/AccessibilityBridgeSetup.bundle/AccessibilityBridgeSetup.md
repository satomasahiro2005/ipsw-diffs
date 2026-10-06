## AccessibilityBridgeSetup

> `/System/Library/NanoPreferenceBundles/SetupBundles/AccessibilityBridgeSetup.bundle/AccessibilityBridgeSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22dc` | `0x22d0` | **`-0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1029.0.0.0.0
+1032.0.0.0.0
Functions:
~ -[AccessibilitySettingsViewController initWithAccessibilityOptions:device:] : 572 -> 568
~ -[AccessibilitySettingsViewController alternateButtonPressed:] : 368 -> 364
~ _accessibilitySetAccessibilityOptionsOnDevice : 656 -> 652
```
