## libTelephonyCapabilities.dylib

> `/usr/lib/libTelephonyCapabilities.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2aef8` | `0x2a92c` | **`-0x5cc`** |
| `__TEXT.__gcc_except_tab` | `0x1f0c` | `0x1ed0` | **`-0x3c`** |
| `__AUTH_CONST.__const` | `0xe0` | `0x100` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x168` | `0x188` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x19b` | `0x1b0` | **`+0x15`** |
| `__DATA_DIRTY.__bss` | `0x18c8` | `0x18d0` | **`+0x8`** |
| `__TEXT.__cstring` | `0xa07` | `0x9ff` | **`-0x8`** |

### Other Changes

```diff

-6567.0.0.0.0
+6567.1.0.0.0

-  Functions: 1486
-  Symbols:   1887
+  Functions: 1487
+  Symbols:   1881
Symbols:
+ __ZL25_readValueFromBasebandEDTPKcPj
+ ____ZL12_readSDDVersv_block_invoke
- __ZNSt12out_of_rangeD0Ev
- __ZNSt12out_of_rangeD1Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC2ERKS5_mmRKS4_
- __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEES7_EENS_19__map_value_compareIS7_NS_4pairIKS7_S7_EENS_4lessIS7_EEEENS5_ISC_EEE14__tree_deleterclB9nqe220106EPNS_11__tree_nodeIS8_PvEE
- __ZTISt12out_of_range
- __ZTVSt12out_of_range
- _memchr
- _memcmp
CStrings:
+ "EDT sdd-vers: 0x%x"
+ "The given parameter is null!"
- "boot-args"
- "boot-args overrides %s: %s"
```
