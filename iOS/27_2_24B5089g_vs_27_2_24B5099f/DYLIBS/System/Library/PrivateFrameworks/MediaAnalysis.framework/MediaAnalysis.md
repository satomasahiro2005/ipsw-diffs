## MediaAnalysis

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/MediaAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x1eb80` | `0x1ed60` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x2cd21` | `0x2cef1` | **`+0x1d0`** |
| `__DATA_CONST.__const` | `0x7c18` | `0x7c90` | **`+0x78`** |
| `__TEXT.__text` | `0x4d1bec` | `0x4d1c0c` | **`+0x20`** |

### Other Changes

```diff

-460.8.2.0.0
+460.12.1.0.0

-  Symbols:   28613
-  CStrings:  9018
+  Symbols:   28628
+  CStrings:  9033
Symbols:
+ _VCPAnalyticsField17246HKSVProcessingConsecutiveIndex
+ _VCPAnalyticsField17246HKSVProcessingCountPreviousRequestsPendingWhenAdmitted
+ _VCPAnalyticsField17246HKSVProcessingDidGlobalLastClipIDMismatchPredecessor
+ _VCPAnalyticsField17246HKSVProcessingDidLapseConsecutiveWindow
+ _VCPAnalyticsField17246HKSVProcessingFragmentTotalDurationMilliseconds
+ _VCPAnalyticsField17246HKSVProcessingPendingPredecessorElapsedMilliseconds
+ _VCPAnalyticsField17246HKSVProcessingPreviousConsecutiveStatus
+ _VCPAnalyticsFieldNumberOfAssetsThumbnailSufficient
+ _VCPAnalyticsFieldNumberOfAssetsThumbnailTooSmall
+ _VCPAnalyticsFieldTimeFetchingFullInSeconds
+ _VCPAnalyticsFieldTimeFetchingGatingInSeconds
+ _VCPAnalyticsFieldTimePreparingFullInSeconds
+ _VCPAnalyticsFieldTimePreparingGatingInSeconds
+ _VCPAnalyticsFieldTimePublishingFullInSeconds
+ _VCPAnalyticsFieldTimePublishingGatingInSeconds
Functions:
~ -[MADAlchemistAnalzyer convertHeadroom:forImage:] : 376 -> 392
~ _VCPVersionForTask : 332 -> 340
~ __ZNKSt3__114default_deleteIN13sentencepiece4util6Status3RepEEclB9fqe220106EPS4_ : 92 -> 100
CStrings:
+ "ConsecutiveIndex"
+ "CountPreviousRequestsPendingWhenAdmitted"
+ "DidGlobalLastClipIDMismatchPredecessor"
+ "DidLapseConsecutiveWindow"
+ "FragmentTotalDurationMilliseconds"
+ "NumberOfAssetsThumbnailSufficient"
+ "NumberOfAssetsThumbnailTooSmall"
+ "PendingPredecessorElapsedMilliseconds"
+ "PreviousConsecutiveStatus"
+ "TimeFetchingFullInSeconds"
+ "TimeFetchingGatingInSeconds"
+ "TimePreparingFullInSeconds"
+ "TimePreparingGatingInSeconds"
+ "TimePublishingFullInSeconds"
+ "TimePublishingGatingInSeconds"
```
