## SmartStyleV1

> `/System/Library/VideoProcessors/SmartStyleV1.bundle/SmartStyleV1`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe660` | `0xea80` | **`+0x420`** |
| `__TEXT.__objc_methname` | `0x5133` | `0x5432` | **`+0x2ff`** |
| `__DATA.__objc_const` | `0x28c0` | `0x2a28` | **`+0x168`** |
| `__TEXT.__objc_stubs` | `0x2380` | `0x24e0` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0x1774` | `0x1844` | **`+0xd0`** |
| `__TEXT.__objc_methtype` | `0x13cf` | `0x1499` | **`+0xca`** |
| `__DATA.__objc_selrefs` | `0xc18` | `0xc80` | **`+0x68`** |
| `__TEXT.__cstring` | `0x1caa` | `0x1cf0` | **`+0x46`** |
| `__TEXT.__const` | `0x70` | `0xb0` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x2a0` | `0x2c0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x200` | `0x214` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x370` | `0x378` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-  Functions: 486
-  Symbols:   971
-  CStrings:  914
+  Functions: 496
+  Symbols:   996
+  CStrings:  948
Symbols:
+ -[CMISmartStyleProcessorInputOutputV1 inputFaceNormalizedRects]
+ -[CMISmartStyleProcessorInputOutputV1 inputSkinMaskPCR]
+ -[CMISmartStyleProcessorInputOutputV1 inputSkinMaskTransform]
+ -[CMISmartStyleProcessorInputOutputV1 inputSkinSmoothingParameters]
+ -[CMISmartStyleProcessorInputOutputV1 setInputFaceNormalizedRects:]
+ -[CMISmartStyleProcessorInputOutputV1 setInputSkinMaskPCR:]
+ -[CMISmartStyleProcessorInputOutputV1 setInputSkinMaskTransform:]
+ -[CMISmartStyleProcessorInputOutputV1 setInputSkinSmoothingParameters:]
+ -[CMISmartStyleProcessorUtilitiesV1 applyOctagonMirrorExtensionToPixelBuffer:]
+ OBJC_IVAR_$_CMISmartStyleProcessorInputOutputV1._inputFaceNormalizedRects
+ OBJC_IVAR_$_CMISmartStyleProcessorInputOutputV1._inputSkinMaskPCR
+ OBJC_IVAR_$_CMISmartStyleProcessorInputOutputV1._inputSkinMaskTransform
+ OBJC_IVAR_$_CMISmartStyleProcessorInputOutputV1._inputSkinSmoothingParameters
+ OBJC_IVAR_$_CMISmartStyleProcessorUtilitiesV1._octagonMirrorExtensionPipelineState
+ _objc_msgSend$inputFaceNormalizedRects
+ _objc_msgSend$inputSkinMaskPCR
+ _objc_msgSend$inputSkinMaskTransform
+ _objc_msgSend$inputSkinSmoothingParameters
+ _objc_msgSend$setInputFaceNormalizedRects:
+ _objc_msgSend$setInputSkinMaskFlipHorizontal:
+ _objc_msgSend$setInputSkinMaskFlipVertical:
+ _objc_msgSend$setInputSkinMaskICR:
+ _objc_msgSend$setInputSkinMaskPCR:
+ _objc_msgSend$setInputSkinMaskRotationDegrees:
+ _objc_msgSend$setInputSkinSmoothingParameters:
CStrings:
+ "@\"CMITextureStylesSkinSmoothParameters\""
+ "@\"CMITextureStylesSkinSmoothParameters\"16@0:8"
+ "@\"NSArray\""
+ "@\"NSArray\"16@0:8"
+ "I16@0:8"
+ "T@\"CMITextureStylesSkinSmoothParameters\",&,N"
+ "T@\"CMITextureStylesSkinSmoothParameters\",&,N,V_inputSkinSmoothingParameters"
+ "T@\"NSArray\",&,N"
+ "T@\"NSArray\",&,N,V_inputFaceNormalizedRects"
+ "TI,N"
+ "TI,N,V_inputSkinMaskTransform"
+ "T{CGRect={CGPoint=dd}{CGSize=dd}},N,V_inputSkinMaskPCR"
+ "_inputFaceNormalizedRects"
+ "_inputSkinMaskPCR"
+ "_inputSkinMaskTransform"
+ "_inputSkinSmoothingParameters"
+ "_octagonMirrorExtensionPipelineState"
+ "applyOctagonMirrorExtensionToPixelBuffer:"
+ "inputFaceNormalizedRects"
+ "inputSkinMaskPCR"
+ "inputSkinMaskTransform"
+ "inputSkinSmoothingParameters"
+ "setInputFaceNormalizedRects:"
+ "setInputSkinMaskFlipHorizontal:"
+ "setInputSkinMaskFlipVertical:"
+ "setInputSkinMaskICR:"
+ "setInputSkinMaskPCR:"
+ "setInputSkinMaskRotationDegrees:"
+ "setInputSkinMaskTransform:"
+ "setInputSkinSmoothingParameters:"
+ "smartStyleOctagonMirrorExtension"
+ "v20@0:8I16"
+ "v24@0:8@\"CMITextureStylesSkinSmoothParameters\"16"
+ "v24@0:8@\"NSArray\"16"
```
