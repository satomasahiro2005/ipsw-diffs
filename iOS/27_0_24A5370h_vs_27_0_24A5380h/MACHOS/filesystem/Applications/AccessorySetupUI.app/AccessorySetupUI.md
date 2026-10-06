## AccessorySetupUI

> `/Applications/AccessorySetupUI.app/AccessorySetupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9f860` | `0xa2550` | **`+0x2cf0`** |
| `__TEXT.__eh_frame` | `0xcb0` | `0xda8` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0x32aa` | `0x338a` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x2e0f` | `0x2eaf` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x6111` | `0x6181` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x19c3` | `0x1a33` | **`+0x70`** |
| `__DATA.__data` | `0x29e8` | `0x2a48` | **`+0x60`** |
| `__DATA.__objc_const` | `0x4190` | `0x41f0` | **`+0x60`** |
| `__DATA.__objc_data` | `0x2fe0` | `0x3038` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x63e0` | `0x6430` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x14b8` | `0x1500` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x1c38` | `0x1c78` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x2098` | `0x20d0` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x1e90` | `0x1ec0` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x15d4` | `0x15f8` | **`+0x24`** |
| `__DATA_CONST.__auth_got` | `0xf50` | `0xf68` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x660` | `0x678` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x2bd4` | `0x2bea` | **`+0x16`** |
| `__DATA_CONST.__auth_ptr` | `0x718` | `0x728` | **`+0x10`** |
| `__TEXT.__const` | `0x26f4` | `0x2704` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x4c` | `0x50` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x2c` | `0x30` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2700.26.0.0.0
+2700.27.0.0.0

+  - /System/Library/Frameworks/MarketplaceKit.framework/MarketplaceKit

-  Functions: 2528
-  Symbols:   900
-  CStrings:  1658
+  Functions: 2543
+  Symbols:   907
+  CStrings:  1668
Symbols:
+ _$s14MarketplaceKit14AppDistributorO18requestProductPage_6itemID07versionI0ySS_s6UInt64VAHSgtYaKFZ
+ _$s14MarketplaceKit14AppDistributorO18requestProductPage_6itemID07versionI0ySS_s6UInt64VAHSgtYaKFZTu
+ _$sScEMa
+ _$sScT6cancelyyF
+ _$ss5NeverON
+ _$ss5NeverOs5ErrorsWP
+ _$ss6UInt64VMn
CStrings:
+ "Alt marketplace product page request was cancelled"
+ "An app is available to manage this accessory with this iPhone."
+ "An app is available to pair this accessory with this iPhone."
+ "App Promotion View: Cannot Launch Store Page Due to Lack of AdamID"
+ "Failed to convert adamID to UInt64: %s"
+ "Failed to open alt marketplace product page: %s"
+ "Opening alt marketplace product page: distributor=%s, adamID=%s"
+ "altMarketplaceProductRequestTask"
+ "appDistributorBundleID"
+ "appDistributorName"
+ "com.apple.AppStore"
- "App Promotion View: Cannot Launch App Store Page Due to Lack of AdamID"
```
