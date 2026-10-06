## TypistFramework

> `/System/Library/PrivateFrameworks/TypistFramework.framework/TypistFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43240` | `0x43ae0` | **`+0x8a0`** |
| `__AUTH_CONST.__const` | `0x628` | `0x788` | **`+0x160`** |
| `__AUTH_CONST.__cfstring` | `0x116e0` | `0x11820` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x3944` | `0x3a2c` | **`+0xe8`** |
| `__DATA.__bss` | `0x2f0` | `0x3a0` | **`+0xb0`** |
| `__AUTH_CONST.__objc_const` | `0x4b58` | `0x4be8` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x2540` | `0x25d0` | **`+0x90`** |
| `__TEXT.__ustring` | `0x1362` | `0x13ea` | **`+0x88`** |
| `__AUTH.__objc_data` | `0xdb8` | `0xe08` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xe80` | `0xe90` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x188` | `0x190` | **`+0x8`** |

### Other Changes

```diff

-498.0.0.0.0
+499.1.0.0.0

-  Functions: 1339
-  Symbols:   2321
-  CStrings:  2285
+  Functions: 1379
+  Symbols:   2377
+  CStrings:  2295
Symbols:
+ +[NSCharacterSet(Devanagari) bottomMarkCharacterSet]
+ +[NSCharacterSet(Devanagari) centerStemConsonantCharacterSet]
+ +[NSCharacterSet(Devanagari) devanagariCharacterSet]
+ +[NSCharacterSet(Devanagari) halantCharacterSet]
+ +[NSCharacterSet(Devanagari) khariPaiConsonantCharacterSet]
+ +[NSCharacterSet(Devanagari) leftMatraCharacterSet]
+ +[NSCharacterSet(Devanagari) openTopCharacterSet]
+ +[NSCharacterSet(Devanagari) raCharacterSet]
+ +[NSCharacterSet(Devanagari) rightMatraCharacterSet]
+ +[NSCharacterSet(Devanagari) roundedConsonantCharacterSet]
+ +[NSCharacterSet(Devanagari) topMarkCharacterSet]
+ +[TypistDevanagariSyllable isCenterStemConsonant:]
+ +[TypistDevanagariSyllable isDevanagariCharacter:]
+ +[TypistDevanagariSyllable isHalant:]
+ +[TypistDevanagariSyllable isKhariPaiConsonant:]
+ +[TypistDevanagariSyllable isOpenTopCharacter:]
+ +[TypistDevanagariSyllable isRa:]
+ +[TypistDevanagariSyllable isRoundedConsonant:]
+ _OBJC_CLASS_$_TypistDevanagariSyllable
+ _OBJC_METACLASS_$_TypistDevanagariSyllable
+ __OBJC_$_CLASS_METHODS_NSCharacterSet(Arabic|Cursive|Devanagari|Hangul|Latex)
+ __OBJC_$_CLASS_METHODS_TypistDevanagariSyllable
+ __OBJC_CLASS_RO_$_TypistDevanagariSyllable
+ __OBJC_METACLASS_RO_$_TypistDevanagariSyllable
+ ___44+[NSCharacterSet(Devanagari) raCharacterSet]_block_invoke
+ ___48+[NSCharacterSet(Devanagari) halantCharacterSet]_block_invoke
+ ___49+[NSCharacterSet(Devanagari) openTopCharacterSet]_block_invoke
+ ___49+[NSCharacterSet(Devanagari) topMarkCharacterSet]_block_invoke
+ ___51+[NSCharacterSet(Devanagari) leftMatraCharacterSet]_block_invoke
+ ___52+[NSCharacterSet(Devanagari) bottomMarkCharacterSet]_block_invoke
+ ___52+[NSCharacterSet(Devanagari) devanagariCharacterSet]_block_invoke
+ ___52+[NSCharacterSet(Devanagari) rightMatraCharacterSet]_block_invoke
+ ___58+[NSCharacterSet(Devanagari) roundedConsonantCharacterSet]_block_invoke
+ ___59+[NSCharacterSet(Devanagari) khariPaiConsonantCharacterSet]_block_invoke
+ ___61+[NSCharacterSet(Devanagari) centerStemConsonantCharacterSet]_block_invoke
+ _bottomMarkCharacterSet.onceToken
+ _bottomMarkCharacterSet.set
+ _centerStemConsonantCharacterSet.onceToken
+ _centerStemConsonantCharacterSet.set
+ _devanagariCharacterSet.onceToken
+ _devanagariCharacterSet.set
+ _halantCharacterSet.onceToken
+ _halantCharacterSet.set
+ _khariPaiConsonantCharacterSet.onceToken
+ _khariPaiConsonantCharacterSet.set
+ _leftMatraCharacterSet.onceToken
+ _leftMatraCharacterSet.set
+ _openTopCharacterSet.onceToken
+ _openTopCharacterSet.set
+ _raCharacterSet.onceToken
+ _raCharacterSet.set
+ _rightMatraCharacterSet.onceToken
+ _rightMatraCharacterSet.set
+ _roundedConsonantCharacterSet.onceToken
+ _roundedConsonantCharacterSet.set
+ _topMarkCharacterSet.onceToken
+ _topMarkCharacterSet.set
- __OBJC_$_CLASS_METHODS_NSCharacterSet(Arabic|Cursive|Hangul|Latex)
CStrings:
+ "कफ"
+ "खगघचजझञणतथधनपबभमयलवशषस"
+ "टठडढदछह"
+ "धभथझशअआओऔ"
+ "र"
+ "ाीोौॉ"
+ "ि"
+ "ुूृ़्"
+ "ेैॅंँ"
+ "्"
```
