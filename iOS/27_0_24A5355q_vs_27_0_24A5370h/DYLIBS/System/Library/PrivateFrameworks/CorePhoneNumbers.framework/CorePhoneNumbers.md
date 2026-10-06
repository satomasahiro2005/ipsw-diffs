## CorePhoneNumbers

> `/System/Library/PrivateFrameworks/CorePhoneNumbers.framework/CorePhoneNumbers`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa448` | `0xa414` | **`-0x34`** |
| `__TEXT.__unwind_info` | `0x2c8` | `0x2d0` | **`+0x8`** |

### Other Changes

```diff

-139.100.27.2.9
+143.100.11.2.1
Functions:
~ _CFPhoneNumberStringIsEncodingASCII : 404 -> 396
~ __PNCreateStringByStrippingFormattingAndNotVisiblyAllowable : 332 -> 336
~ _UIPhoneFormatCountryGetInfoIndex : 472 -> 504
~ __FindFormatEntryForDigitsInCountry : 1696 -> 1628
~ __FindNationalAccessCodeForDigitsInCountry : 232 -> 240
~ ___DecomposePhoneNumberWithCountryIndex : 932 -> 948
~ _InlineBufferHasPatternAtOffset : 520 -> 496
~ ___PNCopyBestGuessNumberForCountry : 1108 -> 1120
~ __GetCountryOffsetFromDialingCode : 692 -> 672
~ __NumberRangeWithoutVerticalServiceCode : 1216 -> 1256
~ ___InternationalPrefixForDigitsInCountry : 792 -> 800
~ ___CreateFormattedNumberForDigitsWithCountryIndex : 3012 -> 3020
~ __CreateFormattedStringForDigitsInRange : 2508 -> 2384
~ __UIPhoneFormatEntryReplacementCountryCodeRange : 156 -> 164
~ __PNCopyCountryCodeForInternationalCode : 152 -> 160
~ __PNCopyFullyQualifiedNumberForCountryInternal : 1328 -> 1352
~ __PNCopySampleNumberForCountry : 416 -> 432
~ __PNCopyInternationalPrefix : 260 -> 264
~ _UIPhoneFormatFileGetCountryHeader : 72 -> 64
~ __PNCopyInternationalDirectDialingPrefixForCountry : 232 -> 236
~ __PNCopyNationalDirectDialingPrefixForCountry : 184 -> 188
~ __PNCopyFormattedNumberForDigitsWithCountryByRemovingAtIndex : 384 -> 380
~ __PNCountNonPhoneFormattingCharactersPrecedingIndex : 236 -> 252
~ __PNIndexCountingNonPhoneFormattingCharactersFromStart : 280 -> 296
~ sub_25526b754 -> sub_25660d738 : 256 -> 252
~ sub_25526b860 -> sub_25660d840 : 28 -> 24
~ sub_25526b920 -> sub_25660d8fc : 44 -> 32
~ sub_25526bf78 -> sub_25660df48 : 24 -> 20
```
