## HealthMedicationsUI

> `/System/Library/AccessibilityBundles/HealthMedicationsUI.axbundle/HealthMedicationsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10e8` | `0x11e4` | **`+0xfc`** |
| `__DATA_CONST.__const` | `0x60` | `0x88` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x108` | `0x120` | **`+0x18`** |
| `__TEXT.__const` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x48` | `0x50` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x148` | `0x150` | **`+0x8`** |
| `__TEXT.__cstring` | `0x6bd` | `0x6c3` | **`+0x6`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 77
-  Symbols:   259
-  CStrings:  68
+  Functions: 78
+  Symbols:   267
+  CStrings:  69
Symbols:
+ GCC_except_table5
+ _AXPerformSafeBlock
+ __Block_object_dispose
+ __NSConcreteStackBlock
+ __Unwind_Resume
+ ___69-[MedicationDoseLogMedicationViewAccessibility _axUpdateButtonTraits]_block_invoke
+ ___block_descriptor_48_e8_32s40r_e5_v8?0lr40l8s32l8
+ ___objc_personality_v0
Functions:
~ -[MedicationDoseLogMedicationViewAccessibility _axUpdateButtonTraits] : 288 -> 424
+ ___69-[MedicationDoseLogMedicationViewAccessibility _axUpdateButtonTraits]_block_invoke
CStrings:
+ "v8@?0"
```
