## CarPlaySetup

> `/System/Library/PrivateFrameworks/CarPlaySetup.framework/CarPlaySetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb6bc` | `0xb754` | **`+0x98`** |
| `__AUTH_CONST.__const` | `0xa0` | `0x80` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x290` | `0x270` | **`-0x20`** |

### Other Changes

```diff

-789.1.0.0.0
+792.0.0.0.0

-  Symbols:   523
+  Symbols:   522
Symbols:
+ +[CARSetupPrompts waitingOnStartSessionPromptWithResponseHandler:]
+ ___66+[CARSetupPrompts waitingOnStartSessionPromptWithResponseHandler:]_block_invoke
- +[CARSetupPrompts waitingOnStartSessionPrompt]
- ___46+[CARSetupPrompts waitingOnStartSessionPrompt]_block_invoke
- ___block_descriptor_32_e19_v16?0"PRXAction"8l
Functions:
~ -[CARSetupOnboardingViewController initWithFeatures:doneHandler:] : 3000 -> 3056
~ -[CALayer(CARMicaPlayerAdditions) car_deepCopyLayer] : 912 -> 900
~ -[CALayer(CARMicaPlayerAdditions) car_addLayerAndSublayersToArray:allowHiddenLayers:] : 364 -> 360
~ -[CALayer(CARMicaPlayerAdditions) car_allLayersWhoseNamesContainString:] : 396 -> 392
~ -[CALayer(CARMicaPlayerAdditions) car_allLayersWithKindOfClass:] : 328 -> 324
~ -[CALayer(CARMicaPlayerAdditions) car_allAnimationsInTree] : 480 -> 476
~ -[CALayer(CARMicaPlayerAdditions) car_setFillOfAllShapeLayersToColor:] : 272 -> 268
~ +[CARMicaPlayer updatePublishedObjects:toReferenceLayersInTree:ratherThanLayersInTree:] : 608 -> 604
~ +[CARSetupPrompts waitingOnStartSessionPrompt] -> +[CARSetupPrompts waitingOnStartSessionPromptWithResponseHandler:] : 480 -> 588
~ ___46+[CARSetupPrompts waitingOnStartSessionPrompt]_block_invoke -> ___66+[CARSetupPrompts waitingOnStartSessionPromptWithResponseHandler:]_block_invoke : 104 -> 128
```
