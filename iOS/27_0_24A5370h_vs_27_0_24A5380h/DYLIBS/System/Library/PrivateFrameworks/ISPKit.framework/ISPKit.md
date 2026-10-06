## ISPKit

> `/System/Library/PrivateFrameworks/ISPKit.framework/ISPKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x280` | `—` | **`-0x280`** |
| `__DATA_DIRTY.__objc_data` | `0xdc0` | `0x1040` | **`+0x280`** |
| `__TEXT.__text` | `0x1ff04` | `0x200f8` | **`+0x1f4`** |
| `__DATA_CONST.__got` | `0x0` | `0x1f0` | **`+0x1f0`** |
| `__TEXT.__oslogstring` | `0x2ece` | `0x2f60` | **`+0x92`** |
| `__AUTH_CONST.__objc_const` | `0x6f98` | `0x6fb8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1f9c` | `0x1fac` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x12a0` | `0x12a8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x5b8` | `0x5bc` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-20.50.6.1.0
+20.55.3.0.0

-  Functions: 938
-  Symbols:   1686
-  CStrings:  543
+  Functions: 942
+  Symbols:   1688
+  CStrings:  546
Symbols:
+ -[LLVProcessorBufferManager emptyHumanFullBodiesMask]
+ _OBJC_IVAR_$_LLVProcessorBufferManager._emptyHumanFullBodiesMask
Functions:
~ -[ABDLookupTable getValueFor:] : 656 -> 660
~ -[LLVProcessorBufferManager prepareAllBuffersWithInput:inputHumanFullBodiesMask:output:scale1Width:scale1Height:opticalFlowWidth:opticalFlowHeight:] : 804 -> 812
+ -[LLVProcessorBufferManager emptyHumanFullBodiesMask]
~ -[LLVProcessorBufferManager .cxx_destruct] : 248 -> 260
+ -[LLVProcessorBufferManager emptyHumanFullBodiesMask].cold.2
- -[LLVProcessorBufferManager dumpAllBuffersToDirectory:frameIndex:].cold.2
+ -[LLVProcessorBufferManager dumpAllBuffersToDirectory:frameIndex:].cold.1
+ -[LLVProcessorBufferManager dumpAllBuffersToDirectory:frameIndex:].cold.23
+ -[LLVProcessorBufferManager dumpAllBuffersToDirectory:frameIndex:].cold.25
CStrings:
+ "1x1 emptyHumanFullBodiesMask created"
+ "Failed to create empty human full bodies mask"
+ "Failed to get base address for emptyHumanFullBodiesMask"
+ "Failed to lock base address for emptyHumanFullBodiesMask"
- "Input human full bodies mask pixel buffer not set"
```
