## StocksCore

> `/System/Library/PrivateFrameworks/StocksCore.framework/StocksCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0xa2b0` | `0xb5e0` | **`+0x1330`** |
| `__AUTH.__data` | `0x12e0` | `0x120` | **`-0x11c0`** |
| `__AUTH.__objc_data` | `0x7f8` | `0x240` | **`-0x5b8`** |
| `__DATA_DIRTY.__objc_data` | `0x1da0` | `0x2358` | **`+0x5b8`** |
| `__TEXT.__text` | `0x25684c` | `0x256448` | **`-0x404`** |
| `__DATA.__data` | `0x45c0` | `0x43d0` | **`-0x1f0`** |
| `__DATA.__bss` | `0x18e40` | `0x18d40` | **`-0x100`** |
| `__DATA_DIRTY.__bss` | `0x17940` | `0x17a40` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0x55b9` | `0x5667` | **`+0xae`** |
| `__TEXT.__unwind_info` | `0x9650` | `0x95f8` | **`-0x58`** |
| `__DATA.__common` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__common` | `0x1b8` | `0x208` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0xd0a4` | `0xd06c` | **`-0x38`** |
| `__AUTH_CONST.__objc_const` | `0x14230` | `0x14260` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x6be4` | `0x6c04` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2478` | `0x2468` | **`-0x10`** |
| `__TEXT.__const` | `0x1d560` | `0x1d570` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x12c0` | `0x12b8` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3730` | `0x3738` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2018.0.0.0.0
+2020.0.0.0.0

-  Functions: 13763
-  Symbols:   5581
+  Functions: 13740
+  Symbols:   5583
Symbols:
+ ___swift_closure_destructor.105Tm
+ ___swift_closure_destructor.11Tm
+ ___swift_closure_destructor.126Tm
+ ___swift_closure_destructor.129Tm
+ ___swift_closure_destructor.165Tm
+ ___swift_closure_destructor.17Tm
+ ___swift_closure_destructor.190Tm
+ ___swift_closure_destructor.20Tm
+ ___swift_closure_destructor.217Tm
+ ___swift_closure_destructor.229Tm
+ ___swift_closure_destructor.260Tm
+ ___swift_closure_destructor.38Tm
+ ___swift_closure_destructor.53Tm
+ ___swift_closure_destructor.72Tm
+ ___swift_closure_destructor.96Tm
+ _flat unique So24OS_dispatch_source_timer_p
+ _symbolic _____ySay_____GG 15Synchronization5MutexVAARi_zrlE 10StocksCore13ObserverProxy33_1F77FA1D2DA459732A6DD76037675CDBLLC
+ _symbolic _____ySay_____GG 15Synchronization5MutexVAARi_zrlE 10StocksCore25QuoteManagerObserverProxy33_7D29A7717B73C85A7D09DB3CD841E24CLLC
+ _symbolic _____ySay_____GG 15Synchronization5MutexVAARi_zrlE 10StocksCore29WatchlistManagerObserverProxy33_D21D55FFBFF3ABACD72AFB343261D479LLC
+ _symbolic _____ySay_____GG 15Synchronization5MutexVAARi_zrlE 10StocksCore29WatchlistServiceObserverProxyC
+ _symbolic _____ySay_____GG 15Synchronization5MutexVAARi_zrlE 10StocksCore5StockV
+ _symbolic _____ySay_____GG 15Synchronization5MutexVAARi_zrlE 10StocksCore9WatchlistV
+ _symbolic _____ySbG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____ySdG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____yShySSGG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 10Foundation4UUIDV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 10StocksCore16WatchlistManagerC15WatchlistsStateV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 10StocksCore18UserIdentitySourceO
+ _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE 10StocksCore11SDSMetadataV
+ _symbolic _____y______pSgG 15Synchronization5MutexVAARi_zrlE So24OS_dispatch_source_timerP
+ _symbolic _____yyycSgG 15Synchronization5MutexVAARi_zrlE
- ___swift_closure_destructor.111Tm
- ___swift_closure_destructor.127Tm
- ___swift_closure_destructor.130Tm
- ___swift_closure_destructor.166Tm
- ___swift_closure_destructor.191Tm
- ___swift_closure_destructor.218Tm
- ___swift_closure_destructor.230Tm
- ___swift_closure_destructor.261Tm
- ___swift_closure_destructor.39Tm
- ___swift_closure_destructor.54Tm
- ___swift_closure_destructor.73Tm
- ___swift_closure_destructor.99Tm
- _get_type_metadata 15Synchronization5MutexVy10Foundation4UUIDVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy10StocksCore11SDSMetadataVSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVy10StocksCore16WatchlistManagerC15WatchlistsStateVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy10StocksCore18UserIdentitySourceOG noncopyable
- _get_type_metadata 15Synchronization5MutexVySay10StocksCore13ObserverProxy33_1F77FA1D2DA459732A6DD76037675CDBLLCGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySay10StocksCore25QuoteManagerObserverProxy33_7D29A7717B73C85A7D09DB3CD841E24CLLCGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySay10StocksCore29WatchlistManagerObserverProxy33_D21D55FFBFF3ABACD72AFB343261D479LLCGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySay10StocksCore29WatchlistServiceObserverProxyCGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySay10StocksCore5StockVGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySay10StocksCore9WatchlistVGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySbG noncopyable
- _get_type_metadata 15Synchronization5MutexVySdG noncopyable
- _get_type_metadata 15Synchronization5MutexVyShySSGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySo24OS_dispatch_source_timer_pSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVyyycSgG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "Whether the watchlist’s name should be shown in the widget."
- "Whether the watchlist's name should be shown in the widget."
```
