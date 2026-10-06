## toolkitd

> `/usr/libexec/toolkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x96c7c` | `0x99710` | **`+0x2a94`** |
| `__DATA_CONST.__const` | `0x3a00` | `0x4160` | **`+0x760`** |
| `__TEXT.__swift5_capture` | `0x914` | `0xc04` | **`+0x2f0`** |
| `__TEXT.__oslogstring` | `0x14dc` | `0x16cc` | **`+0x1f0`** |
| `__TEXT.__const` | `0x452c` | `0x463c` | **`+0x110`** |
| `__DATA.__bss` | `0x2420` | `0x2520` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x1ac0` | `0x1b38` | **`+0x78`** |
| `__TEXT.__auth_stubs` | `0x2c90` | `0x2d00` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x1807` | `0x184b` | **`+0x44`** |
| `__TEXT.__objc_stubs` | `0x1840` | `0x1880` | **`+0x40`** |
| `__DATA.__data` | `0x1d40` | `0x1d78` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x1650` | `0x1688` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x1124` | `0x1158` | **`+0x34`** |
| `__DATA_CONST.__auth_ptr` | `0x760` | `0x790` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x4c28` | `0x4c50` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0xdc4` | `0xde8` | **`+0x24`** |
| `__DATA.__objc_const` | `0x7d0` | `0x7f0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1188` | `0x11a8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x10b3` | `0x10d3` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xbe8` | `0xc00` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x370` | `0x384` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x1c4` | `0x1cc` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x120` | `0x128` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x164` | `0x16c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x154` | `0x158` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-5025.0.25.103.0
+5028.0.21.0.0

-  Functions: 2651
-  Symbols:   1245
-  CStrings:  561
+  Functions: 2755
+  Symbols:   1260
+  CStrings:  571
Symbols:
+ _$s11WorkflowKit04ToolB19IndexingCoordinatorCAA0cbD12CoordinatingAAWP
+ _$s11WorkflowKit27ImmediateIndexingControllerC11coordinator19appIntentsReadiness15staleRunTimeoutAcA04ToolbD12Coordinating_p_AA03ApphdI0_ps8DurationVtcfC
+ _$s11WorkflowKit27ImmediateIndexingControllerC11coordinator19appIntentsReadiness15staleRunTimeoutAcA04ToolbD12Coordinating_p_AA03ApphdI0_ps8DurationVtcfcfA1_
+ _$s11WorkflowKit27ImmediateIndexingControllerC13ensureIndexed7requesty19VoiceShortcutClient04ToolbD7RequestC_tYaKFTjTu
+ _$s11WorkflowKit27ImmediateIndexingControllerCMa
+ _$s11WorkflowKit27ImmediateIndexingControllerCMn
+ _$s11WorkflowKit35LNMetadataProviderIndexingReadinessVAA010AppIntentseF0AAWP
+ _$s11WorkflowKit35LNMetadataProviderIndexingReadinessVACycfC
+ _$s11WorkflowKit35LNMetadataProviderIndexingReadinessVMa
+ _$s19VoiceShortcutClient17DistnotedMatchingOMn
+ _$s19VoiceShortcutClient22ToolKitIndexingRequestC9immediateSbvg
+ _$s19VoiceShortcutClient24DistnotedMatchingTrustedOMn
+ _$s19VoiceShortcutClient37XPCDistributedNotificationEventStreamVMn
+ _$s19VoiceShortcutClient37XPCDistributedNotificationEventStreamVyxGAA08XPCEventG0AAMc
+ _$s19VoiceShortcutClient37XPCDistributedNotificationStreamEventV12notification10Foundation0E0Vvg
+ _$s7ToolKit12TypeInstanceO8deferredyA2CcACmFWC
+ _$s7ToolKit25LinkValueTransformContextV04linkD015sourceContainer34displayRepresentationConfiguration012localizationF016enumerationCases5depth24visitedEntityIdentifiers22typeDefinitionProvider017requestedPropertyS009filteringxS0ACSo7LNValueC_AA0iU0VAA07DisplaykL0VSo014WFLocalizationF0CSayAA015EnumerationCaseU0VGSgSiShySo18LNEntityIdentifierCGAA04TypeuV0_pShySSGA2_SgtcfC
+ _$s7ToolKit25LinkValueTransformContextV04linkD015sourceContainer34displayRepresentationConfiguration012localizationF016enumerationCases5depth24visitedEntityIdentifiers22typeDefinitionProvider017requestedPropertyS009filteringxS0ACSo7LNValueC_AA0iU0VAA07DisplaykL0VSo014WFLocalizationF0CSayAA015EnumerationCaseU0VGSgSiShySo18LNEntityIdentifierCGAA04TypeuV0_pShySSGA2_SgtcfcfA4_
+ _$s7ToolKit25LinkValueTransformContextV04linkD015sourceContainer34displayRepresentationConfiguration012localizationF016enumerationCases5depth24visitedEntityIdentifiers22typeDefinitionProvider017requestedPropertyS009filteringxS0ACSo7LNValueC_AA0iU0VAA07DisplaykL0VSo014WFLocalizationF0CSayAA015EnumerationCaseU0VGSgSiShySo18LNEntityIdentifierCGAA04TypeuV0_pShySSGA2_SgtcfcfA5_
+ _$s7ToolKit25LinkValueTransformContextV04linkD015sourceContainer34displayRepresentationConfiguration012localizationF016enumerationCases5depth24visitedEntityIdentifiers22typeDefinitionProvider017requestedPropertyS009filteringxS0ACSo7LNValueC_AA0iU0VAA07DisplaykL0VSo014WFLocalizationF0CSayAA015EnumerationCaseU0VGSgSiShySo18LNEntityIdentifierCGAA04TypeuV0_pShySSGA2_SgtcfcfA7_
+ _$sScP13userInitiatedScPvgZ
- _$s19VoiceShortcutClient37XPCDistributedNotificationEventStreamV0F0V12notification10Foundation0E0Vvg
- _$s19VoiceShortcutClient37XPCDistributedNotificationEventStreamVAA08XPCEventG0AAMc
- _$s19VoiceShortcutClient37XPCDistributedNotificationEventStreamVMa
- _$s7ToolKit25LinkValueTransformContextV04linkD015sourceContainer34displayRepresentationConfiguration012localizationF016enumerationCases5depth24visitedEntityIdentifiers22typeDefinitionProviderACSo7LNValueC_AA0iU0VAA07DisplaykL0VSo014WFLocalizationF0CSayAA015EnumerationCaseU0VGSgSiShySo18LNEntityIdentifierCGAA04TypeuV0_ptcfC
- _$s7ToolKit25LinkValueTransformContextV04linkD015sourceContainer34displayRepresentationConfiguration012localizationF016enumerationCases5depth24visitedEntityIdentifiers22typeDefinitionProviderACSo7LNValueC_AA0iU0VAA07DisplaykL0VSo014WFLocalizationF0CSayAA015EnumerationCaseU0VGSgSiShySo18LNEntityIdentifierCGAA04TypeuV0_ptcfcfA4_
- _$s7ToolKit25LinkValueTransformContextV04linkD015sourceContainer34displayRepresentationConfiguration012localizationF016enumerationCases5depth24visitedEntityIdentifiers22typeDefinitionProviderACSo7LNValueC_AA0iU0VAA07DisplaykL0VSo014WFLocalizationF0CSayAA015EnumerationCaseU0VGSgSiShySo18LNEntityIdentifierCGAA04TypeuV0_ptcfcfA5_
CStrings:
+ "BundleMetadataCache hit entity %s.%s"
+ "BundleMetadataCache hit query %s.%s"
+ "BundleMetadataCache hit valueQueries %s outputType=%@ -> %ld queries"
+ "BundleMetadataCache miss entity %s.%s"
+ "BundleMetadataCache miss query %s.%s"
+ "BundleMetadataCache miss valueQueries %s outputType=%@"
+ "ToolKitDaemon: Immediate indexing failed: %@"
+ "[ToolKitImmediateIndexing] received request"
+ "[ToolKitImmediateIndexing] request completed successfully"
+ "immediateIndexingController"
```
