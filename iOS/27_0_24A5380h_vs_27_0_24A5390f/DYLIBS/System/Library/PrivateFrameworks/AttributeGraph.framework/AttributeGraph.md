## AttributeGraph

> `/System/Library/PrivateFrameworks/AttributeGraph.framework/AttributeGraph`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d81c` | `0x3d85c` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0xd8` | `0xfd` | **`+0x25`** |
| `__DATA.__data` | `0x268` | `0x258` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x3d8` | `0x3e8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x17d6` | `0x17c6` | **`-0x10`** |
| `__DATA.__common` | `0x10` | `0x8` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x6c8` | `0x6d0` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0xd0` | `0xd8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x1248` | `0x124c` | **`+0x4`** |

### Other Changes

```diff

-8.0.64.0.0
+8.0.76.0.0

-  CStrings:  337
+  CStrings:  336
Functions:
~ __ZNK2AG5Graph11print_cycleENS_4data3ptrINS_4NodeEEE : 552 -> 600
~ __ZNK2AG5Graph11print_cycleENS_4data3ptrINS_4NodeEEE.cold.1 : 80 -> 120
~ __ZN2AG12_GLOBAL__N_115cycle_verbosityEv : 64 -> 60
~ __ZNK2AG5Graph11print_cycleENS_4data3ptrINS_4NodeEEE.cold.2 : 76 -> 60
~ __ZNK2AG5Graph11print_cycleENS_4data3ptrINS_4NodeEEE.cold.3 : 100 -> 96
CStrings:
+ "Cycle detected through attribute: %u"
- "=== Evaluation stack ===\n"
- "cycle detected through attribute: %u"
```
