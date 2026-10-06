## SafariFoundation

> `/System/Library/PrivateFrameworks/SafariFoundation.framework/SafariFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35dec` | `0x3bb10` | **`+0x5d24`** |
| `__TEXT.__eh_frame` | `0xef0` | `0x13f8` | **`+0x508`** |
| `__AUTH.__data` | `—` | `0x1c8` | **`+0x1c8`** |
| `__TEXT.__unwind_info` | `0x14a0` | `0x1648` | **`+0x1a8`** |
| `__TEXT.__constg_swiftt` | `0x400` | `0x57c` | **`+0x17c`** |
| `__TEXT.__const` | `0x734` | `0x874` | **`+0x140`** |
| `__AUTH_CONST.__const` | `0xe68` | `0xf88` | **`+0x120`** |
| `__AUTH_CONST.__objc_const` | `0x3a68` | `0x3b60` | **`+0xf8`** |
| `__AUTH_CONST.__auth_got` | `0x8b0` | `0x988` | **`+0xd8`** |
| `__DATA_CONST.__const` | `0x14e0` | `0x15b0` | **`+0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x1ac` | `0x254` | **`+0xa8`** |
| `__DATA.__data` | `0x550` | `0x5e8` | **`+0x98`** |
| `__DATA.__bss` | `0x1d0` | `0x260` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x2c8` | `0x338` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x38e` | `0x3fe` | **`+0x70`** |
| `__DATA_DIRTY.__data` | `0x5f0` | `0x658` | **`+0x68`** |
| `__TEXT.__swift5_reflstr` | `0x187` | `0x1ed` | **`+0x66`** |
| `__AUTH.__objc_data` | `0xd8` | `0x128` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x540` | `0x588` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x21e0` | `0x2218` | **`+0x38`** |
| `__TEXT.__cstring` | `0x2a67` | `0x2a97` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0xd4` | `0x100` | **`+0x2c`** |
| `__DATA_CONST.__objc_selrefs` | `0x19b8` | `0x19d8` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x20` | `0x2c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x140` | `0x148` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x74` | `0x7c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xc` | `0x10` | **`+0x4`** |

### Other Changes

```diff

-625.1.29.10.29
+625.2.4.1.0

