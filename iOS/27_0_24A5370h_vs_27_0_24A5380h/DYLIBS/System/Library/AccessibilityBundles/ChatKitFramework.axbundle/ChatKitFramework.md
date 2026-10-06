## ChatKitFramework

> `/System/Library/AccessibilityBundles/ChatKitFramework.axbundle/ChatKitFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__objc_data` | `0x5d70` | `0x6bd0` | **`+0xe60`** |
| `__AUTH.__objc_data` | `0x1590` | `0x7d0` | **`-0xdc0`** |
| `__AUTH_CONST.__objc_const` | `0xd308` | `0xd428` | **`+0x120`** |
| `__TEXT.__text` | `0x2b1ac` | `0x2b288` | **`+0xdc`** |
| `__AUTH_CONST.__cfstring` | `0xa840` | `0xa900` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x8c69` | `0x8d1f` | **`+0xb6`** |
| `__TEXT.__objc_methlist` | `0x4d50` | `0x4d78` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0xb80` | `0xb90` | **`+0x10`** |
| `__DATA.__bss` | `0x40` | `0x48` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3c0` | `0x3c8` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 1468
-  Symbols:   3713
-  CStrings:  1417
+  Functions: 1469
+  Symbols:   3726
+  CStrings:  1422
Symbols:
+ +[CKAssistantActionSuggestionButtonAccessibility _accessibilityPerformValidations:]
+ +[CKAssistantActionSuggestionButtonAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[CKAssistantActionSuggestionButtonAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[CKNanoAcknowledgmentBalloonViewAccessibility _accessibilityPerformValidations:]
+ +[CKNanoAcknowledgmentBalloonViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[CKNanoAcknowledgmentBalloonViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[CKAssistantActionSuggestionButtonAccessibility accessibilityLabel]
+ -[CKNanoAcknowledgmentBalloonViewAccessibility isAccessibilityElement]
+ GCC_except_table1051
+ GCC_except_table1075
+ GCC_except_table1134
+ GCC_except_table1193
+ GCC_except_table1206
+ GCC_except_table1264
+ GCC_except_table1306
+ GCC_except_table1322
+ GCC_except_table1350
+ GCC_except_table167
+ GCC_except_table185
+ GCC_except_table229
+ GCC_except_table244
+ GCC_except_table260
+ GCC_except_table274
+ GCC_except_table340
+ GCC_except_table352
+ GCC_except_table390
+ GCC_except_table409
+ GCC_except_table462
+ GCC_except_table466
+ GCC_except_table476
+ GCC_except_table481
+ GCC_except_table491
+ GCC_except_table517
+ GCC_except_table586
+ GCC_except_table678
+ GCC_except_table697
+ GCC_except_table705
+ GCC_except_table707
+ GCC_except_table725
+ GCC_except_table738
+ GCC_except_table778
+ GCC_except_table819
+ GCC_except_table842
+ GCC_except_table855
+ GCC_except_table923
+ GCC_except_table938
+ GCC_except_table959
+ _OBJC_CLASS_$_CKAssistantActionSuggestionButtonAccessibility
+ _OBJC_CLASS_$_CKNanoAcknowledgmentBalloonViewAccessibility
+ _OBJC_CLASS_$_UIImage
+ _OBJC_CLASS_$___CKAssistantActionSuggestionButtonAccessibility_super
+ _OBJC_CLASS_$___CKNanoAcknowledgmentBalloonViewAccessibility_super
+ _OBJC_METACLASS_$_CKAssistantActionSuggestionButtonAccessibility
+ _OBJC_METACLASS_$_CKNanoAcknowledgmentBalloonViewAccessibility
+ _OBJC_METACLASS_$___CKAssistantActionSuggestionButtonAccessibility_super
+ _OBJC_METACLASS_$___CKNanoAcknowledgmentBalloonViewAccessibility_super
+ __OBJC_$_CLASS_METHODS_CKAssistantActionSuggestionButtonAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS_CKNanoAcknowledgmentBalloonViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_CKAssistantActionSuggestionButtonAccessibility
+ __OBJC_$_INSTANCE_METHODS_CKNanoAcknowledgmentBalloonViewAccessibility
+ __OBJC_CLASS_RO_$_CKAssistantActionSuggestionButtonAccessibility
+ __OBJC_CLASS_RO_$_CKNanoAcknowledgmentBalloonViewAccessibility
+ __OBJC_CLASS_RO_$___CKAssistantActionSuggestionButtonAccessibility_super
+ __OBJC_CLASS_RO_$___CKNanoAcknowledgmentBalloonViewAccessibility_super
+ __OBJC_METACLASS_RO_$_CKAssistantActionSuggestionButtonAccessibility
+ __OBJC_METACLASS_RO_$_CKNanoAcknowledgmentBalloonViewAccessibility
+ __OBJC_METACLASS_RO_$___CKAssistantActionSuggestionButtonAccessibility_super
+ __OBJC_METACLASS_RO_$___CKNanoAcknowledgmentBalloonViewAccessibility_super
+ __UIImageIdentityName
- +[CKEntryViewPlusButtonAccessibility _accessibilityPerformValidations:]
- +[CKEntryViewPlusButtonAccessibility(SafeCategory) safeCategoryBaseClass]
- +[CKEntryViewPlusButtonAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[CKEntryViewPlusButtonAccessibility accessibilityActivate]
- -[CKEntryViewPlusButtonAccessibility accessibilityLabel]
- -[CKEntryViewPlusButtonAccessibility accessibilityTraits]
- -[CKEntryViewPlusButtonAccessibility isAccessibilityElement]
- GCC_except_table1050
- GCC_except_table1074
- GCC_except_table1133
- GCC_except_table1192
- GCC_except_table1205
- GCC_except_table1263
- GCC_except_table1305
- GCC_except_table1321
- GCC_except_table1349
- GCC_except_table159
- GCC_except_table177
- GCC_except_table228
- GCC_except_table243
- GCC_except_table259
- GCC_except_table273
- GCC_except_table339
- GCC_except_table351
- GCC_except_table389
- GCC_except_table408
- GCC_except_table461
- GCC_except_table465
- GCC_except_table475
- GCC_except_table479
- GCC_except_table490
- GCC_except_table516
- GCC_except_table585
- GCC_except_table677
- GCC_except_table696
- GCC_except_table704
- GCC_except_table706
- GCC_except_table724
- GCC_except_table737
- GCC_except_table777
- GCC_except_table817
- GCC_except_table841
- GCC_except_table854
- GCC_except_table922
- GCC_except_table937
- GCC_except_table958
- _OBJC_CLASS_$_CKEntryViewPlusButtonAccessibility
- _OBJC_CLASS_$___CKEntryViewPlusButtonAccessibility_super
- _OBJC_METACLASS_$_CKEntryViewPlusButtonAccessibility
- _OBJC_METACLASS_$___CKEntryViewPlusButtonAccessibility_super
- __OBJC_$_CLASS_METHODS_CKEntryViewPlusButtonAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_CKEntryViewPlusButtonAccessibility
- __OBJC_CLASS_RO_$_CKEntryViewPlusButtonAccessibility
- __OBJC_CLASS_RO_$___CKEntryViewPlusButtonAccessibility_super
- __OBJC_METACLASS_RO_$_CKEntryViewPlusButtonAccessibility
- __OBJC_METACLASS_RO_$___CKEntryViewPlusButtonAccessibility_super
CStrings:
+ "CKAssistantActionSuggestionButtonAccessibility"
+ "CKNanoAcknowledgmentBalloonView"
+ "CKTapbackPickerCollectionViewLayout"
+ "CKTextMessagePartChatItem"
+ "ChatKit.CKAssistantActionSuggestionButton"
+ "ChatKit.CKGlassSendMenuButton"
+ "UIButtonConfiguration"
+ "assistant.action.suggestion.tap.to.radar.button"
+ "configuration"
+ "configuration.image"
+ "radar"
- "Array<CKTitleIcon>"
- "CKEntryViewPlusButton"
- "CKEntryViewPlusButtonAccessibility"
- "CKGlassSendMenuButton"
- "CKSendMenuCollectionViewLayout"
- "_sendButton"
```
