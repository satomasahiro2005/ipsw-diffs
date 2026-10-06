## TypistFramework

> `/System/Library/PrivateFrameworks/TypistFramework.framework/TypistFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41fb4` | `0x422a4` | **`+0x2f0`** |
| `__TEXT.__gcc_except_tab` | `0xc40` | `0xd1c` | **`+0xdc`** |
| `__AUTH_CONST.__objc_const` | `0x4a38` | `0x4a68` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x115a0` | `0x11580` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x8d8` | `0x8f8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5902` | `0x5922` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2468` | `0x2480` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x3814` | `0x382c` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x3c28` | `0x3c18` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xe30` | `0xe40` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x530` | `0x538` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2b0` | `0x2b4` | **`+0x4`** |
| `__TEXT.__ustring` | `0x1366` | `0x1362` | **`-0x4`** |

### Other Changes

```diff

-489.0.0.0.0
+491.0.0.0.0

-  Functions: 1308
-  Symbols:   2276
-  CStrings:  2275
+  Functions: 1312
+  Symbols:   2284
+  CStrings:  2274
Symbols:
+ +[TypistPathUtilities _getAdvanceWidthAndHeight:forCharacters:]
+ -[TYPathData advanceWidth]
+ -[TYPathData initWithArray:width:height:isCursive:advanceWidth:]
+ -[TYPathData setAdvanceWidth:]
+ GCC_except_table58
+ GCC_except_table63
+ GCC_except_table70
+ GCC_except_table74
+ GCC_except_table78
+ GCC_except_table85
+ GCC_except_table97
+ _OBJC_IVAR_$_TYPathData._advanceWidth
+ _TIUIKeyboardPersistentSplitProgressPreference
+ ___59+[TypistKeyboardDataInProcess generateKeyplaneSwitchTable:]_block_invoke_2
+ ___67+[TypistKeyboardDataInProcess generateKeyplaneSwitchTableFor10Key:]_block_invoke
+ ___block_descriptor_33_e5_v8?0l
- +[TypistPathUtilities _getWidthAndHeight:forCharacters:]
- -[TYPathData initWithArray:width:height:isCursive:]
- GCC_except_table61
- GCC_except_table64
- GCC_except_table72
- GCC_except_table76
- GCC_except_table83
- GCC_except_table89
CStrings:
+ "Changing Split Settings: Current=%@ Persistent=%@ ChangeTo=%@"
+ "SELECT pathData.pathData, pathData.width, pathData.height, characters.character, pathData.variant_id, pathData.isCursive, pathData.advances FROM pathData INNER JOIN characters ON characters.characterid = pathData.character_id"
- "Changing Split Settings: Current=%@ ChangeTo=%@"
- "SELECT pathData.pathData, pathData.width, pathData.height, characters.character, pathData.variant_id, pathData.isCursive FROM pathData INNER JOIN characters ON characters.characterid = pathData.character_id"
- "ฯ"
```
