## TextInputCJK

> `/System/Library/PrivateFrameworks/TextInputCJK.framework/TextInputCJK`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f228` | `0x1f1d4` | **`-0x54`** |
| `__AUTH_CONST.__cfstring` | `0x28c0` | `0x2880` | **`-0x40`** |
| `__TEXT.__cstring` | `0x1006` | `0xfe8` | **`-0x1e`** |

### Other Changes

```diff

-3559.100.0.0.0
+3562.0.0.0.0

-  CStrings:  375
+  CStrings:  373
Functions:
~ -[TIKeyboardInputManagerChinese generateCompletions] : 784 -> 668
~ +[TIKeyboardInputManagerChinese closingPunctuationMarkForContextBeforeInput:contextAfterInput:] : 540 -> 572
CStrings:
- "com.tencent.xin"
- "jp.naver.line"
```
