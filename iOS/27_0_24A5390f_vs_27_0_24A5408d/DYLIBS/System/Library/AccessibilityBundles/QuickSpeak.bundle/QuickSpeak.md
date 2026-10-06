## QuickSpeak

> `/System/Library/AccessibilityBundles/QuickSpeak.bundle/QuickSpeak`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x920c` | `0x99cc` | **`+0x7c0`** |
| `__AUTH_CONST.__objc_const` | `0x1870` | `0x1ab0` | **`+0x240`** |
| `__AUTH_CONST.__cfstring` | `0xe80` | `0x1020` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0xd23` | `0xe8c` | **`+0x169`** |
| `__AUTH.__objc_data` | `0x780` | `0x8c0` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0xfac` | `0x1044` | **`+0x98`** |
| `__DATA_CONST.__const` | `0x230` | `0x280` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xd38` | `0xd78` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2c0` | `0x2f8` | **`+0x38`** |
| `__DATA_CONST.__objc_classlist` | `0xc0` | `0xe0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x27c` | `0x294` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x38` | `0x48` | **`+0x10`** |
| `__TEXT.__const` | `0x50` | `0x58` | **`+0x8`** |

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 203
-  Symbols:   574
-  CStrings:  152
+  Functions: 216
+  Symbols:   610
+  CStrings:  167
Symbols:
+ +[CKChatController_ClickyOrb_QSExtras _accessibilityPerformValidations:]
+ +[CKChatController_ClickyOrb_QSExtras(SafeCategory) safeCategoryBaseClass]
+ +[CKChatController_ClickyOrb_QSExtras(SafeCategory) safeCategoryTargetClassName]
+ +[CKFullScreenBalloonViewController_QSExtras _accessibilityPerformValidations:]
+ +[CKFullScreenBalloonViewController_QSExtras(SafeCategory) safeCategoryBaseClass]
+ +[CKFullScreenBalloonViewController_QSExtras(SafeCategory) safeCategoryTargetClassName]
+ -[CKChatController_ClickyOrb_QSExtras _axActionForSpeakSelection:]
+ -[CKChatController_ClickyOrb_QSExtras _menuForChatItem:withParentChatItem:menuAppearance:]
+ -[CKFullScreenBalloonViewController_QSExtras performCancelAnimationWithCompletion:]
+ GCC_except_table141
+ GCC_except_table149
+ GCC_except_table156
+ GCC_except_table176
+ GCC_except_table177
+ GCC_except_table183
+ GCC_except_table197
+ GCC_except_table28
+ _OBJC_CLASS_$_CKChatController_ClickyOrb_QSExtras
+ _OBJC_CLASS_$_CKFullScreenBalloonViewController_QSExtras
+ _OBJC_CLASS_$___CKChatController_ClickyOrb_QSExtras_super
+ _OBJC_CLASS_$___CKFullScreenBalloonViewController_QSExtras_super
+ _OBJC_METACLASS_$_CKChatController_ClickyOrb_QSExtras
+ _OBJC_METACLASS_$_CKFullScreenBalloonViewController_QSExtras
+ _OBJC_METACLASS_$___CKChatController_ClickyOrb_QSExtras_super
+ _OBJC_METACLASS_$___CKFullScreenBalloonViewController_QSExtras_super
+ __OBJC_$_CLASS_METHODS_CKChatController_ClickyOrb_QSExtras(SafeCategory)
+ __OBJC_$_CLASS_METHODS_CKFullScreenBalloonViewController_QSExtras(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_CKChatController_ClickyOrb_QSExtras
+ __OBJC_$_INSTANCE_METHODS_CKFullScreenBalloonViewController_QSExtras
+ __OBJC_CLASS_RO_$_CKChatController_ClickyOrb_QSExtras
+ __OBJC_CLASS_RO_$_CKFullScreenBalloonViewController_QSExtras
+ __OBJC_CLASS_RO_$___CKChatController_ClickyOrb_QSExtras_super
+ __OBJC_CLASS_RO_$___CKFullScreenBalloonViewController_QSExtras_super
+ __OBJC_METACLASS_RO_$_CKChatController_ClickyOrb_QSExtras
+ __OBJC_METACLASS_RO_$_CKFullScreenBalloonViewController_QSExtras
+ __OBJC_METACLASS_RO_$___CKChatController_ClickyOrb_QSExtras_super
+ __OBJC_METACLASS_RO_$___CKFullScreenBalloonViewController_QSExtras_super
+ ___66-[CKChatController_ClickyOrb_QSExtras _axActionForSpeakSelection:]_block_invoke
+ ___90-[CKChatController_ClickyOrb_QSExtras _menuForChatItem:withParentChatItem:menuAppearance:]_block_invoke
+ ___Block_byref_object_copy_
+ ___Block_byref_object_dispose_
+ ___block_descriptor_40_e8_32s_e18_v16?0"UIAction"8ls32l8
+ ___block_descriptor_56_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
- GCC_except_table137
- GCC_except_table145
- GCC_except_table163
- GCC_except_table164
- GCC_except_table170
- GCC_except_table184
- GCC_except_table24
CStrings:
+ "#"
+ "@?"
+ "CKBalloonChatItem"
+ "CKChatController"
+ "CKCoreChatController"
+ "CKFullScreenBalloonViewController"
+ "CKMessagePartChatItem"
+ "CKTranscriptCollectionViewController"
+ "_menuForChatItem:withParentChatItem:menuAppearance: @encode(id)"
+ "balloonViewClass"
+ "balloonViewForChatItem:"
+ "collectionViewController"
+ "performCancelAnimationWithCompletion:"
+ "rectangle.3.group.bubble.left"
+ "textView"
```
