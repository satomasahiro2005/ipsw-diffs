## remindd

> `/usr/libexec/remindd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x810ab4` | `0x81486c` | **`+0x3db8`** |
| `__TEXT.__oslogstring` | `0x606e0` | `0x611e0` | **`+0xb00`** |
| `__TEXT.__unwind_info` | `0xfe08` | `0x10360` | **`+0x558`** |
| `__TEXT.__objc_methname` | `0x27f21` | `0x28361` | **`+0x440`** |
| `__DATA_CONST.__const` | `0x25bc0` | `0x25f58` | **`+0x398`** |
| `__TEXT.__eh_frame` | `0x1f6b8` | `0x1f9f0` | **`+0x338`** |
| `__DATA.__objc_const` | `0x1dbc0` | `0x1dec8` | **`+0x308`** |
| `__TEXT.__objc_stubs` | `0x1b940` | `0x1bbe0` | **`+0x2a0`** |
| `__TEXT.__const` | `0x29358` | `0x29548` | **`+0x1f0`** |
| `__TEXT.__cstring` | `0x18d97` | `0x18ed7` | **`+0x140`** |
| `__DATA.__data` | `0x1f330` | `0x1f460` | **`+0x130`** |
| `__DATA.__objc_data` | `0x86e8` | `0x8818` | **`+0x130`** |
| `__TEXT.__objc_methlist` | `0xaa28` | `0xab50` | **`+0x128`** |
| `__TEXT.__swift5_typeref` | `0x141b6` | `0x142c2` | **`+0x10c`** |
| `__TEXT.__swift5_capture` | `0x637c` | `0x6454` | **`+0xd8`** |
| `__DATA.__objc_selrefs` | `0x7bd8` | `0x7ca0` | **`+0xc8`** |
| `__TEXT.__gcc_except_tab` | `0x2038` | `0x20f8` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x8af0` | `0x8ba0` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0xd0c0` | `0xd160` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0xa758` | `0xa7c0` | **`+0x68`** |
| `__DATA_CONST.__cfstring` | `0x5120` | `0x5180` | **`+0x60`** |
| `__TEXT.__objc_classname` | `0x63c6` | `0x6426` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x4588` | `0x45e0` | **`+0x58`** |
| `__TEXT.__swift5_reflstr` | `0xc165` | `0xc1a5` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x43a7` | `0x43d7` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x34b8` | `0x34e0` | **`+0x28`** |
| `__TEXT.__swift5_mpenum` | `0xbc` | `0xe0` | **`+0x24`** |
| `__DATA_CONST.__auth_ptr` | `0x28a8` | `0x28c0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xc40` | `0xc58` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x3ac` | `0x3c0` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x480` | `0x48c` | **`+0xc`** |
| `__DATA.__common` | `0x9f8` | `0xa00` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x138` | `0x140` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xb30` | `0xb38` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1900` | `0x1904` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4040.0.0.0.0
+4043.0.0.0.0

-  Functions: 22580
-  Symbols:   4242
-  CStrings:  11732
+  Functions: 22684
+  Symbols:   4259
+  CStrings:  11803
Symbols:
+ _$s19ReminderKitInternal15REMFileDigesterO9sha512Sum10fileHandleSSSgSo06NSFileI0C_tFZ
+ _$s19ReminderKitInternal20REMGroceryCapabilityO15generativeModelyA2CmFWC
+ _$s19ReminderKitInternal28GroceryCategorizationVersionO2v1yA2CmFWC
+ _$s19ReminderKitInternal28GroceryCategorizationVersionO2v2yA2CmFWC
+ _$s19ReminderKitInternal28GroceryCategorizationVersionO8rawValueSSvg
+ _$s19ReminderKitInternal28GroceryCategorizationVersionOMa
+ _$s19ReminderKitInternal28GroceryCategorizationVersionOMn
+ _$s19ReminderKitInternal42REMGenerativeModelsAvailabilityManagerTypePAAE26supportsAutoCategorizationSbyF
+ _NSPOSIXErrorDomain
+ _OBJC_CLASS_$_NSFileHandle
+ _SANDBOX_CHECK_NO_REPORT
+ ___error
+ _close
+ _fcntl
+ _fcopyfile
+ _fstat
+ _lseek
+ _open
+ _sandbox_check_by_audit_token
- _$s19ReminderKitInternal15REMFeatureFlagsO13groceryListV2yA2CmFWC
- _$s19ReminderKitInternal42REMGenerativeModelsAvailabilityManagerTypePAAE15supportsFeatureySbAA0deJ0OF
CStrings:
+ "(file-read-data on caller-supplied attachment URL)"
+ "@\"NSArray\"16@?0@\"NSManagedObject\"8"
+ "@56@0:8@16{?=[8I]}24"
+ "B64@0:8@16@24@32@40@48^@56"
+ "Failed to compute sha512 for attachment file through pinned handle; refusing to ingest {objectID: %{public}s, clientIdentity: %{public}s}"
+ "Failed to compute sha512 for attachment file; refusing to ingest {objectID: %{public}s, clientIdentity: %{public}s}"
+ "Grocery list-section policy applied {input_sections: %{public}ld, displayed_sections: %{public}ld, promoted_hosts: %{public}ld, grocery_section_count: %{public}ld}"
+ "Grocery toast: dropping message membership for remap-secondary whose host section is not in this batch {listObjectID: %{public}@, from: %{public}s, to: %{public}s}"
+ "Grocery toast: retargeting message membership {listObjectID: %{public}@, from: %{public}s, to: %{public}s}"
+ "Grocery toast: suppressing message membership for hidden canonical {listObjectID: %{public}@, category: %{public}s}"
+ "RDAccountInitializer: updateLocalAccountActiveStatus: CloudKit account is present, ensuring local account is inactive (if empty)."
+ "RDAccountInitializer: updateLocalAccountActiveStatus: No CloudKit account, local account is empty, ensuring local account is inactive."
+ "RDAccountInitializer: updateLocalAccountActiveStatus: No CloudKit account, local account is non-empty alongside secondary cloud accounts, ensuring local account is active."
+ "RDClientAttachmentSandboxCheck"
+ "RDGroceryCorrectionCache: Recording {%s: (from: %s, to: %s, locale: %s, version: %{public}s)} in list: %@"
+ "REMRDSpotlightReindexRule"
+ "Refusing to ingest attachment URL the caller cannot read {clientIdentity: %{public}s}"
+ "Refusing to ingest saved attachment URL the caller cannot read {clientIdentity: %{public}s}"
+ "Reindex All"
+ "Reindex Items (system)"
+ "Spotlight reindex target is not a REMCDObject; skipping bump {target: %@, source: %@}"
+ "T@\"NSSet\",R,C,N,V_triggerProperties"
+ "T@\"RDCoreSpotlightDelegateManager\",N,W,VdelegateManager"
+ "T@?,C,N,V_systemRequestExecutor"
+ "[%{public}@] Attachment copy failed {attachmentID: %{public}@, copyResult: %d, copyErrno: %d, closeResult: %d, closeErrno: %d}"
+ "[%{public}@] Attachment source is not a regular file; refusing to ingest {url: %{public}@}"
+ "[%{public}@] Caller is not permitted to read attachment URL; refusing to ingest {path: %{public}s}"
+ "[%{public}@] F_GETPATH failed; refusing to ingest attachment {errno: %d}"
+ "[%{public}@] open() failed; refusing to ingest attachment {errno: %d, url: %{public}@}"
+ "[%{public}@] open(destination) failed {attachmentID: %{public}@, errno: %d}"
+ "[%{public}@] sandbox_check_by_audit_token() failed; refusing to ingest attachment {errno: %d, path: %{public}s}"
+ "[Spotlight] %{public}@: acknowledged {elapsed: %.3f s}"
+ "[Spotlight] %{public}@: no active delegates; completion fires immediately."
+ "[Spotlight] Reindex Items (system): END {store: %{public}@, elapsed: %.3f s}"
+ "[Spotlight] Reindex Items (system): START {store: %{public}@, count: %lu}"
+ "[Spotlight] Reindex Items (system): requested {indexName: %{public}@, bundle: %{public}@, protectionClass: %{public}@, count: %lu}"
+ "[Spotlight] handleSystemRequest: systemRequestExecutor not set — executing work inline without _ivarLock"
+ "[Spotlight] searchableIndex reindexAll: no delegateManager — falling back to single-store reindex"
+ "[Spotlight] searchableIndex reindexItems: no delegateManager — falling back to single-store reindex"
+ "_TtC7remindd27RDGroceryHostDisplaySection"
+ "_initWithTriggers:targets:"
+ "_systemRequestExecutor"
+ "_targetsBlock"
+ "_triggerProperties"
+ "activeCoreSpotlightDelegates"
+ "authorizedReadHandleForFileURL:withAuditToken:"
+ "backingSection"
+ "caller's sandbox profile"
+ "closeAndReturnError:"
+ "could not compute sha512 for attachment file"
+ "delegateManager"
+ "fanOutReindexWithLabel:completionHandler:perDelegate:"
+ "file-read-data"
+ "fileDescriptor"
+ "handleSystemRequest:"
+ "hostCategory"
+ "initWithFileDescriptor:closeOnDealloc:"
+ "intelligentCanonicalCategoryNamesFromTrial: model category index %{public}ld has no canonical taxonomy mapping {locale: %{public}s, count: %{public}ld}"
+ "isFileURL"
+ "loggingStoreIdentifier"
+ "modifiedOn"
+ "performStoreReindexAllItemsWithAcknowledgementHandler:"
+ "performStoreReindexItemsWithIdentifiers:acknowledgementHandler:"
+ "reindexSearchableItemsWithIdentifiers:completionHandler:"
+ "reindexSearchableItemsWithIdentifiers:completionHandler: called before activation; completion fires immediately without reindex. {coordinator: %@}"
+ "resolveTargetsForSource:"
+ "ruleWithTriggers:targets:"
+ "rulesForObject:"
+ "setDelegateManager:"
+ "setLoggingStoreIdentifier:"
+ "setSystemRequestExecutor:"
+ "spotlightReindexRules"
+ "systemRequestExecutor"
+ "triggerProperties"
+ "updateAttachmentFile:accountID:fileName:sha512Sum:sourceFileHandle:error:"
+ "v16@?0@?<v@?>8"
+ "v32@?0@\"_TtC7remindd31RDCoreDataCoreSpotlightDelegate\"8@\"NSString\"16@?<v@?>24"
- "Grocery list-section policy applied {input_sections: %{public}ld, displayed_sections: %{public}ld, dropped_sections: %{public}ld, grocery_section_count: %{public}ld}"
- "Grocery list-section rewriter: remap {from_category: %{public}s, to_category: %{public}s}"
- "No active delegates to reindex; completion fires immediately."
- "RDAccountInitializer: updateLocalAccountActiveStatus: Let's ensure local account is inactive (if empty) as we have some cloud accounts."
- "RDGroceryCorrectionCache: Recording {%s: (from: %s, to: %s, locale: %s} in list: %@"
- "[Spotlight] Reindex All: acknowledged {elapsed: %.3f s}"
```
