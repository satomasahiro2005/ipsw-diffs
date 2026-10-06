## SearchFoundation

> `/System/Library/PrivateFrameworks/SearchFoundation.framework/SearchFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c4ccc` | `0x3c5dc8` | **`+0x10fc`** |
| `__AUTH_CONST.__objc_const` | `0xafb30` | `0xb02e0` | **`+0x7b0`** |
| `__TEXT.__objc_methlist` | `0x579d4` | `0x57a34` | **`+0x60`** |
| `__TEXT.__cstring` | `0xbd40` | `0xbd60` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x79e0` | `0x79f0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x45b8` | `0x45c0` | **`+0x8`** |
| `__TEXT.__const` | `0x88` | `0x80` | **`-0x8`** |

### Other Changes

```diff

-3600.56.26.11.2
+3605.21.1.1.1

-  Functions: 17809
-  Symbols:   33368
-  CStrings:  2490
+  Functions: 17813
+  Symbols:   33374
+  CStrings:  2491
Symbols:
+ -[SFCardSection setTextual_form:]
+ -[SFCardSection textual_form]
+ -[_SFPBCardSection setTextual_form:]
+ -[_SFPBCardSection textual_form]
+ GCC_except_table8186
+ _OBJC_IVAR_$_SFCardSection._textual_form
+ _OBJC_IVAR_$__SFPBCardSection._textual_form
+ _os_variant_has_internal_diagnostics
- GCC_except_table8184
- _MGGetBoolAnswer
CStrings:
+ "O\r"
+ "com.apple.siri.parsec.CoreParsec"
+ "textualForm"
- "InternalBuild"
- "O\f"
```
