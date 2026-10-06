## Home

> `/System/Library/PrivateFrameworks/Home.framework/Home`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3bfa1c` | `0x3bf4ec` | **`-0x530`** |
| `__TEXT.__eh_frame` | `0x75a0` | `0x73e0` | **`-0x1c0`** |
| `__TEXT.__oslogstring` | `0x1d5b6` | `0x1d704` | **`+0x14e`** |
| `__TEXT.__gcc_except_tab` | `0x4bec` | `0x4cc8` | **`+0xdc`** |
| `__DATA_CONST.__const` | `0x111d0` | `0x11230` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x2c924` | `0x2c974` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x12fb0` | `0x12ff8` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x272a0` | `0x272e0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x34a7f` | `0x34abd` | **`+0x3e`** |
| `__AUTH_CONST.__objc_intobj` | `0x2340` | `0x2370` | **`+0x30`** |
| `__DATA.__data` | `0x76d8` | `0x76a8` | **`-0x30`** |
| `__DATA_DIRTY.__data` | `0xed0` | `0xea0` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x2bff` | `0x2bd7` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0x21e8` | `0x2208` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x4c400` | `0x4c420` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xea70` | `0xea50` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x3240` | `0x3228` | **`-0x18`** |
| `__AUTH.__data` | `0x13d0` | `0x13c0` | **`-0x10`** |
| `__TEXT.__const` | `0x58b0` | `0x58c0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x540` | `0x538` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1608` | `0x160c` | **`+0x4`** |

### Other Changes

```diff

-1216.4.0.1.11
+1227.0.0.0.1

-  Functions: 21216
-  Symbols:   30263
-  CStrings:  8517
+  Functions: 21213
+  Symbols:   30271
+  CStrings:  8525
Symbols:
+ -[HFContactStore _appleAccountFallbackContactWithEmailAddress:]
+ -[HFContactStore _matchingContactForEmailAddress:withKeys:]
+ -[_HFItemUpdateFutureWrapper finished]
+ -[_HFItemUpdateFutureWrapper setFinished:]
+ GCC_except_table103
+ GCC_except_table124
+ GCC_except_table163
+ GCC_except_table276
+ GCC_except_table281
+ _HFMaxConcurrentLiveStreamsKey
+ _HFShouldCapConcurrentLiveStreamsKey
+ _OBJC_IVAR_$__HFItemUpdateFutureWrapper._finished
+ ___63-[HFContactStore _appleAccountFallbackContactWithEmailAddress:]_block_invoke
+ ___block_descriptor_40_e8_32w_e41_v24?0"HFItemUpdateOutcome"8"NSError"16lw32l8
+ ___block_descriptor_48_e8_32s40r_e31_v24?0"ACAccount"8"NSError"16lr40l8s32l8
+ ___block_descriptor_56_e8_32w40w_e19_v16?0"NAPromise"8lw32l8w40l8
+ _dispatch_semaphore_create
+ _dispatch_semaphore_signal
+ _dispatch_semaphore_wait
+ _symbolic Say_____G 13HomeDataModel14StaticEndpointV
+ _symbolic _____Sg 13HomeDataModel21MatterAttributePollerC18SubscriptionRecordV
+ _symbolic _____Sg_ABt 13HomeDataModel14StaticEndpointV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 13HomeDataModel14StaticEndpointV
- -[HFAccessoryCategoryStatusItem hidesWithNoAccessories]
- -[HFEnergyCategoryStatusItem hidesWithNoAccessories]
- GCC_except_table122
- GCC_except_table274
- GCC_except_table279
- GCC_except_table89
- GCC_except_table99
- __IVARS_HFPowerMeasurementStatusItem
- ___block_descriptor_40_e8_32w_e29_v16?0"HFItemUpdateOutcome"8lw32l8
- _symbolic _____3key______5valuet s6UInt16V 13HomeDataModel14StaticEndpointV
- _symbolic _____3key______5valuetSg s6UInt16V 13HomeDataModel14StaticEndpointV
- _symbolic _____Sg 13HomeDataModel34StaticElectricalMeterEndpointGroupV
- _symbolic _____Sg 13HomeDataModel38StaticMeterReferencePointEndpointGroupV
- _symbolic ______p 13HomeDataModel20EndpointLikeProtocolP
- _symbolic ______pSg 13HomeDataModel20EndpointLikeProtocolP
CStrings:
+ "%{public}@: no matter snapshot for home %{public}s"
+ "AppleAccount fallback: no primary account available"
+ "AppleAccount fallback: primary account has no first or last name"
+ "AppleAccount fallback: primary account username does not match requested email"
+ "AppleAccount fetch failed: %@"
+ "AppleAccount fetch timed out; returning nil"
+ "HFMaxConcurrentLiveStreams"
+ "HFShouldCapConcurrentLiveStreams"
+ "v24@?0@\"ACAccount\"8@\"NSError\"16"
- "v16@?0@\"HFItemUpdateOutcome\"8"
```
