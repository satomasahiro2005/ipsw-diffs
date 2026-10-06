## amsaccountsd

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/amsaccountsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26ce6c` | `0x27352c` | **`+0x66c0`** |
| `__TEXT.__unwind_info` | `0xa758` | `0xad48` | **`+0x5f0`** |
| `__TEXT.__eh_frame` | `0x13a00` | `0x13f48` | **`+0x548`** |
| `__DATA_CONST.__const` | `0x137e0` | `0x13ce0` | **`+0x500`** |
| `__TEXT.__const` | `0x23c50` | `0x23f70` | **`+0x320`** |
| `__DATA.__bss` | `0x35838` | `0x35b48` | **`+0x310`** |
| `__TEXT.__cstring` | `0xccdc` | `0xceac` | **`+0x1d0`** |
| `__TEXT.__objc_methname` | `0x11bdb` | `0x11d8b` | **`+0x1b0`** |
| `__TEXT.__objc_stubs` | `0xbdc0` | `0xbf60` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0xfdf9` | `0xff29` | **`+0x130`** |
| `__DATA.__data` | `0xc108` | `0xc218` | **`+0x110`** |
| `__TEXT.__swift5_fieldmd` | `0x7674` | `0x7760` | **`+0xec`** |
| `__DATA.__objc_const` | `0xc9a8` | `0xca78` | **`+0xd0`** |
| `__DATA.__objc_data` | `0x2fa0` | `0x3070` | **`+0xd0`** |
| `__TEXT.__swift5_typeref` | `0x7cc6` | `0x7d96` | **`+0xd0`** |
| `__TEXT.__constg_swiftt` | `0x64ec` | `0x65a4` | **`+0xb8`** |
| `__TEXT.__swift5_reflstr` | `0x4f8c` | `0x503c` | **`+0xb0`** |
| `__TEXT.__swift5_capture` | `0x1078` | `0x110c` | **`+0x94`** |
| `__DATA.__objc_selrefs` | `0x4098` | `0x4100` | **`+0x68`** |
| `__DATA_CONST.__cfstring` | `0x4de0` | `0x4e40` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x618c` | `0x61ec` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x4660` | `0x46b0` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x5218` | `0x5268` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x9d8` | `0xa1c` | **`+0x44`** |
| `__DATA_CONST.__auth_ptr` | `0x2ce8` | `0x2d28` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x4b8` | `0x4ec` | **`+0x34`** |
| `__TEXT.__objc_classname` | `0x1b0b` | `0x1b3b` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x3b8` | `0x3e8` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x2340` | `0x2368` | **`+0x28`** |
| `__TEXT.__swift5_assocty` | `0xa60` | `0xa78` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x1b24` | `0x1b3c` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x190` | `0x1a4` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x820` | `0x834` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x14a8` | `0x14b0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x428` | `0x430` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xd28` | `0xd20` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x108` | `0x110` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3a8` | `0x3ac` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__linkguard`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types2`

### Other Changes

```diff

-10.1.11.2.1
+10.1.13.2.1

-  Functions: 16174
-  Symbols:   2103
-  CStrings:  5689
+  Functions: 16328
+  Symbols:   2109
+  CStrings:  5728
Symbols:
+ _$s10Foundation12NotificationV36_unconditionallyBridgeFromObjectiveCyACSo14NSNotificationCSgFZ
+ _$s10Foundation12NotificationVMa
+ _$s18AppleMediaServices13DeviceDetailsO23deviceUnlockedSinceBootSbSgyFZ
+ _$s18AppleMediaServices3LogV8purchaseACvgZ
+ _$s18AppleMediaServices8FlagKeysO26CardEnrollmentCacheWarmingyA2CmFWC
+ _$s2os12OSSignpostIDV3logACSo03OS_a1_D0C_tcfC
CStrings:
+ "%{public}@ Card-enrollment cache warming is disabled, not scheduling"
+ "%{public}@ Scheduled card-enrollment cache warming"
+ "%{public}@[auto-enrollment] Default pass lookup timed out after %{public}.1f seconds"
+ "%{public}@[auto-enrollment] Dropping cache write, invalidated while fetching"
+ "@\"_TtC12amsaccountsd25CardEnrollmentCacheWarmer\""
+ "AMSDDefaultPaymentPassCacheDidInvalidateNotification"
+ "AMSDPurchaseService.CacheWarming"
+ "[cache-warming] Default pass warm failed: "
+ "[cache-warming] Skipping: "
+ "[cache-warming] ["
+ "_TtC12amsaccountsd25CardEnrollmentCacheWarmer"
+ "_cardEnrollmentCacheWarmer"
+ "_defaultPaymentPassCacheGenerationBox"
+ "_fetchDefaultPaymentPassIdentifierWithLogKey:completion:"
+ "addObserverForName:object:queue:usingBlock:"
+ "alreadyWarming"
+ "arrayWithObject:"
+ "card-enrollment-warming-disabled"
+ "card-enrollment-warming-limit"
+ "cardEnrollmentWarmWindowCount"
+ "cardEnrollmentWarmWindowStart"
+ "com.apple.amsaccountsd.cardenrollmentwarming"
+ "currentDefaultPaymentPassIdentifierWithLogKey:completion:"
+ "defaultPaymentPass"
+ "initWithInteger:"
+ "invalidationObserver"
+ "isWarming"
+ "limitReached"
+ "makeIfEnabled"
+ "notUnlockedSinceBoot"
+ "nothingRegistered"
+ "postNotificationName:object:"
+ "setCardEnrollmentWarmWindowCount:"
+ "setCardEnrollmentWarmWindowStart:"
+ "setObject:atIndexedSubscript:"
+ "setupWarmingScheduleWithCompletionHandler:"
+ "success: %{public}s"
+ "v16@?0@\"NSNotification\"8"
+ "warmDefaultPaymentPass(logKey:)"
+ "warmers"
- "_currentDefaultPaymentPassIdentifierWithLogKey:completion:"
```
