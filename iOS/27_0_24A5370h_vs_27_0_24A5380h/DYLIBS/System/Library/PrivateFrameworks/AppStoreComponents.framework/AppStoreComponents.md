## AppStoreComponents

> `/System/Library/PrivateFrameworks/AppStoreComponents.framework/AppStoreComponents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x29c8` | `0x1168` | **`-0x1860`** |
| `__DATA_DIRTY.__objc_data` | `0x3c0` | `0x1c20` | **`+0x1860`** |
| `__DATA.__bss` | `0x27c0` | `0x2640` | **`-0x180`** |
| `__DATA_DIRTY.__bss` | `—` | `0x180` | **`+0x180`** |
| `__DATA_DIRTY.__data` | `—` | `0x128` | **`+0x128`** |
| `__AUTH.__data` | `0x848` | `0x728` | **`-0x120`** |
| `__DATA_CONST.__got` | `0x898` | `0x918` | **`+0x80`** |
| `__DATA.__data` | `0x2290` | `0x2288` | **`-0x8`** |

### Other Changes

```diff

-27.0.38.0.0
+27.0.43.0.0
Symbols:
+ -[ASCAdLockupView offerPresenterWillPerformActionOfOffer:inState:withActivity:inContext:withPaymentSheetBridge:]
+ -[ASCLockupView offerPresenterWillPerformActionOfOffer:inState:withActivity:inContext:withPaymentSheetBridge:]
+ -[ASCOfferButtonContainerView offerPresenterWillPerformActionOfOffer:inState:withActivity:inContext:withPaymentSheetBridge:]
- -[ASCAdLockupView offerPresenterWillPerformActionOfOffer:inState:withActivity:inContext:withPaymentSheetView:]
- -[ASCLockupView offerPresenterWillPerformActionOfOffer:inState:withActivity:inContext:withPaymentSheetView:]
- -[ASCOfferButtonContainerView offerPresenterWillPerformActionOfOffer:inState:withActivity:inContext:withPaymentSheetView:]
```
