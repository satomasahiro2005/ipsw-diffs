## DocumentManagerCore

> `/System/Library/PrivateFrameworks/DocumentManagerCore.framework/DocumentManagerCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72588` | `0x83dc8` | **`+0x11840`** |
| `__TEXT.__eh_frame` | `0xf40` | `0x2520` | **`+0x15e0`** |
| `__DATA_DIRTY.__data` | `0x728` | `0xf18` | **`+0x7f0`** |
| `__DATA.__data` | `0x1158` | `0xa28` | **`-0x730`** |
| `__TEXT.__unwind_info` | `0x1e88` | `0x2460` | **`+0x5d8`** |
| `__AUTH_CONST.__const` | `0x1798` | `0x1c50` | **`+0x4b8`** |
| `__AUTH.__objc_data` | `0x4a8` | `—` | **`-0x4a8`** |
| `__DATA_DIRTY.__objc_data` | `0x1130` | `0x15d8` | **`+0x4a8`** |
| `__TEXT.__const` | `0x17f0` | `0x19f8` | **`+0x208`** |
| `__TEXT.__oslogstring` | `0x4992` | `0x4b82` | **`+0x1f0`** |
| `__TEXT.__swift5_capture` | `0x2c4` | `0x474` | **`+0x1b0`** |
| `__TEXT.__swift_as_cont` | `0xc8` | `0x258` | **`+0x190`** |
| `__TEXT.__swift5_typeref` | `0xbd6` | `0xd32` | **`+0x15c`** |
| `__TEXT.__cstring` | `0x518a` | `0x52aa` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x1968` | `0x1a58` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x6f50` | `0x7030` | **`+0xe0`** |
| `__TEXT.__swift_as_ret` | `0x60` | `0x13c` | **`+0xdc`** |
| `__AUTH_CONST.__auth_got` | `0xde8` | `0xe98` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x4540` | `0x45f0` | **`+0xb0`** |
| `__TEXT.__swift_as_entry` | `0x60` | `0xf4` | **`+0x94`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a38` | `0x2ac8` | **`+0x90`** |
| `__AUTH_CONST.__objc_intobj` | `0xd8` | `0x150` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x6cc` | `0x6f8` | **`+0x2c`** |
| `__AUTH.__data` | `0x28` | `—` | **`-0x28`** |
| `__DATA_CONST.__got` | `0x748` | `0x770` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x3200` | `0x3220` | **`+0x20`** |
| `__DATA_CONST.__objc_catlist` | `0x60` | `0x70` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0xa20` | `0xa10` | **`-0x10`** |

### Other Changes

```diff

-401.1.5.0.0
+403.1.8.0.0

