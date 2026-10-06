## UnilogInstrumentation

> `/System/Library/PrivateFrameworks/UnilogInstrumentation.framework/UnilogInstrumentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc290` | `0x18cc4` | **`+0xca34`** |
| `__TEXT.__eh_frame` | `0x398` | `0xa70` | **`+0x6d8`** |
| `__TEXT.__const` | `0x9f0` | `0x1010` | **`+0x620`** |
| `__DATA.__bss` | `0x990` | `0xe90` | **`+0x500`** |
| `__AUTH.__data` | `0x4f8` | `0x8a8` | **`+0x3b0`** |
| `__AUTH_CONST.__const` | `0x5e8` | `0x908` | **`+0x320`** |
| `__DATA.__data` | `0x320` | `0x640` | **`+0x320`** |
| `__TEXT.__unwind_info` | `0x398` | `0x688` | **`+0x2f0`** |
| `__TEXT.__constg_swiftt` | `0x3d4` | `0x69c` | **`+0x2c8`** |
| `__AUTH_CONST.__auth_got` | `0x5e0` | `0x888` | **`+0x2a8`** |
| `__TEXT.__swift5_typeref` | `0x376` | `0x5f8` | **`+0x282`** |
| `__TEXT.__swift5_fieldmd` | `0x284` | `0x47c` | **`+0x1f8`** |
| `__TEXT.__oslogstring` | `0x101` | `0x2f1` | **`+0x1f0`** |
| `__TEXT.__swift5_reflstr` | `0xec` | `0x215` | **`+0x129`** |
| `__AUTH_CONST.__objc_const` | `0x600` | `0x710` | **`+0x110`** |
| `__DATA_CONST.__got` | `0x148` | `0x230` | **`+0xe8`** |
| `__TEXT.__swift5_capture` | `0x38` | `0xe4` | **`+0xac`** |
| `__AUTH.__objc_data` | `0x160` | `0x1b0` | **`+0x50`** |
| `__TEXT.__swift_as_entry` | `0xc` | `0x50` | **`+0x44`** |
| `__TEXT.__cstring` | `0x1c1` | `0x1f1` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x5c` | `0x8c` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x8` | `0x34` | **`+0x2c`** |
| `__TEXT.__swift5_types` | `0x40` | `0x68` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x8` | `0x30` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x48` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x8` | `0x10` | **`+0x8`** |

### Other Changes

```diff

-2.0.1.0.0
+2.0.2.0.0
+  - /System/Library/Frameworks/Combine.framework/Combine

