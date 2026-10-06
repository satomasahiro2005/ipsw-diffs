## BiomeLibrary

> `/System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x753ffc` | `0x756610` | **`+0x2614`** |
| `__AUTH_CONST.__cfstring` | `0x4b060` | `0x4b3a0` | **`+0x340`** |
| `__AUTH_CONST.__objc_const` | `0xa2900` | `0xa2bf0` | **`+0x2f0`** |
| `__TEXT.__objc_methlist` | `0x500dc` | `0x5039c` | **`+0x2c0`** |
| `__TEXT.__cstring` | `0x4e720` | `0x4e8a6` | **`+0x186`** |
| `__TEXT.__unwind_info` | `0xf778` | `0xf610` | **`-0x168`** |
| `__AUTH.__objc_data` | `0xb080` | `0xb170` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0x1eb28` | `0x1eba8` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x12948` | `0x129a0` | **`+0x58`** |
| `__DATA_CONST.__objc_arraydata` | `0xb218` | `0xb258` | **`+0x40`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x6660` | `0x6690` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x9ad8` | `0x9af8` | **`+0x20`** |
| `__TEXT.__const` | `0x47b8` | `0x47d8` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x22f8` | `0x2310` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x81f4` | `0x8204` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1bf8` | `0x1c00` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1b28` | `0x1b30` | **`+0x8`** |

### Other Changes

