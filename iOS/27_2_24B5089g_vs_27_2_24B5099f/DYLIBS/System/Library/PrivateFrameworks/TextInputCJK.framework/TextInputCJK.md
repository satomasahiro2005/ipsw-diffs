## TextInputCJK

> `/System/Library/PrivateFrameworks/TextInputCJK.framework/TextInputCJK`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f518` | `0x1f6b8` | **`+0x1a0`** |
| `__AUTH_CONST.__objc_const` | `0x29b8` | `0x2a18` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ca8` | `0x1ce0` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x1f20` | `0x1f50` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x530` | `0x538` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1ac` | `0x1b4` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x428` | `0x430` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6c8` | `0x6d0` | **`+0x8`** |

### Other Changes

```diff

-3568.1.4.0.0
+3568.1.8.0.0

-  Functions: 698
-  Symbols:   1436
+  Functions: 702
+  Symbols:   1444
Symbols:
+ -[TIWordSearchChinesePhonetic chaiziMecabraEnvironment]
+ -[TIWordSearchChinesePhonetic chaiziMecabraWrapper]
+ -[TIWordSearchChinesePhonetic setChaiziMecabraEnvironment:]
+ -[TIWordSearchChinesePhonetic setChaiziMecabraWrapper:]
+ _OBJC_CLASS_$_TIMecabraWrapper
+ _OBJC_IVAR_$_TIWordSearchChinesePhonetic._chaiziMecabraEnvironment
+ _OBJC_IVAR_$_TIWordSearchChinesePhonetic._chaiziMecabraWrapper
+ _objc_retainAutoreleasedReturnValue
```
