## WebContentRestrictions

> `/System/Library/PrivateFrameworks/WebContentRestrictions.framework/WebContentRestrictions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfdcc` | `0x10988` | **`+0xbbc`** |
| `__AUTH_CONST.__cfstring` | `0x19e0` | `0x1b80` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x16fc` | `0x180c` | **`+0x110`** |
| `__DATA_CONST.__const` | `0x5a0` | `0x618` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0xa88` | `0xae0` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0xfa0` | `0xfe0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x4d0` | `0x4f8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x389` | `0x3a9` | **`+0x20`** |
| `__DATA.__bss` | `0x690` | `0x6a0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x1e0` | **`+0x8`** |

### Other Changes

```diff

-70.0.0.0.0
+73.0.0.0.2

-  Functions: 452
-  Symbols:   1179
-  CStrings:  287
+  Functions: 461
+  Symbols:   1192
+  CStrings:  301
Symbols:
+ +[WCRBrowserEngineClient _blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:]
+ +[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:ageVerificationText:generateBlockPage:withCompletion:onCompletionQueue:]
+ +[WCRBrowserEngineClient _familyControlsOverrideCommandForURL:state:]
+ +[WCRBrowserEngineClient _isSensitiveURL:usingBloomFilter:]
+ +[WCRBrowserEngineClient shieldStateForURL:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:language:]
+ -[WCRBloomFilter isSensitive:]
+ -[WCRBrowserEngineClient _presentAskToBrowseMenuForURL:state:presentingView:presentingViewController:completion:]
+ -[WCRBrowserEngineClient allowURLWithFamilyControls:referrerURL:withCompletion:]
+ -[WCRBrowserEngineClient evaluateNonSensitiveURL:withCompletion:]
+ -[WCRBrowserEngineClient evaluateNonSensitiveURL:withCompletion:onCompletionQueue:]
+ -[WCRBrowserEngineClient userRequestedDeviceApproval:isSensitive:]
+ -[WCRRemoteAskToViewController configureWithURL:symbol:title:subtitle:displayURL:showBadge:shieldType:isSensitive:overridePolicy:iframe:]
+ -[WCRRemoteAskToViewController userRequestedDeviceApproval:isSensitive:]
+ -[WCRRemoteDeviceApprovalViewController setURL:isSensitive:]
+ -[WCRShieldState initWithSymbol:title:subtitle:displayURL:showBadge:buttons:shieldType:overridePolicy:iframe:isSensitive:]
+ -[WCRShieldState isSensitive]
+ GCC_except_table49
+ GCC_except_table55
+ GCC_except_table7
+ GCC_except_table84
+ GCC_except_table86
+ GCC_except_table88
+ _OBJC_CLASS_$_NSURLQueryItem
+ _OBJC_IVAR_$_WCRShieldState._isSensitive
+ ___113-[WCRBrowserEngineClient _presentAskToBrowseMenuForURL:state:presentingView:presentingViewController:completion:]_block_invoke
+ ___113-[WCRBrowserEngineClient _presentAskToBrowseMenuForURL:state:presentingView:presentingViewController:completion:]_block_invoke_2
+ ___113-[WCRBrowserEngineClient _presentAskToBrowseMenuForURL:state:presentingView:presentingViewController:completion:]_block_invoke_3
+ ___118+[WCRBrowserEngineClient shieldStateForURL:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:language:]_block_invoke
+ ___119+[WCRBrowserEngineClient _blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:]_block_invoke
+ ___305+[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:ageVerificationText:generateBlockPage:withCompletion:onCompletionQueue:]_block_invoke
+ ___305+[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:ageVerificationText:generateBlockPage:withCompletion:onCompletionQueue:]_block_invoke_2
+ ___305+[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:ageVerificationText:generateBlockPage:withCompletion:onCompletionQueue:]_block_invoke_3
+ ___59-[WCRBrowserEngineClient _fetchAndCacheAgeVerificationText]_block_invoke_3
+ ___66-[WCRBrowserEngineClient userRequestedDeviceApproval:isSensitive:]_block_invoke
+ ___66-[WCRBrowserEngineClient userRequestedDeviceApproval:isSensitive:]_block_invoke_2
+ ___83-[WCRBrowserEngineClient evaluateNonSensitiveURL:withCompletion:onCompletionQueue:]_block_invoke
+ ___83-[WCRBrowserEngineClient evaluateNonSensitiveURL:withCompletion:onCompletionQueue:]_block_invoke_2
+ ___block_descriptor_105_e8_32s40s48s56s64s72s80bs_e8_v16?0Q8ls32l8s40l8s48l8s56l8s64l8s80l8s72l8
+ ___block_descriptor_40_e8_32bs_e19_v20?0B8"NSData"12ls32l8
+ ___block_descriptor_41_e28_"NSString"16?0"NSString"8l
+ ___block_descriptor_57_e8_32s40s48s_e45_v24?0"_UIRemoteViewController"8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_57_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s56l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e8_v12?0B8ls32l8s40l8s48l8s56l8s64l8
+ __fetchAndCacheAgeVerificationText.loadOnce
- +[WCRBrowserEngineClient _blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:ageVerificationText:]
- +[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:ageVerificationText:withCompletion:onCompletionQueue:]
- +[WCRBrowserEngineClient allowURLWithFamilyControls:referrerURL:withCompletion:]
- +[WCRBrowserEngineClient shieldStateForURL:shieldType:overridePolicy:iframe:ageVerificationText:language:]
- -[WCRBrowserEngineClient askToBrowseURL]
- -[WCRBrowserEngineClient setAskToBrowseURL:]
- -[WCRBrowserEngineClient userRequestedDeviceApproval]
- -[WCRRemoteAskToViewController configureWithURL:symbol:title:subtitle:displayURL:showBadge:shieldType:overridePolicy:iframe:]
- -[WCRRemoteAskToViewController userRequestedDeviceApproval]
- -[WCRRemoteDeviceApprovalViewController setURL:]
- -[WCRShieldState initWithSymbol:title:subtitle:displayURL:showBadge:buttons:shieldType:overridePolicy:iframe:]
- GCC_except_table44
- GCC_except_table50
- GCC_except_table6
- GCC_except_table77
- GCC_except_table79
- GCC_except_table81
- _OBJC_IVAR_$_WCRBrowserEngineClient._askToBrowseURL
- ___106+[WCRBrowserEngineClient shieldStateForURL:shieldType:overridePolicy:iframe:ageVerificationText:language:]_block_invoke
- ___107+[WCRBrowserEngineClient _blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:ageVerificationText:]_block_invoke
- ___287+[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:ageVerificationText:withCompletion:onCompletionQueue:]_block_invoke
- ___287+[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:ageVerificationText:withCompletion:onCompletionQueue:]_block_invoke_2
- ___287+[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:ageVerificationText:withCompletion:onCompletionQueue:]_block_invoke_3
- ___53-[WCRBrowserEngineClient userRequestedDeviceApproval]_block_invoke
- ___53-[WCRBrowserEngineClient userRequestedDeviceApproval]_block_invoke_2
- ___85-[WCRBrowserEngineClient askToBrowseContextMenu:presentingView:state:withCompletion:]_block_invoke
- ___85-[WCRBrowserEngineClient askToBrowseContextMenu:presentingView:state:withCompletion:]_block_invoke_2
- ___85-[WCRBrowserEngineClient askToBrowseContextMenu:presentingView:state:withCompletion:]_block_invoke_3
- ___block_descriptor_40_e28_"NSString"16?0"NSString"8l
- ___block_descriptor_48_e8_32s40s_e45_v24?0"_UIRemoteViewController"8"NSError"16ls32l8s40l8
- ___block_descriptor_64_e8_32s40s48s56bs_e8_v12?0B8ls32l8s40l8s48l8s56l8
- ___block_descriptor_96_e8_32s40s48s56s64s72bs_e8_v16?0Q8ls32l8s40l8s48l8s56l8s72l8s64l8
CStrings:
+ "%@/0/%@/%@"
+ "/System/Library/PrivateFrameworks/FamilyCircle.framework"
+ "0"
+ "AV: Failed to load FamilyCircle.framework: %@"
+ "AV: Loaded FamilyCircle.framework"
+ "WCRAuthenticationSites-2026-07-19.plist"
+ "displayURL"
+ "http://0.0.0.0/webfilter.local"
+ "isSensitive"
+ "showBadge"
+ "subtitle"
+ "symbol"
+ "title"
+ "url"
+ "v20@?0B8@\"NSData\"12"
+ "x-apple-content-filter://unblock?context=%@&shield=%@&isSensitive=%@"
- "WCRAuthenticationSites-2026-06-03.plist"
- "x-apple-content-filter://unblock?context=%@&shield=%@"
```
