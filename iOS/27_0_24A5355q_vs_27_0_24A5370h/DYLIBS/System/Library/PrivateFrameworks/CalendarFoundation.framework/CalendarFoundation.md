## CalendarFoundation

> `/System/Library/PrivateFrameworks/CalendarFoundation.framework/CalendarFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5df44` | `0x5e0b0` | **`+0x16c`** |
| `__TEXT.__objc_methlist` | `0x5ccc` | `0x5d0c` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x4140` | `0x4178` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x78a0` | `0x78d0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1b20` | `0x1b48` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x9500` | `0x9520` | **`+0x20`** |
| `__TEXT.__cstring` | `0x64fd` | `0x651d` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x8a8` | `0x8b0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x350` | `0x354` | **`+0x4`** |

### Other Changes

```diff

-1629.0.0.0.0
+1632.0.0.0.0

-  Functions: 2596
-  Symbols:   4383
-  CStrings:  1552
+  Functions: 2604
+  Symbols:   4393
+  CStrings:  1553
Symbols:
+ +[CalSpotlightQueryController searchWithString:clientBundleID:minimumStartDate:completionHandler:]
+ -[CalSpotlightPendingSearch initWithString:clientBundleID:minimumStartDate:completionHandler:]
+ -[CalSpotlightPendingSearch minimumStartDate]
+ -[CalSpotlightPendingSearch setMinimumStartDate:]
+ -[NSURL(CalClassAdditions) cal_hasSchemeHTTPOrHTTPS]
+ -[NSURL(CalClassAdditions) cal_isAddressbookContactURL]
+ _CalAnalyticsSendUnprefixedEventLazy
+ _OBJC_CLASS_$_NSCompoundPredicate
+ _OBJC_IVAR_$_CalSpotlightPendingSearch._minimumStartDate
+ ___CalAnalyticsSendUnprefixedEventLazy_block_invoke
CStrings:
+ "kMDItemStartDate >= %@"
```
