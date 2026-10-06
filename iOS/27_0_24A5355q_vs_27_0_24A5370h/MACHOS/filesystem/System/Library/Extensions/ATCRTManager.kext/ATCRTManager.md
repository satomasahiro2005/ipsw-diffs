## ATCRTManager

> `/System/Library/Extensions/ATCRTManager.kext/ATCRTManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x3e8c` | `0x3ea0` | **`+0x14`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`

### Other Changes

```diff

-3.0.0.0.0
+4.0.0.0.1
Functions:
~ __ZN12ATCRTManager5startEP9IOService : 2968 -> 2976
~ __ZN12ATCRTManager29processConnectionStateChangesEP8OSObjectP18IOTimerEventSource : 556 -> 568
~ __ZN12ATCRTManager32registerForTransportPublicationsEv : 316 -> 304
~ __ZN12ATCRTManager18transportPublishedEPvP9IOServiceP10IONotifier : 548 -> 536
~ __ZN12ATCRTManager16transportMessageEPvjP9IOServiceS0_m : 504 -> 488
~ __ZN12ATCRTManager4stopEP9IOService : 932 -> 972
```
