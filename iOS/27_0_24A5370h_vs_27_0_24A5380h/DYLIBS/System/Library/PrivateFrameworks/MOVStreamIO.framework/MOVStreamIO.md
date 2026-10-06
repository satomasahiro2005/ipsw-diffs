## MOVStreamIO

> `/System/Library/PrivateFrameworks/MOVStreamIO.framework/MOVStreamIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x130` | `0x24d0` | **`+0x23a0`** |
| `__DATA_DIRTY.__objc_data` | `0x23a0` | `—` | **`-0x23a0`** |
| `__TEXT.__text` | `0x8dc58` | `0x8deb8` | **`+0x260`** |
| `__TEXT.__oslogstring` | `0x3ba2` | `0x3cc0` | **`+0x11e`** |
| `__AUTH_CONST.__cfstring` | `0x6140` | `0x6220` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x8dcd` | `0x8d4d` | **`-0x80`** |
| `__DATA_CONST.__const` | `0xb40` | `0xb90` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0xe848` | `0xe850` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x32d0` | `0x32d8` | **`+0x8`** |

### Other Changes

```diff

-3.39.4.0.0
+3.39.5.0.0

-  Functions: 2553
-  Symbols:   4749
-  CStrings:  1285
+  Functions: 2555
+  Symbols:   4751
+  CStrings:  1286
Symbols:
+ _MIOChromaSamplingDescription
+ _MIOPixelBufferCategoryDescription
CStrings:
+ "3.39.5"
+ "MIOWriter.inProcessRecording is set but stream %{public}@ uses standard encoder settings — this could potentially be a misconfiguration of the input."
+ "[MIO PERF] %{public}@: %u slow appendSampleBuffer calls (final) in %llu ms, max %llu µs"
+ "[MIO PERF] %{public}@: %u slow appendSampleBuffer calls in %llu ms, max %llu µs"
- "3.39.4"
- "MIOWriter.inProcessRecording requires custom or none encoder settings. Encoding for stream %@ will not performed in process!"
- "[MIO PERF] duration %{public}@ %llu"
```
