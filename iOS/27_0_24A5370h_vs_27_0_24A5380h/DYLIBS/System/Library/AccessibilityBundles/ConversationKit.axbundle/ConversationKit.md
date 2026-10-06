## ConversationKit

> `/System/Library/AccessibilityBundles/ConversationKit.axbundle/ConversationKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x190` | `0x50` | **`-0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x1310` | `0x1450` | **`+0x140`** |
| `__AUTH_CONST.__cfstring` | `0x2000` | `0x2020` | **`+0x20`** |
| `__TEXT.__text` | `0x9018` | `0x902c` | **`+0x14`** |
| `__TEXT.__cstring` | `0x1bde` | `0x1be9` | **`+0xb`** |
| `__DATA.__bss` | `0xb` | `0x3` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x5c0` | `0x5c8` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xe18` | `0xe20` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 297
-  Symbols:   794
-  CStrings:  289
+  Functions: 298
+  Symbols:   795
+  CStrings:  290
Symbols:
+ -[LocalParticipantViewAccessibility _axButtonShelfHostView]
+ GCC_except_table238
- GCC_except_table237
Functions:
~ -[LocalParticipantViewAccessibility _accessibilityLoadAccessibilityInformation] : 284 -> 244
~ -[LocalParticipantViewAccessibility _accessibilitySupplementaryFooterViews] : 176 -> 144
+ -[LocalParticipantViewAccessibility _axButtonShelfHostView]
CStrings:
+ "microphone"
```
