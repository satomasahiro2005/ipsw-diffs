## TypistFramework

> `/System/Library/PrivateFrameworks/TypistFramework.framework/TypistFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x422bc` | `0x43240` | **`+0xf84`** |
| `__TEXT.__cstring` | `0x5922` | `0x5ac2` | **`+0x1a0`** |
| `__AUTH_CONST.__cfstring` | `0x11580` | `0x116e0` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0x382c` | `0x3944` | **`+0x118`** |
| `__AUTH_CONST.__objc_const` | `0x4a68` | `0x4b58` | **`+0xf0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2480` | `0x2540` | **`+0xc0`** |
| `__TEXT.__const` | `0x3c2` | `0x422` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0xe40` | `0xe80` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x6d0` | `0x6f8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x608` | `0x628` | **`+0x20`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x80` | `0xa0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xd1c` | `0xd34` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x2b4` | `0x2c8` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x8f8` | `0x900` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__ustring`

### Other Changes

```diff

-493.0.0.0.0
+498.0.0.0.0

-  Functions: 1312
-  Symbols:   2284
-  CStrings:  2274
+  Functions: 1339
+  Symbols:   2321
+  CStrings:  2285
Symbols:
+ +[TypistKeyboardUtilities(KeyboardSettings) getShowAllKeysDebugHitAreaPrefSetting]
+ +[TypistKeyboardUtilities(KeyboardSettings) setShowAllKeysDebugHitArea:]
+ +[TypistKeyboardUtilities(MathUtilities) _clampedThumbLengthCM:]
+ +[TypistKeyboardUtilities(MathUtilities) generatePerimeterPointWithCenter:bounds:offset:]
+ +[TypistKeyboardUtilities(MathUtilities) generateThumbReachPointForKeyCenter:reference:errorScale:millimetresPerPoint:]
+ +[TypistKeyboardUtilities(MathUtilities) thumbBaseSigmaMMForLengthCM:]
+ +[TypistKeyboardUtilities(MathUtilities) thumbReachRadiusMMForLengthCM:]
+ +[TypistKeyboardUtilities(MathUtilities) thumbReachReferenceForLengthCM:anchor:isRightThumb:]
+ +[TypistKeyboardUtilities(MathUtilities) validateTouchPoint:withinBounds:]
+ +[TypistKeyboardUtilities(SystemSettings) millimetresPerPoint]
+ -[TypistHWKeyboard senderProperties]
+ -[TypistHWKeyboard setSenderProperties:]
+ -[TypistKeyboard _acceptsTapNoiseForKey:]
+ -[TypistKeyboard _isLeftThumbOption:]
+ -[TypistKeyboard _thumbReachReference]
+ -[TypistKeyboard setTapKeyPerimeterOffset:]
+ -[TypistKeyboard setTapThumbAnchorY:]
+ -[TypistKeyboard setTapThumbErrorScale:]
+ -[TypistKeyboard setTapThumbHand:]
+ -[TypistKeyboard setTapThumbLength:]
+ -[TypistKeyboard tapKeyPerimeterOffset]
+ -[TypistKeyboard tapThumbAnchorY]
+ -[TypistKeyboard tapThumbErrorScale]
+ -[TypistKeyboard tapThumbHand]
+ -[TypistKeyboard tapThumbLength]
+ GCC_except_table89
+ _CGRectGetWidth
+ _CGRectIsEmpty
+ _OBJC_IVAR_$_TypistHWKeyboard._senderProperties
+ _OBJC_IVAR_$_TypistKeyboard._tapKeyPerimeterOffset
+ _OBJC_IVAR_$_TypistKeyboard._tapThumbAnchorY
+ _OBJC_IVAR_$_TypistKeyboard._tapThumbErrorScale
+ _OBJC_IVAR_$_TypistKeyboard._tapThumbHand
+ _OBJC_IVAR_$_TypistKeyboard._tapThumbLength
+ _TIGetShowAllKeysDebugHitAreaValue
+ _TIGetShowAllKeysDebugHitAreaValue.onceToken
+ _TIShowAllKeysDebugHitAreaPreference
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSString_$_ArabicFormConverter
+ __OBJC_$_CATEGORY_NSCharacterSet_$_Arabic
+ __OBJC_$_CATEGORY_NSString_$_ArabicFormConverter
+ __OBJC_$_CATEGORY_NSValue_$_TYArabicCharacter
+ __OBJC_$_CLASS_METHODS_NSCharacterSet(Arabic|Cursive|Hangul|Latex)
+ __OBJC_$_CLASS_METHODS_NSValue(TYArabicCharacter|HangulJamo)
+ __OBJC_$_CLASS_METHODS_TypistKeyboardUtilities(KeyboardSettings|KeyboardUI|MathUtilities|RecapUtilities|SystemSettings)
+ __OBJC_$_INSTANCE_METHODS_NSString(ArabicFormConverter|TYTextDirectionAnnotations|Grapheme)
+ __OBJC_$_INSTANCE_METHODS_NSValue(TYArabicCharacter|HangulJamo)
+ ___62+[TypistKeyboardUtilities(SystemSettings) millimetresPerPoint]_block_invoke
+ ___TIGetShowAllKeysDebugHitAreaValue_block_invoke
+ _atan2
+ _hypot
+ _sin
- -[TypistHWKeyboard propertyDictionary]
- -[TypistHWKeyboard setPropertyDictionary:]
- GCC_except_table86
- _OBJC_IVAR_$_TypistHWKeyboard._propertyDictionary
- __OBJC_$_CATEGORY_NSCharacterSet_$_Cursive
- __OBJC_$_CATEGORY_NSString_$_TYTextDirectionAnnotations
- __OBJC_$_CATEGORY_NSValue_$_HangulJamo
- __OBJC_$_CLASS_METHODS_NSCharacterSet(Cursive|Arabic|Latex|Hangul)
- __OBJC_$_CLASS_METHODS_NSString(TYTextDirectionAnnotations|Grapheme|ArabicFormConverter)
- __OBJC_$_CLASS_METHODS_NSValue(HangulJamo|TYArabicCharacter)
- __OBJC_$_CLASS_METHODS_TypistKeyboardUtilities(MathUtilities|SystemSettings|RecapUtilities|KeyboardSettings|KeyboardUI)
- __OBJC_$_INSTANCE_METHODS_NSString(TYTextDirectionAnnotations|Grapheme|ArabicFormConverter)
- __OBJC_$_INSTANCE_METHODS_NSValue(HangulJamo|TYArabicCharacter)
- __OBJC_$_PROP_LIST_NSValue_$_HangulJamo
CStrings:
+ "######## SPECIFIED KEYBOARD OPTIONS FOR %@\n%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;"
+ "Changing Key Hit Area Debug Overlay Settings: Current=%d ChangeTo=%d"
+ "ShowAllKeysDebugHitArea"
+ "Unable to determine the display pitch (pitch=%@, nativeScale=%f). Any model expressed in millimetres will have to substitute a default."
+ "com.apple.keyboard"
+ "keyPerimeter"
+ "tapNoiseKeyPerimeterOffset"
+ "tapNoiseThumbAnchorY"
+ "tapNoiseThumbErrorScale"
+ "tapNoiseThumbHand"
+ "tapNoiseThumbLength"
+ "thumbReach"
- "######## SPECIFIED KEYBOARD OPTIONS FOR %@\n%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%@;%@=%d;%@=%d;"
```
