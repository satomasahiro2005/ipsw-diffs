## AppStoreComponents

> `/System/Library/PrivateFrameworks/AppStoreComponents.framework/AppStoreComponents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x90ca4` | `0x90a38` | **`-0x26c`** |
| `__AUTH_CONST.__cfstring` | `0x4cc0` | `0x4d00` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0xf930` | `0xf960` | **`+0x30`** |
| `__TEXT.__cstring` | `0x3951` | `0x3971` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2738` | `0x2758` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xd40` | `0xd48` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x19e0` | `0x19e8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3ec0` | `0x3ec8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x8bb4` | `0x8bbc` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x87c` | `0x880` | **`+0x4`** |

### Other Changes

```diff

-27.0.33.0.0
+27.0.38.0.0

-  Functions: 3813
-  Symbols:   5939
-  CStrings:  971
+  Functions: 3814
+  Symbols:   5943
+  CStrings:  973
Symbols:
+ -[ASCIAPOffer initWithID:titles:subtitles:flags:ageRating:metrics:productIdentifier:productName:appName:appAdamId:appBundleId:subscriptionFamilyId:minimumShortVersionSupportingInAppPurchaseFlow:additionalBuyParams:streamlinedOffer:]
+ -[ASCIAPOffer subscriptionFamilyId]
+ _ASCOfferTitleVariantPurchased
+ _OBJC_IVAR_$_ASCIAPOffer._subscriptionFamilyId
+ _bzero
- -[ASCIAPOffer initWithID:titles:subtitles:flags:ageRating:metrics:productIdentifier:productName:appName:appAdamId:appBundleId:minimumShortVersionSupportingInAppPurchaseFlow:additionalBuyParams:streamlinedOffer:]
CStrings:
+ "ASCOfferIsInAppPurchase"
+ "subscriptionFamilyId"
```
