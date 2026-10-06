## PHASE

> `/System/Library/Frameworks/PHASE.framework/PHASE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x252438` | `0x252a58` | **`+0x620`** |
| `__TEXT.__oslogstring` | `0x21c4d` | `0x21da3` | **`+0x156`** |
| `__TEXT.__gcc_except_tab` | `0x26820` | `0x268b8` | **`+0x98`** |
| `__TEXT.__realtime` | `0x17114` | `0x17198` | **`+0x84`** |
| `__TEXT.__unwind_info` | `0xc480` | `0xc4a8` | **`+0x28`** |
| `__TEXT.__cstring` | `0x16384` | `0x163a9` | **`+0x25`** |
| `__AUTH_CONST.__cfstring` | `0x5e20` | `0x5e40` | **`+0x20`** |
| `__TEXT.__const` | `0x47b0c` | `0x47b2c` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x6b8` | `0x6d0` | **`+0x18`** |

### Other Changes

```diff

-396.0.0.0.0
+399.0.0.0.0

-  Functions: 9884
-  Symbols:   13640
-  CStrings:  4590
+  Functions: 9894
+  Symbols:   13652
+  CStrings:  4595
Symbols:
+ GCC_except_table126
+ __ZN5Phase14SpatialModeler12ERClusteringL30GenerateFadingSourceERMetadataEyRKNS0_20SourceListenerResultERKNS0_14RayTracerStateEdmRNS0_25DirectionalMetadataOutputIfEERNS_6VectorIfLm2EEE
+ __ZN5Phase14SpatialModeler30BroadBandScaleMetadataSubbandsIfEEvRNS0_25DirectionalMetadataOutputIT_EERKf
+ __ZNSt3__110__function12__value_funcIFbRKN2CA13ChannelLayoutEbNS_4spanIfLm18446744073709551615EEEEEaSB9nqe220106EDn
+ __ZNSt3__110__function12__value_funcIFbRKN2CA13ChannelLayoutEbNS_4spanIfLm18446744073709551615EEEEEaSB9nqe220106EOS9_
+ __ZNSt3__116allocator_traitsINS_9allocatorIN5Phase14SpatialModeler25DirectionalMetadataOutputIfEEEEE9constructB9nqe220106IS5_JS5_ELi0EEEvRS6_PT_DpOT0_
+ __ZNSt3__134__uninitialized_allocator_relocateB9nqe220106INS_9allocatorIN5Phase14SpatialModeler25DirectionalMetadataOutputIfEEEEPS5_EEvRT_T0_SA_SA_
+ __ZNSt3__16vectorIN5Phase14SpatialModeler20SourcePreProcessData13PerSourceDataENS_9allocatorIS4_EEE20__throw_length_errorB9nqe220106Ev
+ __ZNSt3__16vectorIN5Phase14SpatialModeler25DirectionalMetadataOutputIfEENS_9allocatorIS4_EEE20__throw_length_errorB9nqe220106Ev
+ __ZNSt3__16vectorIN5Phase14SpatialModeler25DirectionalMetadataOutputIfEENS_9allocatorIS4_EEE24__emplace_back_slow_pathIJS4_EEEPS4_DpOT_
+ __ZNSt3__16vectorIN5Phase14SpatialModeler25DirectionalMetadataOutputIfEENS_9allocatorIS4_EEE9push_backB9nqe220106EOS4_
+ __ZNSt3__19allocatorIN5Phase14SpatialModeler20SourcePreProcessData13PerSourceDataEE17allocate_at_leastB9nqe220106Em
+ __ZNSt3__19allocatorIN5Phase14SpatialModeler25DirectionalMetadataOutputIfEEE17allocate_at_leastB9nqe220106Em
- GCC_except_table127
CStrings:
+ "%25s:%-5d [ER_ENERGY_DEBUG] AggregateER src=%llu NAR=%.1f coeffs: b0=%.4f a1=%.4f (minPseudo=%.1f)"
+ "%25s:%-5d [ER_ENERGY_DEBUG] FindERClusters active=%zu fading=%zu numClusters=%u"
+ "%25s:%-5d [ER_ENERGY_DEBUG] HandleResultsER clusterKey=%llu found=%d numClusters=%zu"
+ "%25s:%-5d [ER_ENERGY_DEBUG] ProcessSourcesForClustering active=%zu fading=%zu"
+ "phase_enable_er_energy_debug_logging"
```
