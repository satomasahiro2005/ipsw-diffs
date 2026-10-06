## pmudiagnose

> `/usr/libexec/pmudiagnose/pmudiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3120` | `0x30c4` | **`-0x5c`** |
| `__TEXT.__unwind_info` | `0x148` | `0x140` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-742.0.0.0.0
+743.0.2.0.0
Functions:
~ _main : 1016 -> 1000
~ __ZNSt3__111__introsortINS_17_ClassicAlgPolicyERZ16get_ptmu_regionsjPK10__CFStringS4_E3$_0P6regionLb0EEEvT1_S9_T0_NS_15iterator_traitsIS9_E15difference_typeEb : 3412 -> 3372
~ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERZ16get_ptmu_regionsjPK10__CFStringS4_E3$_0P6regionEEbT1_S9_T0_ : 616 -> 580
```
