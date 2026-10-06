## libAppleEXR.dylib

> `/usr/lib/libAppleEXR.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa02ec` | `0xa16fc` | **`+0x1410`** |
| `__TEXT.__cstring` | `0x456f` | `0x469c` | **`+0x12d`** |
| `__TEXT.__unwind_info` | `0x828` | `0x830` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x4e0` | `0x4e4` | **`+0x4`** |

### Other Changes

```diff

-1006.0.0.0.0
+1010.0.0.0.0

-  Functions: 730
-  Symbols:   936
-  CStrings:  450
+  Functions: 733
+  Symbols:   939
+  CStrings:  452
Symbols:
+ __ZN14AXRChunkHeader11GetMipLevelE11ChunkLayout
+ __ZN4Part11InitOffsetsEPKvmRmm11axr_flags_t
+ __ZNK15TileDecoder_B4426HasSubsampledPartialBlocksEv
+ __ZNK4Part20CheckChunkPartNumberEPKvmmm11axr_flags_t
+ __ZZN4Part11InitOffsetsEPKvmRmm11axr_flags_tE13kRowSizeProcs
- __ZN4Part11InitOffsetsEPKvmRm11axr_flags_t
- __ZZN4Part11InitOffsetsEPKvmRm11axr_flags_tE13kRowSizeProcs
CStrings:
+ "%s error: expected rowBytes for channel size (%lu) x RGBA channel count (%lu) x width (%u) = %lu bytes\n\tThe provided destination row bytes is only %lu and the data will not fit.\n\tSkipping operation."
+ "EXR File corrupted: chunk appears in the offset table for part %lu, but reports it belongs to part %d"
```
