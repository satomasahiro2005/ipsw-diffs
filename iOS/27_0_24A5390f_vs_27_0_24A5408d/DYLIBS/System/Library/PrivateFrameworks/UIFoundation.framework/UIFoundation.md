## UIFoundation

> `/System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x109194` | `0x109284` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x10280` | `0x102c3` | **`+0x43`** |
| `__TEXT.__gcc_except_tab` | `0x3510` | `0x3540` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xcac0` | `0xcae0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x9220` | `0x9240` | **`+0x20`** |
| `__TEXT.__const` | `0x76c` | `0x78c` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3fd0` | `0x3fe0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x12e0` | `0x12e8` | **`+0x8`** |

### Other Changes

```diff

-1054.0.0.0.0
+1056.0.0.0.0

-  Functions: 5352
-  Symbols:   9339
-  CStrings:  3219
+  Functions: 5351
+  Symbols:   9342
+  CStrings:  3220
Symbols:
+ __CFCharacterSetIsLongCharacterMemberForInline
+ _____NSTextContentStorageGetTextElementAtIndex_block_invoke_3
+ ___block_descriptor_56_e18_"NSString"16?08l
CStrings:
+ "%@: Requested an index (%lu) beyond attributed string length (%lu)"
```
