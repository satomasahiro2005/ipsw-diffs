## libfaceCore.dylib

> `/System/Library/Frameworks/Vision.framework/libfaceCore.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__data` | `—` | `0x230` | **`+0x230`** |
| `__DATA_DIRTY.__data` | `0x230` | `—` | **`-0x230`** |
| `__TEXT.__text` | `0x58ebb8` | `0x58ea84` | **`-0x134`** |
| `__DATA_CONST.__got` | `0x140` | `0x148` | **`+0x8`** |

### Other Changes

```diff

-10.0.34.0.0
+10.0.37.0.0
Functions:
~ __ZNK5apple6vision9libraries8facecore10processing9detection11FaceManager10groupFacesERNSt3__16vectorINS2_12FaceInternalENS6_9allocatorIS8_EEEEiffi : 1356 -> 1360
~ __ZNSt3__134__uninitialized_allocator_relocateB9fqe220106INS_9allocatorIN5apple6vision9libraries8facecore12FaceInternalEEEPS6_EEvRT_T0_SB_SB_ : 160 -> 156
~ __ZNSt3__135__uninitialized_allocator_copy_implB9fqe220106INS_9allocatorIN5apple6vision9libraries8facecore12FaceInternalEEEPS6_S8_S8_EET2_RT_T0_T1_S9_ : 152 -> 136
~ __ZNKSt3__111__move_implINS_17_ClassicAlgPolicyEEclB9fqe220106IPN5apple6vision9libraries8facecore12FaceInternalES9_S9_EENS_4pairIT_T1_EESB_T0_SC_ : 192 -> 188
~ __ZN5apple6vision9libraries8facecore3mod15facerecognition23GradientLocalDescriptor19process_next_octaveEv : 396 -> 392
~ __ZN5apple6vision9libraries8facecore3mod9keypoints23KeypointLocalization_U814matrixMultiplyEPsS6_S6_S6_iii : 244 -> 236
~ __Z16deriche_gradientIfEvPKT_PS0_iificj : 1288 -> 1260
~ __ZN5apple6vision9libraries8facecore10processing9detection11FaceTracker8addFacesERNS2_15FaceCoreContextERNSt3__16vectorINS2_12FaceInternalENS8_9allocatorISA_EEEE : 1716 -> 1720
~ __ZNSt3__116__insertion_sortB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPN5apple6vision9libraries8facecore12FaceInternalEEEvT1_SB_T0_ : 640 -> 564
~ __ZNSt3__132__partition_with_equals_on_rightB9fqe220106INS_17_ClassicAlgPolicyEPN5apple6vision9libraries8facecore12FaceInternalERNS_6__lessIvvEEEENS_4pairIT0_bEESC_SC_T1_ : 772 -> 768
~ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPN5apple6vision9libraries8facecore12FaceInternalEEEbT1_SB_T0_ : 1048 -> 1000
~ __ZNSt3__119__partial_sort_implB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPN5apple6vision9libraries8facecore12FaceInternalESA_EET1_SB_SB_T2_OT0_ : 332 -> 316
~ __ZN5apple6vision9libraries8facecore10processing8tracking15keypointtracker14MatchingModule11findMatchesEiiiRi : 872 -> 792
~ __ZN5apple6vision9libraries8facecore3mod15facerecognition23GradientDenseDescriptor26ComputeFastDenseDescriptorEjjPdPhjjjj : 1372 -> 1368
~ __ZN5apple6vision9libraries8facecore5utils3aev18AEVHOG32Descriptor20computeHog32FeaturesEPfPiPS6_PS7_S7_i : 1560 -> 1708
~ __ZNSt3__134__uninitialized_allocator_relocateB9fqe220106INS_9allocatorIN5apple6vision9libraries8facecore4FaceEEEPS6_EEvRT_T0_SB_SB_ : 160 -> 156
~ __ZN5apple6vision9libraries8facecore3mod3aam9AamSearch20GetTextureParametersEi : 1168 -> 1152
~ __ZNSt3__116__insertion_sortB9fqe220106INS_17_ClassicAlgPolicyERPFbRKN5apple6vision9libraries8facecore12FaceInternalES8_EPS6_EEvT1_SD_T0_ : 632 -> 548
~ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERPFbRKN5apple6vision9libraries8facecore12FaceInternalES8_EPS6_EEbT1_SD_T0_ : 1188 -> 1136
~ __ZNSt3__135__uninitialized_allocator_copy_implB9fqe220106INS_9allocatorIN5apple6vision9libraries8facecore4FaceEEEPS6_S8_S8_EET2_RT_T0_T1_S9_ : 152 -> 136
```
