## libSystemDetermination.dylib

> `/System/Library/Frameworks/CoreTelephony.framework/Support/libSystemDetermination.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f278` | `0x6f654` | **`+0x3dc`** |
| `__TEXT.__oslogstring` | `0x9ced` | `0x9d41` | **`+0x54`** |
| `__TEXT.__gcc_except_tab` | `0x5944` | `0x597c` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x920` | `0x940` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3691` | `0x36a3` | **`+0x12`** |
| `__AUTH_CONST.__const` | `0x4a50` | `0x4a60` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2408` | `0x2418` | **`+0x10`** |

### Other Changes

```diff

-13473.1.0.0.0
+13478.3.1.3.0

-  Functions: 1796
-  Symbols:   2961
-  CStrings:  1450
+  Functions: 1798
+  Symbols:   2959
+  CStrings:  1453
Symbols:
+ GCC_except_table173
+ __ZN2sd23RCSSubscriberController26startImsEstablishmentTimerEj
+ __ZNK2sd18IMSSubscriberModel25isLazuliManagedConnectionEv
+ __ZNK2sd19IMSSubscriberConfig31getRCSManagedConnectionOverrideEv
+ __ZNK2sd27IMSSubscriberControllerBase19isManagedConnectionEv
+ __ZThn48_NK2sd27IMSSubscriberControllerBase19isManagedConnectionEv
- GCC_except_table105
- GCC_except_table167
- GCC_except_table169
- GCC_except_table88
- GCC_except_table95
- __ZN2sd23RCSSubscriberController26startImsEstablishmentTimerEv
- __ZNK2sd27IMSSubscriberControllerBase20isLazuliCarrierBasedEv
- __ZThn48_NK2sd27IMSSubscriberControllerBase20isLazuliCarrierBasedEv
CStrings:
+ "ImsEstablishmentTimer: Starting RCS Establishment timer: %u + %u seconds"
+ "ManagedConnection"
+ "getRCSManagedConnection %{bool}d"
+ "getRCSManagedConnection: Null PersonalityShop"
- "ImsEstablishmentTimer: Starting RCS Establishment timer: %u seconds"
```
