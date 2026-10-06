## libglInterpose.dylib

> `/usr/lib/libglInterpose.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ea7dc` | `0x1ea79c` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x1694c` | `0x16944` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ __Z22copyout_vertex_arrays2P11ContextInfolllb : 3704 -> 3816
~ _unapply_draw_overrides : 608 -> 600
~ __ZN16ContextHarvester24harvestLegacyARBProgramsEv : 188 -> 180
~ __ZN16ContextHarvester15harvestTexturesEb : 324 -> 308
~ __ZN16ContextHarvester19harvestQueryObjectsEv : 224 -> 200
~ __ZN16ContextHarvester24encodeProgramXfbVaryingsEjRK10ProgramXfb : 492 -> 480
~ __ZN16ContextHarvester19harvestGroupMarkersEv : 260 -> 252
~ _get_all_per_function_profiling_data : 524 -> 512
~ __ZN11ContextInfo19ExecuteAfterPresentEv : 296 -> 284
~ __ZNSt3__16vectorINS_8functionIFvP11ContextInfoEEENS_9allocatorIS5_EEE26__swap_out_circular_bufferERNS_14__split_bufferIS5_RS7_EE : 368 -> 340
~ __ZN8GPUTools15ResourceUpdater30_GetCombinedLinkedShaderSourceERKNSt3__16vectorI17ProgramShaderInfoNS1_9allocatorIS3_EEEE : 312 -> 296
~ __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqe220106EPKvm : 532 -> 520
~ __ZNSt3__116__insertion_sortB9fqe220106INS_17_ClassicAlgPolicyERU13block_pointerFbRKN8GPUTools15NameTargetTupleES5_ENS2_14array_iteratorIS3_EEEEvT1_SB_T0_ : 236 -> 220
~ __ZNSt3__126__insertion_sort_unguardedB9fqe220106INS_17_ClassicAlgPolicyERU13block_pointerFbRKN8GPUTools15NameTargetTupleES5_ENS2_14array_iteratorIS3_EEEEvT1_SB_T0_ : 272 -> 260
~ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERU13block_pointerFbRKN8GPUTools15NameTargetTupleES5_ENS2_14array_iteratorIS3_EEEEbT1_SB_T0_ : 1016 -> 1024
```
