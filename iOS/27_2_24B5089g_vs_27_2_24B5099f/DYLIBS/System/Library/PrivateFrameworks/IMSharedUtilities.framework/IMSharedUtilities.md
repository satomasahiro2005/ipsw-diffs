## IMSharedUtilities

> `/System/Library/PrivateFrameworks/IMSharedUtilities.framework/IMSharedUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37fc10` | `0x381394` | **`+0x1784`** |
| `__TEXT.__eh_frame` | `0xefa8` | `0xf0b0` | **`+0x108`** |
| `__TEXT.__cstring` | `0x28503` | `0x285b3` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0xfc98` | `0xfd00` | **`+0x68`** |
| `__AUTH_CONST.__const` | `0x17e18` | `0x17e70` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x1a620` | `0x1a670` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x1ed46` | `0x1ed96` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x16c0` | `0x1708` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x24180` | `0x241c0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x299a8` | `0x299d0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xd928` | `0xd950` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x9ef4` | `0x9f14` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x6b43` | `0x6b63` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x790a` | `0x792a` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x6df0` | `0x6e08` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2c60` | `0x2c70` | **`+0x10`** |
| `__DATA.__bss` | `0x39060` | `0x39050` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x1c40` | `0x1c50` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x7fd8` | `0x7fe4` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x558` | `0x564` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x3a8` | `0x3ac` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x33c` | `0x340` | **`+0x4`** |

### Other Changes

```diff

-1491.200.73.0.0
+1491.200.95.0.0

-  Functions: 21591
-  Symbols:   4247
-  CStrings:  8105
+  Functions: 21613
+  Symbols:   4256
+  CStrings:  8110
Symbols:
+ _CGColorSpaceCreateWithName
+ _IMCoreSpotlightIndexBehaviorFromReason
+ _IMFileTransferAttributionInfoIsPendingGenerationAfterMigration
+ _IMPreviewConstraintKeyAssetPxSizeHeight
+ _IMPreviewConstraintKeyAssetPxSizeWidth
+ _IMPreviewConstraintKeyForceRegeneration
+ _IMSharedHelperCurrentRegionForcesFilterUnknownSenders
+ _IMSharedHelperRegionForcingFilterUnknownSenders
+ _kCGColorSpaceDisplayP3
CStrings:
+ "Declared asset size %@ is rotated relative to decoded image size %@, swapping"
+ "The version of AskToCore on this device does not support this feature"
+ "aph"
+ "apw"
+ "fileTransferPreviewWasForceRegenerated(_:)"
+ "filter-unknown-senders-forced-country-codes"
- "HN"
```
