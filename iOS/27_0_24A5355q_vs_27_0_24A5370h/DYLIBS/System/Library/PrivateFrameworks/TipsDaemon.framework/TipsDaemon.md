## TipsDaemon

> `/System/Library/PrivateFrameworks/TipsDaemon.framework/TipsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__bss` | `0x2110` | `0x1c10` | **`-0x500`** |
| `__TEXT.__text` | `0x9f000` | `0x9ebb0` | **`-0x450`** |
| `__TEXT.__const` | `0x35f8` | `0x3218` | **`-0x3e0`** |
| `__DATA.__bss` | `0x2130` | `0x1e30` | **`-0x300`** |
| `__TEXT.__swift5_typeref` | `0x1258` | `0x1188` | **`-0xd0`** |
| `__AUTH.__objc_data` | `0x1060` | `0x1110` | **`+0xb0`** |
| `__TEXT.__swift5_assocty` | `0x2b0` | `0x218` | **`-0x98`** |
| `__TEXT.__unwind_info` | `0x2d80` | `0x2cf0` | **`-0x90`** |
| `__TEXT.__swift5_reflstr` | `0x6de` | `0x65e` | **`-0x80`** |
| `__AUTH_CONST.__const` | `0x28a0` | `0x2838` | **`-0x68`** |
| `__DATA_DIRTY.__data` | `0x1020` | `0xfc0` | **`-0x60`** |
| `__AUTH_CONST.__objc_const` | `0x80b0` | `0x80f8` | **`+0x48`** |
| `__TEXT.__cstring` | `0x433c` | `0x42fc` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x1354` | `0x1394` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x21c` | `0x1dc` | **`-0x40`** |
| `__DATA.__data` | `0x940` | `0x908` | **`-0x38`** |
| `__TEXT.__eh_frame` | `0x4c1c` | `0x4be8` | **`-0x34`** |
| `__TEXT.__swift5_fieldmd` | `0x988` | `0x954` | **`-0x34`** |
| `__TEXT.__objc_methlist` | `0x3848` | `0x3878` | **`+0x30`** |
| `__AUTH.__data` | `0xf0` | `0x118` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1e40` | `0x1e68` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1268` | `0x1248` | **`-0x20`** |
| `__AUTH_CONST.__cfstring` | `0x29e0` | `0x2a00` | **`+0x20`** |
| `__DATA_DIRTY.__common` | `0x30` | `0x18` | **`-0x18`** |
| `__TEXT.__swift_as_entry` | `0x154` | `0x13c` | **`-0x18`** |
| `__TEXT.__constg_swiftt` | `0xe74` | `0xe88` | **`+0x14`** |
| `__TEXT.__swift5_builtin` | `0xdc` | `0xf0` | **`+0x14`** |
| `__DATA_CONST.__got` | `0xd30` | `0xd20` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2688` | `0x2678` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x214` | `0x204` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x528` | `0x530` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x744` | `0x748` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x434` | `0x430` | **`-0x4`** |

### Other Changes

```diff

-850.0.0.0.0
+853.0.0.0.0

