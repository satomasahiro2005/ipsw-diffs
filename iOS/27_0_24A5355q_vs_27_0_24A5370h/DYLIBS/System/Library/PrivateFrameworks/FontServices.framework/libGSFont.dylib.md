## libGSFont.dylib

> `/System/Library/PrivateFrameworks/FontServices.framework/libGSFont.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8208` | `0x821c` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x590` | `0x598` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x260` | `0x268` | **`+0x8`** |

### Other Changes

```diff

-167.0.0.0.0
+168.0.0.0.0

-  Functions: 143
-  Symbols:   425
+  Functions: 144
+  Symbols:   427
Symbols:
+ _ValueHasExpectedClassOrNil
+ _objc_opt_isKindOfClass
Functions:
~ _SandboxExtensionsForPathsAndAuditToken : 520 -> 516
+ _ValueHasExpectedClassOrNil
~ _GSFontChangeNotificationHandler : 716 -> 708
~ _GSFontDoneForFontPicker : 504 -> 500
~ _WriteAddedFontsCache : 752 -> 748
~ _GSFontCopyLocallyActivatedFontFilePaths : 480 -> 476
~ _GSFontCopyFamilyNames : 1292 -> 1288
~ _GSFontSynchronizeProfileFonts : 1016 -> 1004
~ ___GSFontUpdateFontAssetLastAccessedTime_block_invoke : 636 -> 628
~ _RegisterFontsWithFontsInfoDictionary : 2920 -> 2932
~ _AddToCFDictionary : 460 -> 452
~ _RecordChangedFonts : 864 -> 884
```
