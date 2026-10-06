## Maps

> `/System/Library/Assistant/UIPlugins/Maps.siriUIBundle/Maps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x18530` | `0x18738` | **`+0x208`** |
| `__TEXT.__cstring` | `0x9885` | `0x994a` | **`+0xc5`** |
| `__DATA_CONST.__cfstring` | `0x7ec0` | `0x7f60` | **`+0xa0`** |
| `__TEXT.__text` | `0x10da4` | `0x10de0` | **`+0x3c`** |
| `__TEXT.__objc_methtype` | `0x2dbf` | `0x2dfa` | **`+0x3b`** |
| `__TEXT.__objc_methname` | `0x6ec3` | `0x6eeb` | **`+0x28`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2972.31.6.17.20
+2972.31.6.17.31

-  Functions: 1320
-  Symbols:   1221
-  CStrings:  2382
+  Functions: 1325
+  Symbols:   1226
+  CStrings:  2388
Symbols:
+ _MapsConfig_CustomPOIControllerSkipsHashCheck
+ _MapsConfig_DeferAuxiliaryTasksUntilForegrounded
+ _MapsConfig_ParkedCarDonationSeedRetryInterval
+ _MapsConfig_SearchHomeEnrichmentRequestGenerationBudget
+ _MapsConfig_SearchResultsEnrichmentRequestGenerationBudget
CStrings:
+ "CustomPOIControllerSkipsHashCheck"
+ "DeferAuxiliaryTasksUntilForegrounded"
+ "ParkedCarDonationSeedRetryInterval"
+ "SearchHomeEnrichmentRequestGenerationBudget"
+ "SearchResultsEnrichmentRequestGenerationBudget"
+ "placeViewControllerDidSelectPlaceEnrichmentRAP:selectedShowcaseId:displayedShowcaseIds:"
+ "v40@0:8@\"MUPlaceViewController\"16@\"NSString\"24@\"NSArray\"32"
- "placeViewControllerDidSelectPlaceEnrichmentRAP:"
```
