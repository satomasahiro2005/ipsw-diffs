## ImmersiveMediaSupport

> `/System/Library/Frameworks/ImmersiveMediaSupport.framework/ImmersiveMediaSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17eefc` | `0x17d888` | **`-0x1674`** |
| `__TEXT.__const` | `0x1c528` | `0x1c628` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x37dc` | `0x36fc` | **`-0xe0`** |
| `__AUTH.__data` | `0x8be8` | `0x8c28` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x6d0c` | `0x6d3c` | **`+0x30`** |
| `__DATA.__bss` | `0x1cb30` | `0x1cb58` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x23110` | `0x23130` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x4e6e` | `0x4e8e` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x62e0` | `0x62f8` | **`+0x18`** |
| `__DATA.__data` | `0x3dc8` | `0x3dd8` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0xa284` | `0xa294` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x56a4` | `0x56b0` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xc00` | `0xbf8` | **`-0x8`** |

### Other Changes

```diff

-124.0.1.0.0
+124.0.3.0.0

-  Functions: 8314
-  Symbols:   4307
-  CStrings:  1331
+  Functions: 8329
+  Symbols:   4305
+  CStrings:  1327
Symbols:
- ___divti3
- _kCMTimeIndefinite
CStrings:
+ "Clipped metadata item at start %f end %f has timescale mismatch — original: %d, clippedStart: %d, clippedEnd: %d"
+ "Skipping invalid command id: %ld — %s"
- "End is invalid"
- "Failed to generate metadata items because of invalid command id: %ld which time or duration is not valid to process"
- "Generating metadata items is using cache"
- "MetadataItem with time %f start at %f end at %f failed to segment with segmentDuration %f"
- "MetadataItem with time %f start at %f failed to segment with segmentDuration %f"
- "SegmentDuration is invalid"
```
