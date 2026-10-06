## AssistantUI

> `/System/Library/AccessibilityBundles/AssistantUI.axbundle/AssistantUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d68` | `0x1b68` | **`-0x200`** |
| `__AUTH_CONST.__cfstring` | `0x800` | `0x780` | **`-0x80`** |
| `__TEXT.__cstring` | `0x62b` | `0x5e7` | **`-0x44`** |
| `__TEXT.__oslogstring` | `0x77` | `0x35` | **`-0x42`** |
| `__DATA_CONST.__objc_selrefs` | `0x258` | `0x238` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xc0` | `0xb8` | **`-0x8`** |
| `__TEXT.__const` | `0x18` | `0x10` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x20c` | `0x204` | **`-0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 45
-  Symbols:   177
-  CStrings:  84
+  Functions: 44
+  Symbols:   173
+  CStrings:  79
Symbols:
- -[AFUISiriSessionAccessibility cancelRequest]
- _AXIsInternalInstall
- _OBJC_CLASS_$_NSNumber
- _objc_unsafeClaimAutoreleasedReturnValue
Functions:
~ +[AFUISiriSessionAccessibility _accessibilityPerformValidations:] : 216 -> 148
- -[AFUISiriSessionAccessibility cancelRequest]
~ +[AFUISiriCompactViewAccessibility _accessibilityPerformValidations:] : 532 -> 472
~ ___68-[AFUISiriCompactViewAccessibility accessibilityElementDidLoseFocus]_block_invoke : 272 -> 184
CStrings:
- "Transferring voice cancel request in progress %@ to connection %@"
- "VoiceOverCancelRequestInProgress"
- "_connection"
- "_session"
- "cancelRequest"
```
