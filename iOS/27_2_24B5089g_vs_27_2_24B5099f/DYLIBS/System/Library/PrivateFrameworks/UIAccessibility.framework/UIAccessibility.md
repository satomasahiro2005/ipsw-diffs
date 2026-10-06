## UIAccessibility

> `/System/Library/PrivateFrameworks/UIAccessibility.framework/UIAccessibility`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d3c8` | `0x6d460` | **`+0x98`** |
| `__TEXT.__oslogstring` | `0x2ce3` | `0x2d31` | **`+0x4e`** |
| `__DATA_CONST.__const` | `0x15c8` | `0x15a0` | **`-0x28`** |
| `__TEXT.__gcc_except_tab` | `0xda0` | `0xdb8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x5768` | `0x5770` | **`+0x8`** |

### Other Changes

```diff

-3245.8.2.0.0
+3245.8.4.2.0

-  Symbols:   4593
-  CStrings:  1188
+  Symbols:   4592
+  CStrings:  1189
Symbols:
- ___block_descriptor_48_e8_32bs_e8_B16?08ls32l8
Functions:
~ __copyElementAtPositionCallback : 4692 -> 4824
~ -[UIAccessibilityAutoscrollManager pause] : 240 -> 244
~ +[UIAccessibilityHitTestOptions dwellControlElementHighlightOptions] : 352 -> 340
~ ___68+[UIAccessibilityHitTestOptions dwellControlElementHighlightOptions]_block_invoke_4 : 196 -> 224
CStrings:
+ "Hit testing for Dwell Control, so only elements it can highlight are eligible"
```