+  - /System/Library/PrivateFrameworks/BiomeStreams.framework/BiomeStreams

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 269
-  Symbols:   250
-  CStrings:  23
+  Functions: 474
+  Symbols:   332
+  CStrings:  36
Symbols:
+ _MobileGestalt_copy_buildVersion_obj
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_internalBuild
+ _OBJC_CLASS_$_BMPublisherOptions
+ __DATA__TtC21UnilogInstrumentation18IdentifierProvider
+ __IVARS__TtC21UnilogInstrumentation18IdentifierProvider
+ __METACLASS_DATA__TtC21UnilogInstrumentation18IdentifierProvider
+ ___swift_closure_destructor.29Tm
+ ___swift_closure_destructorTm
+ ___swift_destroy_boxed_opaque_existential_0Tm
+ ___swift_destroy_boxed_opaque_existential_1Tm
+ ___unnamed_7
+ __swift_implicitisolationactor_to_executor_cast
+ _associated conformance 21UnilogInstrumentation10PruneScopeOSHAASQ
+ _associated conformance 21UnilogInstrumentation15IdentifierSpaceOSHAASQ
+ _associated conformance 21UnilogInstrumentation18IdentifierProviderC8CacheKey33_D2E5F6091AAE096B04697F2BAAC6CCFFLLVSHAASQ
+ _associated conformance 21UnilogInstrumentation19LongLivedIdentifierVSHAASQ
+ _objc_release
+ _objc_release_x23
+ _objc_release_x24
+ _objc_release_x26
+ _objc_release_x28
+ _objc_release_x8
+ _swift_arrayDestroy
+ _swift_beginAccess
+ _swift_checkMetadataState
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_initEnumMetadataSingleCaseWithLayoutString
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_endAccess
+ _swift_getAssociatedTypeWitness
+ _swift_getEnumCaseMultiPayload
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getTupleTypeLayout2
+ _swift_getTupleTypeMetadata2
+ _swift_release_x22
+ _swift_retain_x26
+ _swift_storeEnumTagSinglePayloadGeneric
+ _symbolic $s21UnilogInstrumentation14PrunableStream33_551DDB4CD3A161A961E50635C079D2CELLP
+ _symbolic $s21UnilogInstrumentation17IdentifierStorageP
+ _symbolic SDy__________G 21UnilogInstrumentation18IdentifierProviderC8CacheKey33_D2E5F6091AAE096B04697F2BAAC6CCFFLLV AA09LongLivedC0V
+ _symbolic _____ 10Foundation4DateV
+ _symbolic _____ 19UnilogCommonLibrary6ClientO
+ _symbolic _____ 21UnilogInstrumentation10PruneRangeO
+ _symbolic _____ 21UnilogInstrumentation10PruneScopeO
+ _symbolic _____ 21UnilogInstrumentation15IdentifierSpaceO
+ _symbolic _____ 21UnilogInstrumentation15InMemoryStorageC16TimestampedEvent33_5DFF3211C0598BF1CE1398156B8971E3LLV
+ _symbolic _____ 21UnilogInstrumentation17PrunableStreamFor33_551DDB4CD3A161A961E50635C079D2CELLO
+ _symbolic _____ 21UnilogInstrumentation18IdentifierProviderC
+ _symbolic _____ 21UnilogInstrumentation18IdentifierProviderC8CacheKey33_D2E5F6091AAE096B04697F2BAAC6CCFFLLV
+ _symbolic _____ 21UnilogInstrumentation19LongLivedIdentifierV
+ _symbolic _____ 21UnilogInstrumentation21IdentifierStreamErrorO
+ _symbolic _____ 21UnilogInstrumentation21IdentifierStreamStoreV
+ _symbolic _____6client______5spacet 19UnilogCommonLibrary6ClientO 0A15Instrumentation15IdentifierSpaceO
+ _symbolic _____Sg 10Foundation8CalendarV
+ _symbolic _____Sg 10Foundation8TimeZoneV
+ _symbolic _____Sg 19UnilogCommonLibrary13DeviceContextV
+ _symbolic _____Sg 19UnilogCommonLibrary21LongTermAggregationIdV
+ _symbolic _____Sg 21UnilogInstrumentation11BiomeWriter33_551DDB4CD3A161A961E50635C079D2CELLC
+ _symbolic _____Sg 21UnilogInstrumentation19LongLivedIdentifierV
+ _symbolic _____Sg 27IntelligencePlatformLibrary24ExternalSchemaStreamDataV
+ _symbolic _____Sg_ABt 19UnilogCommonLibrary21LongTermAggregationIdV
+ _symbolic _____XDXMT 21UnilogInstrumentation12BiomeStorageC
+ _symbolic ______AAt 10Foundation4DateV
+ _symbolic ___________t 19UnilogCommonLibrary6ClientO 0A15Instrumentation15IdentifierSpaceO
+ _symbolic ______p 19UnilogCommonLibrary18AggregationPayloadP
+ _symbolic ______pXmT 21UnilogInstrumentation14PrunableStream33_551DDB4CD3A161A961E50635C079D2CELLP
+ _symbolic ______pXp 19UnilogCommonLibrary18AggregationPayloadP
+ _symbolic ______p___________tYbc 21UnilogInstrumentation17IdentifierStorageP 0A13CommonLibrary6ClientO AA0C5SpaceO
+ _symbolic _____ySay_____y______GGG 2os21OSAllocatedUnfairLockV 21UnilogInstrumentation15InMemoryStorageC16TimestampedEvent33_5DFF3211C0598BF1CE1398156B8971E3LLV 0E13CommonLibrary07StagingK0V
+ _symbolic _____ySay_____y______GGG 2os21OSAllocatedUnfairLockV 21UnilogInstrumentation15InMemoryStorageC16TimestampedEvent33_5DFF3211C0598BF1CE1398156B8971E3LLV 10Foundation4DataV
+ _symbolic _____y_____G 21UnilogInstrumentation13SourceWrapper33_551DDB4CD3A161A961E50635C079D2CELLV 27IntelligencePlatformLibrary0O0O7StreamsO0A0O12SafariSearchO11AggregationO
+ _symbolic _____y_____G 21UnilogInstrumentation13SourceWrapper33_551DDB4CD3A161A961E50635C079D2CELLV 27IntelligencePlatformLibrary0O0O7StreamsO0A0O12SafariSearchO5StageO
+ _symbolic _____y_____G 21UnilogInstrumentation17PrunableStreamFor33_551DDB4CD3A161A961E50635C079D2CELLO 27IntelligencePlatformLibrary0P0O7StreamsO0A0O12SafariSearchO11AggregationO
+ _symbolic _____y_____G 21UnilogInstrumentation17PrunableStreamFor33_551DDB4CD3A161A961E50635C079D2CELLO 27IntelligencePlatformLibrary0P0O7StreamsO0A0O12SafariSearchO5StageO
+ _symbolic _____y_____G 21UnilogInstrumentation17PrunableStreamFor33_551DDB4CD3A161A961E50635C079D2CELLO 27IntelligencePlatformLibrary0P0O7StreamsO0A0O4SiriO5StageO
+ _symbolic _____y_____G 21UnilogInstrumentation17PrunableStreamFor33_551DDB4CD3A161A961E50635C079D2CELLO 27IntelligencePlatformLibrary0P0O7StreamsO0A0O4SiriO9ProcessedO
+ _symbolic _____y______G 21UnilogInstrumentation15InMemoryStorageC16TimestampedEvent33_5DFF3211C0598BF1CE1398156B8971E3LLV 0A13CommonLibrary07StagingG0V
+ _symbolic _____y______G 21UnilogInstrumentation15InMemoryStorageC16TimestampedEvent33_5DFF3211C0598BF1CE1398156B8971E3LLV 10Foundation4DataV
+ _symbolic _____y__________G s18_DictionaryStorageC 21UnilogInstrumentation18IdentifierProviderC8CacheKey33_D2E5F6091AAE096B04697F2BAAC6CCFFLLV AC09LongLivedE0V
+ _symbolic _____y_____y______GG s23_ContiguousArrayStorageC 21UnilogInstrumentation08InMemoryC0C16TimestampedEvent33_5DFF3211C0598BF1CE1398156B8971E3LLV 0D13CommonLibrary07StagingI0V
+ _symbolic _____y_____y______GG s23_ContiguousArrayStorageC 21UnilogInstrumentation08InMemoryC0C16TimestampedEvent33_5DFF3211C0598BF1CE1398156B8971E3LLV 10Foundation4DataV
- ___swift_destroy_boxed_opaque_existential_0
- ___unnamed_4
- _symbolic _____y_____G s23_ContiguousArrayStorageC 19UnilogCommonLibrary12StagingEventV
CStrings:
+ "Aggregate event dropped: client has no aggregation stream"
+ "Aggregate event: %s"
+ "Aggregation prune skipped: client %d has no aggregation stream"
+ "Error serializing aggregate event: %@"
+ "Failed to prune identifier stream: %@"
+ "Failed to read identifier stream: %@"
+ "Failed to write identifier: %@"
+ "Processed prune skipped: client %d has no processed stream"
+ "Prune failed for %s: %@"
+ "Prune requested (scope: %s, range: %s) — no-op for LogStorage"
+ "Safari client"
+ "UnilogInstrumentation.IdentifierProvider"
+ "client space "
```
