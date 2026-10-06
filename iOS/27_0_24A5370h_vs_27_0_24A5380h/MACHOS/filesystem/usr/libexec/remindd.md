## remindd

> `/usr/libexec/remindd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x805608` | `0x810ab4` | **`+0xb4ac`** |
| `__TEXT.__oslogstring` | `0x5fce0` | `0x606e0` | **`+0xa00`** |
| `__DATA.__bss` | `0x23090` | `0x23710` | **`+0x680`** |
| `__TEXT.__const` | `0x28ef8` | `0x29358` | **`+0x460`** |
| `__DATA.__data` | `0x1ef60` | `0x1f330` | **`+0x3d0`** |
| `__DATA_CONST.__const` | `0x25848` | `0x25bc0` | **`+0x378`** |
| `__TEXT.__objc_methname` | `0x27cd1` | `0x27f21` | **`+0x250`** |
| `__TEXT.__unwind_info` | `0x10038` | `0xfe08` | **`-0x230`** |
| `__TEXT.__swift5_typeref` | `0x13fc4` | `0x141b6` | **`+0x1f2`** |
| `__DATA.__objc_const` | `0x1da40` | `0x1dbc0` | **`+0x180`** |
| `__TEXT.__cstring` | `0x18c17` | `0x18d97` | **`+0x180`** |
| `__TEXT.__auth_stubs` | `0x8990` | `0x8af0` | **`+0x160`** |
| `__TEXT.__swift5_reflstr` | `0xc065` | `0xc165` | **`+0x100`** |
| `__TEXT.__objc_methtype` | `0x42b7` | `0x43a7` | **`+0xf0`** |
| `__TEXT.__swift5_fieldmd` | `0xa67c` | `0xa758` | **`+0xdc`** |
| `__TEXT.__objc_methlist` | `0xa968` | `0xaa28` | **`+0xc0`** |
| `__DATA_CONST.__auth_got` | `0x44d8` | `0x4588` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0xd018` | `0xd0c0` | **`+0xa8`** |
| `__DATA.__objc_data` | `0x8650` | `0x86e8` | **`+0x98`** |
| `__TEXT.__objc_stubs` | `0x1b8c0` | `0x1b940` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x62fc` | `0x637c` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x3450` | `0x34b8` | **`+0x68`** |
| `__DATA.__objc_selrefs` | `0x7b80` | `0x7bd8` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0x1f708` | `0x1f6b8` | **`-0x50`** |
| `__DATA_CONST.__auth_ptr` | `0x2870` | `0x28a8` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x18cc` | `0x1900` | **`+0x34`** |
| `__TEXT.__objc_classname` | `0x6396` | `0x63c6` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x1e88` | `0x1eb8` | **`+0x30`** |
| `__DATA_CONST.__objc_protolist` | `0x520` | `0x530` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xb20` | `0xb30` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x470` | `0x460` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xc38` | `0xc40` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x238` | `0x240` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x230` | `0x228` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x1cc` | `0x1c8` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-4037.1.0.0.0
+4040.0.0.0.0

