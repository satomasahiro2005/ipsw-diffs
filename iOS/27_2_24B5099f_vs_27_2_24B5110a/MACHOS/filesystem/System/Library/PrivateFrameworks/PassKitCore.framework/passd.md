## passd

> `/System/Library/PrivateFrameworks/PassKitCore.framework/passd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__gcc_except_tab` | `0x95a8` | `0x91b8` | **`-0x3f0`** |
| `__TEXT.__text` | `0x6292c8` | `0x628ef8` | **`-0x3d0`** |
| `__TEXT.__auth_stubs` | `0x7ca0` | `0x7c70` | **`-0x30`** |
| `__TEXT.__objc_methname` | `0xa96ec` | `0xa96bc` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x333b8` | `0x33390` | **`-0x28`** |
| `__DATA_CONST.__got` | `0x4a88` | `0x4a60` | **`-0x28`** |
| `__TEXT.__objc_stubs` | `0x78940` | `0x78920` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x3e60` | `0x3e48` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x14958` | `0x14940` | **`-0x18`** |
| `__TEXT.__cstring` | `0x69ae4` | `0x69ad4` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x21048` | `0x21040` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1696.2.8.1.0
+1696.2.9.0.0

-  Functions: 29998
-  Symbols:   4452
-  CStrings:  36613
+  Functions: 29997
+  Symbols:   4444
+  CStrings:  36611
Symbols:
- _PKPendingCampaignAttributionCampaignIdentifierKey
- _PKPendingCampaignAttributionForPassUniqueIdentifier
- _PKPendingCampaignAttributionNewToProductUserKey
- _PKPendingCampaignAttributionNewToWalletUserKey
- _PKPendingCampaignAttributionProductTypeKey
- _PKPendingCampaignAttributionReferralSourceKey
- _PKRemovePendingCampaignAttributionForPassUniqueIdentifier
- _PKSetLocalSecureElementPassesProvider
CStrings:
+ "reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:"
- "@\"NSArray\"8@?0"
- "isNewToWalletUser"
- "reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:"
```
