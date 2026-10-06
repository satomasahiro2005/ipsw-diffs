## libGPUCompilerImplLazy.dylib

> `/System/Library/PrivateFrameworks/GPUCompiler.framework/Versions/32023/Libraries/libGPUCompilerImplLazy.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x118d3f4` | `0x117e478` | **`-0xef7c`** |
| `__AUTH_CONST.__const` | `0xf4b88` | `0xf4a20` | **`-0x168`** |
| `__TEXT.__const` | `0xd5ea0` | `0xd5fd0` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0x18a30` | `0x18b60` | **`+0x130`** |
| `__AUTH.__data` | `0x4b70` | `0x4b40` | **`-0x30`** |
| `__TEXT.__cstring` | `0x13a4f5` | `0x13a4c7` | **`-0x2e`** |
| `__DATA_CONST.__const` | `0x192f48` | `0x192f30` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x35a0` | `0x35a8` | **`+0x8`** |
| `__DATA.__data` | `0x16f0` | `0x16e8` | **`-0x8`** |

### Other Changes

```diff

-32023.921.0.0.0
+32023.921.4.0.0

-  Functions: 37816
-  Symbols:   1841
-  CStrings:  56847
+  Functions: 37894
+  Symbols:   1842
+  CStrings:  56845
Symbols:
+ __ZNK4llvm8Argument16hasStructRetAttrEv
CStrings:
+ " has rewritten init"
+ "<deferred this object type>"
+ "AIR-LLD 32023.921 (metalfe-32023.921.4)"
+ "Metal: support deferred default member initializer check"
+ "MetalDeferredThisObject"
+ "MetalDeferredThisObjectType"
+ "MetalDeferredThisObjectTypeLoc"
+ "__metal_assume_tensor_element"
+ "bv*_0"
+ "metalfe-32023.921.4"
+ "tensor_element_addrspace"
+ "unexpected address space conversion. PLEASE submit a bug report to https://developer.apple.com/bug-reporting/ and include a small example that reproduces the issue."
+ "v*_11v*_0"
+ "v*_12v*_0"
+ "v*_19v*_0"
+ "vuu"
- " __metal_generic"
- "-fgeneric-address-space"
- "AIR-LLD 32023.921 (metalfe-32023.921)"
- "MetalGenericAddressSpace"
- "MetalGenericAddressSpaceAttr"
- "__metal_generic"
- "bv*_20"
- "int3b_format"
- "metal_fp6_e2m3_format"
- "metal_fp6_e3m2_format"
- "metal_int8b_p6_format"
- "metal_uint8b_p6_format"
- "metalfe-32023.921"
- "uint3b_format"
- "unexpected address space conversion from %0 to %1. PLEASE submit a bug report to https://developer.apple.com/bug-reporting/ and include a small example that reproduces the issue."
- "v*_11v*_20"
- "v*_12v*_20"
- "v*_19v*_20"
```
