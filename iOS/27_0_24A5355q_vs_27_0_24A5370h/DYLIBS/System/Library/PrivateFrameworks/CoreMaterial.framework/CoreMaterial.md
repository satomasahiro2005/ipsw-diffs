## CoreMaterial

> `/System/Library/PrivateFrameworks/CoreMaterial.framework/CoreMaterial`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1511c` | `0x150a0` | **`-0x7c`** |

### Other Changes

```diff

-222.0.0.0.0
+223.0.0.0.0
Functions:
~ ____LoadCoreMaterialRecipeNames_block_invoke : 564 -> 560
~ -[CABackdropLayer(CoreMaterial) _mt_applyFilterDescription:remainingExistingFilters:filterOrder:removingIfIdentity:] : 800 -> 796
~ -[MTMaterialLayer _updateVisualStylingProviders] : 480 -> 476
~ -[MTTintingMaterialSettings initWithTintingDescription:andDescendantDescriptions:] : 384 -> 380
~ _MTComposedFilterCreateDictionaryRepresentation : 2144 -> 2136
~ -[MTVisualStyleSet initWithName:visualStyleSetDescription:andDescendantDescriptions:] : 1320 -> 1308
~ -[NSMutableDictionary(MTMaterialDescriptionInternal) setValue:forProperty:ofFilter:isCompositingFilter:] : 616 -> 612
~ -[MTCoreMaterialVisualStyling _preProcessFilteringDescription:] : 1228 -> 1224
~ -[NSMutableDictionary(MTMaterialDescriptionInternal) _processAdditionalInfo:forFilterInFiltersArray:] : 328 -> 324
~ -[NSMutableDictionary(MTMaterialDescriptionInternal) setCurvesInputValues:ignoringIdentity:includingOptimizations:withAdditionalInfoPromise:] : 440 -> 436
~ -[MTCoreMaterialVisualStyling initWithVisualStyleSet:styleName:description:andDescendantDescriptions:] : 1236 -> 1220
~ _MTCGImageCreateWithName : 692 -> 688
~ -[CABackdropLayer(CoreMaterial) mt_applyMaterialDescription:removingIfIdentity:] : 1032 -> 1024
~ -[MTMaterialLayer layoutSublayers] : 504 -> 500
~ -[MTMaterialLayer addAnimation:forKey:] : 692 -> 688
~ -[MTCoreMaterialVisualStyling _composedFilter] : 500 -> 496
~ -[MTCoreMaterialVisualStyling _processUserInfoDescription:] : 356 -> 352
~ -[MTTintingFilteringMaterialSettings initWithMaterialDescription:andDescendantDescriptions:bundle:] : 756 -> 748
~ -[MTTintingFilteringMaterialSettings _processUserInfoDescription:] : 356 -> 352
~ -[MTVisualStyleSet description] : 392 -> 388
~ ___MTDiscoveredMaterialRecipes_block_invoke : 620 -> 616
~ ____DiscoveredMaterialRecipeURLs_block_invoke : 384 -> 380
~ -[MTStylingProvidingSolidColorLayer _styleSetForCategory:styleDefinitions:] : 504 -> 500
```
