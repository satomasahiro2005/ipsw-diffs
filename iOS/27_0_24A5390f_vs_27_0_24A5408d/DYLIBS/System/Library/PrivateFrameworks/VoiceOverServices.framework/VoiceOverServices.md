## VoiceOverServices

> `/System/Library/PrivateFrameworks/VoiceOverServices.framework/VoiceOverServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34bdc` | `0x35848` | **`+0xc6c`** |
| `__AUTH_CONST.__cfstring` | `0x8f80` | `0x92a0` | **`+0x320`** |
| `__TEXT.__cstring` | `0x73e1` | `0x7659` | **`+0x278`** |
| `__AUTH_CONST.__const` | `0x3b80` | `0x3ca0` | **`+0x120`** |
| `__DATA.__bss` | `0x988` | `0xa10` | **`+0x88`** |
| `__AUTH_CONST.__objc_const` | `0x4400` | `0x4480` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x2f3c` | `0x2fb4` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x21d0` | `0x2238` | **`+0x68`** |
| `__DATA.__data` | `0xe50` | `0xe70` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2c8` | `0x2e8` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x170` | `0x190` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x138` | `0x150` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x770` | `0x778` | **`+0x8`** |

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 1479
-  Symbols:   3325
-  CStrings:  1213
+  Functions: 1498
+  Symbols:   3370
+  CStrings:  1238
Symbols:
+ +[VOSCommand Braille2DZoomIn]
+ +[VOSCommand Braille2DZoomOut]
+ +[VOSCommand BrailleShowImage]
+ +[VOSCommand IntelligentScreenDescription]
+ +[VOSCommand ShowRecognitionOptions]
+ +[VOSOutputEvent ImageRecognition]
+ +[VOSSettingsHelper swipeNavigationStyleFormatter]
+ +[VOSSettingsItem SwipeNavigation]
+ -[VOSCommandManager _migrateRetiredImageExplorerCommandDefaults:resolver:]
+ GCC_except_table1278
+ GCC_except_table1344
+ GCC_except_table1352
+ GCC_except_table1468
+ GCC_except_table1474
+ GCC_except_table300
+ GCC_except_table307
+ _AXAskShouldHideOptions
+ _AXSVoiceOverSwipeNavigationStyleElement
+ _AXSVoiceOverSwipeNavigationStyleLine
+ _AXSVoiceOverSwipeNavigationStyleParagraph
+ _AXSVoiceOverSwipeNavigationStyleSentence
+ _Braille2DZoomIn._Command
+ _Braille2DZoomIn.onceToken
+ _Braille2DZoomOut._Command
+ _Braille2DZoomOut.onceToken
+ _BrailleShowImage._Command
+ _BrailleShowImage.onceToken
+ _ImageRecognition._Event
+ _ImageRecognition.onceToken
+ _IntelligentScreenDescription._Command
+ _IntelligentScreenDescription.onceToken
+ _ShowRecognitionOptions._Command
+ _ShowRecognitionOptions.onceToken
+ _SwipeNavigation._SettingsItem
+ _SwipeNavigation.onceToken
+ _VOSAccessibilitySharedSupportBundle
+ _VOSAccessibilitySharedSupportBundle._sharedSupportBundle
+ ___29+[VOSCommand Braille2DZoomIn]_block_invoke
+ ___30+[VOSCommand Braille2DZoomOut]_block_invoke
+ ___30+[VOSCommand BrailleShowImage]_block_invoke
+ ___34+[VOSOutputEvent ImageRecognition]_block_invoke
+ ___34+[VOSSettingsItem SwipeNavigation]_block_invoke
+ ___36+[VOSCommand ShowRecognitionOptions]_block_invoke
+ ___42+[VOSCommand IntelligentScreenDescription]_block_invoke
+ ___50+[VOSSettingsHelper swipeNavigationStyleFormatter]_block_invoke
+ ___50+[VOSSettingsHelper swipeNavigationStyleFormatter]_block_invoke_2
+ _kVOTEventCommandBraille2DZoomIn
+ _kVOTEventCommandBraille2DZoomOut
+ _kVOTEventCommandIntelligentScreenDescription
+ _kVOTEventCommandShowRecognitionOptions
+ _swipeNavigationStyleFormatter.formatter
+ _swipeNavigationStyleFormatter.onceToken
- GCC_except_table1262
- GCC_except_table1325
- GCC_except_table1333
- GCC_except_table1449
- GCC_except_table1455
- GCC_except_table299
- GCC_except_table306
CStrings:
+ "/System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework"
+ "B"
+ "Braille2DZoomIn"
+ "Braille2DZoomOut"
+ "BrailleShowImage"
+ "Copy Focus Debug Info to Clipboard"
+ "E"
+ "ImageRecognition"
+ "IntelligentScreenDescription"
+ "LoopScanningMagnifier_HapticOnly_ML"
+ "LoopScanningMagnifier_ML"
+ "P"
+ "R"
+ "ShowRecognitionOptions"
+ "SwipeNavigation"
+ "VOSPref.item.value.swipeNavigationElement"
+ "VOSPref.item.value.swipeNavigationLine"
+ "VOSPref.item.value.swipeNavigationParagraph"
+ "VOSPref.item.value.swipeNavigationSentence"
+ "VOTEventCommandBraille2DZoomIn"
+ "VOTEventCommandBraille2DZoomOut"
+ "VOTEventCommandIntelligentScreenDescription"
+ "VOTEventCommandShowRecognitionOptions"
+ "ahap"
+ "wav"
```