-  Functions: 1412
-  Symbols:   2082
-  CStrings:  439
+  Functions: 1506
+  Symbols:   2117
+  CStrings:  440
Symbols:
+ -[SFAppAutoFillOneTimeCodeProvider _currentOneTimeCodesForWebBrowserOnInternalQueueWithWebsiteFrameURLs:fieldClassification:inContext:]
+ -[SFAppAutoFillOneTimeCodeProvider getCurrentOneTimeCodesForWebBrowserWithWebsiteFrameURLs:fieldClassification:completionHandler:]
+ -[SFAppAutoFillOneTimeCodeProvider getCurrentOneTimeCodesForWebBrowserWithWebsiteFrameURLs:fieldClassification:inContext:completionHandler:]
+ -[SFStrongPasswordGenerator(AppAutoFill) getAutomaticStrongPasswordForApplicationIdentifier:passwordRules:confirmPasswordRules:completionHandler:]
+ __DATA__TtCC16SafariFoundation19SFGuidedBrowsingTab6Status
+ __IVARS__TtCC16SafariFoundation19SFGuidedBrowsingTab6Status
+ __METACLASS_DATA__TtCC16SafariFoundation19SFGuidedBrowsingTab6Status
+ __OBJC_$_INSTANCE_METHODS_SFStrongPasswordGenerator(AppAutoFill)
+ ___135-[SFAppAutoFillOneTimeCodeProvider _currentOneTimeCodesForWebBrowserOnInternalQueueWithWebsiteFrameURLs:fieldClassification:inContext:]_block_invoke
+ ___135-[SFAppAutoFillOneTimeCodeProvider _currentOneTimeCodesForWebBrowserOnInternalQueueWithWebsiteFrameURLs:fieldClassification:inContext:]_block_invoke_2
+ ___140-[SFAppAutoFillOneTimeCodeProvider getCurrentOneTimeCodesForWebBrowserWithWebsiteFrameURLs:fieldClassification:inContext:completionHandler:]_block_invoke
+ ___140-[SFAppAutoFillOneTimeCodeProvider getCurrentOneTimeCodesForWebBrowserWithWebsiteFrameURLs:fieldClassification:inContext:completionHandler:]_block_invoke_2
+ ___146-[SFStrongPasswordGenerator(AppAutoFill) getAutomaticStrongPasswordForApplicationIdentifier:passwordRules:confirmPasswordRules:completionHandler:]_block_invoke
+ ___146-[SFStrongPasswordGenerator(AppAutoFill) getAutomaticStrongPasswordForApplicationIdentifier:passwordRules:confirmPasswordRules:completionHandler:]_block_invoke_2
+ ___block_descriptor_40_e8_32s_e55_"NSString"16?0"SFSharedWebCredentialsDatabaseEntry"8ls32l8
+ ___block_descriptor_56_e8_32s40s48bs_e30_v24?0"NSString"8"NSArray"16ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56r_e5_v8?0lr56l8s32l8s40l8s48l8
+ ___swift_closure_destructor.201Tm
+ __swiftEmptyDictionarySingleton
+ _bzero
+ _memmove
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_retain_x27
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_task_deinitOnExecutor
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
+ _symbolic SDy__________G 10Foundation4UUIDV 06SafariA022SFGuidedBrowsingClientC7WeakTab33_B3096BB282D3FE579566CCBE624FBB60LLV
+ _symbolic SSSg
+ _symbolic SiSg
+ _symbolic _____ 10Foundation3URLV
+ _symbolic _____ 10Foundation4UUIDV
+ _symbolic _____ 10SafariCore32WBSGuidedBrowsingNavigationEventC
+ _symbolic _____ 16SafariFoundation19SFGuidedBrowsingTabC15NavigationEventV
+ _symbolic _____ 16SafariFoundation19SFGuidedBrowsingTabC6StatusC
+ _symbolic _____ 16SafariFoundation22SFGuidedBrowsingClientC7WeakTab33_B3096BB282D3FE579566CCBE624FBB60LLV
+ _symbolic _____Sg 16SafariFoundation19SFGuidedBrowsingTabC15NavigationEventV
+ _symbolic _____Sg 16SafariFoundation22SFGuidedBrowsingClientC7WeakTab33_B3096BB282D3FE579566CCBE624FBB60LLV
+ _symbolic _____SgXw 16SafariFoundation19SFGuidedBrowsingTabC
+ _symbolic ___________t 10Foundation4UUIDV 06SafariA022SFGuidedBrowsingClientC7WeakTab33_B3096BB282D3FE579566CCBE624FBB60LLV
+ _symbolic _____y__________G s18_DictionaryStorageC 10Foundation4UUIDV 06SafariC022SFGuidedBrowsingClientC7WeakTab33_B3096BB282D3FE579566CCBE624FBB60LLV
+ _type_layout_string 16SafariFoundation22SFGuidedBrowsingClientC7WeakTab33_B3096BB282D3FE579566CCBE624FBB60LLV
- -[SFAutoFillHelperProxy _getAutomaticStrongPasswordForAppWithPasswordRules:confirmPasswordRules:overrideApplicationIdentifier:completion:]
- -[SFAutoFillHelperProxy getAutomaticStrongPasswordForAppWithPasswordRules:confirmPasswordRules:completion:]
- -[SFAutoFillHelperProxy getAutomaticStrongPasswordForAppWithPasswordRules:confirmPasswordRules:overrideApplicationIdentifier:completion:]
- GCC_except_table55
- __OBJC_$_INSTANCE_METHODS_SFStrongPasswordGenerator
- ___119-[SFAppAutoFillOneTimeCodeProvider currentOneTimeCodesForWebBrowserWithWebsiteFrameURLs:fieldClassification:inContext:]_block_invoke_2
- ___119-[SFAppAutoFillOneTimeCodeProvider currentOneTimeCodesForWebBrowserWithWebsiteFrameURLs:fieldClassification:inContext:]_block_invoke_3
- ___138-[SFAutoFillHelperProxy _getAutomaticStrongPasswordForAppWithPasswordRules:confirmPasswordRules:overrideApplicationIdentifier:completion:]_block_invoke
- ___swift_closure_destructor.142Tm
- _swift_release_x26
- _symbolic Say_____G 16SafariFoundation19SFGuidedBrowsingTabC
CStrings:
+ "SafariFoundation/SFGuidedBrowsingClient.swift"
```
