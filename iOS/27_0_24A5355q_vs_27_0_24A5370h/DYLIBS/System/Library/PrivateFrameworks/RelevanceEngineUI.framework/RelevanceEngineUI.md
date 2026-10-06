## RelevanceEngineUI

> `/System/Library/PrivateFrameworks/RelevanceEngineUI.framework/RelevanceEngineUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x156a4` | `0x1566c` | **`-0x38`** |

### Other Changes

```text
Functions:
~ -[REUIRelevanceEngineController initWithRelevanceEngine:] : 444 -> 440
~ -[REUIRelevanceEngineController indexPathForElementWithIdentifier:] : 564 -> 560
~ -[REUIRelevanceEngineController generateDiffableSnapshot] : 388 -> 384
~ -[REUIRelevanceEngineController predictedContentForSectionAtIndex:atDate:limit:] : 360 -> 356
~ ___81-[REUIRelevanceEngineController predictedElementsForSectionAtIndex:atDate:limit:]_block_invoke : 424 -> 420
~ ___72-[REUIRelevanceEngineController _loadNewRelevanceEngine:withCompletion:]_block_invoke_2 : 632 -> 628
~ -[REUIRelevanceEngineController _performBatchUpdateUsingBlock:completion:] : 1032 -> 1028
~ -[REUIRelevanceEngineController _performOperations:toSection:] : 2740 -> 2736
~ -[REUIUpNextDataSource initWithRelevanceEngine:] : 444 -> 440
~ -[REUpNextCollectionViewFlowLayout layoutAttributesForElementsInRect:] : 416 -> 412
~ -[REUITrainingContext selectElementWithIdentifier:] : 560 -> 556
~ -[REUITrainingContext resetContext] : 368 -> 364
~ -[REUITrainingContext performSimulationCommand:withOptions:] : 1040 -> 1032
```
