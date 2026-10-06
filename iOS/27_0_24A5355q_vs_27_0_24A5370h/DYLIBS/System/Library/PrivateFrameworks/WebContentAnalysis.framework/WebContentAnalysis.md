## WebContentAnalysis

> `/System/Library/PrivateFrameworks/WebContentAnalysis.framework/WebContentAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe61c` | `0xe5c8` | **`-0x54`** |

### Other Changes

```text
Functions:
~ +[NSString(WFExtension) WF_stringFromArray:] : 284 -> 280
~ +[WFContentSniffer(PrivateMethods) isOctetStream:] : 104 -> 112
~ -[WFImgArrayCache initWithArray:] : 560 -> 556
~ -[WFLSMResult bestMatchingCategory] : 300 -> 296
~ -[WFLSMScoreNormalizedMap initWithMap:] : 684 -> 692
~ -[WFLSMScoreNormalizedMap evaluate:] : 304 -> 296
~ __NSHTMLEncoding : 348 -> 344
~ -[WFWebPageDecorator linkTitlesText] : 296 -> 292
~ -[WFWebPageToFilterText selfRestricted] : 796 -> 792
~ +[WFWhitelistUserPreferences _arrayByConvertingLinesInStringsAtPath:] : 396 -> 392
~ +[WFWhitelistUserPreferences _isURLMetasite:] : 368 -> 364
~ -[WFWhitelistUserPreferences initWithPreferences:] : 960 -> 948
~ -[WFSystemContentWhitelist initWithWhitelistURL:] : 580 -> 576
~ -[WFSystemContentWhitelist isURLWhitelisted:] : 252 -> 248
~ -[WFUserSettings contentFilterOverriddenWhiteListedSitesBufferWithAdditionalURLStrings:] : 432 -> 424
~ -[WFUserSettings contentFilterOverriddenBlackListedSitesBuffer] : 280 -> 276
~ -[WFUserSettings whiteListedSitesBuffer] : 452 -> 448
~ +[WFUserSettings _arrayByConvertingLinesInStringsAtPath:] : 396 -> 392
~ -[WFPINEntryViewController presentViewControllerAnimated:completion:] : 864 -> 852
~ -[WFPINEntryViewController hasUIWebViewSubView:] : 288 -> 284
~ -[WFPINEntryViewController viewDidDisappear:] : 320 -> 316
```
