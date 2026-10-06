## ServicesIntelligence

> `/System/Library/PrivateFrameworks/ServicesIntelligence.framework/ServicesIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c3714` | `0x1cb6e8` | **`+0x7fd4`** |
| `__TEXT.__eh_frame` | `0x17588` | `0x17bb0` | **`+0x628`** |
| `__TEXT.__unwind_info` | `0x8700` | `0x8c98` | **`+0x598`** |
| `__AUTH_CONST.__const` | `0x11f48` | `0x12130` | **`+0x1e8`** |
| `__TEXT.__const` | `0x1ee98` | `0x1efa8` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x6f7e` | `0x6e9e` | **`-0xe0`** |
| `__TEXT.__swift5_capture` | `0xe0c` | `0xeb8` | **`+0xac`** |
| `__TEXT.__swift_as_cont` | `0x157c` | `0x1614` | **`+0x98`** |
| `__DATA_DIRTY.__data` | `0xef0` | `0xf48` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x16f8` | `0x1748` | **`+0x50`** |
| `__DATA.__data` | `0x4750` | `0x47a0` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x549f` | `0x54e1` | **`+0x42`** |
| `__TEXT.__cstring` | `0x5793` | `0x5753` | **`-0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x5ee4` | `0x5f20` | **`+0x3c`** |
| `__TEXT.__swift_as_ret` | `0x9ec` | `0xa28` | **`+0x3c`** |
| `__TEXT.__constg_swiftt` | `0x4804` | `0x4834` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x3303` | `0x3333` | **`+0x30`** |
| `__AUTH.__data` | `0x1588` | `0x15b0` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x11e0` | `0x11c8` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3f0` | `0x408` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x55c` | `0x574` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x98` | `0xa8` | **`+0x10`** |

### Other Changes

```diff

-1.53.0.0.0
+1.60.0.0.0

-  Functions: 9476
-  Symbols:   2620
-  CStrings:  975
+  Functions: 9584
+  Symbols:   2628
+  CStrings:  974
Symbols:
+ _NSFileProtectionCompleteUnlessOpen
+ __IVARS__TtCC20ServicesIntelligence10FitnessXPC6Server
+ __IVARS__TtCCC20ServicesIntelligence10FitnessXPC6Server14SessionHandler
+ ___swift_memcpy42_8
+ _objc_retain_x28
+ _swift_retain_x1
+ _symbolic IeghH_
+ _symbolic _____ySay_____GG s23_ContiguousArrayStorageC 20ServicesIntelligence13InferenceDataO
+ _symbolic _____y_____G s11_SetStorageC 20ServicesIntelligence6DomainO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 20ServicesIntelligence13InferenceDataO
+ _symbolic ytIeghHr_
+ _symbolic yyYaYbcSg
- _objc_retain_x24
- _swift_release_x11
- _swift_retain_x27
- _symbolic ScGyytG
CStrings:
+ " PRIMARY KEY AUTOINCREMENT"
+ "B"
+ "No inference task found in workflow for use case: "
+ "[AccountContext] No signed-in user, skipping"
+ "[AccountContext] dsid=%{public}s, storefront=%{public}s, personalization=%{public}s, isU18=%{public}s"
+ "[KVDatabaseClient][getAllKeys] Failed: "
+ "[KVDatabaseClient][getRawData] Failed: "
+ "] Hello from Apple SId Fitness version 14!"
+ "accountContext.check"
+ "expirationTime > "
+ "expirationTime IS NULL"
- "Failed to decode response data to RunInferenceResponse"
- "Failed to encode RunInferenceRequest to JSON."
- "[AccountContext][reconcile] No signed-in user, skipping"
- "[AccountContext][reconcile] dsid=%{public}s, storefront=%{public}s, personalization=%{public}s, isU18=%{public}s"
- "[AccountContext][reconcile] externalSync failed (continuing with cached): %{public}@"
- "[AccountContext][reconcile] externalSync timed out after %{public}s; continuing with cached"
- "[MLInferenceClient][run] Encoding input data"
- "[MLInferenceClient][run] Failed to decode output data"
- "[MLInferenceClient][run] Failed to encode input data"
- "] Hello from Apple SId Fitness version 13!"
- "accountContext.reconcile"
- "pushNotification"
```
