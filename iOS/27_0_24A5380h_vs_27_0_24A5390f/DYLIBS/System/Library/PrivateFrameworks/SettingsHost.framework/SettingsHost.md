## SettingsHost

> `/System/Library/PrivateFrameworks/SettingsHost.framework/SettingsHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7a2c0` | `0x93320` | **`+0x19060`** |
| `__DATA.__bss` | `0x3bd0` | `0x6a50` | **`+0x2e80`** |
| `__TEXT.__const` | `0x4fa8` | `0x6878` | **`+0x18d0`** |
| `__AUTH_CONST.__const` | `0x4400` | `0x50e0` | **`+0xce0`** |
| `__TEXT.__eh_frame` | `0x2148` | `0x2848` | **`+0x700`** |
| `__TEXT.__swift5_fieldmd` | `0x1590` | `0x1bc4` | **`+0x634`** |
| `__TEXT.__oslogstring` | `0x1f64` | `0x2564` | **`+0x600`** |
| `__DATA.__data` | `0x738` | `0xcc0` | **`+0x588`** |
| `__TEXT.__unwind_info` | `0x1690` | `0x1bd8` | **`+0x548`** |
| `__TEXT.__constg_swiftt` | `0x13e0` | `0x18a0` | **`+0x4c0`** |
| `__TEXT.__swift5_typeref` | `0x16d2` | `0x1b84` | **`+0x4b2`** |
| `__TEXT.__swift5_reflstr` | `0x160e` | `0x189e` | **`+0x290`** |
| `__AUTH_CONST.__auth_got` | `0xf48` | `0x1110` | **`+0x1c8`** |
| `__DATA_DIRTY.__bss` | `0x2080` | `0x2200` | **`+0x180`** |
| `__TEXT.__swift5_proto` | `0x318` | `0x498` | **`+0x180`** |
| `__DATA_DIRTY.__data` | `0x1708` | `0x1880` | **`+0x178`** |
| `__TEXT.__cstring` | `0x3b08` | `0x3c58` | **`+0x150`** |
| `__AUTH_CONST.__objc_const` | `0xc08` | `0xcd8` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0x3ac` | `0x474` | **`+0xc8`** |
| `__AUTH.__data` | `0x220` | `0x298` | **`+0x78`** |
| `__TEXT.__swift5_types` | `0x158` | `0x1c0` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x378` | `0x3d0` | **`+0x58`** |
| `__DATA_DIRTY.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0x3b0` | `0x3f8` | **`+0x48`** |
| `__DATA_DIRTY.__common` | `0xb0` | `0xe0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x148` | `0x168` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x154` | `0x174` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0xb4` | `0xc8` | **`+0x14`** |
| `__DATA.__common` | `0x48` | `0x38` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0xa4` | `0xb4` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xb0` | `0xb8` | **`+0x8`** |

### Other Changes

