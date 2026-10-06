## CVNLP

> `/System/Library/PrivateFrameworks/CVNLP.framework/CVNLP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcb7a8` | `0xcb888` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x7ce` | `0x7f8` | **`+0x2a`** |
| `__TEXT.__gcc_except_tab` | `0xdea0` | `0xdeb8` | **`+0x18`** |

### Other Changes

```diff

-129.0.0.0.0
+130.0.0.0.0

-  CStrings:  812
+  CStrings:  813
Functions:
~ _CVNLPLanguageModelCreate : 6600 -> 6824
CStrings:
+ "Failed to create CVNLP language model: %s"
```
