## AVFAudio

> `/System/Library/Frameworks/AVFAudio.framework/AVFAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x280` | `0x1220` | **`+0xfa0`** |
| `__DATA_DIRTY.__objc_data` | `0x1db0` | `0xe10` | **`-0xfa0`** |
| `__TEXT.__text` | `0x113b58` | `0x113af0` | **`-0x68`** |
| `__TEXT.__const` | `0xba0` | `0xb80` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x62f8` | `0x6318` | **`+0x20`** |
| `__DATA.__data` | `0x948` | `0x930` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x12548` | `0x12560` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x268` | `0x256` | **`-0x12`** |
| `__DATA.__bss` | `0x7a0` | `0x790` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x6b0` | `0x6b8` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x30` | `0x38` | **`+0x8`** |

### Other Changes

```diff

-790.0.0.0.0
+792.0.0.0.0

-  Functions: 4139
-  Symbols:   8067
+  Functions: 4136
+  Symbols:   8065
Symbols:
+ GCC_except_table717
+ GCC_except_table838
- _get_type_metadata s11MutableSpanVySfG noncopyable
- _get_type_metadata s11MutableSpanVys5Int16VG noncopyable
- _get_type_metadata s11MutableSpanVys5Int32VG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
```
