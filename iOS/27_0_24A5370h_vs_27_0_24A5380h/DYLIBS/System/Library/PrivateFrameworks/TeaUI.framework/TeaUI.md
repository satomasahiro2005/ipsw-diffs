## TeaUI

> `/System/Library/PrivateFrameworks/TeaUI.framework/TeaUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x360304` | `0x3607f0` | **`+0x4ec`** |
| `__DATA.__data` | `0x6080` | `0x5ef0` | **`-0x190`** |
| `__DATA_DIRTY.__data` | `0x11398` | `0x114e8` | **`+0x150`** |
| `__DATA_DIRTY.__objc_data` | `0x5b88` | `0x5c98` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x3875` | `0x3975` | **`+0x100`** |
| `__AUTH.__objc_data` | `0x4530` | `0x4438` | **`-0xf8`** |
| `__TEXT.__eh_frame` | `0x9b30` | `0x9a50` | **`-0xe0`** |
| `__TEXT.__swift5_typeref` | `0xd7dc` | `0xd87c` | **`+0xa0`** |
| `__DATA.__bss` | `0x19af0` | `0x19a70` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x8440` | `0x84c0` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x2d6c8` | `0x2d720` | **`+0x58`** |
| `__AUTH.__data` | `0x23e0` | `0x23a0` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x10f50` | `0x10f18` | **`-0x38`** |
| `__TEXT.__constg_swiftt` | `0x13c08` | `0x13c30` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x1a70` | `0x1a50` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x90f0` | `0x9110` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2e30` | `0x2e18` | **`-0x18`** |

### Other Changes

```diff

-1467.0.0.0.0
+1468.0.0.0.0

-  Functions: 31673
-  Symbols:   8234
-  CStrings:  1100
+  Functions: 31679
+  Symbols:   8230
+  CStrings:  1102
Symbols:
+ ___swift_closure_destructor.148Tm
+ ___swift_closure_destructor.251Tm
+ ___swift_closure_destructor.60Tm
+ ___swift_closure_destructor.76Tm
+ ___unnamed_29
+ ___unnamed_36
+ _symbolic _____ySDySSSay_____GGG 15Synchronization5MutexVAARi_zrlE 5TeaUI19CommandContextStoreC0F9ContainerV
+ _symbolic _____ySDySSSay_____GGG 15Synchronization5MutexVAARi_zrlE 5TeaUI20CommandStateObserverC
+ _symbolic _____ySDySSSay_____GGG 15Synchronization5MutexVAARi_zrlE 5TeaUI24CommandExecutionObserverC
+ _symbolic _____ySDySS_____GG 15Synchronization5MutexVAARi_zrlE 5TeaUI21CommandHandlerWrapper33_15CAAAE3F54018A7CB89109419CFFB47LLC
+ _symbolic _____ySay______pGG 15Synchronization5MutexVAARi_zrlE 5TeaUI23TipStorageMigrationTaskP
+ _symbolic _____ySay_____y_____GGG 15Synchronization5MutexVAARi_zrlE 13TeaFoundation4WeakC 0C2UI17ImageCacheRequest33_18B9CE531B3AA4CAC0CBCF0572522BF9LLC
+ _symbolic _____ySiG 15Synchronization6AtomicV
+ _symbolic _____ySo12NSCountedSetCG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____ySuG 15Synchronization6AtomicV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 5TeaUI17ImageCacheRequest33_18B9CE531B3AA4CAC0CBCF0572522BF9LLC5StateV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 5TeaUI25ImageCacheRequestPipeline33_18B9CE531B3AA4CAC0CBCF0572522BF9LLC5StateV
+ _symbolic _____yySScSgG 15Synchronization5MutexVAARi_zrlE
- ___swift_closure_destructor.12Tm
- ___swift_closure_destructor.145Tm
- ___swift_closure_destructor.248Tm
- ___swift_closure_destructor.61Tm
- ___swift_closure_destructor.77Tm
- ___unnamed_25
- ___unnamed_28
- ___unnamed_35
- _get_type_metadata 15Synchronization5MutexVy5TeaUI17ImageCacheRequest33_18B9CE531B3AA4CAC0CBCF0572522BF9LLC5StateVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy5TeaUI25ImageCacheRequestPipeline33_18B9CE531B3AA4CAC0CBCF0572522BF9LLC5StateVG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySS5TeaUI21CommandHandlerWrapper33_15CAAAE3F54018A7CB89109419CFFB47LLCGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySSSay5TeaUI19CommandContextStoreC0F9ContainerVGGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySSSay5TeaUI20CommandStateObserverCGGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySSSay5TeaUI24CommandExecutionObserverCGGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySay13TeaFoundation4WeakCy0C2UI17ImageCacheRequest33_18B9CE531B3AA4CAC0CBCF0572522BF9LLCGGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySay5TeaUI23TipStorageMigrationTask_pGG noncopyable
- _get_type_metadata 15Synchronization5MutexVyySScSgG noncopyable
- _get_type_metadata 15Synchronization6AtomicVySuG noncopyable
- _get_type_metadata l15Synchronization5MutexVySo12NSCountedSetCG noncopyable
- _get_type_metadata l15Synchronization6AtomicVySiG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "Card with view controller %@ is not yet presented, deferring dismiss to present completion, currently in state: %s and future state %s"
+ "Dismiss was requested during presentation for %@, dismissing now"
+ "Presented card with view controller: %@ to state %s, updatedDetent: %{bool}d, futurePresentationState: %s"
- "Presented card with view controller: %@ to state %s, updatedDetent: %{bool}d"
```
