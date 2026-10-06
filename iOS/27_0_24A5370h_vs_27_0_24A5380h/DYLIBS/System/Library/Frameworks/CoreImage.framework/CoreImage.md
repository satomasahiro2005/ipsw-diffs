## CoreImage

> `/System/Library/Frameworks/CoreImage.framework/CoreImage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x347890` | `0x3479d4` | **`+0x144`** |
| `__TEXT.__oslogstring` | `0xad65` | `0xae6f` | **`+0x10a`** |
| `__DATA_CONST.__got` | `0xa88` | `0xae8` | **`+0x60`** |
| `__DATA.__bss` | `0x3b40` | `0x3ae8` | **`-0x58`** |
| `__AUTH_CONST.__cfstring` | `0x1d5e0` | `0x1d620` | **`+0x40`** |
| `__TEXT.__cstring` | `0x103f9c` | `0x103fd9` | **`+0x3d`** |
| `__TEXT.__gcc_except_tab` | `0xa7b0` | `0xa7ec` | **`+0x3c`** |
| `__DATA_CONST.__const` | `0x6488` | `0x64b0` | **`+0x28`** |
| `__DATA.__common` | `0x50` | `0x38` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0x214` | `0x22c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x8e08` | `0x8e18` | **`+0x10`** |
| `__TEXT.__const` | `0xe118` | `0xe128` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xa888` | `0xa898` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x680` | `0x688` | **`+0x8`** |

### Other Changes

```diff

-1657.0.0.0.0
+1660.0.0.0.0

-  Functions: 15146
-  Symbols:   26312
-  CStrings:  8815
+  Functions: 15148
+  Symbols:   26317
+  CStrings:  8820
Symbols:
+ GCC_except_table178
+ GCC_except_table201
+ GCC_except_table206
+ GCC_except_table216
+ GCC_except_table222
+ GCC_except_table224
+ GCC_except_table237
+ GCC_except_table257
+ GCC_except_table264
+ GCC_except_table276
+ __ZGVZN2CI16MetalMainProgram17compile_in_flightEvE3set
+ __ZL19IRectMakeFromCGRect6CGRect
+ __ZN2CI12MetalContext14bind_argumentsEPKNS_11ProgramNodeERKNS_9parentROIERK6CGRectRK6CGSizePNS_8TileTaskE
+ __ZN2CI16MetalMainProgram13compile_guardEv
+ __ZN2CI16MetalMainProgram17compile_in_flightEv
+ __ZN2CI7Context12bind_samplerEPKNS_14TextureSamplerEiNS_18KernelArgumentTypeEPNS_8TileTaskERKNS_9parentROIE
+ __ZN2CI8TileTask6shadowEv
+ __ZN2CI9GLContext14bind_argumentsEPKNS_11ProgramNodeERKNS_9parentROIEPNS_8TileTaskE
+ __ZNK2CI11ProgramNode16roiKeys_of_childERKNS_9parentROIEi
+ __ZNSt3__119__allocate_at_leastB9fqn220106INS_9allocatorINS_4pairIN2CI9NodeIndexEmEEEENS_16allocator_traitsIS6_EEEENS_19__allocation_resultINT0_7pointerENSA_9size_typeEEERT_m
+ __ZNSt3__16vectorINS_4pairIN2CI9NodeIndexEmEENS_9allocatorIS4_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorINS_4pairIN2CI9NodeIndexEmEENS_9allocatorIS4_EEE24__emplace_back_slow_pathIJS4_EEEPS4_DpOT_
+ __ZZN2CI12MetalContext14bind_argumentsEPKNS_11ProgramNodeERKNS_9parentROIERK6CGRectRK6CGSizePNS_8TileTaskEEN13SignpostTimerD1Ev
+ __ZZN2CI16MetalMainProgram17compile_in_flightEvE3set
+ __ZZN2CI7Context12bind_samplerEPKNS_14TextureSamplerEiNS_18KernelArgumentTypeEPNS_8TileTaskERKNS_9parentROIEEN13SignpostTimerD1Ev
+ __ZZN2CI9GLContext14bind_argumentsEPKNS_11ProgramNodeERKNS_9parentROIEPNS_8TileTaskEEN13SignpostTimerD1Ev
+ ____ZNK2CI11ProgramNode16roiKeys_of_childERKNS_9parentROIEi_block_invoke
+ ____ZNK2CI11ProgramNode16roiKeys_of_childERKNS_9parentROIEi_block_invoke_2
+ ___block_descriptor_68_e8_32o_e5_v8?0ls32l8
+ ___block_descriptor_68_e8_32r_e5_v8?0lr32l8
+ _applyParavirtualWorkaround
- GCC_except_table134
- GCC_except_table144
- GCC_except_table156
- GCC_except_table199
- GCC_except_table207
- GCC_except_table217
- GCC_except_table239
- GCC_except_table248
- GCC_except_table258
- GCC_except_table271
- __ZN2CI12MetalContext14bind_argumentsEPKNS_11ProgramNodeERK6CGRectS6_RK6CGSizePNS_8TileTaskE
- __ZN2CI12MetalContext9MTLShadowEv
- __ZN2CI7Context12bind_samplerEPKNS_14TextureSamplerERKNS_6roiKeyEiNS_18KernelArgumentTypeEPNS_8TileTaskE
- __ZN2CI9GLContext14bind_argumentsEPKNS_11ProgramNodeERK6CGRectPNS_8TileTaskE
- __ZN9QueuePoolILi4EED1Ev
- __ZNK2CI11ProgramNode16roiKeys_of_childE6CGRecti
- __ZNK2CI9roiKeyVec3roiEv
- __ZNSt3__13setIN2CI13ProgramDigestENS_4lessIS2_EENS_9allocatorIS2_EEED1B9fqn220106Ev
- __ZNSt3__16__treeIN2CI13ProgramDigestENS_4lessIS2_EENS_9allocatorIS2_EEE14__tree_deleterclB9fqn220106EPNS_11__tree_nodeIS2_PvEE
- __ZZN2CI12MetalContext14bind_argumentsEPKNS_11ProgramNodeERK6CGRectS6_RK6CGSizePNS_8TileTaskEEN13SignpostTimerD1Ev
- __ZZN2CI7Context12bind_samplerEPKNS_14TextureSamplerERKNS_6roiKeyEiNS_18KernelArgumentTypeEPNS_8TileTaskEEN13SignpostTimerD1Ev
- __ZZN2CI9GLContext14bind_argumentsEPKNS_11ProgramNodeERK6CGRectPNS_8TileTaskEEN13SignpostTimerD1Ev
- ____ZN2CI7Context16recursive_renderEPKNS_17RenderDestinationEPNS_8TileTaskERKNS_6roiKeyEPKNS_4NodeEb_block_invoke_2
- ____ZNK2CI11ProgramNode16roiKeys_of_childE6CGRecti_block_invoke
- ____ZNK2CI11ProgramNode16roiKeys_of_childE6CGRecti_block_invoke_2
- ___block_descriptor_60_e8_32r_e5_v8?0lr32l8
CStrings:
+ "1660"
+ "MLNeuralEngineComputeDevice"
+ "Paravirtual"
+ "bind_sampler: missing intermediate for child {node=%u, roiIndex=%d} expected by parent {node=%u, roiIndex=%d, quadIndex=%d, childIndex=%d, tileIndex=%d}; child has %zu active and %zu retired parentROI entries"
+ "tileCount mismatch at parent node=%u quad=%d: %{public}s"
+ "{node=%u tiles=%zu} "
- "1657"
```
