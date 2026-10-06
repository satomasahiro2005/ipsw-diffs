## TypistFramework

> `/System/Library/PrivateFrameworks/TypistFramework.framework/TypistFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43ae0` | `0x44838` | **`+0xd58`** |
| `__TEXT.__cstring` | `0x5ac2` | `0x5c72` | **`+0x1b0`** |
| `__AUTH_CONST.__cfstring` | `0x11820` | `0x11920` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x3a2c` | `0x3b04` | **`+0xd8`** |
| `__AUTH_CONST.__objc_const` | `0x4be8` | `0x4ca8` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x25d0` | `0x2660` | **`+0x90`** |
| `__TEXT.__const` | `0x422` | `0x462` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xe90` | `0xeb0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x2c8` | `0x2d8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x6f8` | `0x700` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x538` | `0x540` | **`+0x8`** |

### Other Changes

```diff

-499.1.0.0.0
+501.0.0.0.0

-  Functions: 1379
-  Symbols:   2377
-  CStrings:  2295
+  Functions: 1397
+  Symbols:   2400
+  CStrings:  2303
Symbols:
+ +[TypistKeyboardUtilities(MathUtilities) generateThumbArcPointForKeyCenter:reference:errorScale:overextensionRate:crampingRate:millimetresPerPoint:]
+ +[TypistKeyboardUtilities(MathUtilities) generateTwoThumbArcPointForKeyCenter:leftReference:rightReference:errorScale:overextensionRate:crampingRate:millimetresPerPoint:]
+ +[TypistKeyboardUtilities(MathUtilities) thumbArcBaseSigmaMMForBaseErrorMM:lengthCM:]
+ +[TypistKeyboardUtilities(MathUtilities) thumbArcTuningForTwoHanded:baseErrorMM:overextensionRate:crampingRate:]
+ -[TYPathData anchorX]
+ -[TYPathData initWithArray:width:height:isCursive:advanceWidth:anchorX:]
+ -[TYPathData setAnchorX:]
+ -[TypistKeyboard _isBothThumbsOption:]
+ -[TypistKeyboard _isTwoHandedPosture]
+ -[TypistKeyboard _resolvedThumbArcTuning]
+ -[TypistKeyboard _thumbArcReferenceForRightThumb:twoHanded:]
+ -[TypistKeyboard _thumbReferenceForRightThumb:twoHanded:]
+ -[TypistKeyboard setTapThumbArcCrampingRate:]
+ -[TypistKeyboard setTapThumbArcOverextensionRate:]
+ -[TypistKeyboard setTapThumbBaseErrorMM:]
+ -[TypistKeyboard tapThumbArcCrampingRate]
+ -[TypistKeyboard tapThumbArcOverextensionRate]
+ -[TypistKeyboard tapThumbBaseErrorMM]
+ GCC_except_table94
+ _OBJC_IVAR_$_TYPathData._anchorX
+ _OBJC_IVAR_$_TypistKeyboard._tapThumbArcCrampingRate
+ _OBJC_IVAR_$_TypistKeyboard._tapThumbArcOverextensionRate
+ _OBJC_IVAR_$_TypistKeyboard._tapThumbBaseErrorMM
+ _sqlite3_column_double
- GCC_except_table89
CStrings:
+ "/AppleInternal/Library/Frameworks/TypistHandwriting.bundle/strokes.db"
+ "/AppleInternal/Library/Typist/Handwriting/strokes.db"
+ "No readable handwriting stroke database; nothing will be drawn. Searched: %@"
+ "SELECT pathData.pathData, pathData.width, pathData.height, characters.character, pathData.variant_id, pathData.isCursive, pathData.advances, COALESCE(characterAnchors.anchor_x, 0.0) AS anchor_x FROM pathData INNER JOIN characters ON characters.characterid = pathData.character_id LEFT JOIN characterAnchors ON characterAnchors.character_id = characters.characterid"
+ "both"
+ "tapNoiseThumbArcCrampingRate"
+ "tapNoiseThumbArcOverextensionRate"
+ "tapNoiseThumbBaseErrorMM"
+ "thumbArc"
- "SELECT pathData.pathData, pathData.width, pathData.height, characters.character, pathData.variant_id, pathData.isCursive, pathData.advances FROM pathData INNER JOIN characters ON characters.characterid = pathData.character_id"
```
