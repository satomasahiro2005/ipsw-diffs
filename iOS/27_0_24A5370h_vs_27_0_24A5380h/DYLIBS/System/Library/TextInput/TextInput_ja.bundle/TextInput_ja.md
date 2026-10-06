## TextInput_ja

> `/System/Library/TextInput/TextInput_ja.bundle/TextInput_ja`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e4c0` | `0x1e6e0` | **`+0x220`** |
| `__AUTH_CONST.__objc_const` | `0x26c0` | `0x26f0` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1840` | `0x1858` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x2148` | `0x2150` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1f0` | `0x1f4` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3557.15.100.0.0
+3559.100.0.0.0

-  Functions: 745
-  Symbols:   1314
+  Functions: 746
+  Symbols:   1316
Symbols:
+ -[TIWordSearchJapaneseOperationGetCandidates initWithWordSearch:inputString:keyboardInput:contextString:onScreenContext:segmentBreakIndex:predictionEnabled:reanalysisMode:autocapitalizationType:target:action:geometryModelData:flickUsed:phraseBoundarySet:hardwareKeyboardMode:logger:]
+ -[TIWordSearchJapaneseOperationGetCandidates onScreenContext]
+ -[TIWordSearchKana makeCandidates:input:contextString:onScreenContext:predictionEnabled:reanalysisMode:withInputManager:geometryModelData:flickUsed:hardwareKeyboardMode:referenceMode:singlePhrase:]
+ _OBJC_IVAR_$_TIWordSearchJapaneseOperationGetCandidates._onScreenContext
- -[TIWordSearchJapaneseOperationGetCandidates initWithWordSearch:inputString:keyboardInput:contextString:segmentBreakIndex:predictionEnabled:reanalysisMode:autocapitalizationType:target:action:geometryModelData:flickUsed:phraseBoundarySet:hardwareKeyboardMode:logger:]
- -[TIWordSearchKana makeCandidates:input:contextString:predictionEnabled:reanalysisMode:withInputManager:geometryModelData:flickUsed:hardwareKeyboardMode:referenceMode:singlePhrase:]
```
