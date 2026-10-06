## MetalTools

> `/System/Library/PrivateFrameworks/MetalTools.framework/MetalTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x35270` | `0x354d7` | **`+0x267`** |
| `__TEXT.__text` | `0x146170` | `0x1463ac` | **`+0x23c`** |
| `__AUTH_CONST.__cfstring` | `0xf640` | `0xf700` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x6ac0` | `0x6ac8` | **`+0x8`** |

### Other Changes

```diff

-382.4.0.0.0
+382.5.0.0.0

-  CStrings:  3680
+  CStrings:  3686
Functions:
~ -[MTL4GPUDebugComputeCommandEncoder performDeepResidencyCheckWithDescriptor:commandInfo:] : 1592 -> 1604
~ -[MTLGPUDebugBuffer dealloc] : 244 -> 280
~ -[MTLDebugCommandBuffer preCommit] : 932 -> 1060
~ -[MTL4DebugCommandQueue validateCommitCommon:commandBuffers:count:] : 1396 -> 1792
CStrings:
+ "The command buffer (at index %lu) requires %lu Metal internal residency sets which exceeds the maximum (%lu)."
+ "The command buffer (at index %lu) requires %lu residency sets which exceeds the maximum (%lu)."
+ "The command buffer requires %lu Metal internal residency sets which exceeds the maximum (%lu)."
+ "The command buffer requires %lu residency sets which exceeds the maximum (%lu)."
+ "The command buffers (from index %lu to index %lu) require %lu Metal internal residency sets which exceeds the maximum (%lu)."
+ "The command buffers (from index %lu to index %lu) require %lu residency sets which exceeds the maximum (%lu)."
```
