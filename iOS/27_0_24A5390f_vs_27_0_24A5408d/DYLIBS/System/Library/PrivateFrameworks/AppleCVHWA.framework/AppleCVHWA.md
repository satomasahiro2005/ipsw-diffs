## AppleCVHWA

> `/System/Library/PrivateFrameworks/AppleCVHWA.framework/AppleCVHWA`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb5a34` | `0xb5ea8` | **`+0x474`** |
| `__TEXT.__cstring` | `0x9001` | `0x8ef8` | **`-0x109`** |
| `__TEXT.__const` | `0x2ed0` | `0x2f90` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x1558` | `0x15a8` | **`+0x50`** |
| `__DATA_DIRTY.__bss` | `0x1b0` | `0x1d0` | **`+0x20`** |
| `__DATA.__common` | `0x20` | `0x10` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x17a8` | `0x17b8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x5e0` | `0x5e8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x5560` | `0x555c` | **`-0x4`** |

### Other Changes

```diff

-4.4.10.0.0
+4.4.12.0.0

-  Functions: 1143
-  Symbols:   444
-  CStrings:  586
+  Functions: 1147
+  Symbols:   448
+  CStrings:  583
Symbols:
+ __ZNSt3__19to_stringEj
+ __xpc_error_connection_interrupted
+ __xpc_error_connection_invalid
+ __xpc_error_termination_imminent
CStrings:
+ " GPAPI Logger uses level "
+ " Logger uses level "
+ "AppleCVHWA version "
+ "CVPixelBufferGetBaseAddress(*buf) && \"NULL base address\""
- "(*counterpart_ptr != *dma_ptr) && \"Shouldn't be in this branch if dma_in_ptr_ == dma_out_ptr_\""
- "(base != buf) && \"Unnecessary memcpy, source == destination.\""
- "(needs_alloc || tracked_cvpb != nullptr) && \"No CVPixelBuffer backing available\""
- "AppleCVHWA GPAPI Logger uses level "
- "AppleCVHWA Logger uses level "
- "base_address && \"NULL pointer\""
- "needs_memcpy && \"needs_memcpy is false unexpectedly\""
```
