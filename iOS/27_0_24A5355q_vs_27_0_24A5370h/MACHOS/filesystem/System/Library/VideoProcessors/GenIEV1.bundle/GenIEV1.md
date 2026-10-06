## GenIEV1

> `/System/Library/VideoProcessors/GenIEV1.bundle/GenIEV1`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfcb8` | `0x10d70` | **`+0x10b8`** |
| `__DATA.__objc_const` | `0x1f20` | `0x2330` | **`+0x410`** |
| `__TEXT.__objc_stubs` | `0x1360` | `0x1560` | **`+0x200`** |
| `__TEXT.__objc_methname` | `0x1ae6` | `0x1c5a` | **`+0x174`** |
| `__TEXT.__objc_methlist` | `0xb1c` | `0xc2c` | **`+0x110`** |
| `__DATA.__objc_data` | `0x5a0` | `0x690` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x111d` | `0x11d6` | **`+0xb9`** |
| `__TEXT.__oslogstring` | `0x2551` | `0x25fa` | **`+0xa9`** |
| `__DATA.__objc_selrefs` | `0x6d0` | `0x730` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x97d` | `0x9c0` | **`+0x43`** |
| `__TEXT.__unwind_info` | `0x338` | `0x370` | **`+0x38`** |
| `__TEXT.__objc_classname` | `0x1da` | `0x20d` | **`+0x33`** |
| `__DATA_CONST.__const` | `0x128` | `0x148` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x3d0` | `0x3b0` | **`-0x20`** |
| `__TEXT.__const` | `0x80` | `0xa0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x154` | `0x170` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x90` | `0xa8` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x80` | `0x98` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x1f8` | `0x1e8` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3

-  Functions: 232
-  Symbols:   689
-  CStrings:  726
+  Functions: 257
+  Symbols:   754
+  CStrings:  765
Symbols:
+ -[GenIENetwork _ensureAEMLoaded]
+ -[GenIENetworkAEM .cxx_destruct]
+ -[GenIENetworkAEM initWithShared:]
+ -[GenIENetworkAEM inputShape]
+ -[GenIENetworkAEM loadNetwork:]
+ -[GenIENetworkAEM outputShape]
+ -[GenIENetworkAEM run]
+ -[GenIENetworkAEM setInputShape:]
+ -[GenIENetworkAEM setOutputShape:]
+ -[GenIENetworkShared featureBufferTileSize]
+ -[GenIENetworkShared featureBuffer]
+ -[GenIENetworkShared inputTileSize]
+ -[GenIENetworkShared setFeatureBuffer:]
+ -[GenIENetworkShared setFeatureBufferTileSize:]
+ -[GenIENetworkShared setInputTileSize:]
+ -[GenIeAEMPostStage initWithShared:]
+ -[GenIeAEMPostStage processTilePipelineStage:]
+ -[GenIeAEMPreStage .cxx_destruct]
+ -[GenIeAEMPreStage initWithShared:]
+ -[GenIeAEMPreStage processTilePipelineStage:]
+ -[GenIeAEMPreStage scaledTileSize]
+ -[GenIeAEMPreStage setScaledTileSize:]
+ OBJC_IVAR_$_GenIENetwork._aem
+ OBJC_IVAR_$_GenIENetwork._aemModelPath
+ OBJC_IVAR_$_GenIENetworkAEM._post
+ OBJC_IVAR_$_GenIENetworkAEM._pre
+ OBJC_IVAR_$_GenIENetworkAEM.inputShape
+ OBJC_IVAR_$_GenIENetworkAEM.outputShape
+ OBJC_IVAR_$_GenIENetworkShared._featureBuffer
+ OBJC_IVAR_$_GenIENetworkShared._featureBufferTileSize
+ OBJC_IVAR_$_GenIENetworkShared._inputTileSize
+ OBJC_IVAR_$_GenIeAEMPreStage._kernelPre
+ OBJC_IVAR_$_GenIeAEMPreStage._scaledTileSize
+ _OBJC_CLASS_$_GenIENetworkAEM
+ _OBJC_CLASS_$_GenIeAEMPostStage
+ _OBJC_CLASS_$_GenIeAEMPreStage
+ _OBJC_METACLASS_$_GenIENetworkAEM
+ _OBJC_METACLASS_$_GenIeAEMPostStage
+ _OBJC_METACLASS_$_GenIeAEMPreStage
+ __OBJC_$_INSTANCE_METHODS_GenIENetworkAEM
+ __OBJC_$_INSTANCE_METHODS_GenIeAEMPostStage
+ __OBJC_$_INSTANCE_METHODS_GenIeAEMPreStage
+ __OBJC_$_INSTANCE_VARIABLES_GenIENetworkAEM
+ __OBJC_$_INSTANCE_VARIABLES_GenIeAEMPreStage
+ __OBJC_$_PROP_LIST_GenIENetworkAEM
+ __OBJC_$_PROP_LIST_GenIeAEMPostStage
+ __OBJC_$_PROP_LIST_GenIeAEMPreStage
+ __OBJC_CLASS_PROTOCOLS_$_GenIENetworkAEM
+ __OBJC_CLASS_PROTOCOLS_$_GenIeAEMPostStage
+ __OBJC_CLASS_PROTOCOLS_$_GenIeAEMPreStage
+ __OBJC_CLASS_RO_$_GenIENetworkAEM
+ __OBJC_CLASS_RO_$_GenIeAEMPostStage
+ __OBJC_CLASS_RO_$_GenIeAEMPreStage
+ __OBJC_METACLASS_RO_$_GenIENetworkAEM
+ __OBJC_METACLASS_RO_$_GenIeAEMPostStage
+ __OBJC_METACLASS_RO_$_GenIeAEMPreStage
+ ___22-[GenIENetworkAEM run]_block_invoke
+ _objc_msgSend$_ensureAEMLoaded
+ _objc_msgSend$blitCommandEncoder
+ _objc_msgSend$copyFromBuffer:sourceOffset:toBuffer:destinationOffset:size:
+ _objc_msgSend$featureBuffer
+ _objc_msgSend$featureBufferTileSize
+ _objc_msgSend$inputTileSize
+ _objc_msgSend$scaledTileSize
+ _objc_msgSend$setFeatureBuffer:
+ _objc_msgSend$setFeatureBufferTileSize:
+ _objc_msgSend$setInputShape:
+ _objc_msgSend$setInputTileSize:
+ _objc_msgSend$setOutputShape:
+ _objc_msgSend$setScaledTileSize:
+ _objc_msgSend$setTiledInferenceProcessor:
+ _objc_msgSend$tileBorder
+ _objc_msgSend$tileSize
+ _objc_msgSend$tileStride
+ _objc_msgSend$waitForIdle
- -[GenIENetworkShared encoderPreStage]
- -[GenIENetworkShared setEncoderPreStage:]
- OBJC_IVAR_$_GenIENetworkEncoder._tiledInferenceProcessor
- OBJC_IVAR_$_GenIENetworkShared._encoderPreStage
- OBJC_IVAR_$_GenIeDecoderPreStage._kernelExtractOriginal
- OBJC_IVAR_$_GenIeDecoderPreStage._kernelSetScale
- _CFPreferencesCopyAppValue
- _objc_msgSend$encoderPreStage
- _objc_msgSend$setEncoderPreStage:
- _objc_opt_isKindOfClass
CStrings:
+ "\n"
+ "-[GenIENetwork _ensureAEMLoaded]"
+ "-[GenIENetworkAEM loadNetwork:]"
+ "-[GenIENetworkAEM run]_block_invoke"
+ "-[GenIeAEMPreStage initWithShared:]"
+ "-[GenIeAEMPreStage processTilePipelineStage:]"
+ "/System/Library/ImagingNetworks/genie_mubb.bundle"
+ "<<<< GenIEV1 >>>> %s: AEM failed, bailing (%d)"
+ "<<<< GenIEV1 >>>> %s: Cannot proceed without the aem, bailing (%d)"
+ "<<<< GenIEV1 >>>> %s: Failed to create _shared.featureBuffer."
+ "<<<< GenIEV1 >>>> %s: Failed to load aem network %s, bailing (%d)"
+ "<<<< GenIEV1 >>>> %s: _aem nil"
+ "<<<< GenIEV1 >>>> %s: feature.shape:[%d, %d]"
+ "<<<< GenIEV1 >>>> %s: shared.inputTileSize not set yet"
+ "@\"GenIENetworkAEM\""
+ "@\"GenIeAEMPostStage\""
+ "@\"GenIeAEMPreStage\""
+ "GenIENetworkAEM"
+ "GenIENetworkAEM.m"
+ "GenIeAEMPostStage"
+ "GenIeAEMPreStage"
+ "Q"
+ "T,N,V_inputTileSize"
+ "T,N,V_scaledTileSize"
+ "T,N,VinputShape"
+ "T,N,VoutputShape"
+ "T@\"<MTLBuffer>\",&,N,V_featureBuffer"
+ "TQ,N,V_featureBufferTileSize"
+ "_aem"
+ "_aemModelPath"
+ "_ensureAEMLoaded"
+ "_featureBuffer"
+ "_featureBufferTileSize"
+ "_inputTileSize"
+ "_scaledTileSize"
+ "blitCommandEncoder"
+ "copyFromBuffer:sourceOffset:toBuffer:destinationOffset:size:"
+ "featureBuffer"
+ "featureBufferTileSize"
+ "genie::aem::pre"
+ "hidden_embed"
+ "in_features"
+ "input"
+ "inputTileSize"
+ "scaledTileSize"
+ "setFeatureBuffer:"
+ "setFeatureBufferTileSize:"
+ "setInputShape:"
+ "setInputTileSize:"
+ "setOutputShape:"
+ "setScaledTileSize:"
+ "spatial_embed"
+ "v20@0:816"
+ "v24@0:8Q16"
+ "v32@0:816"
+ "vision_embed"
+ "waitForIdle"
- "<<<< GenIEV1 >>>> %s: Cannot proceed without the decoder, bailing (%d)"
- "<<<< GenIEV1 >>>> %s: _kernelExtractOriginal nil"
- "<<<< GenIEV1 >>>> %s: _kernelSetScale nil"
- "<<<< GenIEV1 >>>> %s: encoderPreStage nil"
- "@\"GenIENetworkMetalStage\""
- "T@\"GenIENetworkMetalStage\",&,N,V_encoderPreStage"
- "_encoderPreStage"
- "_kernelExtractOriginal"
- "_kernelSetScale"
- "cond_img"
- "encoderPreStage"
- "genie::decoder::pre::extractOriginal"
- "genie::decoder::pre::setScale"
- "genie_decoder_path"
- "genie_denoiser_path"
- "genie_encoder_path"
- "scale"
- "setEncoderPreStage:"
```
