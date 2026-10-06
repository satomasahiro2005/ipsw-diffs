## BackBoardHIDEventFoundation

> `/System/Library/PrivateFrameworks/BackBoardHIDEventFoundation.framework/BackBoardHIDEventFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3cf8c` | `0x3d75c` | **`+0x7d0`** |
| `__TEXT.__oslogstring` | `0x3308` | `0x3440` | **`+0x138`** |
| `__TEXT.__gcc_except_tab` | `0x3bc` | `0x484` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x33af` | `0x3473` | **`+0xc4`** |
| `__AUTH_CONST.__cfstring` | `0x2b40` | `0x2b80` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x15f8` | `0x1620` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x14a0` | `0x14c0` | **`+0x20`** |
| `__TEXT.__const` | `0x68c` | `0x684` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xc30` | `0xc38` | **`+0x8`** |

### Other Changes

```diff

-877.0.0.0.0
+877.2.1.0.0

-  Functions: 1089
-  Symbols:   2426
-  CStrings:  688
+  Functions: 1092
+  Symbols:   2430
+  CStrings:  695
Symbols:
+ -[BKEventDeferringEnvironmentGraph _publishSelectionChangesForReason:]
+ GCC_except_table242
+ GCC_except_table282
+ GCC_except_table337
+ GCC_except_table395
+ GCC_except_table408
+ GCC_except_table411
+ GCC_except_table417
+ GCC_except_table420
+ GCC_except_table665
+ GCC_except_table668
+ GCC_except_table703
+ GCC_except_table752
+ GCC_except_table813
+ GCC_except_table826
+ GCC_except_table858
+ ___64-[BKEventDeferringEnvironmentGraph _requestsSortedByGraphDepth:]_block_invoke
+ ___66-[BKEventDeferringGraph requestSelectionChanges:forClientWithPID:]_block_invoke
+ ___76-[BKHIDEventDeliveryManager _lock_requestSelectionChanges:forClientWithPID:]_block_invoke_2
+ ___block_descriptor_40_e8_32s_e99_q24?0"BKSHIDEventDeferringSelectionChangeRequest"8"BKSHIDEventDeferringSelectionChangeRequest"16ls32l8
+ ___block_descriptor_44_e8_32s_e52_B16?0"BKSHIDEventDeferringSelectionChangeRequest"8ls32l8
+ ___block_descriptor_77_e8_32s40s48s56r64r_e48_v16?0"BKEventDeferringSelectionPathContainer"8lr56l8s32l8s40l8s48l8r64l8
- GCC_except_table241
- GCC_except_table281
- GCC_except_table336
- GCC_except_table394
- GCC_except_table407
- GCC_except_table410
- GCC_except_table416
- GCC_except_table419
- GCC_except_table664
- GCC_except_table667
- GCC_except_table702
- GCC_except_table751
- GCC_except_table812
- GCC_except_table824
- GCC_except_table856
- ___65-[BKEventDeferringGraph requestSelectionChange:forClientWithPID:]_block_invoke
- ___block_descriptor_44_e8_32s_e54_v24?0"BKEventDeferringEnvironmentGraph"8"NSArray"16ls32l8
- ___block_descriptor_61_e8_32s40s48s_e48_v16?0"BKEventDeferringSelectionPathContainer"8ls32l8s40l8s48l8
CStrings:
+ "[%{public}@ %p] admitted on %lu of %lu selection path(s) (%{public}@)"
+ "[%{public}@ %p] admitted on all %lu selection path(s) (%{public}@)"
+ "[%{public}@ %p] changeSelectionPath(%{public}@) reason:%{public}@  -> %{public}@ -- %{public}@"
+ "[%{public}@ %p] no selection path matched (%{public}@)"
+ "[%{public}@ %p] rejected on all %lu selection path(s) (%{public}@)"
+ "[%{public}@ %p] selection recorded reason:%{public}@ generation: %ld -- deferring chains resolve from this"
+ "q24@?0@\"BKSHIDEventDeferringSelectionChangeRequest\"8@\"BKSHIDEventDeferringSelectionChangeRequest\"16"
+ "selection recorded"
+ "selection recorded: target was already selected"
+ "selectionTransaction(%lu request(s))"
- "[%{public}@ %p] changeSelectionPath(%{public}@) reason:%{public}@  -> %{public}@ generation: %ld -- %{public}@"
- "[%{public}@ %p] selected (%{public}@)"
- "success"
```
