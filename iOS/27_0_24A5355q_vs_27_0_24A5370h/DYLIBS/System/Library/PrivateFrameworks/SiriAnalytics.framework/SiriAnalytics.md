## SiriAnalytics

> `/System/Library/PrivateFrameworks/SiriAnalytics.framework/SiriAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe5ac4` | `0x10a594` | **`+0x24ad0`** |
| `__TEXT.__cstring` | `0xaa2f` | `0x3f03` | **`-0x6b2c`** |
| `__TEXT.__oslogstring` | `0x1136` | `0x3c90` | **`+0x2b5a`** |
| `__AUTH_CONST.__const` | `0x6bc0` | `0x8f00` | **`+0x2340`** |
| `__TEXT.__eh_frame` | `0x95cc` | `0xacd8` | **`+0x170c`** |
| `__DATA.__bss` | `0xb340` | `0xc810` | **`+0x14d0`** |
| `__AUTH_CONST.__cfstring` | `0x2200` | `0xea0` | **`-0x1360`** |
| `__TEXT.__const` | `0xa638` | `0xb820` | **`+0x11e8`** |
| `__TEXT.__swift5_capture` | `0xb40` | `0x17a4` | **`+0xc64`** |
| `__TEXT.__unwind_info` | `0x4cc8` | `0x5540` | **`+0x878`** |
| `__TEXT.__swift5_typeref` | `0x3315` | `0x391c` | **`+0x607`** |
| `__AUTH.__data` | `0x22b0` | `0x2740` | **`+0x490`** |
| `__DATA_CONST.__const` | `0x1410` | `0xfb8` | **`-0x458`** |
| `__TEXT.__constg_swiftt` | `0x3bbc` | `0x3ec8` | **`+0x30c`** |
| `__DATA.__data` | `0x2a18` | `0x2ca8` | **`+0x290`** |
| `__TEXT.__swift5_fieldmd` | `0x2e90` | `0x30e8` | **`+0x258`** |
| `__AUTH.__objc_data` | `0x10f0` | `0x12d0` | **`+0x1e0`** |
| `__TEXT.__swift5_reflstr` | `0x224d` | `0x241d` | **`+0x1d0`** |
| `__AUTH_CONST.__objc_const` | `0x6900` | `0x6ac8` | **`+0x1c8`** |
| `__DATA_DIRTY.__data` | `0x1d48` | `0x1b88` | **`-0x1c0`** |
| `__DATA.__common` | `0x248` | `0x3a0` | **`+0x158`** |
| `__TEXT.__swift_as_cont` | `0x6a0` | `0x780` | **`+0xe0`** |
| `__AUTH_CONST.__auth_got` | `0x1620` | `0x16f8` | **`+0xd8`** |
| `__TEXT.__swift5_proto` | `0x6f0` | `0x794` | **`+0xa4`** |
| `__DATA_DIRTY.__objc_data` | `0x1978` | `0x18d8` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x2280` | `0x2210` | **`-0x70`** |
| `__TEXT.__swift_as_entry` | `0x338` | `0x39c` | **`+0x64`** |
| `__TEXT.__swift_as_ret` | `0x3bc` | `0x404` | **`+0x48`** |
| `__TEXT.__swift5_types` | `0x43c` | `0x474` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x14d0` | `0x14a8` | **`-0x28`** |
| `__DATA_CONST.__got` | `0x818` | `0x838` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x350` | `0x368` | **`+0x18`** |
| `__DATA_DIRTY.__common` | `0x108` | `0xf0` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x1cc` | `0x1b8` | **`-0x14`** |
| `__DATA.__objc_ivar` | `0x208` | `0x1f8` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xe0` | `0xd0` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x68` | `0x70` | **`+0x8`** |

### Other Changes