```diff

-2027.0.2.0.0
+2027.0.5.0.0

+  - /System/Library/PrivateFrameworks/SettingsServices.framework/SettingsServices

-  Functions: 2036
-  Symbols:   833
-  CStrings:  562
+  Functions: 2591
+  Symbols:   977
+  CStrings:  590
Symbols:
+ _CFPreferencesCopyKeyList
+ _CFPreferencesCopyValue
+ _CFPreferencesSetValue
+ _CFPreferencesSynchronize
+ _NSTemporaryDirectory
+ _NSURLIsDirectoryKey
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSFileManager
+ __DATA__TtC12SettingsHost28SettingsHostDiagnosticsStore
+ __IVARS__TtC12SettingsHost28SettingsHostDiagnosticsStore
+ __METACLASS_DATA__TtC12SettingsHost28SettingsHostDiagnosticsStore
+ ___swift_destroy_boxed_opaque_existential_0Tm
+ ___swift_memcpy104_8
+ ___swift_memcpy64_8
+ ___swift_memcpy80_8
+ _associated conformance 12SettingsHost0A26SearchIndexGenerationTokenV10CodingKeys33_9CD187E4404BEB3B05B48F48E111B743LLOSHAASQ
+ _associated conformance 12SettingsHost0A26SearchIndexGenerationTokenV10CodingKeys33_9CD187E4404BEB3B05B48F48E111B743LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost0A26SearchIndexGenerationTokenV10CodingKeys33_9CD187E4404BEB3B05B48F48E111B743LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12SettingsHost0aB16DiagnosticsStoreC8Envelope33_13A89FBD6E9E307679DEFE99CFB21591LLV10CodingKeysOy_x_GSHAASQ
+ _associated conformance 12SettingsHost0aB16DiagnosticsStoreC8Envelope33_13A89FBD6E9E307679DEFE99CFB21591LLV10CodingKeysOy_x_Gs0L3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost0aB16DiagnosticsStoreC8Envelope33_13A89FBD6E9E307679DEFE99CFB21591LLV10CodingKeysOy_x_Gs0L3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOSHAASQ
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV12DomainResultV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOSHAASQ
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV12DomainResultV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV12DomainResultV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOSHAASQ
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO17SkippedCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO17SkippedCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO18CompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO18CompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO20IncompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO20IncompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeOSHAASQ
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV5IssueV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOSHAASQ
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV5IssueV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV5IssueV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV5IssueV8SeverityOSHAASQ
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOSHAASQ
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO16FailedCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOSHAASQ
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO16FailedCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO16FailedCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO18CompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO18CompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO20IncompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO20IncompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV7SummaryV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOSHAASQ
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV7SummaryV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 12SettingsHost32SearchIndexingDiagnosticSnapshotV7SummaryV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance So16NSURLResourceKeyaSHSCSQ
+ _associated conformance So16NSURLResourceKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So16NSURLResourceKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _get_enum_tag_for_layout_string 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO
+ _kCFPreferencesAnyHost
+ _kCFPreferencesCurrentUser
+ _swift_getMetatypeMetadata
+ _symbolic $s12SettingsHost0aB16DiagnosticDomainP
+ _symbolic $s12SettingsHost9PrismaticP
+ _symbolic SDySS_____G 12SettingsHost32SearchIndexingDiagnosticSnapshotV12DomainResultV
+ _symbolic SS3key______5valuet 12SettingsHost32SearchIndexingDiagnosticSnapshotV12DomainResultV
+ _symbolic Say_____G 10Foundation11JSONEncoderC16OutputFormattingV
+ _symbolic Say_____G 12SettingsHost32SearchIndexingDiagnosticSnapshotV5IssueV
+ _symbolic Say_____G 8Dispatch0A13WorkItemFlagsV
+ _symbolic ScCy___________pG 10Foundation4DataV s5ErrorP
+ _symbolic SiSg
+ _symbolic _____ 10Foundation4DateV
+ _symbolic _____ 12SettingsHost0A26SearchIndexGenerationTokenV
+ _symbolic _____ 12SettingsHost0A26SearchIndexGenerationTokenV10CodingKeys33_9CD187E4404BEB3B05B48F48E111B743LLO
+ _symbolic _____ 12SettingsHost0aB16DiagnosticsStoreC
+ _symbolic _____ 12SettingsHost0aB16DiagnosticsStoreC8Envelope33_13A89FBD6E9E307679DEFE99CFB21591LLV
+ _symbolic _____ 12SettingsHost0aB16DiagnosticsStoreC8Envelope33_13A89FBD6E9E307679DEFE99CFB21591LLV10CodingKeysO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV12DomainResultV
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV12DomainResultV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO17SkippedCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO18CompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO20IncompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV5IssueV
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV5IssueV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV5IssueV8SeverityO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO16FailedCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO18CompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO20IncompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV7SummaryV
+ _symbolic _____ 12SettingsHost32SearchIndexingDiagnosticSnapshotV7SummaryV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____ 12SettingsHost5PrismV
+ _symbolic _____ So16NSURLResourceKeya
+ _symbolic _____Sg 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO
+ _symbolic _____Sg 12SettingsHost32SearchIndexingDiagnosticSnapshotV7SummaryV
+ _symbolic _____Sg_ABt 10Foundation4DateV
+ _symbolic _____XDXMT 12SettingsHost0aB16DiagnosticsStoreC
+ _symbolic _____m 12SettingsHost32SearchIndexingDiagnosticSnapshotV
+ _symbolic _____ySSG s10ArraySliceV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 12SettingsHost32SearchIndexingDiagnosticSnapshotV12DomainResultV
+ _symbolic _____y_____G s11_SetStorageC So16NSURLResourceKeya
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12SettingsHost0D26SearchIndexGenerationTokenV10CodingKeys33_9CD187E4404BEB3B05B48F48E111B743LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV12DomainResultV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO17SkippedCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO18CompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO20IncompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV5IssueV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO16FailedCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO18CompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO20IncompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV7SummaryV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12SettingsHost0D26SearchIndexGenerationTokenV10CodingKeys33_9CD187E4404BEB3B05B48F48E111B743LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV12DomainResultV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO17SkippedCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO18CompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV13DomainOutcomeO20IncompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV5IssueV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO16FailedCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO18CompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO20IncompleteCodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12SettingsHost32SearchIndexingDiagnosticSnapshotV7SummaryV10CodingKeys33_85D47D187E8AD0B466812DB06C0F1F88LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation11JSONEncoderC16OutputFormattingV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation3URLV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12SettingsHost32SearchIndexingDiagnosticSnapshotV5IssueV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So16NSURLResourceKeya
+ _symbolic _____y______G 12SettingsHost0aB16DiagnosticsStoreC8Envelope33_13A89FBD6E9E307679DEFE99CFB21591LLV AA32SearchIndexingDiagnosticSnapshotV
+ _symbolic _____yq_qd__G 12SettingsHost5PrismV
+ _symbolic _____yxq_G 12SettingsHost5PrismV
+ _type_layout_string 12SettingsHost0A26SearchIndexGenerationTokenV
+ _type_layout_string 12SettingsHost32SearchIndexingDiagnosticSnapshotV12DomainResultV
+ _type_layout_string 12SettingsHost32SearchIndexingDiagnosticSnapshotV5IssueV
+ _type_layout_string 12SettingsHost32SearchIndexingDiagnosticSnapshotV7OutcomeO
+ _type_layout_string 12SettingsHost32SearchIndexingDiagnosticSnapshotV7SummaryV
+ _type_layout_string r0_l12SettingsHost5PrismVyxq_G
CStrings:
+ "Adopting existing index generation '%{public}s' for index '%{public}s'."
+ "Checking reindex key: %{public}s"
+ "Consuming reindex request for domain key '%{public}s', will force a reindex."
+ "Diagnostic domain %{public}s has an empty identifier; falling back to its type name."
+ "Diagnostics container '%{public}s' is unavailable; falling back to the temporary directory."
+ "Failed to %{public}s diagnostics '%{public}s': %{public}s"
+ "Failed to fetch clientState for index '%{public}s': %{public}@. Treating as a dropped index and minting a new generation."
+ "Failed to get container URL for app group '%{public}s'."
+ "Failed to persist generation token for index '%{public}s': %{public}@."
+ "Failed to remove diagnostics '%{public}s': %{public}s"
+ "Failed to write diagnostic '%{public}s': %{public}s"
+ "Index '%{public}s' generation token build/locale changed; minting generation '%{public}s'."
+ "Invalidating recorded indexedItemCount for domain '%{public}s'"
+ "No clientState generation token for index '%{public}s' (index was dropped or never written); minting generation '%{public}s' and forcing full reindex."
+ "No reindexing request found for openIntentIdentifier: '%{public}s' appValueIdentifier: '%{public}s' hostBundleIdentifier: '%{public}s', will not force reindex"
+ "Persisted generation '%{public}s' to clientState for index '%{public}s' (%{public}ld bytes)."
+ "Recorded successful indexing for domain '%{public}s' with build, language, and generation '%{public}s'"
+ "Sweeping unknown reindex flag '%{public}s' (no matching domain in this pass)"
+ "com.apple.settings.search.indexing"
+ "com.apple.settingshost.diagnostics"
+ "com.apple.settingshost.diagnostics.io"
+ "coreSpotlightError"
+ "domainsIncomplete"
+ "domainsProcessed"
+ "important"
+ "informational"
+ "linkServicesError"
+ "postIndexingCleanup"
+ "severe"
- "Recorded successful indexing for domain '%{public}s' with build and language '%{public}s'"
```
