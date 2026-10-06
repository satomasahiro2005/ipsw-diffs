## AssistantUI

> `/System/Library/AccessibilityBundles/AssistantUI.axbundle/AssistantUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b68` | `0x1c0c` | **`+0xa4`** |
| `__DATA_CONST.__got` | `0xb8` | `0xd8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x238` | `0x240` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x204` | `0x20c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xf0` | `0xf8` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 44
-  Symbols:   173
+  Functions: 45
+  Symbols:   179
Symbols:
+ -[AFUISiriSessionAccessibility _axClarityBundleIdentifierForStandardBundleIdentifier:]
+ _AX_CameraBundleName
+ _AX_ClarityCameraBundleName
+ _AX_ClarityPhotosBundleName
+ _AX_PhotosBundleName
+ _objc_retainAutoreleaseReturnValue
Functions:
~ -[AFUISiriSessionAccessibility _axIsAppInClarity:] : 132 -> 168
+ -[AFUISiriSessionAccessibility _axClarityBundleIdentifierForStandardBundleIdentifier:]
```
