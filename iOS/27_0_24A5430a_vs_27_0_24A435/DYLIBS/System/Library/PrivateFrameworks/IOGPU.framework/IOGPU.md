## IOGPU

> `/System/Library/PrivateFrameworks/IOGPU.framework/IOGPU`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x7f50` | `0x7fe0` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x4f54` | `0x4f9c` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x2900` | `0x2930` | **`+0x30`** |
| `__TEXT.__text` | `0x2a898` | `0x2a8a4` | **`+0xc`** |

### Other Changes

```text
Functions:
~ _IOGPUMetalCommandBufferStorageGrowKernelCommandBuffer : 396 -> 400
~ -[IOGPUMetalIOCommandQueue submitAvailableCommands] : 696 -> 700
~ -[IOGPUMetalIOCommandBuffer growKernelCommandBuffer:] : 460 -> 464
```
