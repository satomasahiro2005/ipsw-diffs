## FinanceDaemon

> `/System/Library/PrivateFrameworks/FinanceDaemon.framework/FinanceDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a3720` | `0x4a459c` | **`+0xe7c`** |
| `__DATA.__bss` | `0x12d60` | `0x13060` | **`+0x300`** |
| `__AUTH_CONST.__const` | `0x10710` | `0x10950` | **`+0x240`** |
| `__TEXT.__const` | `0x17f72` | `0x18192` | **`+0x220`** |
| `__TEXT.__cstring` | `0xcd45` | `0xce25` | **`+0xe0`** |
| `__TEXT.__swift5_fieldmd` | `0x84c8` | `0x8574` | **`+0xac`** |
| `__TEXT.__constg_swiftt` | `0x8278` | `0x82e8` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0xa644` | `0xa694` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x149a2` | `0x149e2` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x268e8` | `0x26920` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x9644` | `0x9672` | **`+0x2e`** |
| `__TEXT.__unwind_info` | `0xc408` | `0xc430` | **`+0x28`** |
| `__DATA.__data` | `0x4748` | `0x4768` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0xf18` | `0xf30` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xd88` | `0xda0` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x255c` | `0x256c` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x8b4` | `0x8c4` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x6a80` | `0x6a88` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f90` | `0x1f88` | **`-0x8`** |

### Other Changes

```diff

-376.1.5.0.0
+376.1.6.0.0

-  Functions: 12317
-  Symbols:   3956
-  CStrings:  2536
+  Functions: 12335
+  Symbols:   3965
+  CStrings:  2541
Symbols:
+ ___swift_get_extra_inhabitant_index.46Tm
+ ___swift_store_extra_inhabitant_index.47Tm
+ _associated conformance 13FinanceDaemon36ExtractedOrderAnalyticsEventsBuilderV19MailBannerTapResultOSHAASQ
+ _symbolic _____ 13FinanceDaemon36ExtractedOrderAnalyticsEventsBuilderV0cD21MailBannerTappedEventV
+ _symbolic _____ 13FinanceDaemon36ExtractedOrderAnalyticsEventsBuilderV0cD21MailBannerViewedEventV
+ _symbolic _____ 13FinanceDaemon36ExtractedOrderAnalyticsEventsBuilderV0cD24MerchantDomainCountEventV
+ _symbolic _____ 13FinanceDaemon36ExtractedOrderAnalyticsEventsBuilderV19MailBannerTapResultO
+ _symbolic ___________t 13FinanceDaemon36ExtractedOrderAnalyticsEventsBuilderV19MailBannerTapResultO AA0D7EffectsV
+ _type_layout_string 13FinanceDaemon36ExtractedOrderAnalyticsEventsBuilderV0cD21MailBannerTappedEventV
+ _type_layout_string 13FinanceDaemon36ExtractedOrderAnalyticsEventsBuilderV0cD21MailBannerViewedEventV
+ _type_layout_string 13FinanceDaemon36ExtractedOrderAnalyticsEventsBuilderV0cD24MerchantDomainCountEventV
- ___swift_get_extra_inhabitant_index.27Tm
- ___swift_store_extra_inhabitant_index.28Tm
CStrings:
+ "Unable to count extracted order merchant domains: %@"
+ "com.apple.finance.extracted.orders.mail.banner.tapped"
+ "com.apple.finance.extracted.orders.mail.banner.viewed"
+ "com.apple.finance.extracted.orders.merchant.domains.count"
+ "merchantDomainCount"
```
