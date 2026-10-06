## Scandium

> `/System/Library/PrivateFrameworks/Scandium.framework/Scandium`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x312e4` | `0x31398` | **`+0xb4`** |
| `__TEXT.__oslogstring` | `0xc70` | `0xcb3` | **`+0x43`** |
| `__AUTH_CONST.__auth_got` | `0x3f8` | `0x3f0` | **`-0x8`** |
| `__TEXT.__const` | `0x3b5c` | `0x3b64` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x2854` | `0x2850` | **`-0x4`** |

### Other Changes

```diff

-95.0.0.0.0
+96.0.0.0.0

-  Functions: 785
-  Symbols:   1233
-  CStrings:  497
+  Functions: 786
+  Symbols:   1232
+  CStrings:  498
Symbols:
- __ZNSt3__16__sortIRNS_6__lessIffEEPfEEvT0_S5_T_
Functions:
~ __ZN8Scandium11sort_medianEPKfi : 420 -> 424
~ __ZN8Scandium11ScandiumPPG19calc_ppg_ac_metricsEPKfiPfS3_ : 708 -> 744
~ __ZN8Scandium11ScandiumPPG25scandium_spo2_processor_t11compute_ppgEv : 668 -> 732
~ __ZN8Scandium11ScandiumPPG25scandium_spo2_processor_t11compute_bgaERNS0_7beats_tE : 2260 -> 2268
+ __ZN8Scandium11ScandiumPPG25scandium_spo2_processor_t11compute_ppgEv.cold.1
CStrings:
+ "scandium green average: green_divisor is zero, no valid green path"
```
