## SiriAssetUtilities

> `/System/Library/PrivateFrameworks/SiriAssetUtilities.framework/SiriAssetUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf478` | `0xf68c` | **`+0x214`** |
| `__AUTH_CONST.__cfstring` | `0x520` | `0x5c0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1b97` | `0x1bea` | **`+0x53`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x1e0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x9b8` | `0x9c8` | **`+0x10`** |
| `__DATA.__bss` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xd28` | `0xd30` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4b0` | `0x4b8` | **`+0x8`** |

### Other Changes

```diff

-3600.77.1.0.0
+3605.11.1.0.0

-  Functions: 335
-  Symbols:   695
-  CStrings:  313
+  Functions: 336
+  Symbols:   701
+  CStrings:  318
Symbols:
+ +[SAUCommonUtilities bundle]
+ _OBJC_CLASS_$_NSBundle
+ _UAFFaultCapture
+ _bundle.sSAUBundle
+ _kUAFABCXPCFallback
+ _objc_retain_x5
Functions:
+ +[SAUCommonUtilities bundle]
~ -[SAUXPCService operationWithConfig:completion:] : 444 -> 504
~ -[SAUXPCService lockLatestAtomicInstance:atomicInstance:completion:] : 408 -> 468
~ -[SAUXPCService subscriptions:subscriber:user:completion:] : 12 -> 252
~ -[SAUXPCService markAssetsExpired:completion:] : 380 -> 448
CStrings:
+ "lockLatestAtomicInstance"
+ "markAssetsExpired"
+ "operationWithConfig"
+ "proxy"
+ "subscriptions"
```
