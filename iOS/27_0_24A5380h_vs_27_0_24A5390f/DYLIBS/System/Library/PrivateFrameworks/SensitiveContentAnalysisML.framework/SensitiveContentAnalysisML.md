## SensitiveContentAnalysisML

> `/System/Library/PrivateFrameworks/SensitiveContentAnalysisML.framework/SensitiveContentAnalysisML`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf7f30` | `0xf75b8` | **`-0x978`** |
| `__TEXT.__gcc_except_tab` | `0x461c` | `0x4460` | **`-0x1bc`** |
| `__TEXT.__eh_frame` | `0x8b78` | `0x8c98` | **`+0x120`** |
| `__AUTH_CONST.__const` | `0xa3c8` | `0xa2f8` | **`-0xd0`** |
| `__TEXT.__oslogstring` | `0x1e93` | `0x1ee3` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x484` | `0x43c` | **`-0x48`** |
| `__DATA.__data` | `0x2810` | `0x27d0` | **`-0x40`** |
| `__DATA_DIRTY.__data` | `0x1f30` | `0x1f68` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x5658` | `0x5628` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x2bec` | `0x2bbc` | **`-0x30`** |
| `__TEXT.__cstring` | `0x3d46` | `0x3d76` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1e7c` | `0x1e4c` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1b20` | `0x1b00` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x258c` | `0x2570` | **`-0x1c`** |
| `__TEXT.__swift_as_cont` | `0x55c` | `0x574` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1980` | `0x1990` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x8f0` | `0x8e0` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1178` | `0x1168` | **`-0x10`** |
| `__TEXT.__const` | `0x1157c` | `0x1156c` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x21c` | `0x228` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x50c0` | `0x50b8` | **`-0x8`** |
| `__TEXT.__swift5_reflstr` | `0x114f` | `0x1149` | **`-0x6`** |
| `__DATA.__objc_ivar` | `0x2f8` | `0x2f4` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x424` | `0x420` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x18c` | `0x190` | **`+0x4`** |
| `__TEXT.__swift5_typeref` | `0x29a9` | `0x29a7` | **`-0x2`** |

### Other Changes

```diff

-163.0.0.0.0
+165.0.0.0.0

-  Functions: 6251
-  Symbols:   3894
-  CStrings:  792
+  Functions: 6248
+  Symbols:   3885
+  CStrings:  795
Symbols:
+ -[SCMLImageModelThresholds _goreViolenceThresholdForLabel:error:]
+ _symbolic Say______pG 12ModelCatalog19AssetBackedResourceP
+ _symbolic ScCySDySSSfG______pG s5ErrorP
+ _symbolic ScCy______p______pG So9CSUBufferP s5ErrorP
+ _symbolic ______p So9CSUBufferP
- +[SCMLImageModelThresholds _createSafetyNetThresholdDictionaryWithError:]
- +[SCMLImageModelThresholds _validateSafetyNetScoreThresholdsJson:error:]
- -[SCMLImageModelThresholds _safetyNetThresholdDict]
- -[SCMLImageModelThresholds safetyNetThresholdForLabel:classificationMode:modelVersion:error:]
- -[SCMLImageModelThresholds set_safetyNetThresholdDict:]
- _OBJC_IVAR_$_SCMLImageModelThresholds.__safetyNetThresholdDict
- __ZN12_GLOBAL__N_114checkedConvertI8NSNumberEEPT_P11objc_objectPU15__autoreleasingP7NSError
- __ZN12_GLOBAL__N_121GetImageModelVersionsEv
- _symbolic SDySSSfGz_Xx
- _symbolic _____ 26SensitiveContentAnalysisML17UncheckedSendableV
- _symbolic ______pSg So9CSUBufferP
- _symbolic ______pSgz_Xx So9CSUBufferP
- _symbolic _____ySay______pGG 26SensitiveContentAnalysisML17UncheckedSendableV 12ModelCatalog19AssetBackedResourceP
- _type_layout_string 26SensitiveContentAnalysisML17UncheckedSendableVySay12ModelCatalog19AssetBackedResource_pGG
CStrings:
+ "CSU returned no threshold for label: %@"
+ "Unsupported gore/violence label: %@"
+ "classifyPixelBuffer(_:)"
+ "com.apple.edit_suggestion.default"
- "Models/ImageModel/safetynet_thresholds.json"
```
