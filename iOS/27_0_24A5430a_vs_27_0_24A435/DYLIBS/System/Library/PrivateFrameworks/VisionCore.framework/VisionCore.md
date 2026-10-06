## VisionCore

> `/System/Library/PrivateFrameworks/VisionCore.framework/VisionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x40720` | `0x40698` | **`-0x88`** |
| `__TEXT.__gcc_except_tab` | `0x409c` | `0x40a8` | **`+0xc`** |

### Other Changes

```diff

-  Functions: 1298
+  Functions: 1297
Functions:
~ __ZNSt3__16vectorImNS_9allocatorImEEE24__emplace_back_slow_pathIJmEEEPmDpOT_ : 184 -> 176
~ -[VisionCoreSparseOpticalFlowQuad generateGridKeypointsWithMaxKeypoints:minGridFrequency:] : 972 -> 980
~ -[VisionCoreSparseOpticalFlowSession updateMemoryKeypointsWithOpticalFlowResultsSourceBuffer:destBuffer:matchBuffer:start:] : 1188 -> 1196
~ __ZNSt3__16vectorIDhNS_9allocatorIDhEEE18__insert_with_sizeB9fqe220106INS_17_ClassicAlgPolicyENS_11__wrap_iterIPDhEES8_EES8_NS6_IPKDhEET0_T1_l : 540 -> 556
~ __ZNSt3__16vectorIiNS_9allocatorIiEEE24__emplace_back_slow_pathIJRiEEEPiDpOT_ : 184 -> 176
~ -[VisionCoreValueConfidenceCurve confidenceForValue:] : 196 -> 204
~ -[VisionCoreValueConfidenceCurve encodeWithCoder:] : 856 -> 868
- __ZNSt3__16vectorI30VisionCoreValueConfidencePointNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_
~ -[VisionCoreTensorStrides initWithShape:dataType:] : 632 -> 628
~ -[VisionCoreLKTSparseGPU _enqueueImagePyramidWithCommandBuffer:inputTexture:index:] : 648 -> 656
```
