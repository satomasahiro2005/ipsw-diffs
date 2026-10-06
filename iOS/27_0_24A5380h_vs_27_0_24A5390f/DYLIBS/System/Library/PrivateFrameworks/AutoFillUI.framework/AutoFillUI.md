## AutoFillUI

> `/System/Library/PrivateFrameworks/AutoFillUI.framework/AutoFillUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2abe4` | `0x2afe4` | **`+0x400`** |
| `__AUTH_CONST.__objc_const` | `0x9498` | `0x9668` | **`+0x1d0`** |
| `__TEXT.__objc_methlist` | `0x3e90` | `0x3f08` | **`+0x78`** |
| `__AUTH_CONST.__cfstring` | `0x1ae0` | `0x1b40` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x2ab0` | `0x2b10` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x79c` | `0x7f4` | **`+0x58`** |
| `__AUTH.__objc_data` | `0xce8` | `0xd38` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xc18` | `0xc58` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1d74` | `0x1d94` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x700` | `0x718` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x2cc` | `0x2dc` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x168` | `0x170` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xd8` | `0xe0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd20` | `0xd28` | **`+0x8`** |

### Other Changes

```diff

-111.0.0.0.0
+113.0.0.0.0

-  Functions: 1300
-  Symbols:   2297
-  CStrings:  315
+  Functions: 1307
+  Symbols:   2319
+  CStrings:  318
Symbols:
+ -[AFUICreditCardFieldRow .cxx_destruct]
+ -[AFUICreditCardFieldRow detailText]
+ -[AFUICreditCardFieldRow fillValue]
+ -[AFUICreditCardFieldRow initWithLabel:detailText:fillValue:]
+ -[AFUICreditCardFieldRow label]
+ -[AFUICreditCardViewController displayFieldsByCard]
+ -[AFUICreditCardViewController displayFieldsForCard:]
+ -[AFUICreditCardViewController setDisplayFieldsByCard:]
+ GCC_except_table33
+ _AFTextContentTypeCellularIMEI1Staging
+ _AFTextContentTypeCellularIMEI2Staging
+ _AFTextContentTypeCellularNALStaging
+ _OBJC_CLASS_$_AFUICreditCardFieldRow
+ _OBJC_CLASS_$_UIBlurEffect
+ _OBJC_CLASS_$_UINavigationBarAppearance
+ _OBJC_IVAR_$_AFUICreditCardFieldRow._detailText
+ _OBJC_IVAR_$_AFUICreditCardFieldRow._fillValue
+ _OBJC_IVAR_$_AFUICreditCardFieldRow._label
+ _OBJC_IVAR_$_AFUICreditCardViewController._displayFieldsByCard
+ _OBJC_METACLASS_$_AFUICreditCardFieldRow
+ __OBJC_$_INSTANCE_METHODS_AFUICreditCardFieldRow
+ __OBJC_$_INSTANCE_VARIABLES_AFUICreditCardFieldRow
+ __OBJC_$_PROP_LIST_AFUICreditCardFieldRow
+ __OBJC_CLASS_RO_$_AFUICreditCardFieldRow
+ __OBJC_METACLASS_RO_$_AFUICreditCardFieldRow
+ ___block_descriptor_40_e8_32w_e8_B12?0B8lw32l8
- -[AFUIAppCreditCardViewController _cancelTapped]
- GCC_except_table28
- GCC_except_table43
- GCC_except_table6
CStrings:
+ "esim-imei1"
+ "esim-imei2"
+ "esim-nal"
+ "\xc2"
- "\xb2"
```
