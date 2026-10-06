## Maps

> `/System/Library/Assistant/Plugins/Maps.assistantBundle/Maps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x18a28` | `0x18c30` | **`+0x208`** |
| `__TEXT.__cstring` | `0xa28f` | `0xa354` | **`+0xc5`** |
| `__DATA_CONST.__cfstring` | `0x87c0` | `0x8860` | **`+0xa0`** |
| `__TEXT.__text` | `0x14684` | `0x146c0` | **`+0x3c`** |

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

-  Functions: 1361
-  Symbols:   1319
-  CStrings:  2004
+  Functions: 1366
+  Symbols:   1324
+  CStrings:  2009
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
```