-  Functions: 2951
-  Symbols:   3069
-  CStrings:  914
+  Functions: 3273
+  Symbols:   3135
+  CStrings:  927
Symbols:
+ +[DOCAXIdentifier galleryPickerSheetMetricsLabel]
+ -[DOCManagedPermission canHostWithIdentifier:dataOwnerState:performAction:bundleIdentifier:]
+ -[FINode(DOCNode) _isOrIsAncestorOf:useFileParent:completion:]
+ -[FINode(DOCNode) doc_fetchEligibleActionsFor:completion:]
+ -[FINode(DOCNode) isOrIsAncestorOf:completion:]
+ -[FINode(DOCNode) isOrIsFileAncestorOf:completion:]
+ -[FPItem(DOCNode) _doc_fpEligibleActionsFor:]
+ -[FPItem(DOCNode) _doc_isUsingFPFS:]
+ -[FPItem(DOCNode) doc_fetchEligibleActionsFor:completion:]
+ -[FPItem(DOCNode) doc_shouldRedirectEligibleActionsToDS]
+ -[FPItem(DOCNode) isOrIsAncestorOf:completion:]
+ -[FPItem(DOCNode) isOrIsFileAncestorOf:completion:]
+ -[NSError(DOCXPCSafety) doc_errorSafeForXPCReply]
+ -[NSURL(DOCNoFollow) doc_followableURL]
+ -[NSURL(DOCNoFollow) doc_noFollowURL]
+ GCC_except_table1
+ GCC_except_table212
+ GCC_except_table217
+ GCC_except_table53
+ GCC_except_table57
+ GCC_except_table68
+ GCC_except_table77
+ GCC_except_table80
+ GCC_except_table86
+ _DOCErrorSafeForXPCReply
+ _DOCManagedPermissionHostAccountDataOwnerStateDidChangeNotification
+ _DOCTransformedArray
+ _DOCTransformedDictionary
+ _DOCURLIsFolder
+ _DOCValueSafeForXPCReply
+ _FPActionFetchPublishingURL
+ _KnownProviderForProviderID
+ _KnownProviderForProviderID.onceToken
+ _KnownProviderForProviderID.sProviderIDToKnownProvider
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSError_$_DOCXPCSafety
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSURL_$_DOCNoFollow
+ __OBJC_$_CATEGORY_NSError_$_DOCXPCSafety
+ __OBJC_$_CATEGORY_NSURL_$_DOCNoFollow
+ __OBJC_$_PROP_LIST_NSError_$_DOCXPCSafety
+ __OBJC_$_PROP_LIST_NSURL_$_DOCNoFollow
+ ___47-[FPItem(DOCNode) isOrIsAncestorOf:completion:]_block_invoke
+ ___47-[FPItem(DOCNode) isOrIsAncestorOf:completion:]_block_invoke_2
+ ___53-[DOCManagedPermission setHostAccountDataOwnerState:]_block_invoke
+ ___58-[FINode(DOCNode) doc_fetchEligibleActionsFor:completion:]_block_invoke
+ ___58-[FPItem(DOCNode) doc_fetchEligibleActionsFor:completion:]_block_invoke
+ ___58-[FPItem(DOCNode) doc_fetchEligibleActionsFor:completion:]_block_invoke_2
+ ___62-[FINode(DOCNode) _isOrIsAncestorOf:useFileParent:completion:]_block_invoke
+ ___62-[FINode(DOCNode) _isOrIsAncestorOf:useFileParent:completion:]_block_invoke_2
+ ___62-[FINode(DOCNode) _isOrIsAncestorOf:useFileParent:completion:]_block_invoke_3
+ ___DOCErrorSafeForXPCReply_block_invoke
+ ___DOCValueSafeForXPCReply_block_invoke
+ ___KnownProviderForProviderID_block_invoke
+ ___block_descriptor_40_e8_16?08l
+ ___block_descriptor_40_e8_32bs_e8_B12?0B8ls32l8
+ ___block_descriptor_48_e8_32s40r_e8_v12?0B8lr40l8s32l8
+ ___block_descriptor_56_e8_32bs40bs48bs_e28_v24?0"FPItem"8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_56_e8_32s40r_e25_v32?0"NSString"816^B24lr40l8s32l8
+ ___block_descriptor_56_e8_32s40s48bs_e28_v24?0"FINode"8"NSError"16ls32l8s48l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls48l8s32l8s40l8
+ ___block_descriptor_64_e8_32bs40bs48r56r_e60_"FIOperationReply"24?0"FIOperation"8"FIOperationError"16ls32l8r48l8s40l8r56l8
+ ___block_descriptor_64_e8_32s40bs48bs56bs_e28_v24?0"FPItem"8"NSError"16ls32l8s40l8s48l8s56l8
+ ___swift_closure_destructor.147Tm
+ ___swift_closure_destructor.195Tm
+ ___swift_closure_destructor.23Tm
+ ___swift_closure_destructor.295Tm
+ ___swift_closure_destructor.76Tm
+ ___swift_closure_destructor.82Tm
+ _realpath$DARWIN_EXTSN
+ _swift_allocError
+ _swift_continuation_resume
+ _swift_continuation_throwingResume
+ _swift_continuation_throwingResumeWithError
+ _swift_getAssociatedConformanceWitness
+ _swift_getAssociatedTypeWitness
+ _swift_release_x28
+ _swift_retain_x24
+ _swift_retain_x28
+ _swift_taskGroup_addPending
+ _symbolic SayShy_____GG So8FPActiona
+ _symbolic SayShy_____GSgG So8FPActiona
+ _symbolic SccySb_____G s5NeverO
+ _symbolic SccyShy_____G_____G So8FPActiona s5NeverO
+ _symbolic SccySo6FINodeCSg______pG s5ErrorP
+ _symbolic Shy_____G So8FPActiona
+ _symbolic Shy_____GSg So8FPActiona
+ _symbolic Si_Shy_____Gt So8FPActiona
+ _symbolic So6FINodeC
+ _symbolic So6FINodeCSg6fiNode_So6FPItemCSg6fpItemt
+ _symbolic ______pS2bIeggyd_ So7DOCNodeP
+ _symbolic ______pShy_____GSgAC______pIeghHggozo_ So7DOCNodeP So8FPActiona s5ErrorP
+ _symbolic _____yShy_____GG s23_ContiguousArrayStorageC So8FPActiona
+ _symbolic _____yShy_____G______p_G Scg8IteratorV So8FPActiona s5ErrorP
+ _symbolic _____ySi_Shy_____Gt______p_G Scg8IteratorV So8FPActiona s5ErrorP
+ _symbolic _____ySo6FINodeCSg6fiNode_So6FPItemCSg6fpItemt______p_G Scg8IteratorV s5ErrorP
- +[DOCFeature modernToolbar]
- -[FINode(DOCNode) _isOrIsAncestorOf:useFileParent:]
- -[FINode(DOCNode) doc_eligibleActions]
- -[FPItem(DOCNode) doc_eligibleActions]
- GCC_except_table199
- GCC_except_table204
- GCC_except_table52
- GCC_except_table55
- GCC_except_table65
- GCC_except_table74
- GCC_except_table75
- GCC_except_table88
- ___27+[DOCFeature modernToolbar]_block_invoke
- ___36-[FPItem(DOCNode) isOrIsAncestorOf:]_block_invoke_2
- ___41-[FPItem(DOCNode) shouldUseDSEnumeration]_block_invoke
- ___42-[DOCManagedPermission setHostIdentifier:]_block_invoke
- ___51-[FINode(DOCNode) _isOrIsAncestorOf:useFileParent:]_block_invoke
- ___block_descriptor_56_e8_32s40bs48bs_e28_v24?0"FPItem"8"NSError"16ls32l8s40l8s48l8
- ___block_descriptor_56_e8_32s40bs48bs_e28_v24?0"FPItem"8"NSError"16ls40l8s32l8s48l8
- ___block_descriptor_56_e8_32s40s48r_e29_v24?0"NSArray"8"NSError"16ls32l8r48l8s40l8
- ___block_descriptor_72_e8_32s40bs48bs56r64r_e60_"FIOperationReply"24?0"FIOperation"8"FIOperationError"16ls40l8r56l8s32l8s48l8r64l8
- ___swift_closure_destructor.102Tm
- _modernToolbar.cachedValue
- _modernToolbar.onceToken
- _shouldUseDSEnumeration.onceToken
- _shouldUseDSEnumeration.sProviderIDToDSEnumerationState
- _swift_dynamicCastObjCClassUnconditional
- _symbolic _____ySiG s16PartialRangeFromV
- _symbolic _____ySiG s16PartialRangeUpToV
CStrings:
+ "%s Unable to fetch saved downloads location item. item: %@ domain: %@ trashed: %d isFolder: %d error: %@"
+ "%s Unable to fetch saved downloads. URL: %{public}@ isFolder: %d error: %@"
+ "%{public}s -- expected %ld requested actions. Received: %ld. Returning %ld."
+ "%{public}s: iCloud container '%{public}@' has no file parent. Mobile Documents will not map to the iCloud root, so navigating out of an app container will show the wrong location."
+ "-[FPItem(DOCNode) _doc_isUsingFPFS:]"
+ "-[FPItem(DOCNode) doc_fetchEligibleActionsFor:completion:]_block_invoke_2"
+ "@16@?0@8"
+ "B12@?0B8"
+ "DOCManagedPermissionHostAccountDataOwnerStateDidChangeNotification"
+ "Existing item named %{public}@ in %{public}@ is not a folder"
+ "Q"
+ "[NoFollow] No file system representation for %@"
+ "[NoFollow] realpath failed for %@: %{errno}d"
+ "_doc_fetchPerNodeEligibleActions(with:fetcher:)"
+ "doc_perNodeEligibleActions(with:)"
+ "pickerSheetMetricsLabel"
+ "v32@?0@\"NSString\"8@16^B24"
- "%s Unable to fetch saved downloads location item. Error: %@"
- "%s Unable to fetch saved downloads. Error: %@"
- "-[FPItem(DOCNode) shouldUseDSEnumeration]"
- "modernToolbar"
```
