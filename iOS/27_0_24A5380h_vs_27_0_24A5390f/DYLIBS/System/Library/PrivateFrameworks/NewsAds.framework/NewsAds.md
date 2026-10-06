## NewsAds

> `/System/Library/PrivateFrameworks/NewsAds.framework/NewsAds`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9b88c` | `0x9e9d0` | **`+0x3144`** |
| `__AUTH_CONST.__const` | `0x95e5` | `0x9885` | **`+0x2a0`** |
| `__TEXT.__eh_frame` | `0x2140` | `0x22d0` | **`+0x190`** |
| `__DATA.__bss` | `0xa490` | `0xa610` | **`+0x180`** |
| `__TEXT.__swift5_capture` | `0x848` | `0x9bc` | **`+0x174`** |
| `__TEXT.__const` | `0xc108` | `0xc278` | **`+0x170`** |
| `__TEXT.__swift5_reflstr` | `0x30a4` | `0x31c4` | **`+0x120`** |
| `__DATA.__data` | `0x1a10` | `0x1af0` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x43ac` | `0x448c` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x2e98` | `0x2f70` | **`+0xd8`** |
| `__TEXT.__cstring` | `0x4813` | `0x48e3` | **`+0xd0`** |
| `__TEXT.__swift5_typeref` | `0x2543` | `0x2601` | **`+0xbe`** |
| `__TEXT.__swift5_fieldmd` | `0x48d8` | `0x4994` | **`+0xbc`** |
| `__AUTH_CONST.__objc_const` | `0xa840` | `0xa8a0` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x1448` | `0x14a0` | **`+0x58`** |
| `__TEXT.__swift5_builtin` | `0x17c` | `0x190` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x44d8` | `0x44c8` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x998` | `0x9a4` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x490` | `0x488` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2468` | `0x2470` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x5f8` | `0x600` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0xc4` | `0xcc` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4e8` | `0x4f0` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-5923.0.0.0.0
+5926.0.0.0.0

+  - /usr/lib/swift/libswiftSynchronization.dylib

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 4424
-  Symbols:   1802
-  CStrings:  386
+  Functions: 4498
+  Symbols:   1824
+  CStrings:  389
Symbols:
+ ___swift_async_cont_functlets
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ ___swift_closure_destructor.10Tm
+ ___swift_memcpy121_8
+ ___unnamed_16
+ _associated conformance 7NewsAds13BannerAdStateO14CollapseReasonOSHAASQ
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_getFunctionTypeMetadata1
+ _swift_retain_x11
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _symbolic SDySS_____yxq_q0_q1__GG 7NewsAds19BannerAdViewManagerC16PresentationGate33_C8C4B8D1F3B373AFBEAEFDFB2BD5272FLLO
+ _symbolic SDySSy_____cG So6CGSizeV
+ _symbolic ScA_pSg
+ _symbolic _____ 7NewsAds13BannerAdStateO14CollapseReasonO
+ _symbolic _____ 7NewsAds19BannerAdViewManagerC16PresentationGate33_C8C4B8D1F3B373AFBEAEFDFB2BD5272FLLO
+ _symbolic _____4size_t So6CGSizeV
+ _symbolic _____Iegy_ So6CGSizeV
+ _symbolic _____Iegy_Sg So6CGSizeV
+ _symbolic ______p11contentInfo______6reasont 7NewsAds17AdContentInfoTypeP AA06BannerC5StateO14CollapseReasonO
+ _symbolic _____y_____SgG 13TeaFoundation14SyncObservableC So6CGSizeV
+ _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE 7NewsAds25AdPolicyLayoutEnvironmentV
+ _symbolic _____ytIegnr_ So6CGSizeV
+ _symbolic y____________ptcSg 7NewsAds8BannerAdV s5ErrorP
+ _symbolic y___________tcSg 7NewsAds8BannerAdV AA0D6LayoutV
+ _symbolic ytIeAgHr_
+ _symbolic ytSgIeAgHr_
- ___swift_closure_destructor.11Tm
- ___swift_memcpy104_8
- ___swift_memcpy105_8
- ___unnamed_3
- _swift_retain_x9
- _symbolic _____SgIegy_ So6CGSizeV
- _symbolic _____SgytIegnr_ So6CGSizeV
- _symbolic _____y_____SgG 13TeaFoundation6AtomicC 7NewsAds25AdPolicyLayoutEnvironmentV
- _symbolic y_____SgcSg So6CGSizeV
CStrings:
+ "Banner ad collapsed by Ad Platforms after viewport update for placement=%{public}@, ad=%{public}@, host=%{public}@"
+ "Removing layout for placement=%{public}@"
+ "collapsed(contentInfo: "
```
