## MusicKit

> `/System/Library/Frameworks/MusicKit.framework/MusicKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x541bdc` | `0x545f50` | **`+0x4374`** |
| `__DATA.__bss` | `0x61d40` | `0x629e0` | **`+0xca0`** |
| `__TEXT.__const` | `0x54d24` | `0x55464` | **`+0x740`** |
| `__AUTH_CONST.__const` | `0x2a880` | `0x2aaf0` | **`+0x270`** |
| `__TEXT.__swift5_reflstr` | `0xc03b` | `0xc2ab` | **`+0x270`** |
| `__DATA.__data` | `0xa498` | `0xa6c0` | **`+0x228`** |
| `__TEXT.__swift5_fieldmd` | `0xe908` | `0xeb1c` | **`+0x214`** |
| `__TEXT.__cstring` | `0x110b2` | `0x11252` | **`+0x1a0`** |
| `__TEXT.__unwind_info` | `0x18a08` | `0x18b90` | **`+0x188`** |
| `__AUTH_CONST.__objc_const` | `0x70d0` | `0x7230` | **`+0x160`** |
| `__TEXT.__swift5_typeref` | `0x12204` | `0x12344` | **`+0x140`** |
| `__TEXT.__constg_swiftt` | `0xbf24` | `0xc018` | **`+0xf4`** |
| `__AUTH.__data` | `0x2e58` | `0x2f00` | **`+0xa8`** |
| `__DATA_DIRTY.__data` | `0xc300` | `0xc260` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x229c` | `0x2324` | **`+0x88`** |
| `__TEXT.__swift5_proto` | `0x44b4` | `0x451c` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x1892` | `0x18f2` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x90` | `0xe0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b58` | `0x1ba0` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0xe60` | `0xea0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x27598` | `0x275d0` | **`+0x38`** |
| `__DATA.__common` | `0x190` | `0x1c0` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x3050` | `0x3080` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0xf9c` | `0xfb8` | **`+0x1c`** |
| `__TEXT.__gcc_except_tab` | `0x2088` | `0x20a0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x9e8` | `0x9f0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x320` | `0x328` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x70` | `0x78` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x168` | `0x170` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0xb28` | `0xb30` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x160` | `0x164` | **`+0x4`** |

### Other Changes

