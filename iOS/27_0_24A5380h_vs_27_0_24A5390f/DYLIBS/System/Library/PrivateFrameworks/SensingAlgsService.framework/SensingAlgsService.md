## SensingAlgsService

> `/System/Library/PrivateFrameworks/SensingAlgsService.framework/SensingAlgsService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20d88` | `0x210d0` | **`+0x348`** |
| `__AUTH_CONST.__const` | `0x20c0` | `0x20f8` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x17b4` | `0x1796` | **`-0x1e`** |
| `__TEXT.__const` | `0x1ccb` | `0x1cdb` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xe7c` | `0xe88` | **`+0xc`** |
| `__TEXT.__cstring` | `0x3de` | `0x3df` | **`+0x1`** |

### Other Changes

```diff

-68.0.0.0.0
+70.0.0.0.0

-  Symbols:   1408
+  Symbols:   1413
Symbols:
+ GCC_except_table35
+ __ZN13PlainDataNodeIfED0Ev
+ __ZN13PlainDataNodeIfED1Ev
+ __ZNK13PlainDataNodeIfE12sendCallbackEPFvRK22AlgDataCallbackContentERS1_
+ __ZTV13PlainDataNodeIfE
Functions:
~ __ZN12TouchService22TouchServiceActivePlan17runBeforeChildrenEv : 528 -> 540
~ __ZN13PalmRejection17PalmRejectionTaskC2ER13PlainDataNodeIbERK9TimeStateRKS1_INS_17PalmRejectionInfoEERN12TouchService19PlainPathCollectionERKS1_I18PalmRejSurfaceInfoERK20SA1DArrayDynamicSizeIfESL_ : 2064 -> 2268
~ __ZN13PalmRejection17PalmRejectionTask20runNodeRegistrationsEv : 468 -> 500
~ __ZN28SA2DArrayDynamicSizeWithSyncIfED1Ev -> __ZN27InterpolationParamsDataNodeD1Ev : 4 -> 32
~ __ZN27InterpolationParamsDataNodeD1Ev -> __ZN28SA2DArrayDynamicSizeWithSyncIfED1Ev : 32 -> 4
~ __ZN13PalmRejection17PalmRejectionTask16runAfterChildrenEv : 936 -> 1092
~ __ZN13PalmRejection17PalmRejectionTaskD2Ev : 400 -> 448
~ __ZN13PlainDataNodeIN13PalmRejection17PalmRejTaskParamsEEC2Ey9MemType_tb : 1104 -> 1108
~ __ZN13PalmRejection40CalculateMetaClassifierProbabilitiesStep3runEv : 2072 -> 2128
~ __ZN13PalmRejection27GetClusterLevelFeaturesStep3runEv : 3120 -> 3164
~ __ZN13PalmRejection31UpdatePalmRejectionFeaturesStep24calculatePathProbabilityERNS_11PmRjPathTrkEt : 1824 -> 1892
~ __ZN13PalmRejection28UpdatePathAssignedFingerStep3runEv : 572 -> 604
~ __ZN13PalmRejection34UpdateTouchHoverDetectionFlagsStep3runEv : 264 -> 272
~ __ZN13PalmRejection33DetermineClustersForRejectionStep3runEv : 2088 -> 2052
~ __ZN13PalmRejection20ParseContactDataStep30updatePathCollectionAndExtremaEv : 564 -> 608
~ __ZN13PalmRejection20ParseContactDataStep21detectPathTransitionsERNS_11PmRjPathTrkE : 152 -> 160
~ __ZN13PalmRejection20ParseContactDataStep20detectAndSetPathMakeERNS_11PmRjPathTrkE : 76 -> 84
~ __ZN13PalmRejection35ClusterWithGaussianMixtureModelStep21GMMPathInitializationENS_12DistToWeightE : 572 -> 596
~ __ZN13PalmRejection35ClusterWithGaussianMixtureModelStep27GMMClusterCovInitializationEt : 404 -> 444
~ __ZN13PalmRejection35ClusterWithGaussianMixtureModelStep35populateAllPathGMMCovarianceObjectsEv : 236 -> 268
~ __ZN13PalmRejection35ClusterWithGaussianMixtureModelStep25updateClusterCovColLogDetERNS_16GMMCovCollectionE : 104 -> 132
~ __ZN13PalmRejection35ClusterWithGaussianMixtureModelStep12swapAndScoreERNS_20GMMClusterCollectionERKS1_RKNS_11PmRjPathTrkE : 528 -> 556
CStrings:
+ "21.0.0 (clang-2100.3.27.1) [+internal-os]"
+ "24A5380i"
+ "Edge grip (per-path): path %d mindist=%.0f pencil_cos=%.4f touch_seen_pencil=%.4f\n"
+ "SensingAlgsService-70~23"
- "21.0.0 (clang-2100.3.25.1) [+internal-os]"
- "24A375"
- "Edge grip (per-path): path %d mindist=%.0f pencil_cos=%.4f touch_seen_pencil=%.4f -> marking cluster %d as palm\n"
- "SensingAlgsService-68~214"
```
