## NumberAdder

> `/System/Library/PrivateFrameworks/NumberAdder.framework/NumberAdder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdd0` | `0xe0c` | **`+0x3c`** |
| `__TEXT.__gcc_except_tab` | `0xe4` | `0xd4` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x148` | `0x138` | **`-0x10`** |

### Other Changes

```diff

-  Symbols:   137
+  Symbols:   134
Symbols:
+ GCC_except_table21
+ ____ZN19CLConnectionDeleterclEP12CLConnection_block_invoke
+ _objc_release_x21
- GCC_except_table22
- GCC_except_table25
- __ZSt9terminatev
- ___clang_call_terminate
- ___cxa_begin_catch
- _objc_release
Functions:
~ ___19-[NumberAdder init]_block_invoke : 236 -> 224
~ ___clang_call_terminate -> __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em : 20 -> 144
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em -> __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev : 144 -> 24
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev -> __ZNSt3__120__throw_length_errorB9fqe220106EPKc : 24 -> 92
~ __ZNSt3__120__throw_length_errorB9fqe220106EPKc -> __ZNSt12length_errorC1B9fqe220106EPKc : 92 -> 52
~ __ZNSt12length_errorC1B9fqe220106EPKc -> ____ZL43_CLLogObjectForCategory_NumberAdder_Defaultv_block_invoke : 52 -> 48
~ ____ZL43_CLLogObjectForCategory_NumberAdder_Defaultv_block_invoke -> __ZNSt3__110unique_ptrI12CLConnection19CLConnectionDeleterE5resetB9fqe220106EPS1_ : 48 -> 128
~ __ZNSt3__110unique_ptrI12CLConnection19CLConnectionDeleterE5resetB9fqe220106EPS1_ -> ____ZN19CLConnectionDeleterclEP12CLConnection_block_invoke : 44 -> 8
```
