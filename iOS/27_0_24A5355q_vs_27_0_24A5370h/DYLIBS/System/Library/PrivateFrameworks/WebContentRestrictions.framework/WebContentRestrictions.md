## WebContentRestrictions

> `/System/Library/PrivateFrameworks/WebContentRestrictions.framework/WebContentRestrictions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeaf4` | `0xf4d0` | **`+0x9dc`** |
| `__TEXT.__cstring` | `0x152c` | `0x171c` | **`+0x1f0`** |
| `__AUTH_CONST.__cfstring` | `0x1800` | `0x1940` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x4b0` | `0x550` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0xf0c` | `0xf58` | **`+0x4c`** |
| `__DATA_CONST.__objc_selrefs` | `0xa18` | `0xa60` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x1cb8` | `0x1cf0` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x220` | `0x250` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x773` | `0x743` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x468` | `0x490` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x5a8` | `0x5b0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xe0` | `0xe4` | **`+0x4`** |

### Other Changes

```diff

-63.0.0.0.0
+64.0.0.0.0

-  Functions: 417
-  Symbols:   1132
-  CStrings:  266
+  Functions: 428
+  Symbols:   1151
+  CStrings:  278
Symbols:
+ +[WCRBrowserEngineClient _blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:ageVerificationText:]
+ +[WCRBrowserEngineClient _evaluateURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:overridePolicy:ageVerificationText:withCompletion:onCompletionQueue:]
+ +[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:ageVerificationText:withCompletion:onCompletionQueue:]
+ +[WCRBrowserEngineClient shieldStateForURL:shieldType:overridePolicy:iframe:ageVerificationText:language:]
+ -[WCRBrowserEngineClient _fetchAndCacheAgeVerificationText]
+ -[WCRBrowserEngineClient _requestOpenScreenTimeSettingsForAgeVerificationUseLegacyURL:completion:]
+ -[WCRBrowserEngineClient cachedAgeVerificationText]
+ -[WCRBrowserEngineClient setCachedAgeVerificationText:]
+ -[WCRRemotePINEntryViewController openScreenTimeSettingsUseLegacyURL:withCompletion:]
+ GCC_except_table43
+ GCC_except_table49
+ GCC_except_table5
+ GCC_except_table6
+ GCC_except_table74
+ GCC_except_table76
+ GCC_except_table78
+ _NSClassFromString
+ _OBJC_IVAR_$_WCRBrowserEngineClient._cachedAgeVerificationText
+ ___106+[WCRBrowserEngineClient shieldStateForURL:shieldType:overridePolicy:iframe:ageVerificationText:language:]_block_invoke
+ ___107+[WCRBrowserEngineClient _blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:ageVerificationText:]_block_invoke
+ ___287+[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:ageVerificationText:withCompletion:onCompletionQueue:]_block_invoke
+ ___287+[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:ageVerificationText:withCompletion:onCompletionQueue:]_block_invoke_2
+ ___287+[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:ageVerificationText:withCompletion:onCompletionQueue:]_block_invoke_3
+ ___50-[WCRBrowserEngineClient allowURL:withCompletion:]_block_invoke
+ ___50-[WCRBrowserEngineClient allowURL:withCompletion:]_block_invoke_2
+ ___59-[WCRBrowserEngineClient _fetchAndCacheAgeVerificationText]_block_invoke
+ ___59-[WCRBrowserEngineClient _fetchAndCacheAgeVerificationText]_block_invoke_2
+ ___98-[WCRBrowserEngineClient _requestOpenScreenTimeSettingsForAgeVerificationUseLegacyURL:completion:]_block_invoke
+ ___98-[WCRBrowserEngineClient _requestOpenScreenTimeSettingsForAgeVerificationUseLegacyURL:completion:]_block_invoke_2
+ ___block_descriptor_40_e8_32w_e34_v24?0"NSDictionary"8"NSError"16lw32l8
+ ___block_descriptor_48_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40w_e30_v24?0"NSNumber"8"NSError"16ls32l8w40l8
+ ___block_descriptor_49_e8_32s40bs_e45_v24?0"_UIRemoteViewController"8"NSError"16ls40l8s32l8
+ ___block_descriptor_96_e8_32s40s48s56s64s72bs_e8_v16?0Q8ls32l8s40l8s48l8s56l8s72l8s64l8
- +[WCRBrowserEngineClient _blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:]
- +[WCRBrowserEngineClient _evaluateURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:overridePolicy:withCompletion:onCompletionQueue:]
- +[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:withCompletion:onCompletionQueue:]
- +[WCRBrowserEngineClient shieldStateForURL:shieldType:overridePolicy:iframe:language:]
- GCC_except_table40
- GCC_except_table46
- GCC_except_table66
- GCC_except_table68
- GCC_except_table70
- ___267+[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:withCompletion:onCompletionQueue:]_block_invoke
- ___267+[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:withCompletion:onCompletionQueue:]_block_invoke_2
- ___267+[WCRBrowserEngineClient _evaluateURL:mainDocumentURL:inMode:usingBloomFilter:userSettings:language:allowList:appleAllowList:denyList:allowedWebsitesOnlyList:macOSExemptURLList:authenticationSites:allowTransitiveTrust:overridePolicy:withCompletion:onCompletionQueue:]_block_invoke_3
- ___86+[WCRBrowserEngineClient shieldStateForURL:shieldType:overridePolicy:iframe:language:]_block_invoke
- ___87+[WCRBrowserEngineClient _blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:]_block_invoke
- ___block_descriptor_88_e8_32s40s48s56s64bs_e8_v16?0Q8ls32l8s40l8s48l8s64l8s56l8
CStrings:
+ "AV: FAAgeRangeController not available in process"
+ "AV: No DSID found - Error: %@"
+ "AV: ageAssuranceStringsMap has unexpected type: %@"
+ "AV: getAgeVerificationInfo error: %@"
+ "Age verification: failed to connect to WCRUI: %@"
+ "Change Restriction"
+ "FAAgeRangeController"
+ "This device is required to restrict adult content for anyone who hasn't confirmed they are an adult."
+ "WCRAppleAllowList-2026-03-31.plist"
+ "WCRFilter-2026-03-31.plist"
+ "ageAssuranceStringsMap"
+ "overridePolicy from DC: unverifiedAdultLegacyScreenTime"
+ "overridePolicy from DC: unverifiedAdultScreenTime"
+ "screenTimeWebContentFilterAdultVerificationReason"
+ "v24@?0@\"NSDictionary\"8@\"NSError\"16"
+ "v24@?0@\"NSNumber\"8@\"NSError\"16"
- "WCRAppleAllowList-2026-02-06.plist"
- "WCRFilter-2026-02-06.plist"
- "overridePolicy from DC: unverifiedAdultLegacyScreenTime. Using unset for now."
- "overridePolicy from DC: unverifiedAdultScreenTime. Using unset for now."
```
