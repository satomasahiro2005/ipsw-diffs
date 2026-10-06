## AccessibilityPlatformTranslation

> `/System/Library/PrivateFrameworks/AccessibilityPlatformTranslation.framework/AccessibilityPlatformTranslation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15484` | `0x15408` | **`-0x7c`** |

### Other Changes

```diff

-576.1.0.0.0
+579.1.0.0.0
Functions:
~ -[AXPTranslator_iOS _addCacheElement:translationObject:] : 460 -> 456
~ -[AXPTranslator_iOS _removeCacheEntriesForElement:] : 468 -> 464
~ ___52-[AXPTranslator_iOS attributedStringConversionBlock]_block_invoke : 2348 -> 2344
~ -[AXPTranslator_iOS processMultipleAttributeRequest:removeEmptyValue:] : 1456 -> 1448
~ -[AXPTranslator_iOS _postProcessAttributeRequest:iosAttribute:axpAttribute:result:error:] : 1360 -> 1356
~ __AXPConvertOutgoingValueWithDesiredType : 1628 -> 1624
~ -[AXPTranslator_iOS _processLinkedUIElementsAttributeRequest:error:] : 588 -> 584
~ -[AXPTranslator_iOS _processAuditIssuesAttributeRequest:parameter:error:] : 716 -> 712
~ -[AXPTranslator_iOS processSupportedActions:] : 516 -> 512
~ -[AXPTranslator_iOS processSupportsAttributes:] : 612 -> 608
~ -[AXPTranslator_iOS axTreeDumpGenerateNextSetOfElementAttrsOnMainThread] : 2348 -> 2344
~ ___59-[AXPTranslator_iOS _postProcessResultDataForSecureCoding:]_block_invoke_3 : 280 -> 276
~ ___59-[AXPTranslator_iOS _postProcessResultDataForSecureCoding:]_block_invoke_4 : 280 -> 276
~ -[AXPTranslator_iOS _frontmostAppChildrenForXCTest] : 448 -> 444
~ -[AXPRemoteCacheManager axInitialTreeDumpGeneratedOnBackgroundThreadCallback:success:] : 1092 -> 1088
~ -[AXPRemoteCacheManager _sendTextRelatedAttributesForTranslation:] : 696 -> 692
~ _AXPConvertValue : 800 -> 792
~ -[AXPTranslator _checkCacheForFrontmostAppResponseWithBridgeDelegateToken:] : 360 -> 356
~ -[AXPTranslator handleUpdatedAXTree:] : 1176 -> 1168
~ -[AXPTranslator treeDumpApplicationOrientationForBridgeDelegateToken:] : 340 -> 336
~ -[AXPTranslator _handleFocusedUIElementChangedForInitialDump:] : 684 -> 680
~ -[AXPTranslator _resetBridgeTokensForResponse:bridgeDelegateToken:] : 584 -> 576
~ -[AXPTranslator checkTreeDumpCacheResponses:forMatchingResponse:withBridgeTokenDelegate:] : 512 -> 508
~ -[AXPTranslator treeDumpCacheResultDataForAttributeTypeRequest:] : 1128 -> 1124
~ -[AXPTranslator treeDumpCacheResultDataForCanSetAttributeTypeRequest:] : 532 -> 528
~ -[AXPTranslator treeDumpCacheResultDataForSupportedActionsTypeRequest:] : 840 -> 836
~ -[AXPTranslator treeDumpCacheResultDataForSupportsAttributesTypeRequest:] : 832 -> 828
```
