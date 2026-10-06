## PerfPowerServicesMetadata

> `/System/Library/PrivateFrameworks/PerfPowerServicesMetadata.framework/PerfPowerServicesMetadata`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3efe0` | `0x3f560` | **`+0x580`** |
| `__AUTH_CONST.__cfstring` | `0x8d20` | `0x8e20` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x49e8` | `0x4ad8` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x4768` | `0x47f3` | **`+0x8b`** |
| `__AUTH.__objc_data` | `0x280` | `0x2d0` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x291c` | `0x2954` | **`+0x38`** |
| `__AUTH_CONST.__objc_dictobj` | `0x3e8` | `0x410` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x560` | `0x580` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0xf0` | `0x108` | **`+0x18`** |
| `__DATA.__bss` | `0x90` | `0xa0` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x1e8` | `0x1f8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1330` | `0x1340` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x228` | `0x230` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x200` | `0x208` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x978` | `0x980` | **`+0x8`** |

### Other Changes

```diff

-3486.2.4.0.0
+3486.40.92.0.0

-  Functions: 1090
-  Symbols:   1734
-  CStrings:  1312
+  Functions: 1096
+  Symbols:   1748
+  CStrings:  1320
Symbols:
+ +[PPSSignpostServiceMetrics allDeclMetrics]
+ +[PPSSignpostServiceMetrics collectionSummaryMetrics]
+ +[PPSSignpostServiceMetrics subsystem]
+ +[PPSUnit gigabytes]
+ _OBJC_CLASS_$_PPSSignpostServiceMetrics
+ _OBJC_METACLASS_$_PPSSignpostServiceMetrics
+ __OBJC_$_CLASS_METHODS_PPSSignpostServiceMetrics
+ __OBJC_$_PROP_LIST_PPSSignpostServiceMetrics
+ __OBJC_CLASS_PROTOCOLS_$_PPSSignpostServiceMetrics
+ __OBJC_CLASS_RO_$_PPSSignpostServiceMetrics
+ __OBJC_METACLASS_RO_$_PPSSignpostServiceMetrics
+ ___20+[PPSUnit gigabytes]_block_invoke
+ _gigabytes._unitGigabyte
+ _gigabytes.onceToken
CStrings:
+ "Category"
+ "CollectionSummary"
+ "DistinctCategoryCount"
+ "InternalOnlyRule"
+ "RemainingDiskSpace"
+ "RunDuration"
+ "SignpostServiceMetrics"
+ "TotalSignpostCount"
```
