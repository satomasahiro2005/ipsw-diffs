## UIFoundation

> `/System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x108dd4` | `0x108f00` | **`+0x12c`** |
| `__TEXT.__cstring` | `0x10114` | `0x101e2` | **`+0xce`** |
| `__AUTH_CONST.__cfstring` | `0xca20` | `0xca60` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3f90` | `0x3fc8` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x34ec` | `0x3504` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x68e8` | `0x68f0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xbb94` | `0xbb9c` | **`+0x8`** |

### Other Changes

```diff

-1049.0.0.0.0
+1052.1.0.0.0

-  Functions: 5352
-  Symbols:   9328
-  CStrings:  3212
+  Functions: 5349
+  Symbols:   9329
+  CStrings:  3216
Symbols:
+ -[NSTextLayoutManager enumerateBidiLevelsInTextRange:usingBlock:]
+ GCC_except_table128
+ GCC_except_table131
+ GCC_except_table140
+ GCC_except_table143
+ GCC_except_table146
+ GCC_except_table150
+ GCC_except_table154
+ GCC_except_table174
+ GCC_except_table177
+ GCC_except_table179
+ GCC_except_table181
+ GCC_except_table183
+ GCC_except_table200
+ GCC_except_table205
+ GCC_except_table207
+ GCC_except_table209
+ GCC_except_table216
+ GCC_except_table221
+ GCC_except_table225
+ GCC_except_table234
+ GCC_except_table249
+ GCC_except_table250
+ GCC_except_table251
+ GCC_except_table258
+ GCC_except_table264
+ GCC_except_table265
+ GCC_except_table266
+ ___53-[NSTextLayoutManager textLayoutFragmentForLocation:]_block_invoke_2
+ ___63-[NSTextLayoutFragment _layoutInfoForTextAttachmentAtLocation:]_block_invoke
+ ___65-[NSTextLayoutManager enumerateBidiLevelsInTextRange:usingBlock:]_block_invoke
+ ___90-[_NSTextLayoutFragmentStorage enumerateTextLayoutFragmentInTextRange:options:usingBlock:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40r_e28_v32?08"NSTextRange"16^B24ls32l8r40l8
- GCC_except_table127
- GCC_except_table139
- GCC_except_table142
- GCC_except_table144
- GCC_except_table149
- GCC_except_table152
- GCC_except_table16
- GCC_except_table173
- GCC_except_table176
- GCC_except_table178
- GCC_except_table180
- GCC_except_table182
- GCC_except_table195
- GCC_except_table199
- GCC_except_table204
- GCC_except_table206
- GCC_except_table208
- GCC_except_table215
- GCC_except_table218
- GCC_except_table231
- GCC_except_table246
- GCC_except_table247
- GCC_except_table248
- GCC_except_table255
- GCC_except_table261
- GCC_except_table262
- GCC_except_table263
- GCC_except_table57
- GCC_except_table62
- _OUTLINED_FUNCTION_105
- ___81-[NSTextLineFragment _defaultRenderingAttributesAtCharacterIndex:effectiveRange:]_block_invoke
- ___block_descriptor_48_e8_32s40r_e28_v32?08"NSTextRange"16^B24lr40l8s32l8
CStrings:
+ "%@: nil location"
+ "%@: requested for the attachment information at nil location."
+ "%@: requested to enumerate nil range."
+ "General"
+ "_NSTextLayoutFragmentStorage: offsetFromLocation:toLocation: returned NSNotFound for last fragment range adjustment. Using delta 0."
- "%@: Requested for attributes at %ld for length %ld"
```
