## NetworkQuality

> `/System/Library/PrivateFrameworks/NetworkQuality.framework/NetworkQuality`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f6b8` | `0x1fec0` | **`+0x808`** |
| `__TEXT.__oslogstring` | `0x2138` | `0x2219` | **`+0xe1`** |
| `__TEXT.__cstring` | `0x2b62` | `0x2c3d` | **`+0xdb`** |
| `__TEXT.__objc_methlist` | `0x1cc0` | `0x1d10` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x4418` | `0x4460` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x1300` | `0x1340` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x660` | `0x690` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x6f0` | `0x718` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1dc0` | `0x1de0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x674` | `0x68c` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x508` | `0x510` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xb0` | `0xb8` | **`+0x8`** |

### Other Changes

```diff

-217.0.0.0.0
+219.0.0.0.0

-  Functions: 709
-  Symbols:   1491
-  CStrings:  564
+  Functions: 716
+  Symbols:   1508
+  CStrings:  572
Symbols:
+ -[UploadThroughputDelegate .cxx_destruct]
+ -[UploadThroughputDelegate URLSession:task:didCompleteWithError:]
+ -[UploadThroughputDelegate cancelWithCompletionHandler:]
+ -[UploadThroughputDelegate executeTaskWithRequest:saturationHandler:completionHandler:]
+ -[UploadThroughputDelegate pollWireBytes]
+ -[UploadThroughputDelegate startWireBytesPollTimer]
+ -[UploadThroughputDelegate teardownWireBytesPollTimer]
+ GCC_except_table61
+ _OBJC_IVAR_$_UploadThroughputDelegate._lastPolledWireBytes
+ _OBJC_IVAR_$_UploadThroughputDelegate._wireBytesPollTimer
+ __OBJC_$_INSTANCE_VARIABLES_UploadThroughputDelegate
+ ___51-[UploadThroughputDelegate startWireBytesPollTimer]_block_invoke
+ ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
+ _objc_copyWeak
+ _objc_destroyWeak
+ _objc_initWeak
+ _objc_loadWeakRetained
CStrings:
+ "%s:%u - [%d] %@ task=%@ underlyingError=%@"
+ "%s:%u - [%d] Failed to create upload wire-bytes poll timer"
+ "%s:%u - [%d] Invalidated upload wire-bytes poll timer"
+ "%s:%u - [%d] Started upload wire-bytes poll timer (%.0f ms interval)"
+ "-[UploadThroughputDelegate URLSession:task:didCompleteWithError:]"
+ "-[UploadThroughputDelegate startWireBytesPollTimer]"
+ "-[UploadThroughputDelegate teardownWireBytesPollTimer]"
+ "Failed to create upload wire-bytes poll timer"
```
