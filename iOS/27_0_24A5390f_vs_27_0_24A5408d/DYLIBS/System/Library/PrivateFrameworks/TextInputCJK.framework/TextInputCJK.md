## TextInputCJK

> `/System/Library/PrivateFrameworks/TextInputCJK.framework/TextInputCJK`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f1d4` | `0x1f274` | **`+0xa0`** |
| `__AUTH_CONST.__objc_intobj` | `0x120` | `0x150` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x2880` | `0x2860` | **`-0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x330` | `0x348` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0xdc0` | `0xdd0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c88` | `0x1c98` | **`+0x10`** |
| `__TEXT.__cstring` | `0xfe8` | `0xfe3` | **`-0x5`** |

### Other Changes

```diff

-3562.0.0.0.0
+3567.0.0.0.0
Symbols:
+ ___block_descriptor_89_a8_32s40s48s56s64s72s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8
- ___block_descriptor_88_a8_32s40s48s56s64s72s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8
Functions:
~ -[TIKeyboardInputManagerChinese generateCompletions] : 668 -> 700
~ ___52-[TIKeyboardInputManagerChinese generateCompletions]_block_invoke : 808 -> 784
~ -[TIWordSearchChinesePhonetic chaiziCandidatesWithOperation:candidateResultSet:] : 2232 -> 2384
CStrings:
+ "i"
- "%@%@%@"
```
