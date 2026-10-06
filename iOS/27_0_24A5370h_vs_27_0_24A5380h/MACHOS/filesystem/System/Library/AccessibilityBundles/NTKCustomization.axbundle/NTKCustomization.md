## NTKCustomization

> `/System/Library/AccessibilityBundles/NTKCustomization.axbundle/NTKCustomization`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf1ac` | `0xeff0` | **`-0x1bc`** |
| `__DATA.__objc_const` | `0x3d58` | `0x3c38` | **`-0x120`** |
| `__DATA_CONST.__cfstring` | `0x3680` | `0x35c0` | **`-0xc0`** |
| `__DATA.__objc_data` | `0x21c0` | `0x2120` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x2e93` | `0x2e02` | **`-0x91`** |
| `__TEXT.__gcc_except_tab` | `0x390` | `0x404` | **`+0x74`** |
| `__TEXT.__objc_classname` | `0x117c` | `0x1118` | **`-0x64`** |
| `__TEXT.__objc_methlist` | `0x187c` | `0x182c` | **`-0x50`** |
| `__TEXT.__objc_stubs` | `0x1d60` | `0x1d80` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x2569` | `0x2586` | **`+0x1d`** |
| `__DATA_CONST.__objc_classlist` | `0x360` | `0x350` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0xa68` | `0xa70` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x108` | `0x100` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x628` | `0x620` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-1032.0.0.0.0
+1034.0.0.0.0

-  Functions: 525
-  Symbols:   1514
-  CStrings:  852
+  Functions: 520
+  Symbols:   1500
+  CStrings:  844
Symbols:
+ GCC_except_table215
+ GCC_except_table217
+ GCC_except_table219
+ GCC_except_table223
+ GCC_except_table24
+ GCC_except_table252
+ GCC_except_table277
+ GCC_except_table283
+ GCC_except_table287
+ GCC_except_table289
+ GCC_except_table351
+ GCC_except_table486
+ GCC_except_table492
+ GCC_except_table494
+ GCC_except_table516
+ GCC_except_table52
+ GCC_except_table55
+ GCC_except_table76
+ GCC_except_table80
+ GCC_except_table84
+ ___block_descriptor_80_e8_32s40s48s56r64r_e5_v8?0lr56l8s32l8s40l8s48l8r64l8
+ _objc_msgSend$_usesColorPickerForEditMode:
- +[NTKCCFaceAddedInfoViewControllerAccessibility _accessibilityPerformValidations:]
- +[NTKCCFaceAddedInfoViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[NTKCCFaceAddedInfoViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[NTKCCFaceAddedInfoViewControllerAccessibility _accessibilityLoadAccessibilityInformation]
- -[NTKCCFaceAddedInfoViewControllerAccessibility viewDidLoad]
- GCC_except_table220
- GCC_except_table222
- GCC_except_table224
- GCC_except_table228
- GCC_except_table257
- GCC_except_table282
- GCC_except_table288
- GCC_except_table29
- GCC_except_table292
- GCC_except_table294
- GCC_except_table356
- GCC_except_table491
- GCC_except_table497
- GCC_except_table499
- GCC_except_table521
- GCC_except_table57
- GCC_except_table60
- GCC_except_table81
- GCC_except_table85
- GCC_except_table89
- _OBJC_CLASS_$_NTKCCFaceAddedInfoViewControllerAccessibility
- _OBJC_CLASS_$___NTKCCFaceAddedInfoViewControllerAccessibility_super
- _OBJC_METACLASS_$_NTKCCFaceAddedInfoViewControllerAccessibility
- _OBJC_METACLASS_$___NTKCCFaceAddedInfoViewControllerAccessibility_super
- __OBJC_$_CLASS_METHODS_NTKCCFaceAddedInfoViewControllerAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_NTKCCFaceAddedInfoViewControllerAccessibility
- __OBJC_CLASS_RO_$_NTKCCFaceAddedInfoViewControllerAccessibility
- __OBJC_CLASS_RO_$___NTKCCFaceAddedInfoViewControllerAccessibility_super
- __OBJC_METACLASS_RO_$_NTKCCFaceAddedInfoViewControllerAccessibility
- __OBJC_METACLASS_RO_$___NTKCCFaceAddedInfoViewControllerAccessibility_super
- ___block_descriptor_72_e8_32s40s48s56r_e5_v8?0lr56l8s32l8s40l8s48l8
CStrings:
- "NTKCCFaceAddedInfoViewController"
- "NTKCCFaceAddedInfoViewControllerAccessibility"
- "NTKVideoListingAccessibility"
- "UIButton"
- "__NTKCCFaceAddedInfoViewControllerAccessibility_super"
- "_close"
- "_header"
- "close.button"
```
