## NewsSubscription

> `/System/Library/PrivateFrameworks/NewsSubscription.framework/NewsSubscription`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0xf300` | `0xe380` | **`-0xf80`** |
| `__DATA_DIRTY.__bss` | `0x5c00` | `0x6b80` | **`+0xf80`** |
| `__DATA_DIRTY.__data` | `0x80f8` | `0x8f48` | **`+0xe50`** |
| `__AUTH.__data` | `0x23d8` | `0x1878` | **`-0xb60`** |
| `__DATA.__data` | `0x3b90` | `0x38a0` | **`-0x2f0`** |
| `__TEXT.__text` | `0x186c90` | `0x186a4c` | **`-0x244`** |
| `__AUTH.__objc_data` | `0x1370` | `0x1298` | **`-0xd8`** |
| `__DATA_DIRTY.__objc_data` | `0x2260` | `0x2338` | **`+0xd8`** |
| `__TEXT.__eh_frame` | `0x5710` | `0x56b8` | **`-0x58`** |
| `__TEXT.__unwind_info` | `0x58b8` | `0x5880` | **`-0x38`** |
| `__TEXT.__swift5_typeref` | `0x57a4` | `0x57d6` | **`+0x32`** |
| `__AUTH_CONST.__auth_got` | `0x2460` | `0x2450` | **`-0x10`** |
| `__DATA.__common` | `0x98` | `0x88` | **`-0x10`** |
| `__DATA_DIRTY.__common` | `0x160` | `0x170` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1278` | `0x1270` | **`-0x8`** |

### Other Changes

```diff

-5920.0.0.0.0
+5923.0.0.0.0

-  Functions: 8397
-  Symbols:   3266
+  Functions: 8389
+  Symbols:   3263
Symbols:
+ ___swift_closure_destructor.21Tm
+ _symbolic _____ySo10FCPurchaseCSgG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE 16NewsSubscription13PaywallConfigV
+ _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE 16NewsSubscription24ConfigurableOfferConfigsV
+ _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE 8NewsFeed13FormatContentV8ResolvedV
- ___swift_closure_destructor.22Tm
- ___swift_closure_destructor.23Tm
- _get_type_metadata 15Synchronization5MutexVy16NewsSubscription13PaywallConfigVSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVy16NewsSubscription24ConfigurableOfferConfigsVSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVy8NewsFeed13FormatContentV8ResolvedVSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVySo10FCPurchaseCSgG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
```
