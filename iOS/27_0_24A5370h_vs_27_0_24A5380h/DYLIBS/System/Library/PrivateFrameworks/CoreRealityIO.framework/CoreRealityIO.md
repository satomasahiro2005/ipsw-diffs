## CoreRealityIO

> `/System/Library/PrivateFrameworks/CoreRealityIO.framework/CoreRealityIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c5aa4` | `0x2c4e78` | **`-0xc2c`** |
| `__TEXT.__gcc_except_tab` | `0x36024` | `0x360c0` | **`+0x9c`** |
| `__TEXT.__oslogstring` | `0x3e27` | `0x3e74` | **`+0x4d`** |
| `__TEXT.__cstring` | `0x114b6` | `0x114fb` | **`+0x45`** |
| `__DATA_CONST.__objc_selrefs` | `0x3f8` | `0x408` | **`+0x10`** |

### Other Changes

```diff

-235.0.2.0.0
+235.0.3.0.0

-  Functions: 13379
-  Symbols:   21050
-  CStrings:  2169
+  Functions: 13381
+  Symbols:   21052
+  CStrings:  2176
Symbols:
+ __ZN12_GLOBAL__N_122getSamplerMinMagFilterEN32pxrInternal__aapl__pxrReserved__7TfTokenE
+ __ZN12_GLOBAL__N_122getSamplerMinMagFilterERN32pxrInternal__aapl__pxrReserved__12UsdAttributeE
+ __ZN12_GLOBAL__N_126samplerForTextureAttributeEN32pxrInternal__aapl__pxrReserved__7TfTokenES1_S1_S1_
+ __ZN12_GLOBAL__N_133uvNameAndTransformForTextureInputERKNSt3__13mapIN32pxrInternal__aapl__pxrReserved__7TfTokenENS2_7VtValueENS0_4lessIS3_EENS0_9allocatorINS0_4pairIKS3_S4_EEEEEES3_RNS0_12basic_stringIcNS0_11char_traitsIcEENS7_IcEEEERDv4_fRDv2_fRS3_SP_SP_SP_
- __ZN12_GLOBAL__N_126samplerForTextureAttributeEN32pxrInternal__aapl__pxrReserved__7TfTokenES1_
- __ZN12_GLOBAL__N_133uvNameAndTransformForTextureInputERKNSt3__13mapIN32pxrInternal__aapl__pxrReserved__7TfTokenENS2_7VtValueENS0_4lessIS3_EENS0_9allocatorINS0_4pairIKS3_S4_EEEEEES3_RNS0_12basic_stringIcNS0_11char_traitsIcEENS7_IcEEEERDv4_fRDv2_fRS3_SP_
CStrings:
+ "MinMag filter for imported USD was an invalid option; defaulting to \"linear\""
+ "inputs:magFilter"
+ "inputs:minFilter"
+ "linear"
+ "magFilter"
+ "minFilter"
+ "nearest"
```
