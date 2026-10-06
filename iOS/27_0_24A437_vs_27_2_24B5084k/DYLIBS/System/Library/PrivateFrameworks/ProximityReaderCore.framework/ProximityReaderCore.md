## ProximityReaderCore

> `/System/Library/PrivateFrameworks/ProximityReaderCore.framework/ProximityReaderCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x144fbc` | `0x14aa60` | **`+0x5aa4`** |
| `__AUTH_CONST.__const` | `0x13090` | `0x12ec0` | **`-0x1d0`** |
| `__TEXT.__oslogstring` | `0x3d26` | `0x3eb6` | **`+0x190`** |
| `__TEXT.__cstring` | `0x664c` | `0x677c` | **`+0x130`** |
| `__TEXT.__swift5_reflstr` | `0x3b82` | `0x3c12` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x6198` | `0x613c` | **`-0x5c`** |
| `__AUTH.__data` | `0x3448` | `0x3488` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x6c38` | `0x6c70` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x5a98` | `0x5ad0` | **`+0x38`** |
| `__DATA.__data` | `0x30b0` | `0x30e0` | **`+0x30`** |
| `__TEXT.__const` | `0x1fa88` | `0x1fa58` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x44f0` | `0x4510` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x6cdc` | `0x6cf8` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x17c8` | `0x17e0` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x692a` | `0x6914` | **`-0x16`** |
| `__TEXT.__swift5_types` | `0x95c` | `0x948` | **`-0x14`** |
| `__DATA.__bss` | `0x3be60` | `0x3be70` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xa78` | `0xa88` | **`+0x10`** |
| `__AUTH.__objc_data` | `0x1ae0` | `0x1ae8` | **`+0x8`** |

### Other Changes

```diff

-150.35.0.0.0
+151.2.0.0.0

-  Functions: 9031
-  Symbols:   3513
-  CStrings:  1133
+  Functions: 9038
+  Symbols:   3508
+  CStrings:  1149
Symbols:
+ ___swift_closure_destructor.119Tm
+ ___swift_closure_destructor.138Tm
+ ___swift_closure_destructor.82Tm
+ _symbolic _____Sg 19ProximityReaderCore24EngagementConnectionTypeO
- ___swift_allocate_boxed_opaque_existential_1
- ___swift_closure_destructor.115Tm
- ___swift_closure_destructor.134Tm
- ___swift_closure_destructor.78Tm
- _symbolic _____ 19ProximityReaderCore9AnalyticsV15DiscoveryRegionV
- _symbolic _____ 19ProximityReaderCore9AnalyticsV23DiscoveryContentVersionV
- _symbolic _____ 19ProximityReaderCore9AnalyticsV23DiscoveryScrollQuantileV
- _symbolic _____ 19ProximityReaderCore9AnalyticsV5ValueV
- _symbolic _____ 19ProximityReaderCore9AnalyticsV9PartnerIDV
CStrings:
+ "       contentRegion = %s"
+ "Cached staged raw logo (%ld bytes) for %s"
+ "Devices are not paired (cold), starting pairing with publisher"
+ "MerchantKit-151.2"
+ "NO_NETWORK_ALERT_MESSAGE_CUSTOMER"
+ "NO_NETWORK_ALERT_MESSAGE_CUSTOMER_NO_BRAND"
+ "NO_NETWORK_ALERT_TITLE"
+ "No staged logo data for %s"
+ "Promoted connection, disconnecting %{public}ld loser(s)"
+ "deriveSessionKey: could not parse remoteLinkId to Data"
+ "deriveSessionKey: error deriving key: %@"
+ "engagementForceRelay"
+ "merchantLogoKey"
+ "muteEngagementConnectionSoundsForSoak"
+ "raw:// merchant logo URL has no filename"
+ "recoverableUsingSAF"
+ "retrieveAndStoreLogo: %s"
+ "showNoNetworkDialogForCustomer(brandName:)"
- "        contentRegion = %s"
- "MerchantKit-150.35"
```
