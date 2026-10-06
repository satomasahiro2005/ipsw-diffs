## TextToSpeechBundleSupport

> `/System/Library/PrivateFrameworks/TextToSpeechBundleSupport.framework/TextToSpeechBundleSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ced8` | `0x1c9c0` | **`-0x518`** |
| `__AUTH_CONST.__objc_const` | `0x8f0` | `0x7c0` | **`-0x130`** |
| `__TEXT.__objc_methlist` | `0x2e4` | `0x26c` | **`-0x78`** |
| `__AUTH.__objc_data` | `0x140` | `0xf0` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x6f0` | `0x6b4` | **`-0x3c`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a8` | `0x280` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x6b8` | `0x690` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0xab0` | `0xad0` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0x200` | `0x220` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4bf` | `0x4cc` | **`+0xd`** |
| `__DATA.__objc_ivar` | `0x48` | `0x3c` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x270` | `0x278` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x28` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x10` | `0x8` | **`-0x8`** |

### Other Changes

```diff

-723.3.0.0.0
+727.3.0.0.0

-  Functions: 423
-  Symbols:   564
-  CStrings:  97
+  Functions: 414
+  Symbols:   548
+  CStrings:  98
Symbols:
+ GCC_except_table33
+ GCC_except_table34
+ GCC_except_table40
+ GCC_except_table43
+ GCC_except_table44
+ GCC_except_table53
+ GCC_except_table60
+ GCC_except_table62
+ GCC_except_table64
+ GCC_except_table65
+ GCC_except_table82
+ GCC_except_table83
+ _OBJC_CLASS_$_NSException
+ __ZSt9terminatev
+ __ZTISt9exception
+ ___clang_call_terminate
+ ___cxa_begin_catch
+ ___cxa_end_catch
+ _objc_alloc
+ _objc_exception_throw
- -[TTSNeuralStyle .cxx_destruct]
- -[TTSNeuralStyle getStyleVector]
- -[TTSNeuralStyle initWithName:vector:]
- -[TTSNeuralStyle key]
- -[TTSNeuralStyle name]
- -[TTSNeuralStyle setKey:]
- -[TTSNeuralStyle setName:]
- -[TTSNeuralStyle setStyleVector:]
- -[TTSNeuralStyle styleVector]
- GCC_except_table11
- GCC_except_table13
- GCC_except_table47
- GCC_except_table48
- GCC_except_table54
- GCC_except_table55
- GCC_except_table63
- GCC_except_table7
- GCC_except_table72
- GCC_except_table74
- GCC_except_table80
- GCC_except_table85
- GCC_except_table92
- GCC_except_table93
- _OBJC_CLASS_$_TTSNeuralStyle
- _OBJC_IVAR_$_TTSNeuralStyle._key
- _OBJC_IVAR_$_TTSNeuralStyle._name
- _OBJC_IVAR_$_TTSNeuralStyle._styleVector
- _OBJC_METACLASS_$_TTSNeuralStyle
- __OBJC_$_INSTANCE_METHODS_TTSNeuralStyle
- __OBJC_$_INSTANCE_VARIABLES_TTSNeuralStyle
- __OBJC_$_PROP_LIST_TTSNeuralStyle
- __OBJC_CLASS_RO_$_TTSNeuralStyle
- __OBJC_METACLASS_RO_$_TTSNeuralStyle
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEE24__emplace_back_slow_pathIJfEEEPfDpOT_
- _objc_enumerationMutation
CStrings:
+ "CXXException"
```
