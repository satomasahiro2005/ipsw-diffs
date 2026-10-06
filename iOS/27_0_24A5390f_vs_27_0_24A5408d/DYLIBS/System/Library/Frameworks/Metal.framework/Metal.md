## Metal

> `/System/Library/Frameworks/Metal.framework/Metal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e6bec` | `0x1e6d38` | **`+0x14c`** |
| `__AUTH_CONST.__objc_const` | `0x46bd0` | `0x46bf0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8e68` | `0x8e80` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1eb7c` | `0x1eb8c` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xc3a0` | `0xc3ac` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x2230` | `0x2234` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-382.5.0.0.0
+382.5.3.0.0

-  Functions: 13494
-  Symbols:   22504
+  Functions: 13495
+  Symbols:   22506
Symbols:
+ -[MTLShaderValidationConfiguration isShaderValidationEnabled]
+ _OBJC_IVAR_$__MTL4MachineLearningCommandEncoder._anePrePowerUpEvent
Functions:
+ -[MTLShaderValidationConfiguration isShaderValidationEnabled]
~ __ZN26MTL4MetalScriptBuilderImpl35createShaderValidationConfigurationEP32MTLShaderValidationConfiguration : 356 -> 380
~ -[_MTL4MachineLearningCommandEncoder initWithDevice:] : 152 -> 184
~ -[_MTL4MachineLearningCommandEncoder initWithCommandBuffer:allocator:] : 172 -> 208
~ -[_MTL4MachineLearningCommandEncoder dealloc] : 276 -> 300
~ -[_MTL4MachineLearningCommandEncoder dispatchNetworkWithIntermediatesHeap:] : 608 -> 648
~ -[_MTL4MachineLearningCommandEncoder encodeToCommandQueue:] : 788 -> 884
CStrings:
+ "22:35:33"
+ "Aug  3 2026"
+ "Aug  3 2026 22:35:33"
- "23:33:30"
- "Jul 10 2026"
- "Jul 10 2026 23:33:30"
```
