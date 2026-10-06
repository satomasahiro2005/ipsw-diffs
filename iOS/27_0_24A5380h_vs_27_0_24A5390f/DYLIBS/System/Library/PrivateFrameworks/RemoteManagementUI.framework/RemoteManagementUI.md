## RemoteManagementUI

> `/System/Library/PrivateFrameworks/RemoteManagementUI.framework/RemoteManagementUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77f8` | `0x7900` | **`+0x108`** |
| `__DATA_CONST.__objc_arraydata` | `0x120` | `0x1c0` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0xa0` | `0xe0` | **`+0x40`** |
| `__AUTH_CONST.__objc_dictobj` | `0x50` | `0x78` | **`+0x28`** |
| `__TEXT.__cstring` | `0x7f6` | `0x817` | **`+0x21`** |
| `__AUTH_CONST.__cfstring` | `0x8a0` | `0x8c0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x6e0` | `0x700` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xb8` | `0xa4` | **`-0x14`** |
| `__DATA.__bss` | `0x40` | `0x50` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x340` | `0x338` | **`-0x8`** |
| `__TEXT.__const` | `0x90` | `0x88` | **`-0x8`** |

### Other Changes

```diff

-624.0.8.0.0
+624.0.10.0.0

-  Functions: 290
-  Symbols:   602
-  CStrings:  116
+  Functions: 292
+  Symbols:   604
+  CStrings:  117
Symbols:
+ GCC_except_table13
+ ___57-[RMUIPluginViewModelProvider _symbolForDeclarationType:]_block_invoke_2
+ ___block_descriptor_32_e31_q24?0"NSString"8"NSString"16l
+ __symbolForDeclarationType:.onceToken
+ __symbolForDeclarationType:.sortedPrefixes
- GCC_except_table10
- GCC_except_table12
- ___block_descriptor_48_e8_32s40r_e35_v32?0"NSString"8"NSNumber"16^B24ls32l8r40l8
Functions:
~ -[RMUIPluginViewModelProvider _symbolForDeclarationType:] : 224 -> 344
~ ___57-[RMUIPluginViewModelProvider _symbolForDeclarationType:]_block_invoke : 128 -> 100
+ ___57-[RMUIPluginViewModelProvider _symbolForDeclarationType:]_block_invoke_2
CStrings:
+ "com.apple.configuration.app.settings"
+ "q24@?0@\"NSString\"8@\"NSString\"16"
- "v32@?0@\"NSString\"8@\"NSNumber\"16^B24"
```
