## TextInputUI

> `/System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1350f4` | `0x135a5c` | **`+0x968`** |
| `__AUTH_CONST.__cfstring` | `0xeac0` | `0xeb00` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x7a58` | `0x7a98` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xa330` | `0xa358` | **`+0x28`** |
| `__TEXT.__cstring` | `0xd80d` | `0xd835` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xfe84` | `0xfeac` | **`+0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x270` | `0x288` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0xad0` | `0xae0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4220` | `0x4230` | **`+0x10`** |

### Other Changes

```diff

-9127.0.84.1.112
+9127.0.84.1.113

-  Functions: 6866
-  Symbols:   10785
-  CStrings:  2729
+  Functions: 6872
+  Symbols:   10793
+  CStrings:  2732
Symbols:
+ +[TUIKeyplane maxRowsPerKey:variantSelectorType:]
+ +[TUIKeyplane maxVariantsPerRowForKey:layoutStyle:rowLimit:maxRows:]
+ +[TUIKeyplane variantRowLimitForKey:layoutStyle:variantSelectorType:]
+ -[TUIKey updateVariantOrderForMultilineSelectorWithKeyStartingPosition:rowLimit:maxVariantsPerRow:variantCount:]
+ -[TUIVariantSelectorView keyDisplaysNarrowVariants:]
+ ___112-[TUIKey updateVariantOrderForMultilineSelectorWithKeyStartingPosition:rowLimit:maxVariantsPerRow:variantCount:]_block_invoke
+ ___112-[TUIKey updateVariantOrderForMultilineSelectorWithKeyStartingPosition:rowLimit:maxVariantsPerRow:variantCount:]_block_invoke_2
+ ___block_descriptor_48_e8_q16?0q8l
+ ___block_descriptor_56_e8_q16?0q8l
- -[TUIKeyplane variantRowLimitForLayoutWithKey:variantSelectorType:]
CStrings:
+ "Syriac-Diacritics"
+ "Thai-Accents"
+ "q16@?0q8"
```
