## WebContentRestrictions

> `/System/Library/PrivateFrameworks/WebContentRestrictions.framework/WebContentRestrictions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf4d0` | `0xf8fc` | **`+0x42c`** |
| `__TEXT.__ustring` | `0xf2` | `0x1bc` | **`+0xca`** |
| `__TEXT.__oslogstring` | `0x743` | `0x7f3` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x1940` | `0x19e0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x490` | `0x4b8` | **`+0x28`** |
| `__TEXT.__const` | `0x590` | `0x5b0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x171c` | `0x16fc` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x1d8` | **`-0x8`** |

### Other Changes

```diff

-64.0.0.0.0
+67.0.0.0.0

-  Functions: 428
-  Symbols:   1151
-  CStrings:  278
+  Functions: 443
+  Symbols:   1169
+  CStrings:  287
Symbols:
+ _$s22WebContentRestrictions11BloomFilterC11descriptionSSvgTj
+ _$s22WebContentRestrictions11BloomFilterC14estimatedCountSivgTj
+ _$s22WebContentRestrictions11BloomFilterC21expectedNumberOfItems22falsePositiveToleranceACSi_SdtKcfCTj
+ _$s22WebContentRestrictions11BloomFilterC24falsePositiveProbabilitySdvgTj
+ _$s22WebContentRestrictions11BloomFilterC4fromACs7Decoder_p_tKcfCTj
+ _$s22WebContentRestrictions11BloomFilterC6encode2toys7Encoder_p_tKFTj
+ _$s22WebContentRestrictions11BloomFilterC6insertyy10Foundation4DataVKFTj
+ _$s22WebContentRestrictions11BloomFilterC8containsySb10Foundation4DataVFTj
+ _$s22WebContentRestrictions11BloomFilterCMo
+ _$s22WebContentRestrictions11BloomFilterCMu
+ _$s22WebContentRestrictions15BloomFilterShimC4pathACSgSS_tcfCTj
+ _$s22WebContentRestrictions15BloomFilterShimC8containsySbSSFTj
+ _$s22WebContentRestrictions15BloomFilterShimCMo
+ _$s22WebContentRestrictions15BloomFilterShimCMu
+ _$s22WebContentRestrictions16MembershipFilterP21expectedNumberOfItems22falsePositiveTolerancexSi_SdtKcfCTj
+ _$s22WebContentRestrictions16MembershipFilterP21expectedNumberOfItems22falsePositiveTolerancexSi_SdtKcfCTq
+ _$s22WebContentRestrictions16MembershipFilterP21predictedNumberOfBits08expectedgH5Items22falsePositiveToleranceS2i_SdtKFZTj
+ _$s22WebContentRestrictions16MembershipFilterP21predictedNumberOfBits08expectedgH5Items22falsePositiveToleranceS2i_SdtKFZTq
+ _$s22WebContentRestrictions16MembershipFilterP6insertyy10Foundation4DataVKFTj
+ _$s22WebContentRestrictions16MembershipFilterP6insertyy10Foundation4DataVKFTq
+ _$s22WebContentRestrictions16MembershipFilterP8containsySb10Foundation4DataVFTj
+ _$s22WebContentRestrictions16MembershipFilterP8containsySb10Foundation4DataVFTq
+ _swift_isaMask
+ _swift_lookUpClassMethod
- _$s22WebContentRestrictions15BloomFilterShimC6filterAA010MembershipE0_pSgvpfi
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- ___50-[WCRBrowserEngineClient allowURL:withCompletion:]_block_invoke
- ___50-[WCRBrowserEngineClient allowURL:withCompletion:]_block_invoke_2
- _swift_willThrowTypedImpl
CStrings:
+ "Age Verification (Legacy) requested. error: %@"
+ "Age Verification requested. error: %@"
+ "This device is required to restrict adult content for anyone who hasn’t confirmed they are an adult."
+ "WCRAppleAllowList-2026-06-16.plist"
+ "WCRAuthenticationSites-2026-06-03.plist"
+ "WCRFilter-2026-06-16.plist"
+ "WILL_SHOW_RESTRICTED_URL"
+ "Your parent or guardian has blocked:"
+ "ageVerification"
+ "ageVerificationLegacy"
+ "askToBrowseURL: Age Verification (Legacy) Needed"
+ "askToBrowseURL: Age Verification Needed"
+ "no-url"
+ "show-url"
- "This device is required to restrict adult content for anyone who hasn't confirmed they are an adult."
- "WCRAppleAllowList-2026-03-31.plist"
- "WCRAuthenticationSites-2026-05-01.plist"
- "WCRFilter-2026-03-31.plist"
- "Your parent or guardian has blocked this website."
```
