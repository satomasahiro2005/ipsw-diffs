## LightSourceSupport

> `/System/Library/PrivateFrameworks/LightSourceSupport.framework/LightSourceSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeef8` | `0xeea8` | **`-0x50`** |

### Other Changes

```diff
Symbols:
+ __ZNSt3__16vectorIP11objc_objectNS_9allocatorIS3_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorIyNS_9allocatorIyEEE20__throw_length_errorB9fqn220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqn220106v
- __ZNSt3__16vectorIP11objc_objectNS_9allocatorIS3_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorIyNS_9allocatorIyEEE20__throw_length_errorB9fqn220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqn220100v
Functions:
~ -[LSSController addAssertion:reason:] : 184 -> 180
~ -[LSSInvalidatableSet invalidate] : 268 -> 264
~ -[LSSSampleBuffer removeStartingAt:] : 160 -> 164
~ -[LSSSampleBuffer intervalContaining:] : 416 -> 424
~ -[CAWindowServer(LSS) lss_extendedDisplays] : 436 -> 432
~ -[CAWindowServer(LSS) _lss_primaryDisplay] : 280 -> 276
~ -[CAWindowServer(LSS) lss_filterDisplays:into:] : 348 -> 344
~ -[LSSSubscriber subscribeOnQueue:options:activityLevelChangeHandler:] : 892 -> 888
~ -[LSSSubscriber unsubscribe:] : 696 -> 692
~ -[LSSSubscriber clientInvalidated:] : 516 -> 512
~ -[LSSSubscriber _changeActivityLevel:] : 508 -> 504
~ -[LSSCAService dealloc] : 396 -> 392
~ -[LSSCAService setLightForDynamicDisplays:] : 1228 -> 1224
~ __ZN3lss14_cached_lookupIfP11objc_objectZNS_14_cached_lookupIfEET_S2_RNS_11SimpleCacheIS3_yEEbP14NSUserDefaultsEUlS2_E_EES5_T0_RNS6_ISC_yEET1_ : 312 -> 304
~ __ZNSt3__16vectorIP11objc_objectNS_9allocatorIS3_EEE24__emplace_back_slow_pathIJRKS2_EEEPS3_DpOT_ : 228 -> 224
~ __ZNSt3__16vectorIyNS_9allocatorIyEEE24__emplace_back_slow_pathIJRKyEEEPyDpOT_ : 228 -> 224
~ __ZN3lss14_cached_lookupIdP11objc_objectZNS_14_cached_lookupIdEET_S2_RNS_11SimpleCacheIS3_yEEbP14NSUserDefaultsEUlS2_E_EES5_T0_RNS6_ISC_yEET1_ : 320 -> 312
~ __ZN3lss14_cached_lookupIbP11objc_objectZNS_14_cached_lookupIbEET_S2_RNS_11SimpleCacheIS3_yEEbP14NSUserDefaultsEUlS2_E_EES5_T0_RNS6_ISC_yEET1_ : 316 -> 308
~ -[LSSCAService _updateDisplays] : 720 -> 712
~ -[LSSCAService _setExtendedDisplayLighting] : 564 -> 560
~ -[LSSXPCService _onQueue_updateLightDirection:] : 496 -> 492
```