-  Functions: 3346
-  Symbols:   3468
+  Functions: 3301
+  Symbols:   3448
Symbols:
+ -[TPSTipsManager reindexAllSearchableItemsForScope:completionHandler:]
+ -[TPSTipsManager reindexSearchableItemsWithIdentifiers:scope:completionHandler:]
+ _OBJC_CLASS_$_TPSGenerativeModelsExcludeChinaEligibilityValidation
+ _OBJC_METACLASS_$_TPSGenerativeModelsExcludeChinaEligibilityValidation
+ __DATA_TPSGenerativeModelsExcludeChinaEligibilityValidation
+ __INSTANCE_METHODS_TPSGenerativeModelsExcludeChinaEligibilityValidation
+ __METACLASS_DATA_TPSGenerativeModelsExcludeChinaEligibilityValidation
+ ___70-[TPSTipsManager reindexAllSearchableItemsForScope:completionHandler:]_block_invoke
+ ___70-[TPSTipsManager reindexAllSearchableItemsForScope:completionHandler:]_block_invoke_2
+ ___block_descriptor_112_e8_32s40s48bs56r64r72r80r88r96r104r_e113_v64?0"TPSCollection"8"NSArray"16"NSDictionary"24"NSDictionary"32"NSDictionary"40"NSDictionary"48"NSSet"56lr56l8r64l8r72l8r80l8r88l8r96l8r104l8s32l8s40l8s48l8
+ ___block_descriptor_136_e8_32s40s48s56r64r72r80r88r96r104r112r120r128w_e24_v16?0?<v?"NSError">8lw128l8s32l8r56l8r64l8s40l8s48l8r72l8r80l8r88l8r96l8r104l8r112l8r120l8
+ ___block_descriptor_32_e24_v16?0?<v?"NSError">8l
+ ___block_descriptor_48_e8_32s40w_e24_v16?0?<v?"NSError">8lw40l8s32l8
+ ___block_descriptor_56_e8_32s40r48w_e24_v16?0?<v?"NSError">8lw48l8s32l8r40l8
+ ___block_descriptor_64_e8_32r40r48r56w_e24_v16?0?<v?"NSError">8lw56l8r32l8r40l8r48l8
+ ___block_descriptor_72_e8_32s40bs48r56r64w_e5_v8?0lw64l8s32l8s40l8r48l8r56l8
+ ___block_descriptor_80_e8_32s40s48r56r64r72w_e24_v16?0?<v?"NSError">8lw72l8r48l8s32l8r56l8s40l8r64l8
+ ___block_descriptor_80_e8_32s40s48s56s64r72w_e24_v16?0?<v?"NSError">8lw72l8s32l8s40l8s48l8s56l8r64l8
+ ___block_descriptor_88_e8_32s40s48r56r64r72r80w_e24_v16?0?<v?"NSError">8lw80l8r48l8r56l8s32l8r64l8s40l8r72l8
+ ___block_descriptor_88_e8_32s40s48r56r64r72r80w_e24_v16?0?<v?"NSError">8lw80l8s32l8r48l8r56l8r64l8r72l8s40l8
+ _kTPSCapabilityGenerativeModelsExcludeChinaEligibility
+ _symbolic _____ 10TipsDaemon49GenerativeModelsExcludeChinaEligibilityValidationC
+ _symbolic _____ So22TPSSpotlightIndexScopeV
- -[TPSTipsManager reindexAllSearchableItemsWithCompletionHandler:]
- -[TPSTipsManager reindexSearchableItemsWithIdentifiers:completionHandler:]
- ___65-[TPSTipsManager reindexAllSearchableItemsWithCompletionHandler:]_block_invoke
- ___65-[TPSTipsManager reindexAllSearchableItemsWithCompletionHandler:]_block_invoke_2
- ___block_descriptor_112_e8_32s40bs48r56r64r72r80r88r96r104w_e113_v64?0"TPSCollection"8"NSArray"16"NSDictionary"24"NSDictionary"32"NSDictionary"40"NSDictionary"48"NSSet"56lw104l8r48l8r56l8r64l8r72l8r80l8r88l8r96l8s32l8s40l8
- ___block_descriptor_144_e8_32s40s48s56s64r72r80r88r96r104r112r120r128r136w_e24_v16?0?<v?"NSError">8ls32l8s40l8r64l8r72l8s48l8s56l8w136l8r80l8r88l8r96l8r104l8r112l8r120l8r128l8
- ___block_descriptor_48_e8_32r40r_e24_v16?0?<v?"NSError">8lr32l8r40l8
- ___block_descriptor_48_e8_32s40s_e24_v16?0?<v?"NSError">8ls32l8s40l8
- ___block_descriptor_64_e8_32s40r48r56r_e24_v16?0?<v?"NSError">8ls32l8r40l8r48l8r56l8
- ___block_descriptor_72_e8_32s40bs48r56r64w_e5_v8?0lw64l8r48l8r56l8s32l8s40l8
- ___block_descriptor_80_e8_32s40s48s56r64r72r_e24_v16?0?<v?"NSError">8ls32l8s40l8r56l8s48l8r64l8r72l8
- ___block_descriptor_80_e8_32s40s48s56s64s72r_e24_v16?0?<v?"NSError">8ls32l8s40l8s48l8s56l8s64l8r72l8
- ___block_descriptor_88_e8_32s40s48s56r64r72r80r_e24_v16?0?<v?"NSError">8lr56l8r64l8s32l8s40l8r72l8s48l8r80l8
- ___block_descriptor_96_e8_32s40s48s56r64r72r80r88w_e24_v16?0?<v?"NSError">8lw88l8s32l8s40l8r56l8r64l8r72l8r80l8s48l8
- ___swift_memcpy40_8
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV0cd5IndexG5QueryV10AppIntents0gI0AA0G0AfGP_AF0jG0
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV0cd5IndexG5QueryV10AppIntents0gI0AaF22DynamicOptionsProvider
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV0cd5IndexG5QueryV10AppIntents0gI0AaF24PersistentlyIdentifiable
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV0cd5IndexG5QueryV10AppIntents22DynamicOptionsProviderAA12DefaultValueAfGP_AF07_IntentP0
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV0cd5IndexG5QueryV10AppIntents22DynamicOptionsProviderAA6ResultAfGP_AF17ResultsCollection
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV0cd5IndexG5QueryV10AppIntents22DynamicOptionsProviderAaF09_SupportsJ12Dependencies
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents0H5ValueAaD07_IntentJ0
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents0H5ValueAaD24PersistentlyIdentifiable
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents0H5ValueAaD24TypeDisplayRepresentable
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents0fG0AaD0hG0
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents0hG0AA12DefaultQueryAdEP_AD0gK0
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents0hG0AA2IDs12IdentifiableP_AD0G21IdentifierConvertible
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents0hG0AAs12Identifiable
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents0hG0AaD0H5Value
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents0hG0AaD20DisplayRepresentable
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents12_IntentValueAA0K4TypeAdEP_AdE
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents12_IntentValueAA13SpecificationAdEP_AD08ResolverL0
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents12_IntentValueAA13UnwrappedTypeAdEP_AdE
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents20DisplayRepresentableAaD04TypejK0
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents20DisplayRepresentableAaD08InstancejK0
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityV10AppIntents28InstanceDisplayRepresentableAA10Foundation40CustomLocalizedStringResourceConvertible
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityVSHAASQ
- _associated conformance 10TipsDaemon33SupportFlowSpotlightIndexedEntityVs12IdentifiableAA2IDsADP_SH
- _symbolic Say_____G 10TipsDaemon33SupportFlowSpotlightIndexedEntityV
- _symbolic _____ 10TipsDaemon33SupportFlowSpotlightIndexedEntityV
- _symbolic _____ 10TipsDaemon33SupportFlowSpotlightIndexedEntityV0cd5IndexG5QueryV
- _symbolic _____y_____G 10AppIntents26EmptyResolverSpecificationV 10TipsDaemon33SupportFlowSpotlightIndexedEntityV
- _type_layout_string 10TipsDaemon33SupportFlowSpotlightIndexedEntityV
CStrings:
+ "682edd47056600c7201381fc486dbe9d46af560f"
+ "; nothing reindexed."
+ "Content fetch (scope "
+ "SupportFlow re-indexing completed (scope .supportFlow). "
+ "SupportFlow re-indexing failed (scope .supportFlow): "
+ "Tips re-indexing completed (scope .tips)."
+ "Tips re-indexing failed (scope .tips): "
+ "Unknown reindex scope "
+ "User Guide re-indexing completed (scope .tips)."
+ "User Guide re-indexing failed (scope .tips): "
+ "reindexAllSearchableItems(scope:contentFetcher:completionHandler:)"
- "13SupportFlowUI24SupportFlowSpotlightViewV"
- "Content fetch completed with error: "
- "HMT Collections re-indexing completed successfully. Re-indexed "
- "HMT Collections re-indexing completed with error: "
- "Name of Step-by-Step Help Spotlight Search Entity (not user facing)"
- "SUPPORT_FLOW_SPOTLIGHT_ENTITY_NAME"
- "Tips re-indexing completed successfully."
- "Tips re-indexing completed with error: "
- "User Guide re-indexing completed successfully."
- "User Guide re-indexing completed with error: "
- "reindexAllSearchableItems(contentFetcher:completionHandler:)"
```
