## libGLVMPlugin.dylib

> `/System/Library/Frameworks/OpenGLES.framework/libGLVMPlugin.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4702c` | `0x475c0` | **`+0x594`** |
| `__TEXT.__unwind_info` | `0x6f8` | `0x6f0` | **`-0x8`** |

### Other Changes

```diff
Symbols:
+ __ZNSt3__110unique_ptrIN4llvm6ModuleENS_14default_deleteIS2_EEED1B9fqn220106Ev
+ __ZNSt3__119__allocate_at_leastB9fqn220106INS_9allocatorIPN4llvm6MDNodeEEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
+ __ZNSt3__16vectorINS_4pairIPN4llvm6MDNodeENS2_9SetVectorIPNS2_8MetadataENS0_IS7_NS_9allocatorIS7_EEEENS2_8DenseSetIS7_NS2_12DenseMapInfoIS7_vEEEEEEEENS8_ISG_EEE16__destroy_vectorclB9fqn220106Ev
+ __ZNSt3__16vectorIPN4llvm6MDNodeENS_9allocatorIS3_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__19allocatorINS_4pairIPN4llvm6MDNodeENS2_9SetVectorIPNS2_8MetadataENS_6vectorIS7_NS0_IS7_EEEENS2_8DenseSetIS7_NS2_12DenseMapInfoIS7_vEEEEEEEEE7destroyB9fqn220106EPSG_
+ __ZSt28__throw_bad_array_new_lengthB9fqn220106v
- __ZNSt3__110unique_ptrIN4llvm6ModuleENS_14default_deleteIS2_EEED1B9fqn220100Ev
- __ZNSt3__119__allocate_at_leastB9fqn220100INS_9allocatorIPN4llvm6MDNodeEEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
- __ZNSt3__16vectorINS_4pairIPN4llvm6MDNodeENS2_9SetVectorIPNS2_8MetadataENS0_IS7_NS_9allocatorIS7_EEEENS2_8DenseSetIS7_NS2_12DenseMapInfoIS7_vEEEEEEEENS8_ISG_EEE16__destroy_vectorclB9fqn220100Ev
- __ZNSt3__16vectorIPN4llvm6MDNodeENS_9allocatorIS3_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__19allocatorINS_4pairIPN4llvm6MDNodeENS2_9SetVectorIPNS2_8MetadataENS_6vectorIS7_NS0_IS7_EEEENS2_8DenseSetIS7_NS2_12DenseMapInfoIS7_vEEEEEEEEE7destroyB9fqn220100EPSG_
- __ZSt28__throw_bad_array_new_lengthB9fqn220100v
Functions:
~ _PPParserMacroCreateFromMacro : 224 -> 220
~ _PPParserMacroFree : 128 -> 124
~ _PPParserMacroGetReplaceString : 332 -> 336
~ _PPParserPreprocessString : 2620 -> 2520
~ _PPParserAttachString : 216 -> 224
~ _PPParserLabelsFree : 96 -> 104
~ _llvmir_PPStreamAddAttribBinding : 152 -> 148
~ _llvmir_PPStreamAddOutputBinding : 128 -> 124
~ _llvmir_PPStreamResolveBranches : 208 -> 220
~ _PPParserGetScalars : 316 -> 332
~ _PPParserParseAttributeBinding : 2740 -> 2748
~ _PPParserParseDestinationMask : 444 -> 452
~ _PPParserParseSourceSwizzle : 536 -> 540
~ _PPParserParseLabel : 372 -> 388
~ _PPParserParseBranchCondition : 920 -> 924
~ _PPParserParseDestination : 964 -> 968
~ _PPParserParseOperation : 1560 -> 1552
~ _PPParserExpandMacro : 964 -> 968
~ _PPParserParse : 3168 -> 3164
~ _PPParserParseStatement : 2972 -> 2968
~ _glpARBProgramInfoToLLVMModule : 1588 -> 1592
~ _glpFragProgram_GenerateMetadata : 1900 -> 1884
~ _glpVertProgram_GenerateMetadata : 1900 -> 1892
~ _glp_strtod : 636 -> 680
~ __glpStringHashRehash : 156 -> 160
~ __glpPointerHashRehash : 160 -> 168
~ _glpLLVMCGTopLevel : 1880 -> 1896
~ _glpLLVMBuildSubroutinesTypeClasses : 1136 -> 1104
~ _glpLLVMCleanUpASTObjects : 424 -> 428
~ _glpLLVMCGFindSamplersAndBuffers : 1168 -> 1200
~ _glpLLVMCreateAttributeDescription : 700 -> 724
~ _glpLLVMVertexMetaData : 284 -> 292
~ _glpLLVMFragmentMetaData : 684 -> 680
~ _glpLLVMGetFunctionGlobalVariableUse : 688 -> 700
~ _glpLLVMAddSortedParameters : 264 -> 288
~ _glpLLVMCGPPStreamOpNode : 10316 -> 10288
~ _glpLLVMCGAssign : 1188 -> 1208
~ _glpLLVMCGCommaExpr : 412 -> 404
~ _glpLLVMCGFunctionPrototype : 10228 -> 10148
~ _glpLLVMCGFunctionDefinition : 2468 -> 2496
~ _glpLLVMCGInterfaceBlock : 100 -> 112
~ _glpLLVMCGBlock : 920 -> 880
~ _glpLLVMCGRawCallNode : 260 -> 268
~ _glpLLVMCGSubroutineRawCall : 1032 -> 1060
~ _glpLLVMCGLValue : 2004 -> 2000
~ _glpLLVMWriteOutput : 724 -> 696
~ _glpLLVMCGSamplerNode : 1320 -> 1340
~ _glpBuildConstantIntVector : 304 -> 300
~ _glpLLVMBuildLength : 768 -> 760
~ _glpLLVMBuildCross : 484 -> 456
~ _glpBuildTextureOperation : 5404 -> 5512
~ _glpBuildTextureSizeOperation : 1232 -> 1224
~ _glpLLVMSplatConstantVector : 212 -> 216
~ _glpBuildGetLODOperation : 596 -> 580
~ _glpCGSwizzle : 1396 -> 1412
~ _glpFindGep : 112 -> 116
~ _glpLLVMSplatScalar : 308 -> 312
~ _glpLLVMSplatElement : 340 -> 344
~ _glpProcessComponentWiseVectorAssignment : 2112 -> 2080
~ _glpTypeToLLVMTypeWithUnderlying : 724 -> 720
~ _glpLLVMBuildFunctionType : 1624 -> 1664
~ _glpLLVMVertexGeometryMetadata : 1420 -> 1384
~ _glpLLVMSharedRawCall : 556 -> 592
~ _glpLLVMCGWriteVertexOutput : 464 -> 460
~ _glpMangleNameLLVM : 256 -> 252
~ _glpMangleTypeName : 800 -> 796
~ _glpLLVMCallFunctionInner : 352 -> 356
~ _glpLLVMFunctionType : 248 -> 252
~ _glpLLVMCreateBuilderInContext : 112 -> 108
~ _glpLLVMMDNodeInContext : 232 -> 236
~ _glpLLVMConstInt : 532 -> 492
~ _glpLLVMConstUint64 : 124 -> 120
~ _glpLLVMConstVector : 228 -> 232
~ _glpLLVMConstArray : 244 -> 248
~ _glpLLVMStructTypeInContext : 644 -> 616
~ _glpLLVMBuildFunctionCall : 272 -> 276
~ _glpLLVMBuildGEP : 308 -> 312
~ _glpLLVMBuildInsertValue : 576 -> 544
~ _glpLLVMBuildExtractValue : 560 -> 528
~ _glpLLVMSetCurrentLineStub : 476 -> 444
~ _glpLLVMCallFunction : 472 -> 480
~ _glpGenerateLLVMIRModule : 696 -> 692
~ _glpDeserializeLLVMType : 444 -> 408
~ _glpDeserializeuint32 : 436 -> 404
~ _glpDeserializeArraySize : 436 -> 404
~ _glpDeserializeLLVMValue : 444 -> 408
~ _glpDeserializeLLVMBlock : 444 -> 408
~ _glpGetIBVariableObjectCount : 244 -> 240
~ _glpLinkedProgramGetSubroutineUniformLocationCount : 140 -> 132
~ _deserialize_double : 64 -> 60
~ _glpTypeGetSamplerCount : 244 -> 256
~ __ZN4llvm12DenseMapBaseINS_8DenseMapIPNS_6MDNodeENS_11SmallVectorINS_18TypedTrackingMDRefIS2_EELj1EEENS_12DenseMapInfoIS3_vEENS_6detail12DenseMapPairIS3_S7_EEEES3_S7_S9_SC_E10destroyAllEv : 84 -> 100
~ __ZN4llvm11SmallVectorINS_18TypedTrackingMDRefINS_6MDNodeEEELj1EED2Ev : 116 -> 108
~ __ZN4llvm11SmallVectorINS_18TypedTrackingMDRefINS_6MDNodeEEELj4EED2Ev : 116 -> 108
~ _glpTopLevelNodeGetGlobalTypeQualifier : 88 -> 96
~ _gleLLVMBeginMain : 916 -> 928
~ _gleLLVMAddCommonMetaData : 1256 -> 1240
~ _gleLLVMFinishMain : 728 -> 736
~ _gleLLVMCreateVaryingsMetaData : 604 -> 588
~ _gleLLVMCallFunction : 352 -> 356
~ _gleLLVMCreateConstantVec4 : 196 -> 200
~ _gleLLVMClampColor : 408 -> 412
~ _gleStateProgram_BuildOperation : 708 -> 700
~ _gleLLVMAddOperation : 11664 -> 11688
~ _readTempValue : 204 -> 196
~ _gleLLVMFixPrecision : 192 -> 204
~ _gleStateProgram_BuildTextureOperation : 2464 -> 2444
~ _TestCC_XYZW : 292 -> 300
~ _gleLLVMApplyDestMaskAndCC : 1308 -> 1300
~ _readAddressValue : 204 -> 196
~ _gleLLVMVectorExtend : 484 -> 480
~ _gleVStateProgram_OutputToFunction : 916 -> 920
~ _gleVertexStateToModule : 1012 -> 1036
~ _glpVertexStateToLLVMIR : 1688 -> 1696
~ _gleVStateProgram_AllocateOutputs : 624 -> 708
~ _gleVStateProgram_Core : 15584 -> 15880
~ _gleVStateProgram_GenerateMetadata : 2008 -> 1980
~ _gleVStateProgram_GetAttrib : 152 -> 160
~ _gleVStateProgram_LightingStage : 38392 -> 38868
~ _gleVStateProgram_GetParam : 220 -> 224
~ _gleVStateProgram_MultMatrix4x4 : 2636 -> 2652
~ _gleFStateProgram_AttribToFunction : 564 -> 576
~ _gleFStateProgram_OutputToFunction : 536 -> 540
~ _gleFragmentStateToModule : 1920 -> 1940
~ _glpFragmentStateToLLVMIR : 1356 -> 1380
~ _gleFStateProgram_AllocateAttribs : 904 -> 1028
~ _gleFStateProgram_Core : 12460 -> 12916
~ _gleFStateProgram_GenerateMetadata : 1812 -> 1816
~ _gleFStateProgram_GetFirstActiveTexture : 216 -> 224
~ _gleFStateProgram_AllocateOutput : 116 -> 120
~ _gleFStateProgram_GetOutput : 148 -> 152
~ _gleStateProgram_TextureSampleOp : 652 -> 660
~ _gleFStateProgram_GetParam : 340 -> 344
~ _gleStateProgram_A_MODULATE : 320 -> 328
~ _gleStateProgram_CheckDestInit : 296 -> 304
~ _gleStateProgram_RGB_MODULATE : 320 -> 328
~ _gleStateProgram_RGB_BLEND : 340 -> 348
~ _gleStateProgram_RGB_ADD : 356 -> 364
~ _gleStateProgram_RGBA_MODULATE : 312 -> 320
~ _gleStateProgram_RGBA_BLEND : 608 -> 624
~ _gleStateProgram_RGBA_ADD : 620 -> 636
~ _gleStateProgram_I_BLEND : 332 -> 340
~ _gleStateProgram_I_ADD : 344 -> 352
~ _gleStateProgram_RGBA_DECAL : 340 -> 348
```
