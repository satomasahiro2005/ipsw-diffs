## iCloudQuota

> `/System/Library/PrivateFrameworks/iCloudQuota.framework/iCloudQuota`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7be34` | `0x7c994` | **`+0xb60`** |
| `__TEXT.__oslogstring` | `0x8999` | `0x8aa9` | **`+0x110`** |
| `__TEXT.__objc_methlist` | `0x59cc` | `0x5a3c` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x6680` | `0x66e0` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0xb5b0` | `0xb600` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x3088` | `0x30b8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x5050` | `0x5080` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1ec0` | `0x1ed8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x6b4` | `0x6bc` | **`+0x8`** |

### Other Changes

```diff

-301.24.0.27.0
+301.24.1.3.0

-  Functions: 3036
-  Symbols:   4340
-  CStrings:  1644
+  Functions: 3048
+  Symbols:   4349
+  CStrings:  1652
Symbols:
+ +[ICQOffer _appendAdopterBannerSpecificationsFromEntries:source:to:]
+ +[ICQOffer(Internal) adopterBannerSpecificationsFromServerDictionary:]
+ +[_ICQDeviceInfo normalizedPendingItemsCount:]
+ -[ICQCloudStorageDataController reportDeleteWithSuccess:bundleId:completion:]
+ -[ICQOfferManager _debugMockRegularOfferIfEnabled]
+ -[_ICQAlertSpecification messageWithKey:]
+ -[_ICQAlertSpecification titleWithKey:]
+ -[_ICQBannerSpecification appId]
+ GCC_except_table37
+ GCC_except_table52
+ GCC_except_table70
+ _OBJC_IVAR_$__ICQAlertSpecification._messageTemplates
+ _OBJC_IVAR_$__ICQAlertSpecification._titleTemplates
+ ___77-[ICQCloudStorageDataController reportDeleteWithSuccess:bundleId:completion:]_block_invoke
- GCC_except_table30
- GCC_except_table36
- GCC_except_table51
- GCC_except_table69
- GCC_except_table71
CStrings:
+ "Failed to report delete with error: %@"
+ "Reaching out to daemon to report Manage Storage delete for %{public}@."
+ "Returning icqctl debug mock offer for bundle %@: %@"
+ "XPC Error while reaching out to daemon to report delete."
+ "contextBasedMesg"
+ "contextBasedTitle"
+ "debug-mock-offer"
+ "pendingItemsCount %@ is too low, treating as nil"
```
