## ConversationKit

> `/System/Library/AccessibilityBundles/ConversationKit.axbundle/ConversationKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x902c` | `0x913c` | **`+0x110`** |
| `__AUTH_CONST.__cfstring` | `0x2020` | `0x2040` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1be9` | `0x1c02` | **`+0x19`** |
| `__TEXT.__gcc_except_tab` | `0x210` | `0x224` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x3f8` | `0x3f0` | **`-0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 298
-  Symbols:   795
-  CStrings:  290
+  Functions: 299
+  Symbols:   796
+  CStrings:  291
Symbols:
+ GCC_except_table135
+ GCC_except_table147
+ GCC_except_table150
+ GCC_except_table166
+ GCC_except_table182
+ GCC_except_table239
+ ___87-[LocalParticipantControlsViewAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_4
- GCC_except_table134
- GCC_except_table146
- GCC_except_table149
- GCC_except_table165
- GCC_except_table181
- GCC_except_table238
Functions:
~ +[LocalParticipantControlsViewAccessibility _accessibilityPerformValidations:] : 184 -> 212
~ -[LocalParticipantControlsViewAccessibility _accessibilityLoadAccessibilityInformation] : 688 -> 828
+ ___87-[LocalParticipantControlsViewAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_4
CStrings:
+ "cameraFlipButtonWithText"
```