-  Functions: 22450
-  Symbols:   4215
-  CStrings:  11677
+  Functions: 22580
+  Symbols:   4242
+  CStrings:  11732
Symbols:
+ _$s10Foundation6LocaleV12LanguageCodeV10identifierSSvg
+ _$s10Foundation6LocaleV12LanguageCodeVMa
+ _$s10Foundation6LocaleV12LanguageCodeVMn
+ _$s10Foundation6LocaleV8LanguageV12languageCodeAC0cE0VSgvg
+ _$s10Foundation6LocaleV8LanguageVMa
+ _$s10Foundation6LocaleV8languageAC8LanguageVvg
+ _$s16FoundationModels19SystemLanguageModelC10GuardrailsV32permissiveContentTransformationsAEvgZ
+ _$s16FoundationModels19SystemLanguageModelC25modelCatalogAssetBundleID0f14ManagerUseCaseJ010guardrailsACSS_SSAC10GuardrailsVtcfC
+ _$s16FoundationModels19SystemLanguageModelCMa
+ _$s16FoundationModels20LanguageModelSessionC5model5tools12instructionsAcA06SystemcD0C_SayAA4Tool_pGSSSgtcfC
+ _$s16FoundationModels20LanguageModelSessionC7prewarm12promptPrefixyAA6PromptVSg_tF
+ _$s16FoundationModels6PromptVMa
+ _$s16FoundationModels6PromptVMn
+ _$s19ReminderKitInternal18REMGroceryCategoryO10taxonomyIDSSvg
+ _$s19ReminderKitInternal18REMGroceryCategoryO5match11displayName6localeACSgSS_10Foundation6LocaleVSgtFZ
+ _$s19ReminderKitInternal18REMGroceryCategoryO8rawValueACSgSS_tcfC
+ _$s19ReminderKitInternal18REMGroceryCategoryOSQAAMc
+ _$s19ReminderKitInternal29REMGroceryLocaleDisplayPolicyC11displayHost3forAA0D8CategoryOSgAG_tF
+ _$s19ReminderKitInternal29REMGroceryLocaleDisplayPolicyC19displayedCanonicals4fromSayAA0D8CategoryOGAH_tF
+ _$s19ReminderKitInternal29REMGroceryLocaleDisplayPolicyC6sharedACvgZ
+ _$s19ReminderKitInternal29REMGroceryLocaleDisplayPolicyCMa
+ _$s19ReminderKitInternal29REMGroceryLocaleDisplayPolicyCMn
+ _$s7Combine19CurrentValueSubjectC5valuexvg
+ _$s7Combine19CurrentValueSubjectC5valuexvs
+ _$sSYsSERzSS8RawValueSYRtzrlE6encode2toys7Encoder_p_tKF
+ _$sSYsSeRzSS8RawValueSYRtzrlE4fromxs7Decoder_p_tKcfC
+ _OBJC_CLASS_$_NSLock
CStrings:
+ "%{public}s: Backfilled canonicalName on %{public}ld section(s) after Standard→Grocery conversion {listObjectID: %{public}@}"
+ "%{public}s: Failed to fetch sections for canonical-name backfill {listObjectID: %{public}@, error: %{public}s}"
+ "%{public}s: Failed to obtain REMObjectID for canonical-name backfill {error: %{public}s}"
+ ".eventKitSyncClient"
+ "Building grocery rewriter for grocery list fetch {listID: %{public}@, locale: %{public}s, language: %{public}s, section_count: %{public}ld}"
+ "Building grocery rewriter for predefined grocery sections {listID: %{public}@, locale: %{public}s, language: %{public}s}"
+ "Grocery list-section policy applied {input_sections: %{public}ld, displayed_sections: %{public}ld, dropped_sections: %{public}ld, grocery_section_count: %{public}ld}"
+ "Grocery list-section rewriter: remap {from_category: %{public}s, to_category: %{public}s}"
+ "Grocery rewriter: hidden in current locale {category: %{public}s} — reminder will route to sectionless bucket"
+ "Grocery rewriter: remap {from: %{public}s, to: %{public}s}"
+ "RDGroceryCategorizerSession: {titles: %{private}s}"
+ "RDSignificantChangeStore: KVS quota violation; skipping reload"
+ "RDSignificantChangeStore: acknowledged changeID %{public}s type %{public}s"
+ "RDSignificantChangeStore: decode failure for changeID %{public}s: %{public}s"
+ "RDSignificantChangeStore: missing Data for key %{public}s"
+ "RDSignificantChangeStore: notify_post failed for %{public}s {status: %u}"
+ "RDSignificantChangeStore: resetAll cleared %{public}ld acknowledgments"
+ "RDXPCSignificantChangePerformer: failed to decode record for %{public}s: %{public}s"
+ "RDXPCSignificantChangePerformer: fetched %ld acknowledgments"
+ "RDXPCSignificantChangePerformer: fetched %ld acknowledgments (skipped %ld unencodable)"
+ "RDXPCSignificantChangePerformer: setAcknowledged failed for %{public}s: %{public}s"
+ "RDXPCSignificantChangePerformer: skipping unencodable record for %{public}s: %{public}s"
+ "REMNSPersistentHistoryTracking fetchHistoryAfterDate: scoping to affectedStores {affectedStores.count: %llu, affectedStores.identifiers: %{private}@}"
+ "REMNSPersistentHistoryTracking fetchHistoryAfterDate: skipped fetch — affectedStores was empty, returning empty change set"
+ "REMNSPersistentHistoryTracking fetchHistoryAfterToken: scoping to affectedStores {affectedStores.count: %llu, affectedStores.identifiers: %{private}@}"
+ "REMNSPersistentHistoryTracking fetchHistoryAfterToken: skipped fetch — affectedStores was empty, returning empty change set"
+ "REMSignificantChange."
+ "REMXPCSignificantChangePerformer"
+ "_TtC7remindd24RDSignificantChangeStore"
+ "_TtC7remindd31RDXPCSignificantChangePerformer"
+ "adultNotificationAcknowledged"
+ "asyncSignificantChangePerformerWithReason:loadHandler:errorHandler:"
+ "changeObserver"
+ "changesSubject"
+ "com.apple.Reminders.SignificantChange.changed"
+ "com.apple.exchangesyncd"
+ "com.apple.fm.language.instruct_3b.suggest_recipe_items"
+ "complianceNotRequired"
+ "dataForKey:"
+ "fetchHistoryAfterDate:entityNames:transactionFetchLimit:affectedStores:completionHandler:"
+ "fetchHistoryAfterToken:entityNames:transactionFetchLimit:affectedStores:completionHandler:"
+ "fetchSignificantChangeAcknowledgmentsWithReply:"
+ "gracedByOriginalAppVersion"
+ "parentalConsentApproved"
+ "remindd.RDXPCSignificantChangePerformer"
+ "resetSignificantChangeAcknowledgmentsWithReply:"
+ "setData:forKey:"
+ "setSignificantChangeAcknowledgedWithChangeID:recordData:reply:"
+ "significantChange."
+ "significantChangePerformerWithReason:completion:"
+ "significantChangeStore"
+ "synchronizedKeyValueStore"
+ "unlock"
+ "v32@0:8@\"NSString\"16@?<v@?@\"<REMXPCSignificantChangePerformer>\"@\"NSError\">24"
+ "v40@0:8@\"NSString\"16@\"NSData\"24@?<v@?@\"NSError\">32"
+ "v40@0:8@\"NSString\"16@?<v@?@\"<REMXPCSignificantChangePerformer>\">24@?<v@?@\"NSError\">32"
+ "v56@0:8@16@24Q32@40@?48"
- "_TtCC7remindd27RDGroceryCategorizerSessionP33_B50E0EC0EA75527607BA77EADE0F997C11_ClientInfo"
- "vUBZLTBQvgKsrY8YuaZVS0t8-co."
```
