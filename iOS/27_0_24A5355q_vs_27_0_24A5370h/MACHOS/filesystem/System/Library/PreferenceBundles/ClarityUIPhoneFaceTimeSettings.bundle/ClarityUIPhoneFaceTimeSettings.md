## ClarityUIPhoneFaceTimeSettings

> `/System/Library/PreferenceBundles/ClarityUIPhoneFaceTimeSettings.bundle/ClarityUIPhoneFaceTimeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e94` | `0x2ed4` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x1374` | `0x13ad` | **`+0x39`** |
| `__TEXT.__cstring` | `0x2bc` | `0x28f` | **`-0x2d`** |
| `__DATA_CONST.__cfstring` | `0x360` | `0x340` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x90` | `0xb0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xec0` | `0xee0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x580` | `0x598` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x584` | `0x59c` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1847.0.0.0.0
+1851.0.0.0.0

-  Functions: 83
-  Symbols:   336
-  CStrings:  294
+  Functions: 86
+  Symbols:   341
+  CStrings:  296
Symbols:
+ -[CLPHController recentsEnabled:]
+ -[CLPHController setRecentsEnabled:specifier:]
+ -[CLPHController setVoicemailEnabled:specifier:]
+ -[CLPHController voicemailEnabled:]
+ ___44-[CLPHController _axLoadSpecifiersFromPlist]_block_invoke_2
+ __block_literal_global
+ _objc_msgSend$setVoicemailEnabled:
+ _objc_msgSend$voicemailEnabled
- -[CLPHController setShowRecentsEnabled:specifier:]
- -[CLPHController showRecentsEnabled:]
- _objc_msgSend$groupSpecifierWithID:
CStrings:
+ "OPTIONS_RECENTS"
+ "recentsEnabled:"
+ "setRecentsEnabled:specifier:"
+ "setVoicemailEnabled:"
+ "setVoicemailEnabled:specifier:"
+ "voicemailEnabled"
+ "voicemailEnabled:"
- "ClarityUIFullScreenCompatibilityModeSpecifierID"
- "SHOW_RECENTS"
- "groupSpecifierWithID:"
- "setShowRecentsEnabled:specifier:"
- "showRecentsEnabled:"
```
