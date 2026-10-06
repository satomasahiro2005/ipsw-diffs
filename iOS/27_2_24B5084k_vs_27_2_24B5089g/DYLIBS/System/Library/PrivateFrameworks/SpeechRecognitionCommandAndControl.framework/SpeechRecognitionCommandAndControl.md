## SpeechRecognitionCommandAndControl

> `/System/Library/PrivateFrameworks/SpeechRecognitionCommandAndControl.framework/SpeechRecognitionCommandAndControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x123748` | `0x123ca4` | **`+0x55c`** |
| `__AUTH_CONST.__cfstring` | `0x9a00` | `0x9a60` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xc0cc` | `0xc104` | **`+0x38`** |
| `__TEXT.__cstring` | `0x9787` | `0x97b7` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x4dd8` | `0x4df8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x7f70` | `0x7f90` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x43e8` | `0x4408` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x120` | `0x138` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x8a0` | `0x8b8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1550` | `0x1560` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1f28` | `0x1f30` | **`+0x8`** |

### Other Changes

```diff

-191.2.0.0.0
+191.2.1.0.0

-  Functions: 7368
-  Symbols:   14854
-  CStrings:  1869
+  Functions: 7376
+  Symbols:   14865
+  CStrings:  1872
Symbols:
+ -[CACCorrectionPresentationManager insertReplacementText:]
+ -[CACCorrectionPresentationManager selectCorrectionWithLabelNumber:]
+ -[CACDisplayManager selectCorrectionWithLabelNumber:]
+ -[CACSceneManager selectCorrectionWithLabelNumber:]
+ -[CACSpokenCommandGestureManager prepare]
+ -[CACUtilityToolServer launchableApps]
+ GCC_except_table129
+ GCC_except_table175
+ GCC_except_table35
+ _$sScT6cancelyyF
+ _$ss5NeverON
+ _$ss5NeverOs5ErrorsWP
+ ___49-[CACDisplayManager _initializeWindowsWithScene:]_block_invoke
+ ___58-[CACCorrectionPresentationManager insertReplacementText:]_block_invoke
+ ___68-[CACCorrectionPresentationManager selectCorrectionWithLabelNumber:]_block_invoke
- GCC_except_table127
- GCC_except_table173
- GCC_except_table32
- ___96-[CACCorrectionPresentationManager correctionsPresentationViewController:didSelectItemWithText:]_block_invoke
CStrings:
+ "LaunchableApps"
+ "com.apple.SiriApp"
+ "launchableApps"
```
