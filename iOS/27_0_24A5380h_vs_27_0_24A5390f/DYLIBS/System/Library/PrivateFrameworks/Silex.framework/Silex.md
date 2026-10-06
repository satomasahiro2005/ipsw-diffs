## Silex

> `/System/Library/PrivateFrameworks/Silex.framework/Silex`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1182b4` | `0x1188f0` | **`+0x63c`** |
| `__TEXT.__objc_methlist` | `0x1e63c` | `0x1e6bc` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x243c` | `0x2498` | **`+0x5c`** |
| `__DATA_CONST.__got` | `0x2560` | `0x2590` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x4f00` | `0x4f28` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xb820` | `0xb830` | **`+0x10`** |
| `__TEXT.__const` | `0x5ac` | `0x5bc` | **`+0x10`** |

### Other Changes

```diff

-5923.0.0.0.0
+5926.0.0.0.0

-  Functions: 8559
-  Symbols:   20654
+  Functions: 8569
+  Symbols:   20670
Symbols:
+ -[SXScrollView _accessibilityAttributedValueForRange:]
+ -[SXScrollView _accessibilityIsSpeakThisElement]
+ -[SXScrollView _accessibilityNumberOfCharacters]
+ -[SXScrollView _accessibilitySpeakThisIgnoresAccessibilityElementStatus]
+ -[SXScrollView _accessibilitySpeakThisString]
+ -[SXScrollView _sxaxCanvasView]
+ -[SXScrollView accessibilityAttributedStringForRange:]
+ -[SXScrollView accessibilityAttributedValue]
+ -[SXScrollView accessibilityNumberOfCharacters]
+ -[TSWPRep(SXAccessibility) accessibilityValue]
+ _NSLinkAttributeName
+ _UIAccessibilityTokenBold
+ _UIAccessibilityTokenItalic
+ _UIAccessibilityTokenListItemLevel
+ _UIAccessibilityTokenStrikethrough
+ _UIAccessibilityTokenUnderline
+ ___block_descriptor_72_e8_32s40s48r_e42_v40?0"TSWPListStyle"8{_NSRange=QQ}16^B32ls32l8s40l8r48l8
- ___block_descriptor_64_e8_32s40r_e42_v40?0"TSWPListStyle"8{_NSRange=QQ}16^B32ls32l8r40l8
```
