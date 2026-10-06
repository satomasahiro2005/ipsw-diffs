## IOGPU

> `/System/Library/PrivateFrameworks/IOGPU.framework/IOGPU`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x7fe0` | `0x8000` | **`+0x20`** |
| `__TEXT.__text` | `0x2a8a4` | `0x2a88c` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x4f9c` | `0x4fa4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd70` | `0xd78` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3a4` | `0x3a8` | **`+0x4`** |

### Other Changes

```diff

-162.11.0.0.0
+162.13.0.0.0

-  Symbols:   2286
+  Symbols:   2287
Symbols:
+ -[IOGPUMetal4CommandAllocator getCommandBufferStorage:retainReferences:generation:]
+ -[IOGPUMetal4CommandBuffer allocatorGeneration]
+ OBJC_IVAR_$_IOGPUMetal4CommandBuffer._allocatorGeneration
- -[IOGPUMetal4CommandAllocator getCommandBufferStorage:retainReferences:]
- -[IOGPUMetal4CommandAllocator getGeneration]
```