```diff

-435.0.0.0.0
+436.6.0.0.0

-  Functions: 28633
-  Symbols:   52914
-  CStrings:  9737
+  Functions: 28688
+  Symbols:   53001
+  CStrings:  9763
Symbols:
+ +[BMMailSearchUIEventIndexState columns]
+ +[BMMailSearchUIEventIndexState eventWithData:dataVersion:]
+ +[BMMailSearchUIEventIndexState latestDataVersion]
+ +[BMMailSearchUIEventIndexState protoFields]
+ +[BMMailSearchUIEventIndexState validKeyPaths]
+ +[_BMDemoLibraryNode ScreenTime]
+ +[_BMDemoLibraryNode identifier]
+ +[_BMDemoLibraryNode streamNames]
+ +[_BMDemoLibraryNode streamWithName:]
+ +[_BMDemoLibraryNode sublibraries]
+ +[_BMDemoLibraryNode validKeyPaths]
+ +[_BMDemoScreenTimeLibraryNode AppUsage]
+ +[_BMDemoScreenTimeLibraryNode DisplayBacklight]
+ +[_BMDemoScreenTimeLibraryNode MediaUsage]
+ +[_BMDemoScreenTimeLibraryNode Notifications]
+ +[_BMDemoScreenTimeLibraryNode NowPlaying]
+ +[_BMDemoScreenTimeLibraryNode WebUsage]
+ +[_BMDemoScreenTimeLibraryNode configurationForAppUsage]
+ +[_BMDemoScreenTimeLibraryNode configurationForDisplayBacklight]
+ +[_BMDemoScreenTimeLibraryNode configurationForMediaUsage]
+ +[_BMDemoScreenTimeLibraryNode configurationForNotifications]
+ +[_BMDemoScreenTimeLibraryNode configurationForNowPlaying]
+ +[_BMDemoScreenTimeLibraryNode configurationForWebUsage]
+ +[_BMDemoScreenTimeLibraryNode identifier]
+ +[_BMDemoScreenTimeLibraryNode storeConfigurationForAppUsage]
+ +[_BMDemoScreenTimeLibraryNode storeConfigurationForDisplayBacklight]
+ +[_BMDemoScreenTimeLibraryNode storeConfigurationForMediaUsage]
+ +[_BMDemoScreenTimeLibraryNode storeConfigurationForNotifications]
+ +[_BMDemoScreenTimeLibraryNode storeConfigurationForNowPlaying]
+ +[_BMDemoScreenTimeLibraryNode storeConfigurationForWebUsage]
+ +[_BMDemoScreenTimeLibraryNode streamNames]
+ +[_BMDemoScreenTimeLibraryNode streamWithName:]
+ +[_BMDemoScreenTimeLibraryNode sublibraries]
+ +[_BMDemoScreenTimeLibraryNode syncPolicyForAppUsage]
+ +[_BMDemoScreenTimeLibraryNode syncPolicyForDisplayBacklight]
+ +[_BMDemoScreenTimeLibraryNode syncPolicyForMediaUsage]
+ +[_BMDemoScreenTimeLibraryNode syncPolicyForNotifications]
+ +[_BMDemoScreenTimeLibraryNode syncPolicyForNowPlaying]
+ +[_BMDemoScreenTimeLibraryNode syncPolicyForWebUsage]
+ +[_BMDemoScreenTimeLibraryNode validKeyPaths]
+ +[_BMRootLibraryNode Demo]
+ -[BMMailSearchUIEventDimensionContext indexState]
+ -[BMMailSearchUIEventDimensionContext initWithSystemLocale:currentCountry:build:osType:productType:buildType:indexState:]
+ -[BMMailSearchUIEventDimensionContext(Deprecation) initWithSystemLocale:currentCountry:build:osType:productType:buildType:]
+ -[BMMailSearchUIEventIndexState dataVersion]
+ -[BMMailSearchUIEventIndexState description]
+ -[BMMailSearchUIEventIndexState hasIsHdbEnabled]
+ -[BMMailSearchUIEventIndexState initByReadFrom:]
+ -[BMMailSearchUIEventIndexState initWithIsHdbEnabled:]
+ -[BMMailSearchUIEventIndexState initWithJSONDictionary:error:]
+ -[BMMailSearchUIEventIndexState isEqual:]
+ -[BMMailSearchUIEventIndexState isHdbEnabled]
+ -[BMMailSearchUIEventIndexState jsonDictionary]
+ -[BMMailSearchUIEventIndexState serialize]
+ -[BMMailSearchUIEventIndexState setHasIsHdbEnabled:]
+ -[BMMailSearchUIEventIndexState writeTo:]
+ _BMDemoScreenTimeAppUsageIdentifier
+ _BMDemoScreenTimeDisplayBacklightIdentifier
+ _BMDemoScreenTimeMediaUsageIdentifier
+ _BMDemoScreenTimeNotificationsIdentifier
+ _BMDemoScreenTimeNowPlayingIdentifier
+ _BMDemoScreenTimeWebUsageIdentifier
+ _BMMailSearchUIEventDimensionContextIndexStateColumn
+ _BMMailSearchUIEventIndexStateIsHdbEnabledColumn
+ _OBJC_CLASS_$_BMMailSearchUIEventIndexState
+ _OBJC_CLASS_$__BMDemoLibraryNode
+ _OBJC_CLASS_$__BMDemoScreenTimeLibraryNode
+ _OBJC_IVAR_$_BMMailSearchUIEventDimensionContext._indexState
+ _OBJC_IVAR_$_BMMailSearchUIEventIndexState._dataVersion
+ _OBJC_IVAR_$_BMMailSearchUIEventIndexState._hasIsHdbEnabled
+ _OBJC_IVAR_$_BMMailSearchUIEventIndexState._isHdbEnabled
+ _OBJC_METACLASS_$_BMMailSearchUIEventIndexState
+ _OBJC_METACLASS_$__BMDemoLibraryNode
+ _OBJC_METACLASS_$__BMDemoScreenTimeLibraryNode
+ __OBJC_$_CLASS_METHODS_BMMailSearchUIEventIndexState
+ __OBJC_$_CLASS_METHODS__BMDemoLibraryNode
+ __OBJC_$_CLASS_METHODS__BMDemoScreenTimeLibraryNode
+ __OBJC_$_CLASS_PROP_LIST_BMMailSearchUIEventIndexState
+ __OBJC_$_INSTANCE_METHODS_BMMailSearchUIEventDimensionContext(Deprecation)
+ __OBJC_$_INSTANCE_METHODS_BMMailSearchUIEventIndexState
+ __OBJC_$_INSTANCE_VARIABLES_BMMailSearchUIEventIndexState
+ __OBJC_$_PROP_LIST_BMMailSearchUIEventIndexState
+ __OBJC_CLASS_PROTOCOLS_$_BMMailSearchUIEventIndexState
+ __OBJC_CLASS_RO_$_BMMailSearchUIEventIndexState
+ __OBJC_CLASS_RO_$__BMDemoLibraryNode
+ __OBJC_CLASS_RO_$__BMDemoScreenTimeLibraryNode
+ __OBJC_METACLASS_RO_$_BMMailSearchUIEventIndexState
+ __OBJC_METACLASS_RO_$__BMDemoLibraryNode
+ __OBJC_METACLASS_RO_$__BMDemoScreenTimeLibraryNode
+ ___46+[BMMailSearchUIEventDimensionContext columns]_block_invoke
- -[BMMailSearchUIEventDimensionContext initWithSystemLocale:currentCountry:build:osType:productType:buildType:]
- _OUTLINED_FUNCTION_46
- __OBJC_$_INSTANCE_METHODS_BMMailSearchUIEventDimensionContext
CStrings:
+ "2F0625EA-2AA8-4E4F-9D74-08DC4B224C2A"
+ "40EA0B69-E3F6-4DEE-8469-C41C48712829"
+ "55E93055-8F26-4BD1-B74E-212BAD444D8A"
+ "6212D064-510D-4B9D-A4B6-12FC6C34F1B5"
+ "BMMailSearchUIEventDimensionContext with systemLocale: %@, currentCountry: %@, build: %@, osType: %@, productType: %@, buildType: %@, indexState: %@"
+ "BMMailSearchUIEventIndexState with isHdbEnabled: %@"
+ "Demo"
+ "Demo.ScreenTime.AppUsage"
+ "Demo.ScreenTime.DisplayBacklight"
+ "Demo.ScreenTime.MediaUsage"
+ "Demo.ScreenTime.Notifications"
+ "Demo.ScreenTime.NowPlaying"
+ "Demo.ScreenTime.WebUsage"
+ "DisplayBacklight"
+ "E34779A5-0BDA-4E4B-932D-E2851FCD03F4"
+ "ErrorDidNotFillOneTimeCodeInEntirety"
+ "ErrorDidNotReceiveMailOneTimeCode"
+ "ErrorDidNotReceiveOneTimeCode"
+ "ErrorDidNotReceiveTOTPOneTimeCode"
+ "ErrorDidNotReceiveTextMessageOneTimeCode"
+ "ErrorDidNotReceiveThirdPartyOneTimeCode"
+ "ErrorFinishedWithoutFillingLoginCredentials"
+ "ErrorInvalidOneTimeCode"
+ "F656B030-BC5C-4391-9A9E-08066D83798E"
+ "SUBQUERY(tupleInteraction.candidateIds, $g, $g.type.tool != NULL AND NOT ($g.type.tool.bundleId IN $installed)).@count > 0"
+ "SUBQUERY(tupleInteraction.candidateIds, $g, $g.type.tool.bundleId == $uninstalled).@count > 0"
+ "SUBQUERY(tupleInteraction.candidateIds, $g, $g.type.tool.bundleId IN $disabledApps).@count > 0"
+ "indexState"
+ "indexState_json"
+ "isHdbEnabled"
- "(ANY candidateInteractions.candidateId.identifier IN $disabledApps AND candidateInteractions.candidateId.type.app != nil) OR (ANY tupleInteraction.candidateIds.identifier IN $disabledApps AND tupleInteraction.candidateIds.type.app != nil)"
- "BMMailSearchUIEventDimensionContext with systemLocale: %@, currentCountry: %@, build: %@, osType: %@, productType: %@, buildType: %@"
- "SUBQUERY(candidateInteractions, $g, $g.candidateId.identifier == $uninstalled AND $g.candidateId.type.app != NULL).@count > 0 OR SUBQUERY(tupleInteraction.candidateIds, $g, $g.identifier == $uninstalled AND $g.type.app != NULL).@count > 0"
- "SUBQUERY(candidateInteractions, $g, NOT ($g.candidateId.identifier IN $installed) AND $g.candidateId.type.app != NULL).@count > 0 OR SUBQUERY(tupleInteraction.candidateIds, $g, NOT ($g.identifier IN $installed) AND $g.type.app != NULL).@count > 0"
```
