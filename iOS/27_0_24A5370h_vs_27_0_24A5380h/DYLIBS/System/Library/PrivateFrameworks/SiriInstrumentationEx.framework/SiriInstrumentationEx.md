## SiriInstrumentationEx

> `/System/Library/PrivateFrameworks/SiriInstrumentationEx.framework/SiriInstrumentationEx`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2132bc` | `0x21778c` | **`+0x44d0`** |
| `__AUTH_CONST.__objc_const` | `0x252a0` | `0x259f0` | **`+0x750`** |
| `__TEXT.__objc_methlist` | `0x188b4` | `0x18e04` | **`+0x550`** |
| `__DATA.__bss` | `0x66580` | `0x66800` | **`+0x280`** |
| `__TEXT.__const` | `0x57214` | `0x57464` | **`+0x250`** |
| `__AUTH.__objc_data` | `0x8070` | `0x8200` | **`+0x190`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bd20` | `0x1be78` | **`+0x158`** |
| `__AUTH_CONST.__cfstring` | `0x6620` | `0x6760` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x9810` | `0x9938` | **`+0x128`** |
| `__TEXT.__cstring` | `0x5d57` | `0x5e4c` | **`+0xf5`** |
| `__DATA.__objc_ivar` | `0x194c` | `0x199c` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x1390` | `0x13b8` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0xcd8` | `0xd00` | **`+0x28`** |
| `__DATA_CONST.__objc_superrefs` | `0xcd8` | `0xd00` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x332c` | `0x3340` | **`+0x14`** |
| `__DATA.__data` | `0xa70` | `0xa80` | **`+0x10`** |

### Other Changes

