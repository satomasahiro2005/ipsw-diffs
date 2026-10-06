## AppPrivateData

> `/System/Library/PrivateFrameworks/AppPrivateData.framework/AppPrivateData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x88bd8` | `0x8898c` | **`-0x24c`** |
| `__TEXT.__swift5_typeref` | `0x113d` | `0x1161` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0xf60` | `0xf50` | **`-0x10`** |
| `__DATA.__data` | `0x2870` | `0x2868` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x530` | `0x528` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2158` | `0x2150` | **`-0x8`** |

### Other Changes

```diff

-  Functions: 2750
-  Symbols:   836
+  Functions: 2746
+  Symbols:   834
Symbols:
+ ___swift_closure_destructor.10Tm
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 14AppPrivateData15SerialTaskQueueC5State33_C1E5D1D11A005925A58CD418B277BFFCLLV
+ _symbolic _____y_____ySay_____yxGGGG 15Synchronization5MutexVAARi_zrlE 14AppPrivateData11MulticasterV AD0D10ZoneChangeO
+ _symbolic _____y_____yxGSgG 15Synchronization5MutexVAARi_zrlE 14AppPrivateData6ResultO
- ___swift_closure_destructor.11Tm
- _get_type_metadata 14AppPrivateData0B9ZoneModelRzl15Synchronization5MutexVyAA11MulticasterVySayAA0bD6ChangeOyxGGGG noncopyable
- _get_type_metadata 15Synchronization5MutexVy14AppPrivateData15SerialTaskQueueC5State33_C1E5D1D11A005925A58CD418B277BFFCLLVG noncopyable
- _get_type_metadata l15Synchronization5MutexVy14AppPrivateData6ResultOyxGSgG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
```
