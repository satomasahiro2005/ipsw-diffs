## CTParser

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CTParser.framework/CTParser`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a40` | `0x5924` | **`-0x11c`** |
| `__TEXT.__gcc_except_tab` | `0x5f8` | `0x610` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x166` | `0x14e` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x4b0` | `0x4a8` | **`-0x8`** |

### Other Changes

```diff

-13487.3.0.0.0
+13487.6.0.0.0

-  Functions: 227
-  Symbols:   449
-  CStrings:  35
+  Functions: 225
+  Symbols:   448
+  CStrings:  34
Symbols:
+ GCC_except_table25
+ GCC_except_table35
+ GCC_except_table41
+ GCC_except_table49
+ GCC_except_table51
+ GCC_except_table57
- GCC_except_table32
- GCC_except_table37
- GCC_except_table50
- GCC_except_table53
- GCC_except_table60
- __ZNK3xpc4dict15to_debug_stringEv
- __os_log_debug_impl
CStrings:
- "Received XPC object: %s"
```
