## AccessibilityAudit

> `/System/Library/PrivateFrameworks/AccessibilityAudit.framework/AccessibilityAudit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22470` | `0x2236c` | **`-0x104`** |

### Other Changes

```diff

-191.0.0.0.0
+192.1.0.0.0
Functions:
~ -[AXAuditImageDetectionManager detectedTextResultsForImageData:] : 608 -> 604
~ -[AXAuditObjectTransportManager transportDictionaryForObject:] : 1648 -> 1632
~ -[AXAuditObjectTransportManager objectForTransportDictionary:expectedClass:] : 1372 -> 1364
~ -[AXAuditObjectTransportManager transportArrayForArray:] : 384 -> 380
~ -[AXAuditObjectTransportManager arrayForTransportArray:expectedClass:] : 424 -> 420
~ -[AXAuditObjectTransportManager _transportInfoEncodeOnlyForObject:] : 348 -> 344
~ -[AXAuditObjectTransportManager _transportInfoForObject:] : 364 -> 360
~ -[AXAuditObjectTransportManager registerTransportInfoMasquerade:encodeOnly:] : 584 -> 580
~ -[AXAuditObjectTransportManager validateSupportedConnectionSecureTransport:] : 1108 -> 1096
~ ___60-[AXAuditObjectTransportInfoPropertyBased _initializeBlocks]_block_invoke_2 : 432 -> 428
~ ___60-[AXAuditObjectTransportInfoPropertyBased _initializeBlocks]_block_invoke_3 : 412 -> 408
~ -[AXAuditInspectorFocus setInspectorSections:] : 464 -> 460
~ -[AXAuditInspectorSection displaysHierarchy] : 300 -> 296
~ -[AXAuditInspectorSection hasActions] : 300 -> 296
~ -[AXAuditInspectorSection addAttribute:performsAction:humanReadable:settable:valueType:isInternal:] : 520 -> 516
~ -[AXAuditer _initializeAuditCategories] : 344 -> 340
~ -[AXAuditer _allCategoriesDescription] : 436 -> 432
~ -[AXAuditer _auditCategoryForClass:] : 312 -> 308
~ -[AXAuditer allSupportedAuditTypes] : 340 -> 336
~ -[AXAuditer startWithAuditTypes:] : 840 -> 836
~ -[AXAuditer runCategories:] : 764 -> 760
~ -[AXAuditer _runCategories:] : 544 -> 532
~ -[AXAuditDeduplicatorModels packIssueRects:] : 456 -> 452
~ -[AXAuditResult initWithAXAuditCategoryResults:] : 600 -> 596
~ -[AXAuditResult _generateIssueToImageMapping] : 1088 -> 1084
~ -[XRCInspectorProperty _spacedStringFromCamelCase:] : 688 -> 684
~ -[AXAuditPluginManager loadAuditBundles] : 388 -> 384
~ -[AXAuditDeviceSettingsManager cacheDeviceSettingsValues] : 356 -> 352
~ -[AXAuditDeviceSettingsManager restoreDeviceSettingsValues] : 296 -> 292
~ -[AXAuditDeviceSettingsManager updateCurrentValueForAllSettingsAndPostNotificationIfChanged:] : 264 -> 260
~ -[AXAuditDeviceSettingsManager settingForIdentifier:] : 340 -> 336
~ -[AXAuditDeviceSettingsManager resetToDefaultAccessibilitySettings] : 304 -> 300
~ -[AXAuditContrastDetectionManager contrastResultForInput:] : 1004 -> 1000
~ -[AXAuditContrastDetectionManager _topColorsForColors:] : 512 -> 508
~ -[AXAuditContrastDetectionManager pixelColorInImagePixelData:atX:atY:width:] : 204 -> 212
~ -[AXAuditNode _printDescendantsWithLevel:] : 312 -> 308
~ -[AXAuditCategory _availableCasesDescription] : 388 -> 384
~ -[AXAuditCategory run] : 436 -> 432
~ -[AXAuditCategory stop] : 572 -> 568
~ -[AXAuditReportGenerator textDescriptionForIssues:] : 620 -> 628
~ -[AXAuditReportGenerator _jsonDictionaryForIssue:screenName:] : 1000 -> 996
~ -[AXAuditReportGenerator _anyAuditIssueFromResults:] : 456 -> 452
~ -[AXAuditReportGenerator _jsonArrayForIssues:screenName:] : 356 -> 352
~ -[AXAuditReportGenerator _jsonDictionaryForScreen:issuesOnScreen:] : 576 -> 572
~ -[AXAuditIssueDescriptionManager suggestionDescriptionForAuditIssue:] : 812 -> 808
~ -[AXAuditCategoryResult issueCount] : 284 -> 280
~ -[AXAuditCategoryResult allIssues] : 460 -> 456
~ -[AXAuditCategoryResult issueSummaryStrings] : 488 -> 484
~ -[AXAuditCategoryResult description] : 372 -> 368
~ ___49+[AXAuditDocumentationManager appleDocViewerURLs]_block_invoke : 396 -> 392
~ -[FeatureHashGroup setScreenGroupID:] : 300 -> 296
~ -[AXAuditDeduplicatorHeuristics deduplicateIssues:forFeatureHashGroup:] : 552 -> 548
~ -[AXAuditAssetManager downloadAssetsIfNecessary] : 648 -> 640
~ -[AXAuditAssetManager assetController:didFinishRefreshingAssets:wasSuccessful:error:] : 928 -> 924
~ ___49-[AXAuditService auditer:didCompleteWithResults:]_block_invoke : 588 -> 584
~ -[AXAuditService deviceHighlightIssues:] : 432 -> 428
~ -[AXAuditAutomationSupport _runAudit] : 860 -> 852
~ -[AXAuditAutomationSupport _informDelegateOfResults:error:] : 604 -> 600
~ _updateTimestampOfResults : 568 -> 564
~ -[AXAuditAutomationSupport _sendResultsToDelegate:] : 948 -> 944
~ -[AXAuditAutomationSupport _registerForAXNotifications:] : 368 -> 364
```
