## DoubleAgent

> `/System/Library/PrivateFrameworks/DoubleAgent.framework/DoubleAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d70` | `0x3e40` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x47e` | `0x4fc` | **`+0x7e`** |

### Other Changes

```diff

-46.0.0.0.0
+46.0.1.0.0

-  Functions: 103
-  Symbols:   179
-  CStrings:  46
+  Functions: 105
+  Symbols:   180
+  CStrings:  47
Symbols:
+ _OUTLINED_FUNCTION_10
Functions:
~ -[AppleDoubleParser createAttrHeaderIfNeeded:] : 672 -> 788
~ _OUTLINED_FUNCTION_9 : 12 -> 20
+ _OUTLINED_FUNCTION_10
~ -[AppleDoubleParser createAttrHeaderIfNeeded:].cold.1 : 96 -> 84
+ -[AppleDoubleParser createAttrHeaderIfNeeded:].cold.4
CStrings:
+ "%s: resource fork offset (0x%x) is invalid when there are no other extended attributes; rejecting malformed AppleDouble file."
```
