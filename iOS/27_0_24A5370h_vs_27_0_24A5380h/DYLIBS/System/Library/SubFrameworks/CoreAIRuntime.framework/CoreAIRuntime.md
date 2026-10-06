## CoreAIRuntime

> `/System/Library/SubFrameworks/CoreAIRuntime.framework/CoreAIRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x50ed5c` | `0x5283fc` | **`+0x196a0`** |
| `__DATA_DIRTY.__data` | `—` | `0x1a50` | **`+0x1a50`** |
| `__AUTH.__data` | `0x2400` | `0xc78` | **`-0x1788`** |
| `__TEXT.__unwind_info` | `0x6378` | `0x5e20` | **`-0x558`** |
| `__DATA.__data` | `0x2068` | `0x1de0` | **`-0x288`** |
| `__TEXT.__const` | `0xe090` | `0xde10` | **`-0x280`** |
| `__AUTH.__objc_data` | `0x230` | `—` | **`-0x230`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x230` | **`+0x230`** |
| `__TEXT.__cstring` | `0xbda1` | `0xbfd1` | **`+0x230`** |
| `__TEXT.__eh_frame` | `0x12248` | `0x12410` | **`+0x1c8`** |
| `__DATA_DIRTY.__common` | `—` | `0xe0` | **`+0xe0`** |
| `__DATA.__common` | `0x168` | `0x90` | **`-0xd8`** |
| `__AUTH_CONST.__const` | `0xa288` | `0xa208` | **`-0x80`** |
| `__DATA.__bss` | `0x8ba0` | `0x8b20` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `—` | `0x80` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x11a4` | `0x1154` | **`-0x50`** |
| `__TEXT.__swift5_typeref` | `0x31bd` | `0x3175` | **`-0x48`** |
| `__TEXT.__constg_swiftt` | `0x34c0` | `0x34e8` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x386c` | `0x3894` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x2526` | `0x254d` | **`+0x27`** |
| `__AUTH_CONST.__objc_const` | `0x52c0` | `0x52e0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x14e0` | `0x14f8` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x3e4` | `0x3e8` | **`+0x4`** |

### Other Changes

```diff

-3600.73.1.0.0
+3600.75.3.0.0

-  Functions: 7925
-  Symbols:   331
-  CStrings:  1013
+  Functions: 7990
+  Symbols:   334
+  CStrings:  1016
Symbols:
+ _objc_retain_x12
+ _swift_retain_x11
+ _vDSP_mtrans
+ _vDSP_mtransD
+ _vDSP_vsmsa
- _objc_retain_x13
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ ", output.strides="
+ "CoreAIRuntime/ConcatKernel.swift"
+ "CoreAIRuntime/FastBlockwiseShiftScaleKernel.swift"
+ "CoreAIRuntime/FastMatMulKernel+SIMDBackend.swift"
+ "MatMulSIMDBackend does not support "
+ "Sub-byte concat requires contiguous input and output (got input.strides="
+ "This function's reshape implementation reads input values, but reshape(for:) only carries shape metadata. Use reshape(inputs:) to provide input values, or omit the explicit reshape call — the standard inference path re-runs reshape with real values on every call."
- "CallSiteLoc"
- "FileLineCol"
- "Fused"
- "NameLoc"
```
