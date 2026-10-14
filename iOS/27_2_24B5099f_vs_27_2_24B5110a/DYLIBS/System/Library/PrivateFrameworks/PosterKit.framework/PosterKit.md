## PosterKit

> `/System/Library/PrivateFrameworks/PosterKit.framework/PosterKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1884cc` | `0x188b84` | **`+0x6b8`** |
| `__TEXT.__oslogstring` | `0x8229` | `0x8389` | **`+0x160`** |
| `__DATA.__data` | `0x5f50` | `0x5fc8` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x6350` | `0x6388` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x1e98` | `0x1ec0` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x2ac8` | `0x2adc` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0xc650` | `0xc658` | **`+0x8`** |

### Other Changes

```diff

-355.2.10.100.0
+355.2.12.101.0

-  Functions: 10621
-  Symbols:   15726
-  CStrings:  2148
+  Functions: 10642
+  Symbols:   15729
+  CStrings:  2151
Symbols:
+ -[PRRenderer _updatePreferences:deferringOverrideReport:]
+ GCC_except_table45
+ GCC_except_table47
+ GCC_except_table73
+ GCC_except_table88
+ _OUTLINED_FUNCTION_51
+ _OUTLINED_FUNCTION_52
+ _OUTLINED_FUNCTION_53
+ ___block_descriptor_76_e8_32s40s48s_e8_v12?0B8ls32l8s40l8s48l8
- GCC_except_table37
- GCC_except_table44
- GCC_except_table46
- GCC_except_table72
- GCC_except_table87
- ___block_descriptor_75_e8_32s40s48s_e8_v12?0B8ls32l8s40l8s48l8
CStrings:
+ "<PRPosterEnvironmentImpl %p> Could not compute adjustable salient content range: %{public}@"
+ "<PRRenderer %p> PREFERENCES deferring environment override report to the orientation scene update (orientation %ld, salient content rect %{public}@)"
+ "<PRRenderer %p> PREFERENCES reported deferred environment override with the orientation update (animated: %{BOOL}u)"
```
