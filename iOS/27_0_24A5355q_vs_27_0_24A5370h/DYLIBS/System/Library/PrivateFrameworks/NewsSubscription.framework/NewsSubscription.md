## NewsSubscription

> `/System/Library/PrivateFrameworks/NewsSubscription.framework/NewsSubscription`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x185cc8` | `0x186c90` | **`+0xfc8`** |
| `__TEXT.__cstring` | `0xf4b7` | `0xf6b7` | **`+0x200`** |
| `__TEXT.__swift5_capture` | `0x226c` | `0x23dc` | **`+0x170`** |
| `__AUTH_CONST.__const` | `0xff80` | `0x10048` | **`+0xc8`** |
| `__AUTH_CONST.__objc_const` | `0x128f0` | `0x12920` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x5774` | `0x57a4` | **`+0x30`** |
| `__DATA.__data` | `0x3b70` | `0x3b90` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x4970` | `0x4990` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x37a8` | `0x37c0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1270` | `0x1278` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x58c0` | `0x58b8` | **`-0x8`** |

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

-  Functions: 8389
-  Symbols:   3261
-  CStrings:  1193
+  Functions: 8397
+  Symbols:   3266
+  CStrings:  1199
Symbols:
+ _OBJC_CLASS_$_NSArray
+ ___swift_closure_destructor.31Tm
+ ___swift_closure_destructor.43Tm
+ _symbolic _____SgXw 16NewsSubscription0B13StatusCheckerC
+ _symbolic _____SgXw 16NewsSubscription19EntitlementsManagerC
+ _symbolic _____SgXwz_Xx 16NewsSubscription0B13StatusCheckerC
+ _symbolic _____SgXwz_Xx 16NewsSubscription19EntitlementsManagerC
- ___swift_closure_destructor.26Tm
- ___swift_closure_destructor.35Tm
CStrings:
+ "Entitlement check completed from validateEntitlementsCache but self is deallocated"
+ "Entitlement check on msin from validateEntitlementsCache but self is deallocated"
+ "PaywallTypeProvider.alaCartePaywallType: Showing ala carte soft paywall for paid article %@ - article is in reading history"
+ "entitlementsDidChange skipped — app in background state"
+ "entitlementsDidChange skipped — app not yet fully launched"
+ "entitlementsDidChange skipped — self is deallocated"
```
