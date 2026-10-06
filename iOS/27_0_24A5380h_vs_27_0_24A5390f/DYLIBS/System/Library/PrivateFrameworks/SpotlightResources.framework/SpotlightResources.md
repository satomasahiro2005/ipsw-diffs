## SpotlightResources

> `/System/Library/PrivateFrameworks/SpotlightResources.framework/SpotlightResources`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a910` | `0x29f40` | **`-0x9d0`** |
| `__AUTH_CONST.__cfstring` | `0x4b40` | `0x45e0` | **`-0x560`** |
| `__TEXT.__cstring` | `0x2758` | `0x22fc` | **`-0x45c`** |
| `__DATA_CONST.__objc_arraydata` | `0xa50` | `0x930` | **`-0x120`** |
| `__TEXT.__gcc_except_tab` | `0xef0` | `0xf4c` | **`+0x5c`** |
| `__AUTH_CONST.__objc_dictobj` | `0xf0` | `0xa0` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x24bd` | `0x24ec` | **`+0x2f`** |
| `__DATA_CONST.__const` | `0xc90` | `0xc68` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0x1648` | `0x1628` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1120` | `0x1108` | **`-0x18`** |
| `__DATA_DIRTY.__bss` | `0x2e8` | `0x2d0` | **`-0x18`** |
| `__TEXT.__const` | `0x110` | `0x128` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x9d8` | `0x9c0` | **`-0x18`** |

### Other Changes

```diff

-2451.1.101.0.0
+2454.100.0.0.0

-  Functions: 826
-  Symbols:   1339
-  CStrings:  917
+  Functions: 820
+  Symbols:   1332
+  CStrings:  875
Symbols:
+ -[SRParameter initWithBoolean:name:]
+ -[SRParameter initWithDouble:name:]
+ -[SRParameter initWithFilePath:name:]
+ -[SRParameter initWithLong:name:]
+ -[SRParameter initWithString:name:]
+ -[SRParameter initWithType:name:]
+ -[SRParameter isCurrent]
+ -[SRParameter setIsCurrent:]
+ _OBJC_IVAR_$_SRParameter._isCurrent
+ _uafAssetSetName_block_invoke_2.kDeliveryTypes
- +[SRResourcesManager defaultParameterWithType:value:name:]
- +[SRResourcesManager fetchUserDefaults]
- +[SRResourcesManager updateDefaultParameter:withValue:]
- -[SRParameter flag]
- -[SRParameter initWithBoolean:flags:name:]
- -[SRParameter initWithDouble:flags:name:]
- -[SRParameter initWithFilePath:flags:name:]
- -[SRParameter initWithLong:flags:name:]
- -[SRParameter initWithString:flags:name:]
- -[SRParameter initWithType:flags:name:]
- -[SRParameter setFlag:]
- _OBJC_IVAR_$_SRParameter._flag
- ___39+[SRResourcesManager fetchUserDefaults]_block_invoke
- ___block_descriptor_48_e8_32s_e5_v8?0ls32l8
- _fetchUserDefaults.userListOnceToken
- _sUserDefaultsParameterList
- _sUserDefaultsParameterListLock
CStrings:
+ "Delta2026"
+ "Delta2026Test"
+ "Optional2026"
+ "Optional2026Test"
+ "[%d] Error loading (%@, %@) assets: %@"
+ "loadOTA[%llu] server 3.1.1 found (%@, %@)"
+ "loadOTA[%llu] server 3.1.2 no match for (%@, %@)"
- "BlueButton"
- "CommittedScreenMatchingBehavior"
- "Delta"
- "Delta2025"
- "Delta2025Test"
- "EnableSafariTopHitsLogic"
- "FilterLocalSuggestions"
- "HideSearchThroughSuggestions"
- "L1Threshold"
- "L2Threshold"
- "Legacy"
- "MaxCountTopHits"
- "MaxSectionsBeforeShowMore"
- "MaxSectionsBeforeShowMoreWithScopedSearch"
- "MaxVisibleResultsCountPerSection"
- "MinSectionCountThresholdForShowMore"
- "MinSpellCorrectedAppTopHitScore"
- "MinTopHitScore"
- "MinTopHitThresholdForBigResult"
- "Optional"
- "Optional2024"
- "Optional2025"
- "Optional2025Test"
- "Parameter %@ has value from user defaults"
- "SPBlueButtonBehavior"
- "SPBullseyeFilterLocalSuggestions"
- "SPBullseyeMinSpellCorrectedAppTopHitScore"
- "SPBullseyeMinTopHitScore"
- "SPCommittedScreenMatchingBehavior"
- "SPEnableSafariTopHitsLogic"
- "SPHideSearchThroughSuggestions"
- "SPL1Threshold"
- "SPL2Threshold"
- "SPMaxCountTopHits"
- "SPMaxSectionsBeforeShowMore"
- "SPMaxSectionsBeforeShowMoreWithScopedSearch"
- "SPMaxVisibleResultsCountPerSection"
- "SPMinSectionCountThresholdForShowMore"
- "SPMinTopHitThresholdForBigResult"
- "SPSuggestionDetailTextBehavior"
- "SPUIBullseyeShowDebugLocalSuggestions"
- "SPUIBullseyeShowTopHitSectionHeaderInAsYouTypeScreen"
- "ShowDebugLocalSuggestions"
- "ShowTopHitSectionHeaderInAsYouTypeScreen"
- "SuggestionDetailTextBehaviorType"
- "User default is not set for parameter %@"
- "UserDefault"
- "UserDefaultFirst"
- "com.apple.searchd"
```
