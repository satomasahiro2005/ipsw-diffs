## ProofReader

> `/System/Library/PrivateFrameworks/ProofReader.framework/ProofReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x9b80` | `0x9ca0` | **`+0x120`** |
| `__TEXT.__text` | `0xbdad0` | `0xbdbf0` | **`+0x120`** |
| `__TEXT.__cstring` | `0x9681` | `0x96f4` | **`+0x73`** |
| `__DATA_CONST.__got` | `0x320` | `0x348` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0xfe8` | `0x1008` | **`+0x20`** |
| `__DATA.__bss` | `0x518` | `0x500` | **`-0x18`** |
| `__DATA_DIRTY.__bss` | `0xb40` | `0xb58` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x28e8` | `0x2900` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c78` | `0x1c88` | **`+0x10`** |

### Other Changes

```diff

-689.0.0.0.0
+693.0.0.0.0

-  Functions: 1807
-  Symbols:   3092
-  CStrings:  4759
+  Functions: 1809
+  Symbols:   3095
+  CStrings:  4768
Symbols:
+ -[PRLanguage isChinese]
+ -[PRLanguage isJapanese]
+ ___NSArray0__struct
CStrings:
+ "Chinese"
+ "Japanese"
+ "Simplified Chinese"
+ "SimplifiedChinese"
+ "Traditional Chinese"
+ "TraditionalChinese"
+ "ja_JP"
+ "zh_Hans"
+ "zh_Hant"
```
