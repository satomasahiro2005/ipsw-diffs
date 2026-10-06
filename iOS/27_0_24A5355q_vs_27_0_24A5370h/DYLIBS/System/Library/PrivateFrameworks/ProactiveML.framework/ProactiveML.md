## ProactiveML

> `/System/Library/PrivateFrameworks/ProactiveML.framework/ProactiveML`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x449a0` | `0x447a0` | **`-0x200`** |

### Other Changes

```diff

-1331.0.1.0.0
+1334.0.1.0.0
Functions:
~ -[PMLTraining deleteSessionsWithIdentifiers:bundleID:] : 276 -> 272
~ +[PMLMultiLabelEspressoClassifier makeStringForShape:] : 160 -> 168
~ +[PMLMultiLabelEspressoClassifier getNumParametersFromShape:rank:] : 48 -> 56
~ -[PMLMultiLabelEspressoClassifier predict:] : 680 -> 676
~ -[AWDProactiveModelFittingEvaluation dictionaryRepresentation] : 652 -> 648
~ -[AWDProactiveModelFittingEvaluation writeTo:] : 420 -> 416
~ -[AWDProactiveModelFittingEvaluation copyWithZone:] : 492 -> 488
~ -[AWDProactiveModelFittingEvaluation mergeFrom:] : 492 -> 488
~ -[PMLMultiLabelRegressionEvaluationPlan _precisionAtEvaluationPointsForSessions:] : 1480 -> 1468
~ -[AWDProactiveModelFittingQuantizedSparseVector writeTo:] : 400 -> 392
~ -[PMLLogRegTrainingPlan normalizeRegressor:] : 288 -> 280
~ -[AWDProactiveModelFittingSparseFloatVector writeTo:] : 260 -> 252
~ ___87-[PMLTrainingStore storeSession:label:model:bundleId:domainId:itemIds:isAppleInternal:]_block_invoke : 996 -> 992
~ -[PMLTrainingStore _loadDataFromLabelAndTuples:model:numberOfRows:numberOfColumns:lastUsedMax:block:] : 1044 -> 1040
~ -[PMLTrainingStore limitSessionsForEachLabelWithSessionDescriptor:totalSessionLimit:] : 816 -> 812
~ ___78+[PMLTrainingStore _runQueries:andUpdateVersionTo:inTransactionOnDb:forStore:]_block_invoke : 512 -> 508
~ ___52-[PMLTrainingStore convertToBagOfIdsVectorForModel:]_block_invoke_3 : 544 -> 536
~ -[AWDProactiveModelFittingSparseFloatMatrix writeTo:] : 368 -> 356
~ -[AWDProactiveModelFittingQuantizedSparseMatrix writeTo:] : 536 -> 524
~ -[PMLModelWeights(PMLMobileAssetParameterGetStrategy) initFromDictionary:] : 492 -> 488
~ -[PMLModelWeights(PMLMobileAssetParameterGetStrategy) toDictionary] : 428 -> 424
~ _arrayFromFloats : 156 -> 164
~ -[PMLModelRegressor(PMLMobileAssetParameterGetStrategy) initFromDictionary:] : 388 -> 384
~ -[PMLModelWeights(PMLPlistAndChunksSerialization) migrateDenseDoubleVectorToDenseFloatVector:] : 272 -> 264
~ -[PMLModelRegressor(PMLPlistAndChunksSerialization) migrateDenseDoubleVectorToDenseFloatVector:] : 272 -> 264
~ -[PMLMultiLabelLogisticRegressionModel initWithWeightsArray:andIntercept:] : 372 -> 368
~ -[PMLMultiLabelLogisticRegressionModel predict:] : 492 -> 488
~ -[PMLMultiLabelLogisticRegressionModel toPlistWithChunks:] : 420 -> 416
~ -[PMLMultiLabelLogisticRegressionModel initWithPlist:chunks:context:] : 424 -> 420
~ -[PMLDiffPrivacyNoiseStrategy createSamplerByName:] : 248 -> 244
~ -[PMLDiffPrivacyNoiseStrategy addNoiseToSparseVector:] : 756 -> 740
~ -[PMLDiffPrivacyNoiseStrategy addNoiseToSparseMatrix:] : 1016 -> 1024
~ +[PMLClassificationEvaluationMetrics precision:predictions:predicate:] : 272 -> 264
~ +[PMLClassificationEvaluationMetrics recall:predictions:predicate:] : 272 -> 264
~ +[PMLClassificationEvaluationMetrics truePositives:predictions:predicate:] : 232 -> 224
~ +[PMLClassificationEvaluationMetrics falsePositives:predictions:predicate:] : 232 -> 224
~ +[PMLClassificationEvaluationMetrics trueNegatives:predictions:predicate:] : 236 -> 228
~ +[PMLClassificationEvaluationMetrics falseNegatives:predictions:predicate:] : 236 -> 228
~ +[PMLClassificationEvaluationMetrics addScoresForOutcomes:predictions:predicate:metrics:] : 348 -> 340
~ -[AWDProactiveModelFittingQuantizedSparseMatrix(PML_VisibleForTesting) originalValueAtRow:column:] : 220 -> 212
~ -[AWDProactiveModelFittingEvaluation(VisibleForTesting) precisionAtK:] : 296 -> 292
~ ___migrateSessionsToFloats_block_invoke : 528 -> 532
~ -[PMLDenseVector initWithNumbers:] : 244 -> 240
~ -[PMLDenseVector minValue] : 136 -> 132
~ -[PMLDenseVector maxValue] : 136 -> 132
~ -[PMLDenseVector enumerateValuesWithBlock:] : 156 -> 152
~ -[PMLDenseVector enumerateNonZeroValuesWithBlock:] : 164 -> 160
~ -[PMLMutableDenseVector processValuesInPlaceWithBlock:] : 168 -> 156
~ +[AWDProactiveModelFittingSparseFloatVector(PML) sparseFloatVectorFromModelWeights:] : 200 -> 196
~ -[AWDProactiveModelFittingSparseFloatVector(PML) valueAtIndex:] : 132 -> 128
~ -[AWDProactiveModelFittingEvalMetrics writeTo:] : 564 -> 556
~ -[PMLSparseMatrix valueAtRow:column:] : 320 -> 316
~ ___51-[PMLSparseMatrix enumerateNonZeroValuesWithBlock:]_block_invoke : 108 -> 116
~ +[PMLEspressoTrainingPlan numberOfParametersInTensor:] : 264 -> 260
~ +[PMLEspressoTrainingPlan isValidGradient:error:] : 512 -> 508
~ +[PMLEspressoTrainingPlan _iterateModelParametersForTask:globalNames:weightNames:biasNames:block:] : 1576 -> 1564
~ +[PMLEspressoTrainingPlan _calculateTrainingMetricsWithSamplingProb:groundTruthProvider:predictionsProvider:trueLabelName:trainingOutputName:lossValueName:probThreshold:includeSummableOnly:] : 2940 -> 2932
~ -[AWDProactiveModelFittingSparseFloatMatrix(PML) valueAtRow:column:] : 160 -> 152
~ ___156+[PMLLogisticRegressionModel solverWithWeights:andIntercept:learningRate:minIterations:stoppingThreshold:regularizationStrategy:regularizationRate:l1Ratio:]_block_invoke : 1684 -> 1652
~ ___156+[PMLLogisticRegressionModel solverWithWeights:andIntercept:learningRate:minIterations:stoppingThreshold:regularizationStrategy:regularizationRate:l1Ratio:]_block_invoke_3 : 328 -> 316
~ +[PMLModelRegressor regressorVectorFrom:] : 256 -> 252
~ _DescribeTensorDescriptor : 3372 -> 3336
~ -[PMLMultiLabelE5Classifier predict:] : 380 -> 376
~ -[PMLHashingVectorizer transformWithFrequency:shouldDecrement:] : 376 -> 384
~ _hashingVectorizeTokens : 1428 -> 1424
~ ___63-[PMLHashingVectorizer transformWithFrequency:shouldDecrement:]_block_invoke : 64 -> 68
~ ___50-[PMLHashingVectorizer transformSequentialNGrams:]_block_invoke : 56 -> 52
~ -[PMLHashingVectorizer transformBatch:] : 324 -> 320
~ ___hashingVectorizeTokens_block_invoke : 300 -> 292
~ -[AWDProactiveModelFittingEvalMetrics(PMLJson) toDictionary] : 800 -> 792
~ -[PMLDenseMatrix enumerateNonZeroValuesWithBlock:] : 220 -> 208
~ +[PMLDenseMatrix denseMatrixFromNumbers:] : 544 -> 536
~ ___38-[PMLTraining sendSessionStatsToFides]_block_invoke : 1076 -> 1064
~ -[PMLTraining deleteSessionsWithDomainIdentifiers:bundleID:] : 276 -> 272
~ -[PMLTraining planReceivedWithRecipe:attachments:error:] : 1260 -> 1248
~ -[AWDProactiveModelFittingQuantizedSparseVector(PML_VisibleForTesting) originalValueAtIndex:] : 192 -> 188
~ -[AWDProactiveModelFittingQuantizedDenseVector writeTo:] : 248 -> 244
~ +[PMLDataChunk chunksFromData:] : 596 -> 600
~ -[PMLWordPieceTokenizer tokenizeToIds:fromString:tokens:tokenCount:length:] : 920 -> 928
~ -[AWDProactiveModelFittingMinibatchStats dictionaryRepresentation] : 548 -> 544
~ -[AWDProactiveModelFittingMinibatchStats writeTo:] : 360 -> 356
~ -[AWDProactiveModelFittingMinibatchStats copyWithZone:] : 416 -> 412
~ -[AWDProactiveModelFittingMinibatchStats mergeFrom:] : 380 -> 376
~ +[PMLModelWeights constWeightsOfLength:value:] : 244 -> 248
~ +[PMLModelWeights weightsFromNumbers:] : 300 -> 296
~ -[PMLTrainingStoredSessionBatch minibatchStatsForPositiveLabels:] : 600 -> 596
~ -[PMLTrackerMockAdapter trackedMessagesByClass:] : 316 -> 312
~ -[PMLLogRegEvaluationPlan normalizeRegressor:] : 288 -> 280
~ -[PMLEspressoDataProvider initWithRowsData:labelsData:inputName:inputDim:trueLabelName:] : 684 -> 680
~ +[PMLSparseVector sparseVectorFromDense:length:] : 276 -> 272
~ -[PMLSparseVector indicesData] : 212 -> 216
~ -[PMLSparseVector indicesAsUInt16Data] : 300 -> 304
~ -[PMLSparseVector quantizedValuesAsUInt8DataWithMin:max:] : 276 -> 272
~ -[PMLSparseVector minValue] : 56 -> 64
~ -[PMLSparseVector maxValue] : 56 -> 64
~ -[PMLSparseVector applyOneHotNormalization] : 48 -> 56
~ -[PMLSparseVector enumerateNonZeroValuesWithBlock:] : 112 -> 104
~ -[PMLSparseVector processNonZeroValuesInPlaceWithBlock:] : 128 -> 116
~ +[PMLSparseVector sparseVectorWithLength:numberOfNonZeroValues:isSparseIndexInt64:sparseIndices:sparseValues:toDenseValues:withLength:] : 324 -> 312
~ -[PMLSparseVector convertToBagOfIds] : 60 -> 52
~ -[PMLSparseVector addStartId:endId:paddingId:withMaxVectorLength:] : 404 -> 396
~ -[PMLSparseVector valueAtIndex:] : 140 -> 136
~ +[PMLSparseVector sparseVectorFromNumbers:] : 276 -> 272
~ _collectPerLabelCounts : 448 -> 444
~ -[AWDProactiveModelFittingMinibatchStats(VisibleForTesting) supportForLabel:] : 296 -> 292
~ +[AWDProactiveModelFittingMinibatchStats(VisibleForTesting) statsWithPerLabelCounts:] : 432 -> 428
```
