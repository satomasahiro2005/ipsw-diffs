## ClipServices

> `/System/Library/PrivateFrameworks/ClipServices.framework/ClipServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x384b0` | `0x385a4` | **`+0xf4`** |
| `__AUTH_CONST.__objc_const` | `0x5138` | `0x5158` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x323c` | `0x3254` | **`+0x18`** |
| `__DATA.__bss` | `0x130` | `0x120` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2508` | `0x2518` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x138` | `0x148` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x10d8` | `0x10e8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x37c` | `0x380` | **`+0x4`** |

### Other Changes

```diff

-1038.10.0.0.0
+1039.1.0.0.0

-  Functions: 1489
-  Symbols:   2492
+  Functions: 1491
+  Symbols:   2495
Symbols:
+ -[CPSAppInfoFetcher _downloadIconIfNeeded:sourceBundleID:completionHandler:]
+ -[CPSImageDownloader initWithSourceApplicationBundleIdentifier:]
+ -[CPSImageLoader initWithSourceApplicationBundleIdentifier:]
+ _OBJC_IVAR_$_CPSImageDownloader._sourceApplicationBundleIdentifier
+ ___76-[CPSAppInfoFetcher _downloadIconIfNeeded:sourceBundleID:completionHandler:]_block_invoke
+ ___block_descriptor_65_e8_32s40s48bs56w_e36_v24?0"AMSMediaResult"8"NSError"16ls48l8w56l8s32l8s40l8
- -[CPSAppInfoFetcher _downloadIconIfNeeded:completionHandler:]
- ___61-[CPSAppInfoFetcher _downloadIconIfNeeded:completionHandler:]_block_invoke
- ___block_descriptor_57_e8_32s40bs48w_e36_v24?0"AMSMediaResult"8"NSError"16ls40l8w48l8s32l8
```
