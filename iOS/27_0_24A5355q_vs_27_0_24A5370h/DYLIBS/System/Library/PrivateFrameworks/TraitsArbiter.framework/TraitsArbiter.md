## TraitsArbiter

> `/System/Library/PrivateFrameworks/TraitsArbiter.framework/TraitsArbiter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe144` | `0xe0ec` | **`-0x58`** |

### Other Changes

```text
Functions:
~ -[TRAArbiter acquireParticipantWithRole:delegate:] : 796 -> 792
~ -[TRAArbiter _updateArbitrationWithClientContext:defaultContext:] : 1268 -> 1256
~ -[TRAArbitrationPreferencesResolutionStage updateResolutionWithContext:] : 888 -> 876
~ -[TRAArbiterUpdateOrientationResolutionPolicySpecifier updateStageParticipantsResolutionPolicies:context:] : 348 -> 344
~ +[TRAPreferencesTree treeWithNodesSpecifications:traversalType:debugName:] : 1372 -> 1364
~ _preOrder : 404 -> 400
~ -[TRAArbitrationInputsValidationStage validateInputs:withContext:] : 324 -> 320
~ -[TRAArbiter _resolutionStageWithType:] : 300 -> 296
~ -[TRAPreferencesTree participantsTopologicalSort] : 336 -> 332
~ -[TRAArbiter _setNeedsUpdateArbitrationWithClientContext:defaultContext:] : 604 -> 600
~ -[TRAPreferencesTreeNode setChildren:] : 356 -> 352
~ _appendDescription : 1088 -> 1084
~ -[TRAOrientationResolutionPolicyInfo succinctDescriptionBuilder] : 1348 -> 1340
~ -[TRAArbiter _invalidateParticipant:] : 616 -> 612
~ -[TRAArbiter descriptionBuilderWithMultilinePrefix:] : 696 -> 692
~ ___52-[TRAArbiter descriptionBuilderWithMultilinePrefix:]_block_invoke_5 : 432 -> 428
```
