## Dendrite

> `/System/Library/PrivateFrameworks/Dendrite.framework/Dendrite`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70110` | `0x70898` | **`+0x788`** |
| `__TEXT.__cstring` | `0x2ae8` | `0x2b48` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x15cd` | `0x161b` | **`+0x4e`** |
| `__TEXT.__swift5_reflstr` | `0x10ac` | `0x10dc` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x5238` | `0x5260` | **`+0x28`** |
| `__DATA.__data` | `0x1020` | `0x1040` | **`+0x20`** |
| `__TEXT.__const` | `0x5370` | `0x5390` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1ed8` | `0x1ef8` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1828` | `0x1840` | **`+0x18`** |

### Other Changes

```diff

-6.7.0.0.0
+7.1.0.0.0

-  Functions: 2406
-  Symbols:   897
-  CStrings:  196
+  Functions: 2413
+  Symbols:   901
+  CStrings:  198
Symbols:
+ _symbolic _____ 8Dendrite24DataFrameStreamContainerV16SegmentSizeStateO
+ _symbolic _____11segmentSize_t s6UInt32V
+ _symbolic _____Sg20requestedSegmentSize_t s6UInt32V
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 8Dendrite24DataFrameStreamContainerV16SegmentSizeStateO
+ _symbolic _____y_____GSg 2os21OSAllocatedUnfairLockV 8Dendrite24DataFrameStreamContainerV16SegmentSizeStateO
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 8Dendrite24DataFrameStreamContainerV16SegmentSizeStateO So16os_unfair_lock_sV
- _symbolic _____ 8Dendrite24DataFrameStreamContainerV18ConfigurationStateO
- _symbolic _____Sg11segmentSize_t s6UInt32V
CStrings:
+ "error resolving segment size: "
+ "resolveSegmentSize(storageContainer:requestedSegmentSize:)"
```
