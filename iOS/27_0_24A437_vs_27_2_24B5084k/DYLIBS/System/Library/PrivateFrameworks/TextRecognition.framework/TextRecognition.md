## TextRecognition

> `/System/Library/PrivateFrameworks/TextRecognition.framework/TextRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x213d58` | `0x2135d0` | **`-0x788`** |
| `__TEXT.__gcc_except_tab` | `0x116ec` | `0x11678` | **`-0x74`** |
| `__TEXT.__unwind_info` | `0x8528` | `0x84f8` | **`-0x30`** |

### Other Changes

```diff

-446.13.100.0.0
+446.13.101.0.0

-  Functions: 8699
-  Symbols:   8801
+  Functions: 8697
+  Symbols:   8800
Symbols:
+ GCC_except_table101
+ GCC_except_table108
+ GCC_except_table111
+ GCC_except_table80
+ GCC_except_table86
+ __ZN17CRTextRecognition6CRCTLD17CTLDPriorityQueue4pushEONS0_8CTLDNodeE
+ __ZN17CRTextRecognition6CRCTLD34CRConstrainedTextLineDetectionImpl13getSubregionsERKNS0_7CTLDBoxERKNS0_10CTLDRegionERNSt3__15arrayIS2_Lm4EEE
+ __ZN17CRTextRecognition6CRCTLD34CRConstrainedTextLineDetectionImpl16getRegionQualityERKNS0_7CTLDBoxE
+ __ZN17CRTextRecognition6CRCTLD34CRConstrainedTextLineDetectionImpl24getIntersectingObstaclesERKNS0_7CTLDBoxERKNSt3__16vectorINS0_12CTLDObstacleENS5_9allocatorIS7_EEEE
+ __ZNK17CRTextRecognition6CRCTLD34CRConstrainedTextLineDetectionImpl30distanceBetweenCenterOfRegionsERKNS0_10CTLDRegionERKNS0_7CTLDBoxE
+ __ZNSt3__16vectorIN17CRTextRecognition6CRCTLD12CTLDObstacleENS_9allocatorIS3_EEE7reserveEm
+ __ZNSt3__16vectorIN17CRTextRecognition6CRCTLD8CTLDNodeENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJS3_EEEPS3_DpOT_
+ __ZNSt3__16vectorIN17CRTextRecognition6CRCTLD8CTLDNodeENS_9allocatorIS3_EEE8pop_backB9fqe220106Ev
- GCC_except_table104
- GCC_except_table109
- GCC_except_table131
- GCC_except_table92
- __ZN17CRTextRecognition6CRCTLD17CTLDPriorityQueue4pushERNS0_8CTLDNodeE
- __ZN17CRTextRecognition6CRCTLD34CRConstrainedTextLineDetectionImpl13getSubregionsERKNS0_10CTLDRegionES4_
- __ZN17CRTextRecognition6CRCTLD34CRConstrainedTextLineDetectionImpl16getRegionQualityERKNS0_10CTLDRegionE
- __ZN17CRTextRecognition6CRCTLD34CRConstrainedTextLineDetectionImpl24getIntersectingObstaclesERKNS0_10CTLDRegionERKNSt3__16vectorINS0_12CTLDObstacleENS5_9allocatorIS7_EEEE
- __ZN17CRTextRecognition6CRCTLD8CTLDNodeD1Ev
- __ZNSt3__116allocator_traitsINS_9allocatorIN17CRTextRecognition6CRCTLD8CTLDNodeEEEE7destroyB9fqe220106IS4_Li0EEEvRS5_PT_
- __ZNSt3__16vectorIN17CRTextRecognition6CRCTLD10CTLDRegionENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJRKfS9_S9_S9_EEEPS3_DpOT_
- __ZNSt3__16vectorIN17CRTextRecognition6CRCTLD12CTLDObstacleENS_9allocatorIS3_EEE16__init_with_sizeB9fqe220106IPS3_S8_EEvT_T0_m
- __ZNSt3__16vectorIN17CRTextRecognition6CRCTLD8CTLDNodeENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJRS3_EEEPS3_DpOT_
- __ZNSt3__16vectorIN17CRTextRecognition6CRCTLD8CTLDNodeENS_9allocatorIS3_EEE30__emplace_back_assume_capacityB9fqe220106IJRS3_EEEvDpOT_
```
