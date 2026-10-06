## EmailCore

> `/System/Library/PrivateFrameworks/EmailCore.framework/EmailCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5be50` | `0x5cf04` | **`+0x10b4`** |
| `__TEXT.__gcc_except_tab` | `0x728c` | `0x7344` | **`+0xb8`** |
| `__AUTH_CONST.__cfstring` | `0x53e0` | `0x5480` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0xa900` | `0xa990` | **`+0x90`** |
| `__AUTH.__objc_data` | `0xa38` | `0xa88` | **`+0x50`** |
| `__TEXT.__cstring` | `0x833e` | `0x837e` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x2230` | `0x2258` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x50e8` | `0x5108` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a60` | `0x2a78` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2aa8` | `0x2ab8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa20` | `0xa28` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x6a8` | `0x6b0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x350` | `0x358` | **`+0x8`** |

### Other Changes

```diff

-3901.200.34.0.0
+3901.200.41.0.0

-  Functions: 2048
-  Symbols:   4170
-  CStrings:  1534
+  Functions: 2051
+  Symbols:   4180
+  CStrings:  1540
Symbols:
+ +[ECMessageBodyParsingUtils strippedQuoteBlockFromHTMLBody:]
+ +[ECQuoteParser strippedQuoteBlockFromHTMLBody:]
+ _CFStringCompareWithOptions
+ _OBJC_CLASS_$_ECQuoteParser
+ _OBJC_METACLASS_$_ECQuoteParser
+ __OBJC_$_CLASS_METHODS_ECQuoteParser
+ __OBJC_CLASS_RO_$_ECQuoteParser
+ __OBJC_METACLASS_RO_$_ECQuoteParser
+ ___48+[ECQuoteParser strippedQuoteBlockFromHTMLBody:]_block_invoke
+ ___block_descriptor_40_ea8_32s_e24_v32?0{_NSRange=QQ}8^B24ls32l8
CStrings:
+ "/blockquote"
+ "/div"
+ "/span"
+ "head"
+ "span"
+ "v32@?0{_NSRange=QQ}8^B24"
```
