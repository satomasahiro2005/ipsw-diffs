## ConversationKit

> `/System/Library/AccessibilityBundles/ConversationKit.axbundle/ConversationKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x913c` | `0x9024` | **`-0x118`** |
| `__TEXT.__cstring` | `0x1c02` | `0x1c5a` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0x2040` | `0x2080` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xe20` | `0xe10` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x5c8` | `0x5c0` | **`-0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 299
-  Symbols:   796
-  CStrings:  291
+  Functions: 298
+  Symbols:   795
+  CStrings:  294
Symbols:
+ GCC_except_table238
- -[InCallControlsParticipantCellAccessibility _accessibilityActivateKickMemberButton]
- GCC_except_table239
Functions:
~ +[InCallControlsParticipantCellAccessibility _accessibilityPerformValidations:] : 312 -> 284
~ -[InCallControlsParticipantCellAccessibility accessibilityCustomActions] : 544 -> 432
- -[InCallControlsParticipantCellAccessibility _accessibilityActivateKickMemberButton]
CStrings:
+ "$__lazy_storage_$_lmiApproveButton"
+ "$__lazy_storage_$_lmiRejectButton"
+ "Optional<UIButton>"
```
