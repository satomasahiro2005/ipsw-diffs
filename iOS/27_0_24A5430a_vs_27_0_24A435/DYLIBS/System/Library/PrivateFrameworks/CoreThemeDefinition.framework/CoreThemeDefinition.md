## CoreThemeDefinition

> `/System/Library/PrivateFrameworks/CoreThemeDefinition.framework/CoreThemeDefinition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x7965` | `0x78fe` | **`-0x67`** |
| `__AUTH_CONST.__cfstring` | `0x64c0` | `0x6480` | **`-0x40`** |
| `__TEXT.__text` | `0x561b4` | `0x561b8` | **`+0x4`** |

### Other Changes

```diff

-  CStrings:  864
+  CStrings:  862
Functions:
~ ___87-[CoreThemeDocument importNamedAssetsWithImportInfos:referenceFiles:completionHandler:]_block_invoke : 612 -> 588
~ +[CoreThemeConstantHelper helperForStructAtIndex:inAssociatedGlobalList:] : 848 -> 892
~ -[TDThemeSchema _sanityCheckColorNamesAndUpdateIfNecessary] : 596 -> 580
CStrings:
- "Apple11 not supported"
- "Unrecognised Metal GPU Family (Apple11) is not supported by this target platform"
```
