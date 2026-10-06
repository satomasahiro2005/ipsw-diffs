## CardioHealth

> `/System/Library/PrivateFrameworks/CardioHealth.framework/CardioHealth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd27c` | `0xd3d0` | **`+0x154`** |
| `__TEXT.__oslogstring` | `0x25ac` | `0x265a` | **`+0xae`** |
| `__TEXT.__const` | `0x550` | `0x564` | **`+0x14`** |
| `__TEXT.__gcc_except_tab` | `0x3ac` | `0x39c` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2a8` | `0x2a0` | **`-0x8`** |

### Other Changes

```diff

-3185.0.6.0.3
+3186.0.12.0.0

-  Functions: 103
-  Symbols:   86
-  CStrings:  94
+  Functions: 105
+  Symbols:   88
+  CStrings:  96
Symbols:
+ __ZN17CHVO2MaxEstimator20setHRConfidenceScaleE23VO2MaxHRConfidenceScale
+ __ZN17CHVO2MaxEstimator34setMinPointsToTrustClusterOverrideEd
CStrings:
+ "Overriding minPointsToTrustCluster,default,%f,override,%f"
+ "VO2Max HR confidence scale set: scale,%{public}d"
+ "VO2Max InsufficientSamplesForClustering, Only %{public}zu of %{public}zu samples usable, need %{public}zu minimum - clusteringMode=%{public}d"
+ "VO2Max deriveStageBasedClusters failed: inputSize=%zu, highConfidenceInputs=%zu, hrConfScale=%{public}d, hrConfThreshold=%{public}.4f"
- "VO2Max InsufficientSamplesForClustering, Only %{public}zu samples provided, need %{public}zu minimum - clusteringMode=%{public}d"
- "VO2Max deriveStageBasedClusters failed: inputSize=%zu, highConfidenceInputs=%zu"
```