```diff

-3600.69.7.0.0
+3600.77.1.0.0

+  - /System/Library/PrivateFrameworks/SchemaTypesCore.framework/SchemaTypesCore

-  Functions: 6920
-  Symbols:   3353
-  CStrings:  998
+  Functions: 7780
+  Symbols:   3503
+  CStrings:  716
Symbols:
+ -[SiriAnalyticsClientMessageStream emitMessagePayload:typeIdentifier:timestamp:isolatedStreamUUID:completion:]
+ -[SiriAnalyticsClientMessageStream initWithMachServiceName:]
+ -[SiriAnalyticsXPCConnection _barrierWithCompletion:]
+ -[SiriAnalyticsXPCConnection _createTag:callerQoS:completion:]
+ -[SiriAnalyticsXPCConnection _packageMessageForXPC:timestamp:messageUUID:isolatedStreamUUID:]
+ -[SiriAnalyticsXPCConnection _sensitiveCondition:startedAt:callerQoS:completion:]
+ -[SiriAnalyticsXPCConnection emitMessage:timestamp:isolatedStreamUUID:completion:]
+ -[SiriAnalyticsXPCConnection emitMessagePayload:typeIdentifier:timestamp:isolatedStreamUUID:completion:]
+ -[SiriAnalyticsXPCConnection enqueueLargeMessageObjectFromPath:dataUploadEvent:requestIdentifier:completion:]
+ -[SiriAnalyticsXPCConnection resolvePartialMessage:timestamp:messageUUID:isolatedStreamUUID:completion:]
+ GCC_except_table171
+ GCC_except_table175
+ GCC_except_table183
+ GCC_except_table331
+ GCC_except_table334
+ GCC_except_table341
+ GCC_except_table348
+ GCC_except_table373
+ GCC_except_table380
+ GCC_except_table387
+ GCC_except_table393
+ GCC_except_table399
+ GCC_except_table406
+ _OBJC_CLASS_$_SISchemaProvisionalEvent
+ _OBJC_CLASS_$_SiriAnalyticsAssistantServicesShim
+ _OBJC_CLASS_$_SiriAnalyticsTelemetrySideChannel
+ _OBJC_IVAR_$_AssistantSiriAnalytics._servicesShim
+ _OBJC_IVAR_$_SiriAnalyticsClientMessageStream._connection
+ _OBJC_METACLASS_$_SiriAnalyticsAssistantServicesShim
+ _OBJC_METACLASS_$_SiriAnalyticsTelemetrySideChannel
+ _OUTLINED_FUNCTION_196
+ _OUTLINED_FUNCTION_197
+ _OUTLINED_FUNCTION_198
+ _OUTLINED_FUNCTION_199
+ _OUTLINED_FUNCTION_200
+ _OUTLINED_FUNCTION_201
+ _OUTLINED_FUNCTION_202
+ _OUTLINED_FUNCTION_203
+ _OUTLINED_FUNCTION_204
+ _OUTLINED_FUNCTION_205
+ _OUTLINED_FUNCTION_206
+ _OUTLINED_FUNCTION_207
+ _OUTLINED_FUNCTION_208
+ _OUTLINED_FUNCTION_209
+ _OUTLINED_FUNCTION_210
+ _OUTLINED_FUNCTION_211
+ _OUTLINED_FUNCTION_212
+ _OUTLINED_FUNCTION_213
+ _OUTLINED_FUNCTION_214
+ _OUTLINED_FUNCTION_215
+ _OUTLINED_FUNCTION_216
+ _OUTLINED_FUNCTION_217
+ _OUTLINED_FUNCTION_218
+ _OUTLINED_FUNCTION_219
+ _OUTLINED_FUNCTION_220
+ _OUTLINED_FUNCTION_221
+ _OUTLINED_FUNCTION_222
+ _OUTLINED_FUNCTION_223
+ _OUTLINED_FUNCTION_224
+ _OUTLINED_FUNCTION_225
+ _OUTLINED_FUNCTION_226
+ _OUTLINED_FUNCTION_227
+ _OUTLINED_FUNCTION_228
+ _OUTLINED_FUNCTION_229
+ _OUTLINED_FUNCTION_230
+ _OUTLINED_FUNCTION_231
+ _OUTLINED_FUNCTION_232
+ _OUTLINED_FUNCTION_233
+ _OUTLINED_FUNCTION_234
+ _OUTLINED_FUNCTION_235
+ _OUTLINED_FUNCTION_236
+ _OUTLINED_FUNCTION_237
+ _OUTLINED_FUNCTION_238
+ __DATA_SiriAnalyticsAssistantServicesShim
+ __DATA_SiriAnalyticsTelemetrySideChannel
+ __DATA__TtC13SiriAnalytics16RuntimeXPCClient
+ __DATA__TtC13SiriAnalytics26SensitiveConditionsService
+ __DATA__TtCC13SiriAnalytics20TelemetrySideChannelP33_C3C7EEDE249CC3F0CA97FD46AD670B3410Aggregator
+ __DATA__TtCV13SiriAnalytics11AhoCorasickP33_6CAD5E5F60A95F936EF30427E37BF1DD4Node
+ __INSTANCE_METHODS_SiriAnalyticsAssistantServicesShim
+ __INSTANCE_METHODS_SiriAnalyticsTelemetrySideChannel
+ __IVARS_SiriAnalyticsAssistantServicesShim
+ __IVARS_SiriAnalyticsTelemetrySideChannel
+ __IVARS__TtC13SiriAnalytics16RuntimeXPCClient
+ __IVARS__TtC13SiriAnalytics26SensitiveConditionsService
+ __IVARS__TtCC13SiriAnalytics20TelemetrySideChannelP33_C3C7EEDE249CC3F0CA97FD46AD670B3410Aggregator
+ __IVARS__TtCV13SiriAnalytics11AhoCorasickP33_6CAD5E5F60A95F936EF30427E37BF1DD4Node
+ __METACLASS_DATA_SiriAnalyticsAssistantServicesShim
+ __METACLASS_DATA_SiriAnalyticsTelemetrySideChannel
+ __METACLASS_DATA__TtC13SiriAnalytics16RuntimeXPCClient
+ __METACLASS_DATA__TtC13SiriAnalytics26SensitiveConditionsService
+ __METACLASS_DATA__TtCC13SiriAnalytics20TelemetrySideChannelP33_C3C7EEDE249CC3F0CA97FD46AD670B3410Aggregator
+ __METACLASS_DATA__TtCV13SiriAnalytics11AhoCorasickP33_6CAD5E5F60A95F936EF30427E37BF1DD4Node
+ ___104-[SiriAnalyticsXPCConnection emitMessagePayload:typeIdentifier:timestamp:isolatedStreamUUID:completion:]_block_invoke
+ ___104-[SiriAnalyticsXPCConnection resolvePartialMessage:timestamp:messageUUID:isolatedStreamUUID:completion:]_block_invoke
+ ___109-[SiriAnalyticsXPCConnection enqueueLargeMessageObjectFromPath:dataUploadEvent:requestIdentifier:completion:]_block_invoke
+ ___52-[SiriAnalyticsXPCConnection barrierWithCompletion:]_block_invoke_2
+ ___53-[SiriAnalyticsXPCConnection _barrierWithCompletion:]_block_invoke
+ ___62-[SiriAnalyticsXPCConnection _createTag:callerQoS:completion:]_block_invoke
+ ___62-[SiriAnalyticsXPCConnection _createTag:callerQoS:completion:]_block_invoke_2
+ ___62-[SiriAnalyticsXPCConnection _createTag:callerQoS:completion:]_block_invoke_3
+ ___81-[SiriAnalyticsXPCConnection _sensitiveCondition:startedAt:callerQoS:completion:]_block_invoke
+ ___81-[SiriAnalyticsXPCConnection _sensitiveCondition:startedAt:callerQoS:completion:]_block_invoke_2
+ ___82-[SiriAnalyticsXPCConnection emitMessage:timestamp:isolatedStreamUUID:completion:]_block_invoke
+ ___block_descriptor_52_e8_32s40bs_e20_v20?0B8"NSError"12ls32l8s40l8
+ ___block_descriptor_60_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40bs_e5_v8?0ls32l8s40l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_76_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ ___swift_closure_destructor.10Tm
+ ___swift_closure_destructor.21Tm
+ ___swift_closure_destructor.75Tm
+ ___swift_project_boxed_opaque_existential_1Tm
+ ___unnamed_8
+ __swift_stdlib_bridgeErrorToNSError
+ _associated conformance 13SiriAnalytics10SchemaUUIDV8Dendrite17DataRepresentableAaD0F8Readable
+ _associated conformance 13SiriAnalytics10SchemaUUIDV8Dendrite18ProtoMessageReaderAaD10AnyBuilder
+ _associated conformance 13SiriAnalytics10SchemaUUIDV8Dendrite19KeyPathBoundMessageAaD05ProtoI6Reader
+ _associated conformance 13SiriAnalytics10SchemaUUIDV8Dendrite19KeyPathBoundMessageAaD05ProtoI6Writer
+ _associated conformance 13SiriAnalytics10SchemaUUIDV8Dendrite19KeyPathBoundMessageAaD17DataRepresentable
+ _associated conformance 13SiriAnalytics16RuntimeXPCClientC15ConnectionErrorOSHAASQ
+ _associated conformance 13SiriAnalytics20TelemetrySideChannelC10Aggregator33_C3C7EEDE249CC3F0CA97FD46AD670B34LLC19EventAggregationKeyVSHAASQ
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV0C0V8Dendrite17DataRepresentableAaF0G8Readable
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV0C0V8Dendrite18ProtoMessageReaderAaF10AnyBuilder
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV0C0V8Dendrite19KeyPathBoundMessageAaF05ProtoJ6Reader
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV0C0V8Dendrite19KeyPathBoundMessageAaF05ProtoJ6Writer
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV0C0V8Dendrite19KeyPathBoundMessageAaF17DataRepresentable
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV0C10IdentifierV8Dendrite17DataRepresentableAaF0H8Readable
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV0C10IdentifierV8Dendrite18ProtoMessageReaderAaF10AnyBuilder
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV0C10IdentifierV8Dendrite19KeyPathBoundMessageAaF05ProtoK6Reader
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV0C10IdentifierV8Dendrite19KeyPathBoundMessageAaF05ProtoK6Writer
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV0C10IdentifierV8Dendrite19KeyPathBoundMessageAaF17DataRepresentable
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV15SchemaTypesCore11ProvisionalAaD16TypeIdentifiable
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV7ByClockV8Dendrite17DataRepresentableAaF0I8Readable
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV7ByClockV8Dendrite18ProtoMessageReaderAaF10AnyBuilder
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV7ByClockV8Dendrite19KeyPathBoundMessageAaF05ProtoL6Reader
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV7ByClockV8Dendrite19KeyPathBoundMessageAaF05ProtoL6Writer
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV7ByClockV8Dendrite19KeyPathBoundMessageAaF17DataRepresentable
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV8Dendrite17DataRepresentableAaD0G8Readable
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV8Dendrite18ProtoMessageReaderAaD10AnyBuilder
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV8Dendrite19KeyPathBoundMessageAaD05ProtoJ6Reader
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV8Dendrite19KeyPathBoundMessageAaD05ProtoJ6Writer
+ _associated conformance 13SiriAnalytics22ConnectedComponentsLogV8Dendrite19KeyPathBoundMessageAaD17DataRepresentable
+ _dispatch_block_create
+ _flat unique So23SiriAnalyticsXPCService_p
+ _get_enum_tag_for_layout_string 13SiriAnalytics10SchemaUUIDVSg
+ _get_enum_tag_for_layout_string 13SiriAnalytics22ConnectedComponentsLogV0C10IdentifierVSg
+ _get_enum_tag_for_layout_string 13SiriAnalytics22ConnectedComponentsLogV7ByClockVSg
+ _qos_class_self
+ _swift_release_x10
+ _swift_release_x11
+ _symbolic SDySJSiG
+ _symbolic SDySSSo8NSObjectCGIego_
+ _symbolic SDySS_____G 13SiriAnalytics22TextDataClassificationV
+ _symbolic SDy__________G 13SiriAnalytics20TelemetrySideChannelC10Aggregator33_C3C7EEDE249CC3F0CA97FD46AD670B34LLC19EventAggregationKeyV s6UInt64V
+ _symbolic SDy__________y______GG 10Foundation4UUIDV 13SiriAnalytics8PatternsV7FetchedO AD27TextClassificationProcessorV0H3SetV
+ _symbolic SDy_____y______pcG 10Foundation4UUIDV s5ErrorP
+ _symbolic SNy_____GIegr_ s6UInt64V
+ _symbolic SSIego_
+ _symbolic Say_____G 13SiriAnalytics11AhoCorasickV4Node33_6CAD5E5F60A95F936EF30427E37BF1DDLLC
+ _symbolic Say_____G 13SiriAnalytics18LogicalClocksTableV6RecordV
+ _symbolic Say_____G 13SiriAnalytics22TextDataClassificationV
+ _symbolic Say_____G 19ExtensionFoundation03AppA8IdentityV
+ _symbolic Say_____GIegr_ 10Foundation4UUIDV
+ _symbolic Say_____GIegr_ So30SISchemaDeviceSensitivityStateV
+ _symbolic Say_____GSg 13SiriAnalytics22ConnectedComponentsLogV0C0V
+ _symbolic Say_____GSg 13SiriAnalytics22ConnectedComponentsLogV0C10IdentifierV
+ _symbolic Sb______pSgIegyg_Sg s5ErrorP
+ _symbolic SiIegd_
+ _symbolic SiIegr_
+ _symbolic Sny_____G SS5IndexV
+ _symbolic So25SiriAnalyticsLogicalClockC
+ _symbolic So25SiriAnalyticsLogicalClockC_Sbt
+ _symbolic So8NSObjectCIego_
+ _symbolic So8NSObjectCSg
+ _symbolic So8NSObjectCSgIego_
+ _symbolic SuIegd_
+ _symbolic SuIegr_
+ _symbolic _____ 13SiriAnalytics10SchemaUUIDV
+ _symbolic _____ 13SiriAnalytics11AhoCorasickV
+ _symbolic _____ 13SiriAnalytics11AhoCorasickV4Node33_6CAD5E5F60A95F936EF30427E37BF1DDLLC
+ _symbolic _____ 13SiriAnalytics11AhoCorasickV5MatchV
+ _symbolic _____ 13SiriAnalytics16RuntimeXPCClientC
+ _symbolic _____ 13SiriAnalytics16RuntimeXPCClientC15ConnectionErrorO
+ _symbolic _____ 13SiriAnalytics20InstrumentationErrorO
+ _symbolic _____ 13SiriAnalytics20TelemetrySideChannelC
+ _symbolic _____ 13SiriAnalytics20TelemetrySideChannelC10Aggregator33_C3C7EEDE249CC3F0CA97FD46AD670B34LLC
+ _symbolic _____ 13SiriAnalytics20TelemetrySideChannelC10Aggregator33_C3C7EEDE249CC3F0CA97FD46AD670B34LLC19EventAggregationKeyV
+ _symbolic _____ 13SiriAnalytics21AssistantServicesShimC
+ _symbolic _____ 13SiriAnalytics22ConnectedComponentsLogV
+ _symbolic _____ 13SiriAnalytics22ConnectedComponentsLogV0C0V
+ _symbolic _____ 13SiriAnalytics22ConnectedComponentsLogV0C10IdentifierV
+ _symbolic _____ 13SiriAnalytics22ConnectedComponentsLogV7ByClockV
+ _symbolic _____ 13SiriAnalytics26SensitiveConditionsServiceC
+ _symbolic _____ 13SiriAnalytics27TextClassificationProcessorV0D3SetV
+ _symbolic _____ 15SchemaTypesCore29InstrumentationTypeIdentifierO
+ _symbolic _____ 19SiriInstrumentation16LogicalTimestampC
+ _symbolic _____14classification_Sny_____G5ranget 13SiriAnalytics22TextDataClassificationV SS5IndexV
+ _symbolic _____Iegd_ s6UInt64V
+ _symbolic _____Iegr_ 10Foundation4UUIDV
+ _symbolic _____Iegr_ So30SISchemaDeviceSensitivityStateV
+ _symbolic _____Iegr_ s6UInt64V
+ _symbolic _____Sg 13SiriAnalytics10SchemaUUIDV
+ _symbolic _____Sg 13SiriAnalytics16RuntimeXPCClientC
+ _symbolic _____Sg 13SiriAnalytics20TelemetrySideChannelC
+ _symbolic _____Sg 13SiriAnalytics22ConnectedComponentsLogV0C10IdentifierV
+ _symbolic _____Sg 13SiriAnalytics22ConnectedComponentsLogV7ByClockV
+ _symbolic _____SgXw 13SiriAnalytics16RuntimeXPCClientC
+ _symbolic _____SgXwz_Xx 13SiriAnalytics16RuntimeXPCClientC
+ _symbolic _____XDXMT 13SiriAnalytics16RuntimeXPCClientC
+ _symbolic ______Sny_____Gt 13SiriAnalytics22TextDataClassificationV SS5IndexV
+ _symbolic ___________y_____Gt s6UInt32V 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics0C4UUIDV
+ _symbolic ___________y_____Gt s6UInt32V 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics22ConnectedComponentsLogV
+ _symbolic ___________y_____Gt s6UInt32V 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics22ConnectedComponentsLogV0I0V
+ _symbolic ___________y_____Gt s6UInt32V 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics22ConnectedComponentsLogV0I10IdentifierV
+ _symbolic ___________y_____Gt s6UInt32V 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics22ConnectedComponentsLogV7ByClockV
+ _symbolic ______p So23SiriAnalyticsXPCServiceP
+ _symbolic ______pIego_ s5ErrorP
+ _symbolic _____ySJSiG s17_NativeDictionaryV
+ _symbolic _____ySSSo8NSObjectCG s17_NativeDictionaryV
+ _symbolic _____ySS_So8NSObjectCtG s23_ContiguousArrayStorageC
+ _symbolic _____ySS_____G s17_NativeDictionaryV 13SiriAnalytics22TextDataClassificationV
+ _symbolic _____ySiG s23_ContiguousArrayStorageC
+ _symbolic _____ySo25SiriAnalyticsLogicalClockC_SbtG s23_ContiguousArrayStorageC
+ _symbolic _____y_____14classification_Sny_____G5rangetG s23_ContiguousArrayStorageC 13SiriAnalytics22TextDataClassificationV SS5IndexV
+ _symbolic _____y_____G 13SiriAnalytics24PrivateBiomeStreamPrunerV AA010RawUnifiedE7MessageC
+ _symbolic _____y_____G 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics0B4UUIDV
+ _symbolic _____y_____G 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics22ConnectedComponentsLogV
+ _symbolic _____y_____G 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics22ConnectedComponentsLogV0H0V
+ _symbolic _____y_____G 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics22ConnectedComponentsLogV0H10IdentifierV
+ _symbolic _____y_____G 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics22ConnectedComponentsLogV7ByClockV
+ _symbolic _____y_____G s11_SetStorageC 10Foundation8CalendarV9ComponentO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation8CalendarV9ComponentO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 13SiriAnalytics11AhoCorasickV5MatchV
+ _symbolic _____y______Sny_____GtG s23_ContiguousArrayStorageC 13SiriAnalytics22TextDataClassificationV SS5IndexV
+ _symbolic _____y__________G s17_NativeDictionaryV 13SiriAnalytics20TelemetrySideChannelC10Aggregator33_C3C7EEDE249CC3F0CA97FD46AD670B34LLC19EventAggregationKeyV s6UInt64V
+ _symbolic _____y___________G SD8_VariantV 13SiriAnalytics20TelemetrySideChannelC10Aggregator33_C3C7EEDE249CC3F0CA97FD46AD670B34LLC19EventAggregationKeyV s6UInt64V
+ _symbolic _____y___________y_____GtG s23_ContiguousArrayStorageC s6UInt32V 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics0F4UUIDV
+ _symbolic _____y___________y_____GtG s23_ContiguousArrayStorageC s6UInt32V 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics22ConnectedComponentsLogV
+ _symbolic _____y___________y_____GtG s23_ContiguousArrayStorageC s6UInt32V 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics22ConnectedComponentsLogV0L0V
+ _symbolic _____y___________y_____GtG s23_ContiguousArrayStorageC s6UInt32V 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics22ConnectedComponentsLogV0L10IdentifierV
+ _symbolic _____y___________y_____GtG s23_ContiguousArrayStorageC s6UInt32V 8Dendrite18SchemaBoundKeyPathV 13SiriAnalytics22ConnectedComponentsLogV7ByClockV
+ _symbolic _____y__________y______GG s17_NativeDictionaryV 10Foundation4UUIDV 13SiriAnalytics8PatternsV7FetchedO AF27TextClassificationProcessorV0J3SetV
+ _symbolic _____yySpy_____Gz_SpySo8NSObjectCSgGSgzSpyypGSgztcG s23_ContiguousArrayStorageC s5UInt8V
+ _symbolic y______pc s5ErrorP
+ _type_layout_string 13SiriAnalytics10SchemaUUIDV
+ _type_layout_string 13SiriAnalytics11AhoCorasickV
+ _type_layout_string 13SiriAnalytics11AhoCorasickV5MatchV
+ _type_layout_string 13SiriAnalytics20TelemetrySideChannelC10Aggregator33_C3C7EEDE249CC3F0CA97FD46AD670B34LLC19EventAggregationKeyV
+ _type_layout_string 13SiriAnalytics22ConnectedComponentsLogV
+ _type_layout_string 13SiriAnalytics22ConnectedComponentsLogV0C0V
+ _type_layout_string 13SiriAnalytics22ConnectedComponentsLogV0C10IdentifierV
+ _type_layout_string 13SiriAnalytics22ConnectedComponentsLogV7ByClockV
+ _type_layout_string 13SiriAnalytics27TextClassificationProcessorV0D3SetV
- -[SiriAnalyticsClientMessageStream analyticsService]
- -[SiriAnalyticsClientMessageStream initWithQueue:analyticsService:]
- -[SiriAnalyticsClientMessageStream setAnalyticsService:]
- -[SiriAnalyticsInternalTelemetry _trackLogicalClock:isDerivativeClock:]
- -[SiriAnalyticsInternalTelemetry initWithPreferences:]
- -[SiriAnalyticsInternalTelemetry trackAnyEventEmitted:]
- -[SiriAnalyticsInternalTelemetry trackEmittedEvents:]
- -[SiriAnalyticsInternalTelemetry trackEventEmitted:]
- -[SiriAnalyticsInternalTelemetry trackLogicalClock:]
- -[SiriAnalyticsInternalTelemetry trackMessageStagedWithSuccess:]
- -[SiriAnalyticsInternalTelemetry trackMessageStreamProcessed:timeToFirstMessage:messageCount:processingReason:failureReason:]
- -[SiriAnalyticsInternalTelemetry trackRuntimeBootstrapCompleteWithBootstrapTimeInNs:]
- -[SiriAnalyticsInternalTelemetry trackRuntimeBootstrapWithKillSwitchEnabled:]
- -[SiriAnalyticsRemoteService .cxx_destruct]
- -[SiriAnalyticsRemoteService _packageMessageForXPC:timestamp:messageUUID:isolatedStreamUUID:]
- -[SiriAnalyticsRemoteService barrierWithCompletion:]
- -[SiriAnalyticsRemoteService createTag:completion:]
- -[SiriAnalyticsRemoteService emitMessage:timestamp:messageUUID:isolatedStreamUUID:completion:]
- -[SiriAnalyticsRemoteService enqueueLargeMessageObjectFromPath:dataUploadEvent:requestIdentifier:completion:]
- -[SiriAnalyticsRemoteService initWithMachServiceName:]
- -[SiriAnalyticsRemoteService resolvePartialMessage:timestamp:messageUUID:isolatedStreamUUID:completion:]
- -[SiriAnalyticsRemoteService sensitiveCondition:endedAt:completion:]
- -[SiriAnalyticsRemoteService sensitiveCondition:startedAt:completion:]
- -[SiriAnalyticsXPCConnection _createTag:completion:]
- -[SiriAnalyticsXPCConnection _sensitiveCondition:startedAt:completion:]
- GCC_except_table176
- GCC_except_table180
- GCC_except_table188
- GCC_except_table371
- GCC_except_table374
- GCC_except_table381
- GCC_except_table388
- GCC_except_table420
- GCC_except_table427
- GCC_except_table433
- GCC_except_table439
- GCC_except_table446
- GCC_except_table453
- _OBJC_CLASS_$_NSCalendar
- _OBJC_CLASS_$_SiriAnalyticsRemoteService
- _OBJC_IVAR_$_AssistantSiriAnalytics._remoteService
- _OBJC_IVAR_$_SiriAnalyticsClientMessageStream._queue
- _OBJC_IVAR_$_SiriAnalyticsClientMessageStream._service
- _OBJC_IVAR_$_SiriAnalyticsInternalTelemetry._isInternal
- _OBJC_IVAR_$_SiriAnalyticsRemoteService._connection
- _OBJC_IVAR_$_SiriAnalyticsRemoteService._queue
- _OBJC_METACLASS_$_SiriAnalyticsRemoteService
- __DATA__TtC13SiriAnalytics12CustomLogger
- __DATA__TtC13SiriAnalytics18InternalOnlyLogger
- __IVARS__TtC13SiriAnalytics12CustomLogger
- __IVARS__TtC13SiriAnalytics18InternalOnlyLogger
- __METACLASS_DATA__TtC13SiriAnalytics12CustomLogger
- __METACLASS_DATA__TtC13SiriAnalytics18InternalOnlyLogger
- __OBJC_$_INSTANCE_METHODS_SiriAnalyticsRemoteService
- __OBJC_$_INSTANCE_VARIABLES_SiriAnalyticsInternalTelemetry
- __OBJC_$_INSTANCE_VARIABLES_SiriAnalyticsRemoteService
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_SiriAnalyticsService
- __OBJC_$_PROTOCOL_METHOD_TYPES_SiriAnalyticsService
- __OBJC_CLASS_PROTOCOLS_$_SiriAnalyticsRemoteService
- __OBJC_CLASS_RO_$_SiriAnalyticsRemoteService
- __OBJC_LABEL_PROTOCOL_$_SiriAnalyticsService
- __OBJC_METACLASS_RO_$_SiriAnalyticsRemoteService
- __OBJC_PROTOCOL_$_SiriAnalyticsService
- ___104-[SiriAnalyticsRemoteService resolvePartialMessage:timestamp:messageUUID:isolatedStreamUUID:completion:]_block_invoke
- ___109-[SiriAnalyticsRemoteService enqueueLargeMessageObjectFromPath:dataUploadEvent:requestIdentifier:completion:]_block_invoke
- ___125-[SiriAnalyticsInternalTelemetry trackMessageStreamProcessed:timeToFirstMessage:messageCount:processingReason:failureReason:]_block_invoke
- ___131-[SiriAnalyticsClientMessageStream enqueueLargeMessageObjectFromPath:assetIdentifier:requestIdentifier:messageMetadata:completion:]_block_invoke
- ___51-[SiriAnalyticsRemoteService createTag:completion:]_block_invoke
- ___52-[SiriAnalyticsInternalTelemetry trackEventEmitted:]_block_invoke
- ___52-[SiriAnalyticsInternalTelemetry trackLogicalClock:]_block_invoke
- ___52-[SiriAnalyticsRemoteService barrierWithCompletion:]_block_invoke
- ___52-[SiriAnalyticsRemoteService barrierWithCompletion:]_block_invoke_2
- ___52-[SiriAnalyticsXPCConnection _createTag:completion:]_block_invoke
- ___52-[SiriAnalyticsXPCConnection _createTag:completion:]_block_invoke_2
- ___52-[SiriAnalyticsXPCConnection _createTag:completion:]_block_invoke_3
- ___55-[SiriAnalyticsInternalTelemetry trackAnyEventEmitted:]_block_invoke
- ___58-[SiriAnalyticsClientMessageStream barrierWithCompletion:]_block_invoke
- ___64-[SiriAnalyticsInternalTelemetry trackMessageStagedWithSuccess:]_block_invoke
- ___68-[SiriAnalyticsRemoteService sensitiveCondition:endedAt:completion:]_block_invoke
- ___70-[SiriAnalyticsRemoteService sensitiveCondition:startedAt:completion:]_block_invoke
- ___71-[SiriAnalyticsInternalTelemetry _trackLogicalClock:isDerivativeClock:]_block_invoke
- ___71-[SiriAnalyticsXPCConnection _sensitiveCondition:startedAt:completion:]_block_invoke
- ___71-[SiriAnalyticsXPCConnection _sensitiveCondition:startedAt:completion:]_block_invoke_2
- ___77-[SiriAnalyticsClientMessageStream emitMessage:timestamp:isolatedStreamUUID:]_block_invoke
- ___77-[SiriAnalyticsInternalTelemetry trackRuntimeBootstrapWithKillSwitchEnabled:]_block_invoke
- ___85-[SiriAnalyticsInternalTelemetry trackRuntimeBootstrapCompleteWithBootstrapTimeInNs:]_block_invoke
- ___87-[SiriAnalyticsClientMessageStream resolvePartialMessage:timestamp:isolatedStreamUUID:]_block_invoke
- ___94-[SiriAnalyticsRemoteService emitMessage:timestamp:messageUUID:isolatedStreamUUID:completion:]_block_invoke
- ___block_descriptor_33_e19_"NSDictionary"8?0l
- ___block_descriptor_40_e19_"NSDictionary"8?0l
- ___block_descriptor_40_e8_32s_e45_v32?0"SiriAnalyticsDerivativeClock"8Q16^B24ls32l8
- ___block_descriptor_41_e8_32s_e19_"NSDictionary"8?0ls32l8
- ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s64l8s56l8
- ___block_descriptor_72_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
- ___block_descriptor_72_e8_32s40s_e19_"NSDictionary"8?0ls32l8s40l8
- ___unnamed_7
- _objc_retain_x6
- _symbolic SDy__________y_Say_____GGG 10Foundation4UUIDV 13SiriAnalytics8PatternsV7FetchedO AD22TextDataClassificationV
- _symbolic So30SiriAnalyticsInternalTelemetryCSg
- _symbolic _____ 13SiriAnalytics12CustomLoggerC
- _symbolic _____ 13SiriAnalytics18InternalOnlyLoggerC
- _symbolic _____ 2os6LoggerV
- _symbolic _____ So033SUTSchemaTestExecutionEvent_WhichD5_TypeV
- _symbolic _____Sg 13SiriAnalytics18InternalOnlyLoggerC
- _symbolic _____y__________y_Say_____GGG s17_NativeDictionaryV 10Foundation4UUIDV 13SiriAnalytics8PatternsV7FetchedO AF22TextDataClassificationV
CStrings:
+ "%@"
+ "%@.xpc.connection"
+ "%ld redaction summaries accumulated."
+ "%llu <%s> : %s<%s> %s"
+ "%s"
+ "%s %s"
+ "%s affecting entire clock"
+ "%s does not exist"
+ "%s endedAt: %llu"
+ "%s exists at %s, removing..."
+ "%s on: %llu reason: %lu"
+ "%s on: %s reason: %s"
+ "%s root: %s bootSessionUUID:%s on: %llu"
+ "%s startedAt: %llu"
+ "%s type: %u bootSessionUUID:%s on: %s"
+ "-[SiriAnalyticsXPCConnection _barrierWithCompletion:]"
+ "-[SiriAnalyticsXPCConnection _barrierWithCompletion:]_block_invoke"
+ "-[SiriAnalyticsXPCConnection _createTag:callerQoS:completion:]_block_invoke_3"
+ "-[SiriAnalyticsXPCConnection _sensitiveCondition:startedAt:callerQoS:completion:]"
+ "-[SiriAnalyticsXPCConnection _sensitiveCondition:startedAt:callerQoS:completion:]_block_invoke"
+ "Access vending is disabled. Internal is %{bool}d, UnilogMigration: %{bool}d"
+ "Adding new columns for %s: %s"
+ "Adding opted in search request exceptions for %s"
+ "Aligned %llu : %s to clock: %s"
+ "Applied retention policy to %llu enqueued messages."
+ "Applied retention policy to %llu staged messages."
+ "Applied retention policy to %llu stream events at %s."
+ "Applying removePersistentIdentifiers policy to clockId: %s"
+ "Asking host to vend staging access for extension: %s "
+ "Begin fetching sensitive conditions for logical clock: %s, root clock: %s"
+ "Begin processing reason:%s executionId:%s"
+ "Beginning ingest with extension: %s"
+ "Bootstrapped successfully at %s"
+ "COMPONENTNAME_CONTEXT_PREDICTOR"
+ "Calling ingest on %s"
+ "Can't get XPC connection for %s"
+ "Can't instantiate extension %s"
+ "Can't terminate: failed to get pid for %s"
+ "Checkpointing db at %s"
+ "Cleaning up abandoned clock identifiers: %s"
+ "Connection error to %s: %@"
+ "Consumed extension token: %s)"
+ "Creating instance at %s, readonly: %{bool}d"
+ "Deallocating"
+ "Detected %ld unique chatIds for clock %s, tagging as concurrent chat session"
+ "Directory %s doesn't exist and can't be created"
+ "Dropping provisional message for topic: %s on seed/customer images"
+ "Dropping provisional message: %@ on seed/customer images"
+ "Dropping provisional message: %s for seed/customer images"
+ "Emitting redaction summary for %s"
+ "End fetching sensitive conditions for logical clock: %s"
+ "End processing with processedMessages: %llu of total staged: %llu"
+ "Ending open span for %s start: %llu end: %llu"
+ "Error applying %s protections to: %s, error:%@"
+ "Error applying purge policy: %@"
+ "Error applying retention policy: %@"
+ "Error applying retention policy: %@ at %s"
+ "Error checkpointing StagingPool: %@"
+ "Error checkpointing: %@"
+ "Error getting extension process for %s"
+ "Error ingesting with %s"
+ "Error mapping tag record: %@"
+ "Error querying extensions: %@"
+ "Error serializing tag: %@"
+ "Error updating tag: %@"
+ "Error with remoteObjectProxy: %@"
+ "Even worse, they have the same TextExecutionEnd with the same timestamp: %llu and %llu"
+ "Extension %s will be terminated because it hit the hard timeout"
+ "Extension timed out and terminated: %s"
+ "Extension timed out: %s, error: %@"
+ "FBF storage failed with: %@"
+ "Failed processing message of type %s due to %@"
+ "Failed to alter %s."
+ "Failed to bootstrap: %@"
+ "Failed to bootstrap: %@ at %s"
+ "Failed to connect to db at: %s with error: %@"
+ "Failed to create new indexes for %s, failing alter."
+ "Failed to create or alter table schema for %s"
+ "Failed to create or alter table: %s"
+ "Failed to drop unexpected indexes for %s, failing alter."
+ "Failed to emit telemetry: %@"
+ "Failed to get kern.bootsessionuuid: %s"
+ "Failed to init with: %@"
+ "Failed to open path: %s"
+ "Failed to prepare for message staging %s"
+ "Failed to prune table: %s"
+ "Failed to register for %s"
+ "Failed to store sensitive condition %s startedAt: %llu to metastore"
+ "Fall through to approved for %@"
+ "Found %ld ingestion extensions."
+ "Found %ld open clock records."
+ "Found multiple user request tags for requestId: %s. Data will not be annotated."
+ "Found sensitive conditions: %s for logical clock: %s"
+ "Found sensitive conditions: <none> for logical clock: %s"
+ "Found user request tag for %s"
+ "Found user request tag: <none> for %s"
+ "Ignoring infeasible timestamp: %llu, substituting with: %llu"
+ "Ingestion extension does not implement protocol: %s"
+ "Integration step finished, %llu messages integrated to staging"
+ "Issued extension for path: %s, readonly: %{bool}d)"
+ "Mapping composite predicate for %s to old clock scoped predicate. This represents a loss in fidelity."
+ "Marking processed for clockIdentifiers: %s"
+ "Message did not wrap as AnyEvent: %@"
+ "Metastore storage: %s"
+ "Moving %s to %s..."
+ "Multiple closed clocks: %s contain timestamp: %llu"
+ "No aligned logical clock found for %llu : %s"
+ "No beginning span found for: %s"
+ "No clock record found for %s"
+ "No componentIdentifier on %@, returning approved."
+ "No existing schema found for %s, creating."
+ "No intersecting tags causing a suppression for %@ on %s"
+ "No new columns for %s, skipping alter."
+ "No tags found for clockId %s"
+ "No tags found."
+ "Not applying removePersistentIdentifiers policy to clockId: %s"
+ "Not applying removePersistentIdentifiers policy to clockId: %s due to error: %@"
+ "Not tagging clockId: %s because user is opted in to Siri data collection"
+ "Not tagging clockId: %s due to error: %@"
+ "Not tailing messages to syslog (internal image: %{bool}d, tailing preference enabled:%{bool}d"
+ "Notifying name:%s with state: %s"
+ "Orchestrator failed with %@"
+ "Per-proxy XPC error; invalidating: %@"
+ "Pruning stream %s with max age: %f seconds"
+ "Pruning stream %s with max size: %llu bytes"
+ "Purged %llu enqueued messages."
+ "Purged %llu staged messages."
+ "Queued message: %s could not be fetched for packaging"
+ "Queued message: %s could not unwrap TLUT"
+ "Queued message: %s was lacking a logical timestamp"
+ "Queued message: %s was lacking a logical timestamp and could not unwrap TLUT"
+ "RBS request failed: %@"
+ "RBS request termination for process: %d"
+ "Received notification for %s"
+ "Released extension token: %s)"
+ "Resolved clockIds: %s for uploadEvent: %@"
+ "Resolved componentId: %@ for uploadEvent: %@"
+ "RuntimeXPCClient idle timer fired; tearing down connection"
+ "SUTSchemaTestExecutionEvent event types unknown: %lu"
+ "Saving component: %s, component Id: %s, clusterIdentifier: %s, startedOn: %llu, onClock: %s"
+ "StagedMessage of anyEventType: %s did not have a timestamp, dropping event"
+ "Stream access vending is disabled. Internal is %{bool}d"
+ "Stream access vending is disabled. IsInternalInstall: %{bool}d"
+ "Suppressing large upload for %@ on %s"
+ "Suppressing large upload for fuzzed requestID: %s on %s"
+ "Suppressing message of type %s from off-device due to %s"
+ "Suppressing message of type %s from on-device and off-device due to %s"
+ "Suppressing message of type %s from on-device due to %s"
+ "Suppressing provisional collection internalInstall: %{bool}d seedBuild: %{bool}d."
+ "Tagging clockId: %s as opted out for Siri data collection"
+ "Two TextExecutionBegin events have the same timestamp: %llu and %llu"
+ "Unable to create directory at %s"
+ "Unable to determine clockId for %@, indeterminate response."
+ "Unable to find clock start for bookmark: %llu"
+ "Unable to get current state for %s"
+ "Unable to infer tag for %s"
+ "Unable to infer wrapped type for %s"
+ "Unable to remove %s"
+ "Unable to set page_size to %ld"
+ "Unable to stage message: %@"
+ "Unable to wrap %@ as AnyEvent"
+ "Unexpected error: Fingerprint for range %s doesn't exist."
+ "Unknown tag space: %u"
+ "Unknown topic: %s, ignoring message."
+ "Unmatched TestExecutionEnd for fingerprint: %s"
+ "Unmatched TestExecutionEnd for malformed fingerprint Data: %s"
+ "applied %ld transforms across %ld classifications to %s"
+ "assistantd XPC connection interrupted"
+ "assistantd XPC connection invalidated"
+ "com.apple.aiml.siri.platform.ConnectedComponentsWrapper"
+ "conditionType: %s for requestId: %s affects subsequent requests: %s"
+ "db storage connected at: %s"
+ "error: %d extended: %d"
+ "error: %d extended: %d description: %s"
+ "execution: %s step: %s at %lldns"
+ "ingest()"
+ "processing text classifications for %s on clock %s"
+ "prune failed"
+ "setting up notify: %s"
- " affecting entire clock"
- " affects subsequent requests: "
- " as opted out for Siri data collection"
- " because user is opted in to Siri data collection"
- " bootSessionUUID:"
- " classifications to "
- " contain timestamp: "
- " could not be fetched for packaging"
- " could not unwrap TLUT"
- " did not have a timestamp, dropping event"
- " doesn't exist and can't be created"
- " enqueued messages."
- " for logical clock: "
- " for requestId: "
- " for seed/customer images"
- " for uploadEvent: "
- " from off-device due to "
- " from on-device and off-device due to "
- " from on-device due to "
- " ingestion extensions."
- " messages integrated to staging"
- " of total staged: "
- " on seed/customer images"
- " open clock records."
- " protections to: "
- " redaction summaries accumulated."
- " staged messages."
- " stream events at "
- " to old clock scoped predicate. This represents a loss in fidelity."
- " to vend staging access for extension: "
- " transforms across "
- " unique chatIds for clock "
- " was lacking a logical timestamp"
- " was lacking a logical timestamp and could not unwrap TLUT"
- " will be terminated because it hit the hard timeout"
- " with max size: "
- "%@.analytics.xpc.connection"
- ", UnilogMigration: "
- ", clusterIdentifier: "
- ", component Id: "
- ", failing alter."
- ", ignoring message."
- ", indeterminate response."
- ", returning approved."
- ", substituting with: "
- ", tagging as concurrent chat session"
- ", tailing preference enabled:"
- "-[SiriAnalyticsXPCConnection _createTag:completion:]_block_invoke_3"
- "-[SiriAnalyticsXPCConnection _sensitiveCondition:startedAt:completion:]"
- "-[SiriAnalyticsXPCConnection _sensitiveCondition:startedAt:completion:]_block_invoke"
- "-[SiriAnalyticsXPCConnection barrierWithCompletion:]"
- "-[SiriAnalyticsXPCConnection barrierWithCompletion:]_block_invoke"
- ". Data will not be annotated."
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Assistant/Privacy/DataSharingOptOutDataCollectionPolicy.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Assistant/Privacy/PersistentIdentifiersDataCollectionPolicy.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Assistant/Privacy/UserHistoryDeletionRequestObserver.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Assistant/Privacy/UserHistoryPolicy.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/ExtensionOrchestration/ExtensionConnection.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/ExtensionOrchestration/ExtensionOrchestratorConnection.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/ExtensionOrchestration/IngestionExtension.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/ExtensionOrchestration/Orchestrator.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/MessageTopics/DirectUploadTopic.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/MessageTopics/OnDeviceSyndicationTopic.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/MessageTopics/PackagedUploadTopic.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/MessageTopics/TailToOSLog.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Preprocessing/ClockInactivityScheduler.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Preprocessing/DataCollectionPolicyResolver.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Preprocessing/ExternalDataIngestion.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Preprocessing/LargeMessageUploadProcessor.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Preprocessing/MessageProcessingStrategy.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Preprocessing/MetadataExtractor.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Preprocessing/Preprocessor.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Preprocessing/PreprocessorShim.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Preprocessing/SUTProcessor.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Preprocessing/SensitiveConditionsProcessor.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Preprocessing/SessionBoundIdDetector.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Preprocessing/TextClassificationProcessor.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Preprocessing/UserRequestAnnotator.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/SensitiveConditions/SensitiveConditionsLedger.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Services/LogicalClocks.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Services/RuntimeService.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Services/TaggingService.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/DataVault.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Db/DbStorage.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Db/DbTableDefinition.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Metastore/Db/LogicalClockRecord.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Metastore/Db/MetastoreDb+Clocks.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Metastore/Db/MetastoreDb+Tags.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Metastore/Db/MetastoreDb.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Metastore/MetastoreStreams.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Metastore/Stream/MetastoreStream+Clocks.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Metastore/Stream/MetastoreStream.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/OffDevice/MessageStoreReader.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/OffDevice/OffDeviceStorage.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/OffDevice/PackagingQueue+Policy.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/OffDevice/PackagingQueue.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/OffDevice/PackagingQueueProcessor.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/OnDevice/Biome/PrivateBiomeStreamPruner.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/OnDevice/Biome/RawUnifiedStream.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/OnDevice/Biome/UnifiedMessageStreamHelper.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/PersistentStorage.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/ResourceAccessDemands/MetastoreStreamsAccessDemand.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/ResourceAccessDemands/PackagingStreamAccessDemand.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/ResourceAccessDemands/RawUnifiedMessageStreamAccessDemand.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/ResourceAccessDemands/UnifiedMessageStreamAccessDemand.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/SandboxExtension.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Staging/Pool/StagingPool.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Staging/StagedMessage+Mapping.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Staging/Stream/MessageStagingProvider+Policies.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Staging/Stream/MessageStagingProvider.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Storage/Staging/Stream/MessageStagingStream.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Tagging/TagExpander.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Tagging/TaggingLoggables.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Telemetry/PreprocessorTelemetry+Instrumentation.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Telemetry/PreprocessorTelemetry.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Utility/DarwinNotificationObserver.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Utility/DeviceClock.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Utility/FirstUnlockObserver.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Utility/Protobuf/ProtoUnionTypeDomain.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriAnalytics/SiriAnalytics/Utility/RuntimeConfiguration.swift"
- "ABE_CLIENT_EVENT"
- "ABE_SERVER_EVENT"
- "ACTIVATION_CLIENT_EVENT"
- "ANC_CLIENT_EVENT"
- "ANC_SERVER_EVENT"
- "APCT_CLIENT_EVENT"
- "ASR_CLIENT_EVENT"
- "ASR_SPEECH_PROFILE_CLIENT_EVENT"
- "ASV_CLIENT_EVENT"
- "Access vending is disabled. Internal is "
- "Adding new columns for component_identifiers: "
- "Adding new columns for logical_clocks: "
- "Adding new columns for tags: "
- "Adding opted in search request exceptions for "
- "Applied retention policy to "
- "Applying removePersistentIdentifiers policy to clockId: "
- "Begin fetching sensitive conditions for logical clock: "
- "Begin processing reason:"
- "Beginning ingest with extension: "
- "Bootstrapped successfully at "
- "CAAR_CLIENT_EVENT"
- "CAM_CLIENT_EVENT"
- "CDA_CLIENT_EVENT"
- "CH_CLIENT_EVENT"
- "CLOUDKIT_CLIENT_EVENT"
- "CLP_CLIENT_EVENT"
- "CM_CLIENT_EVENT"
- "CNV_CLIENT_EVENT"
- "COLS_CLIENT_EVENT"
- "CONTEXTRETRIEVAL_CLIENT_EVENT"
- "CPR_CLIENT_EVENT"
- "Calling ingest on "
- "Can't get XPC connection for "
- "Can't instantiate extension "
- "Can't terminate: failed to get pid for "
- "Checkpointing db at "
- "Cleaning up abandoned clock identifiers: "
- "Connection error to "
- "Consumed extension token: "
- "Creating instance at "
- "DAILY_DEVICE_STATUS"
- "DATA_UPLOAD_EVENT"
- "DELETE_HISTORY_TRIGGER_SERVER_EVENT"
- "DER_CLIENT_EVENT"
- "DFI_DATA_EVENT"
- "DIALOGENGINE_CLIENT_EVENT"
- "DIM_CLIENT_EVENT"
- "DODML_CLIENT_EVENT"
- "Dropping provisional message for topic: "
- "Dropping provisional message: "
- "ES_CLIENT_EVENT"
- "EXECUTOR_CLIENT_EVENT"
- "EXP_SEARCH_CLIENT_EVENT"
- "EXP_SIRI_CLIENT_EVENT"
- "EXP_SIRI_SERVER_EVENT"
- "Emitting redaction summary for "
- "End fetching sensitive conditions for logical clock: "
- "End processing with processedMessages: "
- "Ending open span for "
- "Error applying purge policy: "
- "Error applying retention policy: "
- "Error checkpointing StagingPool: "
- "Error checkpointing: "
- "Error getting extension process for "
- "Error ingesting with "
- "Error mapping tag record: "
- "Error querying extensions: "
- "Error serializing tag: "
- "Error updating tag: "
- "Error with remoteObjectProxy: "
- "Even worse, they have the same TextExecutionEnd with the same timestamp: "
- "Extension timed out and terminated: "
- "Extension timed out: "
- "FBF storage failed with: "
- "FLOWTOOLS_CLIENT_EVENT"
- "FLOW_CLIENT_EVENT"
- "FLOW_LINK_CLIENT_EVENT"
- "FLOW_SERVER_EVENT"
- "FL_CLIENT_EVENT"
- "FTD_CLIENT_EVENT"
- "Failed processing message of type "
- "Failed to alter component_identifiers."
- "Failed to alter logical_clocks."
- "Failed to alter tags."
- "Failed to bootstrap: "
- "Failed to connect to db at: "
- "Failed to create new indexes for "
- "Failed to create or alter table schema for component_identifiers"
- "Failed to create or alter table schema for logical_clocks"
- "Failed to create or alter table schema for tags"
- "Failed to create or alter table: "
- "Failed to drop unexpected indexes for "
- "Failed to emit telemetry: "
- "Failed to get kern.bootsessionuuid: "
- "Failed to init with: "
- "Failed to open path: "
- "Failed to prepare for message staging "
- "Failed to prune table: "
- "Failed to register for "
- "Failed to store sensitive condition "
- "Fall through to approved for "
- "Found multiple user request tags for requestId: "
- "Found sensitive conditions: "
- "Found sensitive conditions: <none> for logical clock: "
- "Found user request tag for "
- "Found user request tag: <none> for "
- "GAA_CLIENT_EVENT"
- "GAT_CLIENT_EVENT"
- "GMS_CLIENT_EVENT"
- "GROUPED_MESSAGES_CLIENT_EVENT"
- "GROUPED_MESSAGES_GROUPING"
- "GROUPED_MESSAGES_PRODUCER_METADATA"
- "GROUPED_MESSAGES_SERVER_EVENT"
- "GRR_CLIENT_EVENT"
- "HAL_CLIENT_EVENT"
- "HOMEKIT_CLIENT_EVENT"
- "HOME_CLIENT_EVENT"
- "IA_CLIENT_EVENT"
- "IDENTITY_CLIENT_EVENT"
- "IFTMGR_CLIENT_EVENT"
- "IFT_CLIENT_EVENT"
- "IF_PLATFORM_CLIENT_EVENT"
- "IF_PLATFORM_REQUEST_CLIENT_EVENT"
- "IH_CLIENT_EVENT"
- "INFERENCE_CLIENT_EVENT"
- "Ignoring infeasible timestamp: "
- "Ingestion extension does not implement protocol: "
- "Integration step finished, "
- "Issued extension for path: "
- "JR_CLIENT_EVENT"
- "LOG_REDACTION_CLIENT_EVENT"
- "MH_CLIENT_EVENT"
- "MT_CLIENT_EVENT"
- "MT_CLIENT_EVENT_V2"
- "MWT_CLIENT_EVENT"
- "Mapping composite predicate for "
- "Marking processed for clockIdentifiers: "
- "Message did not wrap as AnyEvent: "
- "Metastore storage: "
- "Multiple closed clocks: "
- "NET_CLIENT_EVENT"
- "NLG_CLIENT_EVENT"
- "NLROUTER_CLIENT_EVENT"
- "NLX_CLIENT_EVENT"
- "No aligned logical clock found for "
- "No beginning span found for: "
- "No clock record found for "
- "No componentIdentifier on "
- "No existing schema found for component_identifiers, creating."
- "No existing schema found for logical_clocks, creating."
- "No existing schema found for tags, creating."
- "No intersecting tags causing a suppression for "
- "No new columns for component_identifiers, skipping alter."
- "No new columns for logical_clocks, skipping alter."
- "No new columns for tags, skipping alter."
- "No tags found for clockId "
- "Not applying removePersistentIdentifiers policy to clockId: "
- "Not tagging clockId: "
- "Not tailing messages to syslog (internal image: "
- "ODBATCH_CLIENT_EVENT"
- "ODD_SIRI_CLIENT_EVENT"
- "ODFUNNEL_SIRI_CLIENT_EVENT"
- "ODM_SIRI_CLIENT_EVENT"
- "ODSAMPLE_CLIENT_EVENT"
- "OPAQUE_CLIENT_EVENT"
- "OPT_IN_CHANGELOG_CLIENT_EVENT"
- "OPT_IN_CLIENT_EVENT"
- "OPT_IN_PROPAGATION_CLIENT_EVENT"
- "ORCH_CLIENT_EVENT"
- "ORDERED_ANY_EVENT"
- "Orchestrator failed with "
- "PEGASUS_SERVER_EVENT"
- "PFA_CLIENT_EVENT"
- "PG_CLIENT_EVENT"
- "PLANNERTOOL_CLIENT_EVENT"
- "PLANNER_CLIENT_EVENT"
- "PLUS_CLIENT_EVENT"
- "PNR_ON_DEVICE_CLIENT_EVENT"
- "POMMES_CLIENT_EVENT"
- "PROACTIVE_EVENT_TRACKER"
- "PROVISIONAL_EVENT"
- "PR_CLIENT_EVENT"
- "PSE_CLIENT_EVENT"
- "QUERY_DECORATION_CLIENT_EVENT"
- "Queued message: "
- "RBS request failed: "
- "RBS request termination for process: "
- "READ_CLIENT_EVENT"
- "REQUEST_LINK_EVENT"
- "RESOLVE_CLIENT_EVENT"
- "RESPONSETOOLS_CLIENT_EVENT"
- "RFG_CLIENT_EVENT"
- "RF_CLIENT_EVENT"
- "RG_CLIENT_EVENT"
- "RR_CLIENT_EVENT"
- "RSS_CLIENT_EVENT"
- "RTS_CLIENT_EVENT"
- "Received notification for "
- "Released extension token: "
- "Resolved clockIds: "
- "Resolved componentId: "
- "RuntimeConfiguration"
- "SAD_CLIENT_EVENT"
- "SAM_SERVER_EVENT"
- "SA_CLIENT_EVENT"
- "SC_CLIENT_EVENT"
- "SEARCH_TOOL_CLIENT_EVENT"
- "SERVER_ORDERED_ANY_EVENT"
- "SERVER_REQUEST_LINK_EVENT"
- "SESSION_BYTE_EVENT"
- "SESSION_EVENT"
- "SIC_CLIENT_EVENT"
- "SIRIXAGENT_CLIENT_EVENT"
- "SIRI_SERVER_ORDERED_ANY_EVENT"
- "SIRI_SETUP_CLIENT_EVENT"
- "SIRI_UNDER_TEST_EVENT"
- "SKIMMER_CLIENT_EVENT"
- "SMT_CLIENT_EVENT"
- "SPANMATCH_CLIENT_EVENT"
- "SPEECH_DONATION_EVENT"
- "SRST_CLIENT_EVENT"
- "SR_CLIENT_EVENT"
- "SUGGESTIONS_CLIENT_EVENT"
- "SUTSchemaTestExecutionEvent event types unknown: "
- "Saving component: "
- "StagedMessage of anyEventType: "
- "Stream access vending is disabled. Internal is false"
- "Stream access vending is disabled. IsInternalInstall: "
- "Suppressing large upload for "
- "Suppressing large upload for fuzzed requestID: "
- "Suppressing message of type "
- "Suppressing provisional collection internalInstall: "
- "TA_CLIENT_EVENT"
- "TMSTURN_CLIENT_EVENT"
- "TMS_CLIENT_EVENT"
- "TRP_REQUEST_LINK_CLIENT_EVENT"
- "TR_CLIENT_EVENT"
- "TTM_CLIENT_EVENT"
- "TTS_CLIENT_EVENT"
- "Tagging clockId: "
- "Two TextExecutionBegin events have the same timestamp: "
- "UAF_CLIENT_EVENT"
- "UEI_CLIENT_EVENT"
- "UEI_SERVER_EVENT"
- "UInt64TieBreaker(_:_:)"
- "UNIFIED_SIRI_PERFORMANCE_EVENT"
- "UNKNOWN_EVENT"
- "Unable to create directory at "
- "Unable to determine clockId for "
- "Unable to find clock start for bookmark: "
- "Unable to get current state for "
- "Unable to infer tag for "
- "Unable to infer wrapped type for "
- "Unable to remove "
- "Unable to set page_size to "
- "Unable to stage message: "
- "Unexpected error: Fingerprint for range "
- "Unknown tag space: "
- "Unmatched TestExecutionEnd for fingerprint: "
- "Unmatched TestExecutionEnd for malformed fingerprint Data: "
- "[%s: %s] %s"
- "add(timestamp:message:)"
- "annotate(orderedEvent:)"
- "anyEvent.%@"
- "append(_:topic:)"
- "append(attributes:message:)"
- "append(message:)"
- "applySensitiveConditions(tags:logicalTimestamp:anyEvent:)"
- "applyStorageProtections()"
- "applyStorageRetentionPolicy()"
- "byteSize"
- "cleanupAbandonedClocks(activeClockIdentifier:)"
- "clockAge"
- "clockForcefullyDestroyed(completion:)"
- "com.apple.siri.analytics.stream.xpc"
- "createClock(_:rootClockIdentifier:bootSessionUUID:startedOn:)"
- "createInactivityTimer(job:completion:)"
- "createOrAlter(db:)"
- "createOrAlterTableSchema(db:)"
- "createTag(tagId:tag:onClock:)"
- "currentBootSessionUUID()"
- "db storage connected at: "
- "destroyInactivityTimer()"
- "end(sensitiveCondition:at:)"
- "endClock(_:endedOn:endedReason:)"
- "endClock(clockIdentifier:endedOn:reason:)"
- "ensureDbConnected(bootstrapping:)"
- "ensureDirectoryExists(at:)"
- "execute(_:parameters:)"
- "expand(tags:clockIdentifier:rootClockIdentifier:)"
- "failureReason"
- "fetch(sinceBookmark:receiveMessage:completion:)"
- "fetchClockRecords(predicate:)"
- "firstPassAnalysis(processors:messageStaging:)"
- "handleConnectionError(_:)"
- "handleNotification()"
- "hourOfDay"
- "ingest(identity:)"
- "init(logicalClocks:tags:componentIds:textDataClassifications:)"
- "init(name:queue:onNotify:)"
- "init(streamURL:dataProtectionClass:readonly:)"
- "isolated"
- "issue(auditToken:url:readonly:)"
- "killSwitchEnabled(_:)"
- "map(deviceSensitivityState:)"
- "markProcessed(clockIdentifiers:)"
- "meetsDemand(entitlements:readonly:)"
- "messageCount"
- "onDeleteRequest()"
- "prepareForStaging(_:allClocks:)"
- "prepareStatement(sql:parameters:)"
- "process(clockId:nanosecondsSinceBoot:message:)"
- "process(messages:)"
- "process(orderedEvent:end:)"
- "process(reason:)"
- "process(tlut:logicalTimestamp:)"
- "process(uploadEvent:requestIdentifier:)"
- "processMessage(_:telemetry:metadataExtractor:sensitiveConditionsProcessor:sutProcessor:textPreprocessor:userRequestAnnotator:)"
- "processing text classifications for "
- "pulseClock(_:lastEventOn:)"
- "pulseClock(bookmark:lastEventOn:)"
- "purgePackagingMessages()"
- "purgeStagedMessages()"
- "reason"
- "removePersistentIdentifiers"
- "resolve(dataClassifications:)"
- "rootClockCreated(rootClockIdentifier:)"
- "send(runtimeEvents:)"
- "sensitiveConditions(for:)"
- "setting up notify: "
- "start(clockIdentifier:type:bootSessionUUID:startedOn:)"
- "start(sensitiveCondition:at:)"
- "startObserving()"
- "success"
- "tail(timestamp:clockIdentifier:messageUUID:message:)"
- "terminate(reason:)"
- "trigger(reason:completion:)"
- "unknown"
- "updateTag(tagId:tag:)"
- "userRequestTag(clusterId:clockIdentifier:)"
- "v32@?0@\"SiriAnalyticsDerivativeClock\"8Q16^B24"
```
