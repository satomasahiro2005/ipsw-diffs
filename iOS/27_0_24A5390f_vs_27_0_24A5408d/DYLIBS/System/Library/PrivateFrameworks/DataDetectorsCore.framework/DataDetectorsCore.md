## DataDetectorsCore

> `/System/Library/PrivateFrameworks/DataDetectorsCore.framework/DataDetectorsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37af8` | `0x37b8c` | **`+0x94`** |
| `__TEXT.__lazy_helpers` | `0x4ec` | `0x498` | **`-0x54`** |
| `__TEXT.__unwind_info` | `0xa08` | `0xa20` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xae4` | `0xaf4` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xae8` | `0xaf0` | **`+0x8`** |
| `__AUTH_CONST.__lazy_load_got` | `0x78` | `0x70` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xd08` | `0xd10` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x48` | `0x40` | **`-0x8`** |

### Other Changes

```diff

-843.0.0.0.0
+847.0.0.0.0

-  Functions: 777
-  Symbols:   1772
+  Functions: 779
+  Symbols:   1771
Symbols:
+ -[DDScannerResult getValidPhoneValue:label:regionCode:]
+ GCC_except_table600
+ GCC_except_table612
+ GCC_except_table627
+ GCC_except_table704
+ GCC_except_table722
+ GCC_except_table752
+ _DDResultIsValidPhoneNumberStringForRegion
+ _DDResultIsValidPhoneNumberStringForRegion.frameworkAvailable
+ _DDResultIsValidPhoneNumberStringForRegion.onceToken
+ ___DDResultIsValidPhoneNumberStringForRegion_block_invoke
+ _objc_retain_x4
- GCC_except_table599
- GCC_except_table611
- GCC_except_table626
- GCC_except_table703
- GCC_except_table720
- GCC_except_table750
- _CPPhoneNumberCopyHomeCountryCode
- _CPPhoneNumberCopyHomeCountryCode$lazyAuthGOT_IA_ad_0
- _CPPhoneNumberCopyHomeCountryCode$lazyLoadStub
- _DDResultIsValidPhoneNumberString.frameworkAvailable
- _DDResultIsValidPhoneNumberString.onceToken
- ___DDResultIsValidPhoneNumberString_block_invoke
- _lazyLoadFlag$AppSupport
```