```diff

-3600.77.1.0.0
+3600.79.1.0.0

-  Functions: 15070
-  Symbols:   12943
-  CStrings:  821
+  Functions: 15192
+  Symbols:   13108
+  CStrings:  831
Symbols:
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts .cxx_destruct]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts deleteTurnCounts]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts dictionaryRepresentation]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts hasTurnCounts]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts hash]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts initWithDictionary:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts initWithJSON:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts isEqual:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts jsonData]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts readFrom:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts setHasTurnCounts:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts setTurnCounts:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts turnCounts]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsCounts writeTo:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest .cxx_destruct]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest counts]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest deleteCounts]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest deleteDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest dictionaryRepresentation]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest dimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest hasCounts]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest hasDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest hash]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest initWithDictionary:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest initWithJSON:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest isEqual:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest jsonData]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest readFrom:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest setCounts:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest setDimensions:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest setHasCounts:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest setHasDimensions:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigest writeTo:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported .cxx_destruct]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported addDigests:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported clearDigests]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported deleteDigests]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported deleteFixedDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported dictionaryRepresentation]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported digestsAtIndex:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported digestsCount]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported digests]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported fixedDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported hasFixedDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported hash]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported initWithDictionary:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported initWithJSON:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported isEqual:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported jsonData]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported readFrom:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported setDigests:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported setFixedDimensions:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported setHasFixedDimensions:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported writeTo:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions .cxx_destruct]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions addProviderName:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions assistantDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions clearProviderName]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions deleteAssistantDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions deleteHasSiriExtensionsEnabled]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions deleteProviderName]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions deleteRequestType]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions dictionaryRepresentation]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions hasAssistantDimensions]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions hasHasSiriExtensionsEnabled]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions hasRequestType]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions hasSiriExtensionsEnabled]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions hash]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions initWithDictionary:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions initWithJSON:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions isEqual:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions jsonData]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions providerNameAtIndex:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions providerNameCount]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions providerNames]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions readFrom:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions requestType]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setAssistantDimensions:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setHasAssistantDimensions:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setHasHasSiriExtensionsEnabled:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setHasRequestType:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setHasSiriExtensionsEnabled:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setProviderNames:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions setRequestType:]
+ -[ODDSiriSchemaODDAssistantSiriExtensionsDimensions writeTo:]
+ -[ODDSiriSchemaODDSiriExtensionProvider .cxx_destruct]
+ -[ODDSiriSchemaODDSiriExtensionProvider deleteIsProviderEnabled]
+ -[ODDSiriSchemaODDSiriExtensionProvider deleteIsProviderInstalled]
+ -[ODDSiriSchemaODDSiriExtensionProvider deleteProviderName]
+ -[ODDSiriSchemaODDSiriExtensionProvider dictionaryRepresentation]
+ -[ODDSiriSchemaODDSiriExtensionProvider hasIsProviderEnabled]
+ -[ODDSiriSchemaODDSiriExtensionProvider hasIsProviderInstalled]
+ -[ODDSiriSchemaODDSiriExtensionProvider hasProviderName]
+ -[ODDSiriSchemaODDSiriExtensionProvider hash]
+ -[ODDSiriSchemaODDSiriExtensionProvider initWithDictionary:]
+ -[ODDSiriSchemaODDSiriExtensionProvider initWithJSON:]
+ -[ODDSiriSchemaODDSiriExtensionProvider isEqual:]
+ -[ODDSiriSchemaODDSiriExtensionProvider isProviderEnabled]
+ -[ODDSiriSchemaODDSiriExtensionProvider isProviderInstalled]
+ -[ODDSiriSchemaODDSiriExtensionProvider jsonData]
+ -[ODDSiriSchemaODDSiriExtensionProvider providerName]
+ -[ODDSiriSchemaODDSiriExtensionProvider readFrom:]
+ -[ODDSiriSchemaODDSiriExtensionProvider setHasIsProviderEnabled:]
+ -[ODDSiriSchemaODDSiriExtensionProvider setHasIsProviderInstalled:]
+ -[ODDSiriSchemaODDSiriExtensionProvider setHasProviderName:]
+ -[ODDSiriSchemaODDSiriExtensionProvider setIsProviderEnabled:]
+ -[ODDSiriSchemaODDSiriExtensionProvider setIsProviderInstalled:]
+ -[ODDSiriSchemaODDSiriExtensionProvider setProviderName:]
+ -[ODDSiriSchemaODDSiriExtensionProvider writeTo:]
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsCounts._turnCounts
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest._counts
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest._dimensions
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported._digests
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported._fixedDimensions
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._assistantDimensions
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._has
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._hasSiriExtensionsEnabled
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._providerNames
+ OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._requestType
+ OBJC_IVAR_$_ODDSiriSchemaODDSiriExtensionProvider._has
+ OBJC_IVAR_$_ODDSiriSchemaODDSiriExtensionProvider._isProviderEnabled
+ OBJC_IVAR_$_ODDSiriSchemaODDSiriExtensionProvider._isProviderInstalled
+ OBJC_IVAR_$_ODDSiriSchemaODDSiriExtensionProvider._providerName
+ _OBJC_CLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ _OBJC_CLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ _OBJC_CLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ _OBJC_CLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ _OBJC_CLASS_$_ODDSiriSchemaODDSiriExtensionProvider
+ _OBJC_CLASS_$_ODDSiriSchemaODDTurnCounts
+ _OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsCounts._hasTurnCounts
+ _OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest._hasCounts
+ _OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest._hasDimensions
+ _OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported._hasFixedDimensions
+ _OBJC_IVAR_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions._hasAssistantDimensions
+ _OBJC_IVAR_$_ODDSiriSchemaODDSiriExtensionProvider._hasProviderName
+ _OBJC_METACLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ _OBJC_METACLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ _OBJC_METACLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ _OBJC_METACLASS_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ _OBJC_METACLASS_$_ODDSiriSchemaODDSiriExtensionProvider
+ __OBJC_$_INSTANCE_METHODS_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ __OBJC_$_INSTANCE_METHODS_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ __OBJC_$_INSTANCE_METHODS_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ __OBJC_$_INSTANCE_METHODS_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ __OBJC_$_INSTANCE_METHODS_ODDSiriSchemaODDSiriExtensionProvider
+ __OBJC_$_INSTANCE_VARIABLES_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ __OBJC_$_INSTANCE_VARIABLES_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ __OBJC_$_INSTANCE_VARIABLES_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ __OBJC_$_INSTANCE_VARIABLES_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ __OBJC_$_INSTANCE_VARIABLES_ODDSiriSchemaODDSiriExtensionProvider
+ __OBJC_$_PROP_LIST_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ __OBJC_$_PROP_LIST_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ __OBJC_$_PROP_LIST_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ __OBJC_$_PROP_LIST_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ __OBJC_$_PROP_LIST_ODDSiriSchemaODDSiriExtensionProvider
+ __OBJC_CLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ __OBJC_CLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ __OBJC_CLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ __OBJC_CLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ __OBJC_CLASS_RO_$_ODDSiriSchemaODDSiriExtensionProvider
+ __OBJC_METACLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsCounts
+ __OBJC_METACLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsDigest
+ __OBJC_METACLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsDigestsReported
+ __OBJC_METACLASS_RO_$_ODDSiriSchemaODDAssistantSiriExtensionsDimensions
+ __OBJC_METACLASS_RO_$_ODDSiriSchemaODDSiriExtensionProvider
CStrings:
+ "ODDSIRIEXTENSIONREQUESTTYPE_THIRD_PARTY_PROVIDER_REQUEST"
+ "ODDSIRIEXTENSIONREQUESTTYPE_UNKNOWN"
+ "ODDSIRIEXTENSIONREQUESTTYPE_VISUAL_INTELLIGENCE"
+ "counts"
+ "dimensions"
+ "hasSiriExtensionsEnabled"
+ "isProviderEnabled"
+ "isProviderInstalled"
+ "requestType"
+ "turnCounts"
```
