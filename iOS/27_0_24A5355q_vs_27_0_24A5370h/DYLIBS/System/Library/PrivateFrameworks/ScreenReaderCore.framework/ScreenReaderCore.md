## ScreenReaderCore

> `/System/Library/PrivateFrameworks/ScreenReaderCore.framework/ScreenReaderCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24fd4` | `0x24f8c` | **`-0x48`** |
| `__TEXT.__unwind_info` | `0xa38` | `0xa40` | **`+0x8`** |

### Other Changes

```diff

-280.1.0.0.0
+281.0.0.0.0
Symbols:
+ _objc_retain_x12
- _objc_retain_x11
Functions:
~ -[SCRCArgumentParser parse] : 1252 -> 1228
~ -[SCRCArgumentParser _displayHelp:] : 872 -> 868
~ -[SCRCArgumentSubcommand description] : 428 -> 424
~ -[NSArray(SCRCArrayExtras) scrc_deepMutableCopyWithZone:] : 392 -> 388
~ -[NSBundle(SCRCBundleExtras) localizedStringForKey:table:locale:] : 916 -> 908
~ -[SCRCComposedCharacter copyUnicodeDescriptionString] : 252 -> 248
~ -[SCRCComposedCharacter _formKCContaintsUpperCase] : 148 -> 144
~ -[NSDictionary(SCRCDictionaryExtras) scrc_deepMutableCopyWithZone:] : 408 -> 404
~ -[SCRCGestureEvent dealloc] : 124 -> 120
~ -[SCRCGestureEvent description] : 208 -> 204
~ -[SCRCGestureEvent removeFingerWithIdentifier:] : 280 -> 272
~ -[SCRCGestureEvent fingerWithIdentifier:] : 116 -> 124
~ -[SCRCGestureEvent fingerWithoutIdentifier:] : 116 -> 124
~ -[SCRCGestureEvent fingers] : 144 -> 140
~ -[SCRCGestureEvent .cxx_destruct] : 60 -> 72
~ -[SCRCGestureFactory _down:] : 1356 -> 1336
~ -[SCRCGestureFactory _drag:] : 2724 -> 2792
~ -[SCRCGestureFactory captureCurrentState] : 1408 -> 1428
~ -[SCRCGestureFactory gestureState] : 40 -> 36
~ -[SCRCGestureFactory rawAverageLocation] : 112 -> 136
~ -[SCRCIndexMap initWithObjects:andIndexes:count:] : 192 -> 204
~ -[SCRCIndexMap _initAndDeepCopyIndexMap:] : 292 -> 280
~ ___47-[SCRCIndexMap _ensureCodableAttributedString:]_block_invoke : 324 -> 320
~ -[SCRCIndexMap encodeWithCoder:] : 380 -> 376
~ -[SCRCIndexMap indexes] : 148 -> 144
~ -[SCRCIndexMap addObjectsFromIndexMap:] : 168 -> 164
~ -[SCRCIndexMap description] : 296 -> 292
~ -[NSIndexPath(SCRCIndexPathExtras) initWithString:] : 280 -> 276
~ -[SCRCMathMultiscriptsExpression initWithDictionary:] : 784 -> 776
~ -[SCRCMathMultiscriptsExpression _subSuperScriptsDescriptionFromArray:withSpeakingStyle:arePausesAllowed:outSubscripts:outSuperscripts:] : 716 -> 712
~ -[SCRCMathArrayExpression initWithDictionary:] : 456 -> 452
~ -[SCRCMathArrayExpression speakableDescriptionWithSpeakingStyle:arePausesAllowed:] : 416 -> 412
~ -[SCRCMathArrayExpression mathMLString] : 388 -> 384
~ -[SCRCMathExpression maximumDepth] : 324 -> 320
~ -[SCRCMathExpression numberOfTables] : 260 -> 256
~ -[SCRCMathExpression maximumFractionLevelOfSubExpressions] : 288 -> 284
~ -[SCRCMathExpression latexDescriptionForChildrenJoinedByString:] : 388 -> 384
~ -[SCRCMathFractionExpression _speakableSegmentsWithSpeakingStyle:upToDepth:treePosition:asBinomialCoefficient:] : 800 -> 796
~ -[SCRCMathRadicalExpression speakableSegmentsWithSpeakingStyle:upToDepth:treePosition:] : 792 -> 788
~ -[SCRCMathRowExpression childSpeakableSegmentsWithSpeakingStyle:upToDepth:parentTreePosition:childIndex:] : 908 -> 904
~ -[SCRCMathRowExpression speakableSummary] : 600 -> 596
~ -[SCRCMathRowExpression latexDescriptionInMathMode:] : 496 -> 492
~ -[SCRCMathSubSuperscriptExpression speakableDescriptionWithSpeakingStyle:arePausesAllowed:] : 1096 -> 1080
~ -[SCRCMathSubSuperscriptExpression speakableSegmentsWithSpeakingStyle:upToDepth:treePosition:] : 1812 -> 1804
~ -[SCRCMathTableExpression _numberOfColumns] : 292 -> 288
~ -[SCRCMathUnderOverExpression speakableSegmentsWithSpeakingStyle:upToDepth:treePosition:] : 1232 -> 1224
~ +[SCRCPhotoEvaluatorBlur detect:inRect:] : 1572 -> 1596
~ +[SCRCPhotoEvaluatorColor detect:inRect:] : 496 -> 500
~ +[SCRCPhotoEvaluatorLuminance detect:inRect:] : 568 -> 572
~ -[NSSet(SCRCSetExtras) scrc_deepMutableCopyWithZone:] : 396 -> 392
~ -[NSSet(SCRCSetExtras) containsObjectClass:] : 272 -> 268
~ -[SCRCStackQueue pushArray:] : 252 -> 248
~ _SCRCStringForVariableArray : 344 -> 340
~ -[NSString(SCRCStringExtras) hasMultipleWordsWithLocaleName:ignorePunctuation:] : 376 -> 380
~ -[NSAttributedString(SCRCAttributedStringExtras) scrcIndexSetForAttributes:limit:] : 680 -> 676
~ -[SCRCThread _setIsWaitingForStoppingThread:] : 348 -> 344
~ -[SCRCWebDateTimeParser _handleDuration:] : 848 -> 844
```
