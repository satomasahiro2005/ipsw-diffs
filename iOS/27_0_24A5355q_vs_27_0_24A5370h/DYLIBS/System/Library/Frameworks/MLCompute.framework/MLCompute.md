## MLCompute

> `/System/Library/Frameworks/MLCompute.framework/MLCompute`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x113284` | `0x112e90` | **`-0x3f4`** |
| `__TEXT.__unwind_info` | `0x1e38` | `0x1e30` | **`-0x8`** |

### Other Changes

```text
Functions:
~ _CPU_BuildBNNSNDArrayLastMajorDescriptor : 1428 -> 1468
~ _CPU_BuildBNNSNDArrayDescriptor : 1684 -> 1728
~ _CPU_BuildPermuteBNNSNDArrayDescriptor : 1320 -> 1352
~ _CPU_BuildBNNSNDArrayDescriptorRowMajor : 604 -> 600
~ _CPU_BuildBNNSNDArrayDescriptorColMajor : 436 -> 448
~ _convertDataLayout : 1012 -> 948
~ _convertNCHWtoTNC : 616 -> 544
~ _convertNSEtoTNC : 496 -> 448
~ _convertTNCtoNCHW : 616 -> 568
~ _convertTNCtoNTC : 476 -> 436
~ _convertHiddenBNNStoMLC : 372 -> 348
~ _convertNCtoTNC : 200 -> 228
~ +[_MLCGPUMatMul compileWithDevice:deviceOps:sourceTensors:resultTensor:] : 3044 -> 3064
~ _ANE_CreateSliceLayer : 1232 -> 1228
~ _ANE_CompileComparisonLayer : 2068 -> 2064
~ _ANE_CreateUnitsWithArithmeticOpeartion : 6740 -> 6732
~ -[MLCDeviceANE(MLCLayerOperations) resetLayer:] : 284 -> 280
~ -[MLCDeviceANE(MLCLayerOperations) partitionInferenceGraph:startAtLayerIndex:aneDevice:secondaryDevice:configurationJSON:] : 1320 -> 1312
~ -[MLCDeviceANE(MLCLayerOperations) saveGraphPartitioning:toFile:] : 776 -> 772
~ -[MLCDeviceANE(MLCLayerOperations) partitionInferenceGraph:startAtLayerIndex:aneDevice:secondaryDevice:] : 4424 -> 4416
~ _ANE_IsSupportedLayer : 1244 -> 1236
~ _buildANESubgraph : 1992 -> 1980
~ -[MLCDeviceANE(MLCLayerOperations) updateTensorsForFusedLayers:ofInferenceGraph:] : 1840 -> 1824
~ _canMergeANESubgraphsHelper : 1100 -> 1088
~ -[MLCLayer isFirstLayer] : 296 -> 292
~ -[MLCLayer isLastLayer] : 296 -> 292
~ -[MLCDeviceGPU(MLCLayerOperations) fuseLayersForGraph:stopGradientTensorList:startAtLayerIndex:forInference:] : 2476 -> 2472
~ -[MLCDeviceGPU(MLCLayerOperations) weightsGradients:] : 1784 -> 1776
~ -[MLCDeviceGPU(MLCLayerOperations) biasesGradients:] : 792 -> 784
~ -[MLCDeviceGPU(MLCLayerOperations) mhaWeightGradient:withSize:index:] : 524 -> 540
~ -[MLCDeviceGPU(MLCLayerOperations) mhaBiasGradient:withSize:index:] : 528 -> 544
~ -[MLCDeviceGPU(MLCLayerOperations) mhaAttnBiasGradient:withSize:index:] : 556 -> 552
~ -[MLCDeviceGPU(MLCLayerOperations) lstmInputWeightGradient:mlcWeightIndex:] : 716 -> 708
~ -[MLCDeviceGPU(MLCLayerOperations) lstmHiddenWeightGradient:mlcWeightIndex:] : 716 -> 708
~ -[MLCDeviceGPU(MLCLayerOperations) lstmBiasGradient:mlcBiasIndex:] : 716 -> 708
~ -[MLCDeviceGPU(MLCLayerOperations) betaGradients:] : 476 -> 468
~ -[MLCDeviceGPU(MLCLayerOperations) gammaGradients:] : 476 -> 468
~ -[MLCDeviceGPU(MLCLayerOperations) embeddingWeightsGradients:embeddingCount:embeddingDimension:] : 440 -> 432
~ -[MLCDeviceGPU commitAndWaitForCompletion:enableProfiling:graphExecutionTime:graphResultTensor:] : 992 -> 976
~ -[MLCDeviceGPU multiDeviceTensorReduction:sourceBuffer:targetBuffer:] : 336 -> 312
~ -[MLCDeviceGPU signalNextEvent] : 128 -> 124
~ -[MLCDeviceGPU waitForOthers] : 120 -> 116
~ -[MLCDeviceCPU(MLCLayerOperations) weightsGradients:] : 200 -> 192
~ -[MLCDeviceCPU(MLCLayerOperations) lstmInputWeightGradient:mlcWeightIndex:] : 324 -> 328
~ -[MLCDeviceCPU(MLCLayerOperations) embeddingWeightsGradients:embeddingCount:embeddingDimension:] : 516 -> 508
~ -[MLCDeviceCPU(MLCLayerOperations) allocateParameterGradientsForDeviceOps:parameters:] : 4132 -> 4144
~ -[_MLCCPUMHAttention initWithDevice:descriptor:weights:bias:attnBias:inferenceOnly:] : 4272 -> 4296
~ +[_MLCCPUMHAttention setOptimizerDataForDevice:deviceOps:dataForWeights:dataForBias:] : 1528 -> 1468
~ +[_MLCANEPlistBuilder createUnitWithLayer:unitParams:] : 1588 -> 1580
~ -[_MLCANEPlistBuilder addInputs:ofUnit:ofOperation:toProcedure:toNetwork:] : 1208 -> 1196
~ -[_MLCANEPlistBuilder unitBottomNamesWithSourceTensor:liveInputs:unitBottomNames:sourceTensorsToLiveUp:] : 1084 -> 1080
~ -[_MLCANEPlistBuilder addUnitsAndInputsAndOutpusOfLayer:toNetwork:toProcedure:operationName:liveInputs:liveOutputs:] : 2080 -> 2068
~ -[_MLCANEPlistBuilder buildProcedureWithRootLayer:aneSubgraphLayerList:liveInputs:liveOutputs:] : 1752 -> 1748
~ -[_MLCANEPlistBuilder releaseWeights] : 336 -> 332
~ -[MLCDeviceANE needToAllocateDeviceMemoryForTensor:] : 440 -> 436
~ -[MLCDeviceANE allocateDeviceMemoryForSourceAndResultTensorsOfLayer:tensorLabelToIOSurfaceMap:] : 824 -> 820
~ -[MLCDeviceANE procedureInformationWithModelAttributes:procedureName:procedureID:procedureInputSymbols:procedureInputSymbolIndices:procedureOutputSymbols:procedureOutputSymbolIndices:] : 1420 -> 1412
~ -[MLCDeviceANE postProcessCompiledGraph:compilerOptions:] : 2484 -> 2480
~ -[MLCDeviceGPU(MLCEngineDispatch) dispatchTransposeKernel:sourceTensor:resultTensor:deviceIndex:forward:] : 1668 -> 1636
~ -[MLCDeviceGPU(MLCEngineDispatch) dispatchGradientArithmeticBinaryKernel:sourceGradientTensor:resultGradientTensor:secondaryResultGradientTensor:deviceIndex:] : 4672 -> 4720
~ -[MLCDeviceGPU(MLCEngineDispatch) dispatchForwardScatterLayer:sourceTensors:resultTensor:forTraining:] : 2676 -> 2692
~ -[MLCDeviceGPU(MLCEngineDispatch) dispatchForwardGatherLayer:sourceTensors:resultTensor:forTraining:] : 1528 -> 1544
~ -[MLCDeviceGPU(MLCEngineDispatch) dispatchForwardSliceLayer:sourceTensor:resultTensor:forTraining:] : 1512 -> 1584
~ -[MLCDeviceGPU(MLCEngineDispatch) dispatchGradientMatMulLayer:sourceGradientTensor:resultGradientTensors:] : 3836 -> 3832
~ -[MLCDeviceGPU(MLCEngineDispatch) dispatchGradientMHALayer:sourceGradientTensor:resultGradientTensors:resultStateIsTemporary:] : 8296 -> 8292
~ -[MLCDeviceGPU(MLCEngineDispatch) dispatchGradientSliceLayer:sourceGradientTensor:resultGradientTensor:] : 1528 -> 1596
~ -[MLCDeviceGPU(MLCEngineDispatch) dispatchForwardAndGradientLossLayer:sourceTensor:labelsTensor:labelsTensorStride:weightsTensor:resultTensor:resultGradientTensor:] : 3684 -> 3648
~ -[MLCDeviceGPU(MLCEngineDispatch) dispatchRNNForwardLayer:sourceTensors:resultTensors:] : 8432 -> 8332
~ -[MLCDeviceGPU(MLCEngineDispatch) dispatchRNNForwardLayer:sourceTensors:resultTensors:resultStateIsTemporary:forTraining:] : 9636 -> 9656
~ -[MLCDeviceGPU(MLCEngineDispatch) dispatchRNNGradientLayer:sourceGradientTensors:resultGradientTensors:] : 7200 -> 7236
~ -[MLCTrainingGraph sumAllRootSourceGradientTensors:] : 508 -> 504
~ -[MLCTrainingGraph compileWithOptions:device:inputTensors:inputTensorsData:] : 4468 -> 4464
~ _rotateWeightsTensorBy180Degree : 400 -> 392
~ _GPU_GetDataSourceFromTensors : 312 -> 308
~ _GPU_AssociateDataSourceToTensors : 256 -> 252
~ _GPU_clearTemporaryImageBatchReadCount : 304 -> 300
~ -[MLCInferenceGraph compileWithOptions:device:inputTensors:inputTensorsData:] : 4228 -> 4216
~ -[MLCInferenceGraph executeWithInputsData:lossLabelsData:lossLabelWeightsData:outputsData:batchSize:options:completionHandler:] : 10848 -> 10836
~ -[MLCDeviceCPU(MLCEngineDispatch) dispatchForwardSplitLayer:sourceTensor:resultTensors:forConcat:] : 1344 -> 1328
~ -[MLCDeviceCPU(MLCEngineDispatch) dispatchGradientSplitLayer:sourceGradientTensors:resultGradientTensor:forConcat:] : 1376 -> 1360
~ -[MLCDeviceCPU(MLCEngineDispatch) dispatchForwardEmbeddingLayer:weight:sourceTensor:resultTensor:] : 1444 -> 1424
~ -[MLCDeviceCPU(MLCEngineDispatch) dispatchGradientMatMulLayer:sourceGradientTensor:resultGradientTensors:] : 1332 -> 1328
~ -[MLCDeviceCPU(MLCEngineDispatch) dispatchGradientEmbeddingLayer:sourceGradientTensor:] : 792 -> 804
~ -[MLCDeviceCPU(MLCEngineDispatch) dispatchRNNForwardLayer:sourceTensors:resultTensors:resultStateIsTemporary:forTraining:] : 2828 -> 2824
~ -[MLCDeviceCPU(MLCEngineDispatch) dispatchRNNGradientLayer:sourceGradientTensors:resultGradientTensors:] : 3372 -> 3368
~ -[MLCDeviceCPU(MLCEngineDispatch) dispatchForwardScatterLayer:sourceTensors:resultTensor:forTraining:] : 1316 -> 1320
~ -[MLCDeviceCPU(MLCEngineDispatch) dispatchForwardGatherLayer:sourceTensors:resultTensor:forTraining:] : 1152 -> 1160
~ _ANE_ValidateConcatUnit : 1096 -> 1084
~ _ANE_ValidateConvolutionUnit : 1536 -> 1532
~ _ANE_ValidateInstanceNormUnit : 1080 -> 1072
~ _ANE_ValidateNeuronUnit : 1056 -> 1052
~ _ANE_ValidatePoolingUnit : 1220 -> 1216
~ _ANE_ValidateSoftmaxUnit : 1000 -> 996
~ _ANE_ValidateReshapeUnit : 1152 -> 1148
~ _ANE_ValidateTransposeUnit : 1180 -> 1176
~ _ANE_ValidateReductionUnit : 1132 -> 1124
~ _ANE_ValidateBroadcastUnit : 988 -> 984
~ _ANE_ValidateElementWiseUnit : 1144 -> 1116
~ _ANE_ValidateInputViewUnit : 1060 -> 1056
~ _ANE_ValidateArgMinMaxUnit : 1116 -> 1112
~ _ANE_ValidateGOCUnit : 924 -> 920
~ _ANE_ValidateMatrixMultUnit : 1196 -> 1168
~ _ANE_ValidateLayerNormUnit : 1152 -> 1144
~ _ANE_BuildReductionParams : 744 -> 736
~ +[_MLCCPULSTM setOptimizerDataForDevice:deviceOps:dataForInputWeights:dataForHiddenWeights:dataForPeepholeWeights:dataForBias:] : 1776 -> 1784
~ _createParameterPointersForGate : 432 -> 436
~ _createBiDirectionalAndStackedGateWeightData : 404 -> 412
~ +[_MLCANEWeightOps hexStringForData:] : 248 -> 256
~ +[MLCPatternMatcher canTransformToHardSwishFromLayer:stopGradientTensorList:fusedLayers:inputTensor:] : 2400 -> 2388
~ +[MLCPatternMatcher getAccuracyForLayer:] : 356 -> 352
~ +[MLCPatternMatcher isConstTensor:withValue:withAccuracy:] : 440 -> 456
~ _ANE_BuildBatchNormalizationParams : 1508 -> 1492
~ _ANE_CalculateScaleAndBiasForInstanceNorm : 772 -> 756
~ _ANE_CreateBroadcastedConstantTensor : 704 -> 708
~ _ANE_CompressSparseKernel : 824 -> 808
~ _ANE_FindUnitWithType : 356 -> 352
~ _ANE_CalculateIOInterleave : 340 -> 344
~ _ANE_ConvertInputTensor : 2056 -> 1936
~ _ANE_ReadOutputTensor : 2448 -> 2340
~ _ANE_ComputeLiveOutputs : 724 -> 720
~ _ANE_ComputeLiveInputs : 708 -> 704
~ _ANE_WriteANEModelFiles : 1052 -> 1048
~ +[MLCDataHelper fillData:withFloatValue:] : 124 -> 132
~ -[MLCConcatenationLayer resultTensorFromSources:] : 768 -> 756
~ -[_MLCANEDomTree doesLayer:dominatesSubgraph:] : 300 -> 296
~ -[_MLCANEDomTree doesSubgraph:dominatesLayer:] : 304 -> 300
~ -[_MLCANEDomTree doesSubgraph:dominatesSubgraph:] : 640 -> 636
~ -[_MLCANEDomTree getDominanceFrontierForSubgraph:] : 620 -> 616
~ -[_MLCANEDomTree getPostDominanceFrontierForSubgraph:] : 620 -> 616
~ +[_MLCANEDomTree computeDominationForLayer:dominationTree:] : 656 -> 652
~ +[_MLCANEDomTree computeDominationForGraphImpl:] : 320 -> 316
~ -[MLCDeviceGPU(MLCEngineDispatch) updateConvolutionLayer:optimizer:weightsParameter:biasesParameter:arrayOfParams:] : 1692 -> 1688
~ -[MLCDeviceGPU(MLCEngineDispatch) updateFullyConnectedLayer:optimizer:weightsParameter:biasesParameter:arrayOfParams:] : 1352 -> 1348
~ -[MLCDeviceGPU(MLCEngineDispatch) saveOrRestoreTempMatrixDisableUpdates:commandBuffer:auxiliaryWeightsMemory:auxiliaryMomentumMemory:auxiliaryVelocityMemory:auxiliaryCenterWeightMemory:deviceNumber:kernelNumber:mlcIndex:auxIndex:numOptimizerData:saveToAux:isInputWeight:isHiddenWeight:isBias:] : 1468 -> 1464
~ -[MLCDeviceGPU(MLCEngineDispatch) synchronizeUpdatesForLayer:] : 2752 -> 2748
~ -[MLCDeviceGPU(MLCEngineDispatch) checkToConvertTensor:inLayer:] : 296 -> 292
~ -[MLCDeviceGPU(MLCEngineDispatch) updateMultiheadAttentionLayer:optimizer:weightsParameter:biasesParameter:arrayOfParams:] : 2100 -> 2092
~ -[MLCDeviceGPU(MLCEngineDispatch) reloadLSTMParameters:rnnGPUDeviceOps:mlcParameterIndex:tensor:isInputWeight:isHiddenWeight:isBias:deviceNumber:] : 1492 -> 1560
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) updateBatchNormalizationLayer:optimizer:betaParameter:gammaParameter:meanTensor:varianceTensor:arrayOfParams:] : 1108 -> 1116
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) sumSharedGradientsForConvolutionLayerTensorParameter:layerIndexForSummedGradients:] : 888 -> 892
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) sumSharedGradientsForNormalizationLayerTensorParameter:layerIndexForSummedGradients:isBetaTensor:] : 832 -> 844
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) updateFullyConnectedLayer:optimizer:weightsParameter:biasesParameter:arrayOfParams:] : 1008 -> 1012
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) optimizerStepForSingleParameterLSTM:tensorParameters:parameterForGateDesc:gradientsForGateDesc:parameterMomentumDescData:gateIndex:deviceOptimizers:isStackedInputWeight:] : 1288 -> 1292
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) updateRNNLayer:optimizer:inputWeightsParameter:hiddenWeightsParameter:biasesParameter:arrayOfParams:] : 2388 -> 2400
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) updateMultiheadAttentionLayer:optimizer:weightsParameter:biasesParameter:arrayOfParams:] : 2520 -> 2448
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) updateEmbeddingLayer:weightsParameter:optimizer:arrayOfParams:] : 1208 -> 1228
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) updateAllParametersWithOptimizer:arrayOfParameters:] : 624 -> 612
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) updateTensorParameter:optimizer:gradient:arrayOfParams:] : 896 -> 892
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) exportBiasGateOptimizerDataForDeviceOps:biasTensors:gateIndex:optimizerDataIndex:] : 424 -> 420
~ -[MLCDeviceCPU(MLComputeEngineOptimizerUpdate) accumulateParams:gradients:accumulators:numOfParameters:inArrayOfParams:] : 424 -> 432
~ ___37-[MLCTensor dataContainsScalarWhere:]_block_invoke : 572 -> 568
~ +[MLCTensor newRandomDataForWeightTensorDescriptor:randomInitializerType:] : 964 -> 948
~ -[MLCGraph initWithGraphObjects:] : 1636 -> 1624
~ -[MLCGraph dealloc] : 2076 -> 2064
~ -[MLCGraph linkSourceTensorsWithLayer:sources:] : 928 -> 924
~ -[MLCGraph bindAndWriteData:forInputs:toDevice:batchSize:synchronous:skipWrite:] : 1720 -> 1716
~ -[MLCGraph createVariableLengthSequenceTensorsForLayer:withVariableSequenceLength:] : 796 -> 792
~ -[MLCGraph enumerateInputsUsingBlock:] : 368 -> 364
~ -[MLCGraph enumerateOutputsUsingBlock:] : 544 -> 540
~ -[MLCGraph checkPageAlignmentAndSizeForOutputs:] : 388 -> 384
~ -[MLCGraph updateOutputTensorsDeviceMemoryWithData:] : 392 -> 388
~ -[MLCGraph addOutputs:] : 788 -> 780
~ -[MLCGraph dispatchReadsForMultipleTensorOutputs:finalTensorInGraph:finalResultTensor:batchSize:] : 768 -> 760
~ -[MLCGraph summarizedDOTDescription] : 4868 -> 4852
~ -[MLCGraph updateLSTMLayersForVariableSequenceLengthInGraph:withInputData:] : 672 -> 668
~ -[MLCLSTMLayer isSupportedShapeForTensorSources:] : 1624 -> 1620
~ -[MLCLSTMLayer linkAssociatedTensors] : 776 -> 760
~ -[MLCLSTMLayer unlinkAssociatedTensors] : 776 -> 760
~ _ANE_CompileFullyConnectedLayer : 2524 -> 2464
```
