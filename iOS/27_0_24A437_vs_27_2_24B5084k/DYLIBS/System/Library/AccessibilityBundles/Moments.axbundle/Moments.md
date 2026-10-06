## Moments

> `/System/Library/AccessibilityBundles/Moments.axbundle/Moments`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a04` | `0x1280` | **`-0x784`** |
| `__AUTH_CONST.__cfstring` | `0x640` | `0x540` | **`-0x100`** |
| `__TEXT.__cstring` | `0x70d` | `0x665` | **`-0xa8`** |
| `__DATA_CONST.__objc_selrefs` | `0x160` | `0x118` | **`-0x48`** |
| `__TEXT.__objc_methlist` | `0x494` | `0x450` | **`-0x44`** |
| `__DATA_CONST.__const` | `0xd0` | `0xa8` | **`-0x28`** |
| `__DATA_CONST.__got` | `0x88` | `0x68` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x120` | `0x100` | **`-0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x28` | `0x18` | **`-0x10`** |
| `__DATA.__bss` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 84
-  Symbols:   276
-  CStrings:  63
+  Functions: 76
+  Symbols:   255
+  CStrings:  54
Symbols:
- -[MOSuggestionCollectionViewCellAccessibility accessibilityCustomActions]
- -[MOSuggestionCollectionViewCellAccessibility accessibilityHint]
- -[MOSuggestionCollectionViewCellAccessibility accessibilityLabel]
- -[MOSuggestionCollectionViewSingleAssetCellAccessibility accessibilityLabel]
- -[MapImageViewAccessibility accessibilityLabel]
- -[ReflectionPromptViewAccessibility accessibilityCustomActions]
- _OBJC_CLASS_$_NSBundle
- _OBJC_CLASS_$_NSString
- _OBJC_CLASS_$_UIAccessibilityCustomAction
- _OBJC_CLASS_$_UIButton
- ___73-[MOSuggestionCollectionViewCellAccessibility accessibilityCustomActions]_block_invoke
- ___block_descriptor_40_e8_32s_e37_B16?0"UIAccessibilityCustomAction"8ls32l8
- _accessibilityJurassicLocalizedString
- _accessibilityJurassicLocalizedString.axBundle
- _objc_alloc
- _objc_release_x23
- _objc_release_x24
- _objc_release_x25
- _objc_release_x8
- _objc_retain
- _objc_retain_x22
CStrings:
- ""
- "%lu"
- "Accessibility-Jurassic"
- "B16@?0@\"UIAccessibilityCustomAction\"8"
- "map"
- "shuffle.reflection"
- "suggestion.cell.collapsed.hint"
- "suggestion.elements"
- "suggestion.write.about.this"
```
