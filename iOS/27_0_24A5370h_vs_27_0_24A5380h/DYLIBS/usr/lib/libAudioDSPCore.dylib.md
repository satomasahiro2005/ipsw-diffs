## libAudioDSPCore.dylib

> `/usr/lib/libAudioDSPCore.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5e29c` | `0x5e1ec` | **`-0xb0`** |

### Other Changes

```diff

-881.104.0.0.0
+881.108.0.0.0
Functions:
~ __ZN8AudioDSP4Core34GetAudioChannelLayoutTagFromStringENSt3__117basic_string_viewIcNS1_11char_traitsIcEEEE : 1248 -> 1216
~ __ZNSt3__16vectorIN2IR15FFTFilterKernelIfEENS_9allocatorIS3_EEE6resizeEm : 488 -> 468
~ __ZN2IR18FFTFilterTranspose14Implementation10initializeEjjjbjjbbb : 2348 -> 2344
~ __ZN2IR6IRData14Implementation19createSizeDimensionERKNSt3__16vectorIfNS2_9allocatorIfEEEEN10applesauce2CF8ArrayRefENS_21DynamicSizeDesignGridE : 5124 -> 5116
~ __ZN2IR6IRData14Implementation31createSerializedIRDataWithNoiseEPK8__CFData : 3724 -> 3736
~ __ZN2IR6IRData14Implementation21generatePanningIRDataEjfbii : 7932 -> 7900
~ __ZN2IR22HOA2BinauralIRRenderer7processEPKPfjjfffNS_13IRCoordinatesE : 2348 -> 2352
~ __ZN2IR22HOA2BinauralIRRenderer25extractSubNodesFromIRTreeERNSt3__16vectorINS_13IRCoordinatesENS1_9allocatorIS3_EEEERKNS_16IRCoordinateTreeES3_b : 536 -> 540
~ __ZNSt3__16vectorINS_4listIiNS_9allocatorIiEEEENS2_IS4_EEE6resizeEm : 568 -> 528
~ __ZN2IR6IRData14Implementation21initVBAPTriangulationERKNSt3__16vectorINS3_IiNS2_9allocatorIiEEEENS4_IS6_EEEERKNS3_INS3_INS2_4listIiS5_EENS4_ISC_EEEENS4_ISE_EEEEb : 6232 -> 6220
~ __ZNKSt3__113__string_hashIcNS_9allocatorIcEEEclB9foe220106ERKNS_12basic_stringIcNS_11char_traitsIcEES2_EE : 1092 -> 1080
~ __ZNSt3__16vectorIN2IR15FFTFilterKernelIDF16_EENS_9allocatorIS3_EEE6resizeEm : 488 -> 468
~ __ZN4VBAP21delaunayTriangulationERKNSt3__16vectorIfNS0_9allocatorIfEEEERKNS1_IiNS2_IiEEEERKNS1_INS0_4listIiS7_EENS2_ISC_EEEE : 16204 -> 16196
~ __ZN4VBAP35calculateVirtualLoudspeakersPolygonERKNSt3__16vectorIfNS0_9allocatorIfEEEERNS1_IS4_NS2_IS4_EEEERNS1_INS1_IjNS2_IjEEEENS2_ISB_EEEE : 4804 -> 4796
```
