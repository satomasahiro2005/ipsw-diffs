## TextInput

> `/System/Library/PrivateFrameworks/TextInput.framework/TextInput`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80644` | `0x80850` | **`+0x20c`** |
| `__AUTH_CONST.__cfstring` | `0x255b20` | `0x255ce0` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x494a8` | `0x495e6` | **`+0x13e`** |
| `__DATA_CONST.__const` | `0x2440` | `0x2490` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x11b28` | `0x11b70` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0xb5b8` | `0xb600` | **`+0x48`** |
| `__DATA_CONST.__objc_arraydata` | `0x101920` | `0x101948` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x5678` | `0x56a0` | **`+0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x5040` | `0x5058` | **`+0x18`** |

### Other Changes

```diff

-3559.100.0.0.0
+3562.0.0.0.0

-  Functions: 4001
-  Symbols:   7633
-  CStrings:  76788
+  Functions: 4007
+  Symbols:   7649
+  CStrings:  76802
Symbols:
+ -[TIKeyboardState canInsertGenmoji]
+ -[TIKeyboardState setCanInsertGenmoji:]
+ -[TIKeyboardState setSupportsGenmojiCreation:]
+ -[TIKeyboardState supportsGenmojiCreation]
+ -[TIPreferencesController alwaysShowOnscreenKeyboardEnabled]
+ _TIAssistiveTouchMouseAlwaysShowSoftwareKeyboardPreference
+ _TIKeyboardOutputInfoTypeCellularIMEI1Str
+ _TIKeyboardOutputInfoTypeCellularIMEI2Str
+ _TIKeyboardOutputInfoTypeCellularNALStr
+ _TIKeyboardSecureCandidateCellularIMEI1Str
+ _TIKeyboardSecureCandidateCellularIMEI2Str
+ _TIKeyboardSecureCandidateCellularNALStr
+ _TITextContentTypeCellularIMEI1
+ _TITextContentTypeCellularIMEI2
+ _TITextContentTypeCellularNAL
+ _getMCFeatureKeyboardMathSolvingAllowed
CStrings:
+ ".notification"
+ "; canInsertGenmoji = %s"
+ "; supportsGenmojiCreation = %s"
+ "AssistiveTouchMouseAlwaysShowSoftwareKeyboard"
+ "AutofillCellularIMEI1"
+ "AutofillCellularIMEI2"
+ "AutofillCellularNAL"
+ "Insert Cellular IMEI1"
+ "Insert Cellular IMEI2"
+ "Insert Cellular NAL"
+ "allowAutoCapitalization"
+ "com.apple.Accessibility"
+ "esim-imei1"
+ "esim-imei2"
+ "esim-nal"
- "ar_"
```
