## UIFoundation

> `/System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x109048` | `0x109194` | **`+0x14c`** |
| `__TEXT.__cstring` | `0x1021d` | `0x10280` | **`+0x63`** |
| `__AUTH_CONST.__const` | `0x1278` | `0x12d8` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0xca80` | `0xcac0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x91f8` | `0x9220` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x12b00` | `0x12b20` | **`+0x20`** |
| `__DATA.__bss` | `0x818` | `0x820` | **`+0x8`** |
| `__DATA.__data` | `0xe19` | `0xe21` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3fc8` | `0x3fd0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1318` | `0x131c` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x350c` | `0x3510` | **`+0x4`** |

### Other Changes

```diff

-1053.0.0.0.0
+1054.0.0.0.0

-  Functions: 5349
-  Symbols:   9329
-  CStrings:  3217
+  Functions: 5352
+  Symbols:   9339
+  CStrings:  3219
Symbols:
+ +[NSRTFReader maximumNestedGroups]
+ GCC_except_table87
+ _OBJC_IVAR_$_NSRTFReader._maximumNestedGroups
+ ___34+[NSRTFReader maximumNestedGroups]_block_invoke
+ ___41-[NSWritingToolsEditTracker adjustRange:]_block_invoke
+ ___43-[NSRTFReader attributedStringToEndOfGroup]_block_invoke
+ ___45-[NSWritingToolsEditTracker _adjustLocation:]_block_invoke
+ ___block_descriptor_40_e8_32o_e18_"NSString"16?08ls32l8
+ _maximumNestedGroups._maximumNestedGroups
+ _maximumNestedGroups.onceToken
CStrings:
+ "Encountered an RTF document with groups nested beyond the limit %ul"
+ "__NSDefaultMaximumNestedGroups"
```
