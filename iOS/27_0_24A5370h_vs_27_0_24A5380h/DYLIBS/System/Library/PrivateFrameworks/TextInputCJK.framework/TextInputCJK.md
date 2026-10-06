## TextInputCJK

> `/System/Library/PrivateFrameworks/TextInputCJK.framework/TextInputCJK`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1edd8` | `0x1f228` | **`+0x450`** |
| `__TEXT.__cstring` | `0xfbc` | `0x1006` | **`+0x4a`** |
| `__AUTH_CONST.__cfstring` | `0x2880` | `0x28c0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x758` | `0x780` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c68` | `0x1c88` | **`+0x20`** |
| `__DATA.__bss` | `0x100` | `0x110` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x418` | `0x420` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1f08` | `0x1f00` | **`-0x8`** |

### Other Changes

```diff

-3557.15.100.0.0
+3559.100.0.0.0

-  Functions: 691
-  Symbols:   1424
-  CStrings:  373
+  Functions: 695
+  Symbols:   1430
+  CStrings:  375
Symbols:
+ +[TIKeyboardInputManagerChinese closingPunctuationMarkForContextBeforeInput:contextAfterInput:]
+ +[TIKeyboardInputManagerChinese closingPunctuationMarkSet]
+ -[TIKeyboardInputManagerPinyin supportsPairedPunctutationInput]
+ _OBJC_CLASS_$_NSSet
+ __ZZ58+[TIKeyboardInputManagerChinese closingPunctuationMarkSet]E11__onceToken
+ __ZZ58+[TIKeyboardInputManagerChinese closingPunctuationMarkSet]E27__closingPunctuationMarkSet
+ ___58+[TIKeyboardInputManagerChinese closingPunctuationMarkSet]_block_invoke
+ ___95+[TIKeyboardInputManagerChinese closingPunctuationMarkForContextBeforeInput:contextAfterInput:]_block_invoke
+ ___block_descriptor_72_a8_32s40s48r56r64r_e52_v56?0"NSString"8{_NSRange=QQ}16{_NSRange=QQ}32^B48lr48l8s32l8r56l8s40l8r64l8
+ ___block_descriptor_88_a8_32s40s48s56s64s72s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8
- -[TIKeyboardInputManagerChinese rightContextAdjacentToCaretContainsText]
- -[TIKeyboardInputManagerChinese shouldUsePairedPunctuationWhenCharacterAfterCaretIsText]
- -[TIKeyboardInputManagerChinesePhonetic shouldUsePairedPunctuationWhenCharacterAfterCaretIsText]
- ___block_descriptor_80_a8_32s40s48s56s64s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
CStrings:
+ "%s [Environment] Set left context: %{sensitive}@, Right context: %{sensitive}@, On-screen length: %@"
+ "com.tencent.xin"
+ "jp.naver.line"
- "%s [Environment] Set left context: %@, Right context: %@"
```
