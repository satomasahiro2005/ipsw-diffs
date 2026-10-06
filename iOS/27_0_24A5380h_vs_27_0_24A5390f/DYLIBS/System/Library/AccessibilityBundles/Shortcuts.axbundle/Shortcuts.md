## Shortcuts

> `/System/Library/AccessibilityBundles/Shortcuts.axbundle/Shortcuts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb00` | `0x1228` | **`+0x728`** |
| `__AUTH_CONST.__cfstring` | `0x3c0` | `0x460` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x286` | `0x307` | **`+0x81`** |
| `__DATA_CONST.__objc_selrefs` | `0xe8` | `0x168` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x90` | `0x108` | **`+0x78`** |
| `__DATA_CONST.__got` | `0x40` | `0x80` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xb8` | `0xe0` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xd4` | `0xec` | **`+0x18`** |
| `__TEXT.__const` | `0x8` | `0x10` | **`+0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 23
-  Symbols:   95
-  CStrings:  36
+  Functions: 30
+  Symbols:   132
+  CStrings:  43
Symbols:
+ -[LibraryCellAccessibility _axAppendCustomActionsForMenuElements:intoArray:]
+ -[LibraryCellAccessibility _axAutoShortcutContextMenuCustomActions]
+ GCC_except_table8
+ _CGPointZero
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSBlock
+ _OBJC_CLASS_$_UIAction
+ _OBJC_CLASS_$_UICollectionView
+ _OBJC_CLASS_$_UIMenu
+ __Block_object_dispose
+ __Unwind_Resume
+ ___67-[LibraryCellAccessibility _axAutoShortcutContextMenuCustomActions]_block_invoke
+ ___76-[LibraryCellAccessibility _axAppendCustomActionsForMenuElements:intoArray:]_block_invoke
+ ___76-[LibraryCellAccessibility _axAppendCustomActionsForMenuElements:intoArray:]_block_invoke_2
+ ___Block_byref_object_copy_
+ ___Block_byref_object_dispose_
+ ___NSArray0__struct
+ ___UIAccessibilityCastAsClass
+ ___block_descriptor_40_e8_32s_e37_B16?0"UIAccessibilityCustomAction"8ls32l8
+ ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_64_e8_32s40s48s56r_e5_v8?0lr56l8s32l8s40l8s48l8
+ ___objc_personality_v0
+ ___stack_chk_fail
+ ___stack_chk_guard
+ _abort
+ _objc_enumerationMutation
+ _objc_opt_isKindOfClass
+ _objc_release_x24
+ _objc_release_x25
+ _objc_release_x26
+ _objc_release_x27
+ _objc_release_x28
+ _objc_release_x9
+ _objc_retain_x19
+ _objc_retain_x22
+ _objc_retain_x23
+ _objc_retain_x25
CStrings:
+ "\n"
+ " "
+ "@?"
+ "UIContextMenuConfiguration"
+ "actionProvider"
+ "collectionView:contextMenuConfigurationForItemsAtIndexPaths:point:"
+ "{CGPoint=dd}"
```
