## CoreNavigation

> `/System/Library/PrivateFrameworks/CoreNavigation.framework/CoreNavigation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x362bb8` | `0x361f64` | **`-0xc54`** |
| `__TEXT.__gcc_except_tab` | `0x167d8` | `0x16768` | **`-0x70`** |
| `__TEXT.__const` | `0x52011` | `0x51fb1` | **`-0x60`** |
| `__TEXT.__cstring` | `0x38344` | `0x3839c` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0xed20` | `0xecf8` | **`-0x28`** |

### Other Changes

```diff

-423.0.0.0.0
+425.0.0.0.0

-  Functions: 15563
-  Symbols:   13565
-  CStrings:  3915
+  Functions: 15553
+  Symbols:   13563
+  CStrings:  3917
Symbols:
+ __ZN5cndft10SlidingDFT9AddSampleEdd
+ __ZNK5cndft10SlidingDFT13GetCurrentDFTEv
- __ZN5cndft10SlidingDFT9AddSampleEd
- __ZN5cndft10SlidingDFTC1Ev
- __ZN5cndft10SlidingDFTC2Ev
- __ZNK5cndft10SlidingDFTixEj
CStrings:
+ "gnss_preprocessor_avg_doppler_min_unc_mps"
+ "gnss_preprocessor_disable_avg_doppler_when_driving"
```
