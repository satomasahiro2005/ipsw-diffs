## SetupAssistant

> `/System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x443c0` | `0x44824` | **`+0x464`** |
| `__TEXT.__dlopen_cstrs` | `0x138b` | `0x13dd` | **`+0x52`** |
| `__AUTH_CONST.__objc_const` | `0x6288` | `0x62d0` | **`+0x48`** |
| `__TEXT.__cstring` | `0x349e` | `0x34e3` | **`+0x45`** |
| `__DATA.__bss` | `0x630` | `0x648` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x1760` | `0x1778` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c70` | `0x2c88` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xf34` | `0xf4c` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x419c` | `0x41b4` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x538` | `0x540` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1358` | `0x1360` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3cc` | `0x3d0` | **`+0x4`** |

### Other Changes

```diff

-5407.0.0.0.0
+5409.0.0.0.0

-  Functions: 1795
-  Symbols:   3098
-  CStrings:  1135
+  Functions: 1801
+  Symbols:   3110
+  CStrings:  1138
Symbols:
+ -[BYDevice firstSupportedOSReleaseVersionForThisDevice]
+ _AVFCaptureLibrary
+ _AVFCaptureLibraryCore
+ _AVFCaptureLibraryCore.frameworkLibrary
+ _OBJC_CLASS_$_NSCharacterSet
+ _OBJC_IVAR_$_BYDevice._firstSupportedOSReleaseVersionForThisDevice
+ ___AVFCaptureLibraryCore_block_invoke
+ ___getAVGQFirstSupportedReleaseVersionSymbolLoc_block_invoke
+ ___getAVGestaltGetStringAnswerWithDefaultSymbolLoc_block_invoke
+ _audit_stringAVFCapture
+ _getAVGQFirstSupportedReleaseVersionSymbolLoc.ptr
+ _getAVGestaltGetStringAnswerWithDefaultSymbolLoc.ptr
CStrings:
+ "AVGQFirstSupportedReleaseVersion"
+ "AVGestaltGetStringAnswerWithDefault"
+ "softlink:o:path:/System/Library/PrivateFrameworks/AVFCapture.framework/AVFCapture"
```
