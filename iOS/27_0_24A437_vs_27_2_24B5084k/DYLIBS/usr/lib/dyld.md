## dyld

> `/usr/lib/dyld`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9eda4` | `0x9f00c` | **`+0x268`** |
| `__DATA_CONST.__const` | `0x55f0` | `0x5618` | **`+0x28`** |
| `__TEXT.__const` | `0x1978` | `0x1998` | **`+0x20`** |
| `__TEXT.__cstring` | `0x12573` | `0x12587` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x35b0` | `0x35c0` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x2758` | `0x2760` | **`+0x8`** |

### Other Changes

```diff

-27062.0.0.0.0
-  Functions: 3422
-  Symbols:   3273
-  CStrings:  2255
+27102.0.0.0.0
+  Functions: 3425
+  Symbols:   3277
+  CStrings:  2256
Symbols:
+ __ZN5dyld44APIs28_dyld_with_active_atlas_PRIVEPvPFvS1_PKvmE
+ __ZNK6mach_o5Image19maxAuthRebaseOffsetEv
+ __ZNK6mach_o6Policy34enforceAuthRebasesPointWithinImageEv
+ ____ZNK6mach_o5Image19maxAuthRebaseOffsetEv_block_invoke
CStrings:
+ "27102"
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Fri Sep  4 23:05:44 PDT 2026; root:libignition-64~25453/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Fri Sep  4 23:05:44 PDT 2026; root:libignition-64~25453/libignition_core/RELEASE_ARM64E"
+ "rebase out of range"
- "27062"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Thu Aug 13 21:26:15 PDT 2026; root:libignition-64~19679/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Thu Aug 13 21:26:15 PDT 2026; root:libignition-64~19679/libignition_core/RELEASE_ARM64E"
```