```diff

-4026.110.3.0.0
+4026.210.18.1.0

-  Functions: 44349
-  Symbols:   11785
-  CStrings:  1763
+  Functions: 44587
+  Symbols:   11809
+  CStrings:  1777
Symbols:
+ +[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:versionHash:modelObjectType:source:]
+ +[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:versionHash:modelObjectType:source:]
+ +[MusicKit_SoftLinking_MPModelAlbum albumTypeForRawValue:]
+ +[MusicKit_SoftLinking_MPModelAlbum rawValueForAlbumType:]
+ -[MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue .cxx_destruct]
+ -[MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue description]
+ -[MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue initWithRawArtworkCatalogs:]
+ -[MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue makeModelKeyValue]
+ -[NSObject(MusicKit_SoftLinking_MPIdentifierSet) musicKit_versionHash]
+ _OBJC_CLASS_$_MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue
+ _OBJC_IVAR_$_MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue._artworkCatalogs
+ _OBJC_METACLASS_$_MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue
+ __OBJC_$_INSTANCE_METHODS_MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue
+ __OBJC_$_INSTANCE_VARIABLES_MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue
+ __OBJC_$_PROP_LIST_MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MusicKit_SoftLinking_MPModelPropertyValue
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MusicKit_SoftLinking_MPModelPropertyValue
+ __OBJC_$_PROTOCOL_REFS_MusicKit_SoftLinking_MPModelPropertyValue
+ __OBJC_CLASS_PROTOCOLS_$_MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue
+ __OBJC_CLASS_RO_$_MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue
+ __OBJC_LABEL_PROTOCOL_$_MusicKit_SoftLinking_MPModelPropertyValue
+ __OBJC_METACLASS_RO_$_MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue
+ __OBJC_PROTOCOL_$_MusicKit_SoftLinking_MPModelPropertyValue
+ __OBJC_PROTOCOL_REFERENCE_$_MusicKit_SoftLinking_MPModelPropertyValue
+ ___307+[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:versionHash:modelObjectType:source:]_block_invoke
+ ___307+[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:versionHash:modelObjectType:source:]_block_invoke_2
+ ___307+[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:versionHash:modelObjectType:source:]_block_invoke_3
+ ___307+[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:versionHash:modelObjectType:source:]_block_invoke_4
+ ___307+[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:versionHash:modelObjectType:source:]_block_invoke_5
+ ___307+[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:versionHash:modelObjectType:source:]_block_invoke_6
+ ___81-[MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue makeModelKeyValue]_block_invoke
+ ___81-[MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue makeModelKeyValue]_block_invoke_2
+ ___91-[MusicKit_SoftLinking_MPEditorialArtworkCatalogsPropertyValue initWithRawArtworkCatalogs:]_block_invoke
+ ___block_descriptor_160_e8_32s40s48s56s64s72s80s88s96s104s112s120s128s136s144s_e55_v16?0"MPIdentifierSet<MPMutableMusicKitIdentifiers>"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8s120l8s128l8s136l8s144l8
+ ___block_descriptor_40_e8_32s_e37_"NSDictionary"16?0"MPModelObject"8ls32l8
+ ___getMPModelPropertyAlbumCloudChannelNameSymbolLoc_block_invoke
+ ___getMPModelPropertyAlbumShouldShowCountdownTimerSymbolLoc_block_invoke
+ ___swift_memcpy385_8
+ ___swift_memcpy392_8
+ ___swift_memcpy416_8
+ _associated conformance 8MusicKit12CloudConcertV0C12DataProviderV10CodingKeys33_386C520BD12A65B93DA32110B9F85C8BLLOSHAASQ
+ _associated conformance 8MusicKit12CloudConcertV0C12DataProviderV10CodingKeys33_386C520BD12A65B93DA32110B9F85C8BLLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 8MusicKit12CloudConcertV0C12DataProviderV10CodingKeys33_386C520BD12A65B93DA32110B9F85C8BLLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8MusicKit12CloudConcertV0C12DataProviderVSHAASQ
+ _associated conformance 8MusicKit20LegacyModelAlbumKindO10CodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLOSHAASQ
+ _associated conformance 8MusicKit20LegacyModelAlbumKindO10CodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 8MusicKit20LegacyModelAlbumKindO10CodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8MusicKit20LegacyModelAlbumKindO12EpCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 8MusicKit20LegacyModelAlbumKindO12EpCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8MusicKit20LegacyModelAlbumKindO16DeluxeCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 8MusicKit20LegacyModelAlbumKindO16DeluxeCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8MusicKit20LegacyModelAlbumKindO16SingleCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 8MusicKit20LegacyModelAlbumKindO16SingleCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8MusicKit20LegacyModelAlbumKindO18StandardCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 8MusicKit20LegacyModelAlbumKindO18StandardCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8MusicKit20LegacyModelAlbumKindO21CompilationCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 8MusicKit20LegacyModelAlbumKindO21CompilationCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8MusicKit20LegacyModelAlbumKindOSHAASQ
+ _associated conformance 8MusicKit20LegacyModelAlbumKindOs12CaseIterableAA8AllCasessADP_Sl
+ _getMPModelPropertyAlbumCloudChannelNameSymbolLoc.ptr
+ _getMPModelPropertyAlbumShouldShowCountdownTimerSymbolLoc.ptr
+ _symbolic Say_____G 8MusicKit20LegacyModelAlbumKindO
+ _symbolic Say_____y_____GG 8MusicKit14CloudAttributeV AA0C7ConcertV0C12DataProviderV
+ _symbolic Say_____y_____GGSg 8MusicKit14CloudAttributeV AA0C7ConcertV0C12DataProviderV
+ _symbolic _____ 8MusicKit12CloudConcertV0C12DataProviderV
+ _symbolic _____ 8MusicKit12CloudConcertV0C12DataProviderV10CodingKeys33_386C520BD12A65B93DA32110B9F85C8BLLO
+ _symbolic _____ 8MusicKit20LegacyModelAlbumKindO
+ _symbolic _____ 8MusicKit20LegacyModelAlbumKindO10CodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____ 8MusicKit20LegacyModelAlbumKindO12EpCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____ 8MusicKit20LegacyModelAlbumKindO16DeluxeCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____ 8MusicKit20LegacyModelAlbumKindO16SingleCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____ 8MusicKit20LegacyModelAlbumKindO18StandardCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____ 8MusicKit20LegacyModelAlbumKindO21CompilationCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____Sg 8MusicKit20LegacyModelAlbumKindO
+ _symbolic _____y_____G 8MusicKit14CloudAttributeV AA0C7ConcertV0C12DataProviderV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8MusicKit12CloudConcertV0F12DataProviderV10CodingKeys33_386C520BD12A65B93DA32110B9F85C8BLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8MusicKit20LegacyModelAlbumKindO10CodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8MusicKit20LegacyModelAlbumKindO12EpCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8MusicKit20LegacyModelAlbumKindO16DeluxeCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8MusicKit20LegacyModelAlbumKindO16SingleCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8MusicKit20LegacyModelAlbumKindO18StandardCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8MusicKit20LegacyModelAlbumKindO21CompilationCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8MusicKit12CloudConcertV0F12DataProviderV10CodingKeys33_386C520BD12A65B93DA32110B9F85C8BLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8MusicKit20LegacyModelAlbumKindO10CodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8MusicKit20LegacyModelAlbumKindO12EpCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8MusicKit20LegacyModelAlbumKindO16DeluxeCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8MusicKit20LegacyModelAlbumKindO16SingleCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8MusicKit20LegacyModelAlbumKindO18StandardCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8MusicKit20LegacyModelAlbumKindO21CompilationCodingKeys33_41C9BDFCF3219D2888482DC4B65C0AD0LLO
+ _symbolic _____y_____GSg 8MusicKit14CloudAttributeV AA0C7ConcertV0C12DataProviderV
+ _symbolic _____y_____GSg_ADt 8MusicKit14CloudAttributeV AA0C7ConcertV0C12DataProviderV
+ _symbolic _____y__________G 8MusicKit0A17AttributePropertyC AA5AlbumV AA011LegacyModelE4KindO
- +[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:modelObjectType:source:]
- _OUTLINED_FUNCTION_2161
- _OUTLINED_FUNCTION_2162
- _OUTLINED_FUNCTION_2163
- _OUTLINED_FUNCTION_2164
- _OUTLINED_FUNCTION_2165
- _OUTLINED_FUNCTION_2166
- _OUTLINED_FUNCTION_2167
- _OUTLINED_FUNCTION_2168
- _OUTLINED_FUNCTION_2169
- _OUTLINED_FUNCTION_2170
- _OUTLINED_FUNCTION_2171
- _OUTLINED_FUNCTION_2172
- _OUTLINED_FUNCTION_2173
- _OUTLINED_FUNCTION_2174
- _OUTLINED_FUNCTION_2175
- _OUTLINED_FUNCTION_2176
- _OUTLINED_FUNCTION_2177
- _OUTLINED_FUNCTION_2178
- _OUTLINED_FUNCTION_2179
- _OUTLINED_FUNCTION_2180
- _OUTLINED_FUNCTION_2181
- _OUTLINED_FUNCTION_2182
- _OUTLINED_FUNCTION_2183
- _OUTLINED_FUNCTION_2184
- _OUTLINED_FUNCTION_2185
- _OUTLINED_FUNCTION_2186
- _OUTLINED_FUNCTION_2187
- _OUTLINED_FUNCTION_2188
- _OUTLINED_FUNCTION_2189
- _OUTLINED_FUNCTION_2190
- _OUTLINED_FUNCTION_2191
- _OUTLINED_FUNCTION_2192
- _OUTLINED_FUNCTION_2193
- _OUTLINED_FUNCTION_2194
- _OUTLINED_FUNCTION_2195
- _OUTLINED_FUNCTION_2196
- _OUTLINED_FUNCTION_2197
- _OUTLINED_FUNCTION_2198
- _OUTLINED_FUNCTION_2199
- _OUTLINED_FUNCTION_2200
- _OUTLINED_FUNCTION_2201
- _OUTLINED_FUNCTION_2202
- _OUTLINED_FUNCTION_2203
- ___118+[MusicKit_SoftLinking_MPModelObject _createUnderlyingModelObjectWithIdentifierSet:modelObjectType:storageDictionary:]_block_invoke_4
- ___118+[MusicKit_SoftLinking_MPModelObject _createUnderlyingModelObjectWithIdentifierSet:modelObjectType:storageDictionary:]_block_invoke_5
- ___295+[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:modelObjectType:source:]_block_invoke
- ___295+[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:modelObjectType:source:]_block_invoke_2
- ___295+[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:modelObjectType:source:]_block_invoke_3
- ___295+[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:modelObjectType:source:]_block_invoke_4
- ___295+[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:modelObjectType:source:]_block_invoke_5
- ___295+[MusicKit_SoftLinking(MusicKit_SoftLinking_MPIdentifierSet) _identifierSetWithCatalogID:libraryID:cloudAlbumLibraryID:cloudID:reportingAdamID:purchasedAdamID:assetAdamID:deviceLocalID:possibleDeviceLocalID:occurrenceID:containedDeviceLocalID:syncID:playbackID:formerIDs:modelObjectType:source:]_block_invoke_6
- ___block_descriptor_152_e8_32s40s48s56s64s72s80s88s96s104s112s120s128s136s_e55_v16?0"MPIdentifierSet<MPMutableMusicKitIdentifiers>"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8s120l8s128l8s136l8
- ___block_descriptor_40_e8_32s_e44_"NSMutableDictionary"16?0"MPModelObject"8ls32l8
- ___swift_memcpy369_8
- ___swift_memcpy400_8
- _associated conformance 8MusicKit12CloudConcertV0C6TicketV0C12DataProviderV10CodingKeys33_C7F008B7795B2BDCFFF36C0AECF06BB1LLOSHAASQ
- _associated conformance 8MusicKit12CloudConcertV0C6TicketV0C12DataProviderV10CodingKeys33_C7F008B7795B2BDCFFF36C0AECF06BB1LLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 8MusicKit12CloudConcertV0C6TicketV0C12DataProviderV10CodingKeys33_C7F008B7795B2BDCFFF36C0AECF06BB1LLOs0H3KeyAAs28CustomDebugStringConvertible
- _associated conformance 8MusicKit12CloudConcertV0C6TicketV0C12DataProviderVSHAASQ
- _symbolic Say_____y_____GG 8MusicKit07PartialA8PropertyC AA5AlbumV
- _symbolic _____ 8MusicKit12CloudConcertV0C6TicketV0C12DataProviderV
- _symbolic _____ 8MusicKit12CloudConcertV0C6TicketV0C12DataProviderV10CodingKeys33_C7F008B7795B2BDCFFF36C0AECF06BB1LLO
- _symbolic _____y_____G 8MusicKit14CloudAttributeV AA0C7ConcertV0C6TicketV0C12DataProviderV
- _symbolic _____y_____G s22KeyedDecodingContainerV 8MusicKit12CloudConcertV0F6TicketV0F12DataProviderV10CodingKeys33_C7F008B7795B2BDCFFF36C0AECF06BB1LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 8MusicKit12CloudConcertV0F6TicketV0F12DataProviderV10CodingKeys33_C7F008B7795B2BDCFFF36C0AECF06BB1LLO
- _symbolic _____y_____GSg 8MusicKit14CloudAttributeV AA0C7ConcertV0C6TicketV0C12DataProviderV
- _symbolic _____y_____GSg_ADt 8MusicKit14CloudAttributeV AA0C7ConcertV0C6TicketV0C12DataProviderV
CStrings:
+ ", "
+ "<%@: %p; flavors = %@>"
+ "@\"NSDictionary\"16@?0@\"MPModelObject\"8"
+ "Editorial artwork for flavor %{public}@ was %{public}@, not an artwork catalog. Dropping it."
+ "MPModelPropertyAlbumCloudChannelName"
+ "MPModelPropertyAlbumShouldShowCountdownTimer"
+ "MPModelPropertyAlbumType"
+ "MPModelPropertyRadioStationEditorialArtworks"
+ "SpatialTimingInformation"
+ "com.apple.TVMusic"
+ "eventDataProviders"
+ "isReleaseCountdownEnabled"
+ "live_release_albums"
+ "plainEditorialCard"
+ "pushNotificationChannelId"
+ "requiresUpdatedPayloadForPlayback"
- "@\"NSMutableDictionary\"16@?0@\"MPModelObject\"8"
- "CloudAttribute<CloudSpatialTimingInformation>"
```
