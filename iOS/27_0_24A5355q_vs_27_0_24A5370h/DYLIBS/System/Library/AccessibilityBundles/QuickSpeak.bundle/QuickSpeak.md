## QuickSpeak

> `/System/Library/AccessibilityBundles/QuickSpeak.bundle/QuickSpeak`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9324` | `0x92ec` | **`-0x38`** |

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0
Functions:
~ -[NSObject_QSExtras _accessibilitySpeakLanguageSelection:] : 1720 -> 1704
~ +[AXQuickSpeak quickSpeakClassIsDenied:] : 592 -> 588
~ -[AXQuickSpeak _manipulateOtherTextViews:] : 620 -> 616
~ -[AXQuickSpeak _rectsByUnionSamelineRects:] : 328 -> 324
~ -[AXQuickSpeak _sliceRects:withSentenceRects:wordRects:] : 948 -> 944
~ -[AXQuickSpeak _handleQuickSpeakHighlight:sentenceRects:textRect:initiator:] : 2800 -> 2796
~ -[AXQuickSpeak selectedContentRequiresUserChoice] : 712 -> 704
~ -[PDFView_QSExtras _axConvertRange:toRects:operatingPage:] : 708 -> 704
~ ___74-[UITextInteraction_QSExtras _updatedAccessibilityTextSpeechMenuWithMenu:]_block_invoke : 2048 -> 2044
~ -[WKContentView_QSExtras _webTextRectsFromWKTextRects:] : 356 -> 352
```
