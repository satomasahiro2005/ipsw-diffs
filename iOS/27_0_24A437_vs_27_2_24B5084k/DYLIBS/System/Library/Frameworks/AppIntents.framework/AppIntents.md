## AppIntents

> `/System/Library/Frameworks/AppIntents.framework/AppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f8740` | `0x515290` | **`+0x1cb50`** |
| `__AUTH_CONST.__const` | `0x26478` | `0x28c30` | **`+0x27b8`** |
| `__TEXT.__eh_frame` | `0x30ce4` | `0x31d6c` | **`+0x1088`** |
| `__TEXT.__swift5_capture` | `0x6320` | `0x71f8` | **`+0xed8`** |
| `__TEXT.__const` | `0x357b8` | `0x35dc0` | **`+0x608`** |
| `__DATA.__bss` | `0x3fa30` | `0x40030` | **`+0x600`** |
| `__TEXT.__oslogstring` | `0x7148` | `0x7722` | **`+0x5da`** |
| `__TEXT.__unwind_info` | `0x175b8` | `0x17a90` | **`+0x4d8`** |
| `__TEXT.__swift5_typeref` | `0x13663` | `0x1391d` | **`+0x2ba`** |
| `__DATA.__data` | `0xf3e0` | `0xf630` | **`+0x250`** |
| `__TEXT.__constg_swiftt` | `0x138cc` | `0x13ab8` | **`+0x1ec`** |
| `__TEXT.__swift5_fieldmd` | `0xb8f8` | `0xba74` | **`+0x17c`** |
| `__TEXT.__objc_methlist` | `0x1788` | `0x18d8` | **`+0x150`** |
| `__TEXT.__cstring` | `0x6ca7` | `0x6de2` | **`+0x13b`** |
| `__DATA_CONST.__objc_selrefs` | `0x24f8` | `0x25f0` | **`+0xf8`** |
| `__TEXT.__swift5_reflstr` | `0x8b6c` | `0x8c5c` | **`+0xf0`** |
| `__TEXT.__swift_as_cont` | `0x2680` | `0x2754` | **`+0xd4`** |
| `__AUTH.__data` | `0x9238` | `0x91a8` | **`-0x90`** |
| `__AUTH_CONST.__auth_got` | `0x2458` | `0x24c8` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x1768` | `0x17d8` | **`+0x70`** |
| `__TEXT.__swift_as_ret` | `0x1abc` | `0x1b2c` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x8c0` | `0x910` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x5538` | `0x5580` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x1830` | `0x1870` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x45a0` | `0x45e0` | **`+0x40`** |
| `__TEXT.__swift_as_entry` | `0x17d0` | `0x1810` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x5290` | `0x52c0` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x29ac` | `0x29dc` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x174` | `0x19c` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0x5f0` | `0x618` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x260` | `0x280` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0xe54` | `0xe6c` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x6c` | `0x7c` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x4e0` | `0x4f0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x250` | `0x248` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xf8` | `0x100` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x1f0` | `0x1f8` | **`+0x8`** |
| `__DATA.__common` | `0x310` | `0x309` | **`-0x7`** |
| `__TEXT.__swift5_types2` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-301.0.51.1.104
+301.1.9.1.101

-  Functions: 36461
-  Symbols:   8166
-  CStrings:  1222
+  Functions: 37069
+  Symbols:   8208
+  CStrings:  1247
Symbols:
+ +[LNProcessInstanceRegistryClient _retryDelayForAttempt:]
+ +[LNProcessInstanceRegistryClient _shouldAttemptRetryForAttempt:]
+ -[LNClientConnection fetchDisplayRepresentationsForEntities:components:completionHandler:]
+ -[LNClientConnection performDynamicMigrationForAction:targetVersion:completionHandler:]
+ -[LNProcessInstanceRegistryClient _canRegisterWithError:]
+ -[LNProcessInstanceRegistryClient _handleInterruptionForConnectionGeneration:]
+ -[LNProcessInstanceRegistryClient _handleInvalidationForConnectionGeneration:]
+ -[LNProcessInstanceRegistryClient _makeXPCConnection]
+ -[LNProcessInstanceRegistryClient _oneShotCompletionHandler:]
+ -[LNProcessInstanceRegistryClient _performRegistrationWithCompletionHandler:]
+ -[LNProcessInstanceRegistryClient connectionGeneration]
+ -[LNProcessInstanceRegistryClient listenerEndpoint]
+ -[LNProcessInstanceRegistryClient registerWithCompletionHandler:]
+ -[LNProcessInstanceRegistryClient registrationQueue]
+ -[LNProcessInstanceRegistryClient setConnectionGeneration:]
+ -[LNProcessInstanceRegistryClient setListenerEndpoint:]
+ -[LNProcessInstanceRegistryClient setSuccessfulRegistrationCount:]
+ -[LNProcessInstanceRegistryClient successfulRegistrationCount]
+ -[LNProcessInstanceRegistryClient(Deprecated) registerWithError:]
+ GCC_except_table393
+ GCC_except_table397
+ GCC_except_table399
+ GCC_except_table403
+ GCC_except_table414
+ GCC_except_table417
+ GCC_except_table419
+ GCC_except_table63
+ GCC_except_table78
+ _LNConnectionDefaultRequestTimeout
+ _MDItemIsFromMe
+ _NSSelectorFromString
+ _OBJC_CLASS_$_LNActionMigrationNode
+ _OBJC_CLASS_$_LNAppEntityContext
+ _OBJC_CLASS_$_LNEntityDisplayRepresentationFetchResult
+ _OBJC_CLASS_$_LNWatchdogTimer
+ _OBJC_IVAR_$_LNProcessInstanceRegistryClient._connectionGeneration
+ _OBJC_IVAR_$_LNProcessInstanceRegistryClient._listenerEndpoint
+ _OBJC_IVAR_$_LNProcessInstanceRegistryClient._registrationQueue
+ _OBJC_IVAR_$_LNProcessInstanceRegistryClient._successfulRegistrationCount
+ __DATA__TtC10AppIntentsP33_9252267F7014912BD235250E1970668A24InProcessLongRunningTask
+ __IVARS__TtC10AppIntentsP33_9252267F7014912BD235250E1970668A24InProcessLongRunningTask
+ __METACLASS_DATA__TtC10AppIntentsP33_9252267F7014912BD235250E1970668A24InProcessLongRunningTask
+ __OBJC_$_INSTANCE_METHODS_LNAppContext(AppIntents|AppIntents1|AppIntents2|AppIntents3|AppIntents4|AppIntents5|AppIntents6|AppIntents7|AppIntents8|AppIntents9|AppIntents10|AppIntents11|AppIntents12|AppIntents13|AppIntents14|AppIntents15|AppIntents16|AppIntents17|AppIntents18|AppIntents19|AppIntents20|AppIntents21|AppIntents22|AppIntents23|AppIntents24|AppIntents25|AppIntents26|AppIntents27|AppIntents28|AppIntents29|AppIntents30|AppIntents31)
+ __OBJC_$_INSTANCE_METHODS_LNProcessInstanceRegistryClient(Deprecated)
+ __OBJC_$_INSTANCE_METHODS__TtC10AppIntents10AppManager(AppIntents)
+ __OBJC_CLASS_PROTOCOLS_$__TtC10AppIntents10AppManager(AppIntents)
+ __PROTOCOL_INSTANCE_METHODS__TtP12LinkServices28LNMigrationMetadataResolving_
+ __PROTOCOL_METHOD_TYPES__TtP12LinkServices28LNMigrationMetadataResolving_
+ __PROTOCOL__TtP12LinkServices28LNMigrationMetadataResolving_
+ ___53-[LNProcessInstanceRegistryClient _makeXPCConnection]_block_invoke
+ ___61-[LNProcessInstanceRegistryClient _oneShotCompletionHandler:]_block_invoke
+ ___65-[LNProcessInstanceRegistryClient registerWithCompletionHandler:]_block_invoke
+ ___65-[LNProcessInstanceRegistryClient registerWithCompletionHandler:]_block_invoke_2
+ ___65-[LNProcessInstanceRegistryClient(Deprecated) registerWithError:]_block_invoke
+ ___77-[LNProcessInstanceRegistryClient _performRegistrationWithCompletionHandler:]_block_invoke
+ ___77-[LNProcessInstanceRegistryClient _performRegistrationWithCompletionHandler:]_block_invoke_2
+ ___78-[LNProcessInstanceRegistryClient _handleInterruptionForConnectionGeneration:]_block_invoke
+ ___78-[LNProcessInstanceRegistryClient _handleInvalidationForConnectionGeneration:]_block_invoke
+ ___87-[LNClientConnection performDynamicMigrationForAction:targetVersion:completionHandler:]_block_invoke
+ ___87-[LNClientConnection performDynamicMigrationForAction:targetVersion:completionHandler:]_block_invoke_2
+ ___87-[LNClientConnection performDynamicMigrationForAction:targetVersion:completionHandler:]_block_invoke_3
+ ___87-[LNClientConnection performDynamicMigrationForAction:targetVersion:completionHandler:]_block_invoke_4
+ ___87-[LNClientConnection performDynamicMigrationForAction:targetVersion:completionHandler:]_block_invoke_5
+ ___90-[LNClientConnection fetchDisplayRepresentationsForEntities:components:completionHandler:]_block_invoke
+ ___90-[LNClientConnection fetchDisplayRepresentationsForEntities:components:completionHandler:]_block_invoke_2
+ ___90-[LNClientConnection fetchDisplayRepresentationsForEntities:components:completionHandler:]_block_invoke_3
+ ___90-[LNClientConnection fetchDisplayRepresentationsForEntities:components:completionHandler:]_block_invoke_4
+ ___90-[LNClientConnection fetchDisplayRepresentationsForEntities:components:completionHandler:]_block_invoke_5
+ ___AppIntentMigrations_isAvailable
+ ___block_descriptor_32_e30_v24?0"NSString"8"NSError"16l
+ ___block_descriptor_40_e8_32bs_e17_v16?0"NSError"8ls32l8
+ ___block_descriptor_40_e8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_48_e8_32bs40r_e30_v24?0"NSString"8"NSError"16lr40l8s32l8
+ ___block_descriptor_48_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_48_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_56_e8_32s_e5_v8?0ls32l8
+ ___swift_cannot_copy_noncopyable_type
+ ___swift_closure_destructor.101Tm
+ ___swift_closure_destructor.28Tm
+ ___swift_exist.box.addr_destructor.312Tm
+ ___swift_exist.box.addr_destructor.522Tm
+ ___swift_exist.box.addr_destructor.524Tm
+ ___swift_exist.box.addr_destructor.569Tm
+ ___swift_exist.box.addr_destructor.571Tm
+ ___swift_exist.box.addr_destructor.573Tm
+ ___unnamed_23
+ ___unnamed_26
+ ___unnamed_27
+ ___unnamed_35
+ __os_feature_enabled_impl
+ _associated conformance 10AppIntents19ObviatedIntentErrorO10Foundation13CustomNSErrorAAs0E0
+ _associated conformance 10AppIntents19ObviatedIntentErrorOSHAASQ
+ _associated conformance 10AppIntents23UserIdentityAccessLevelOSHAASQ
+ _associated conformance 10AppIntents28DynamicMigrationRuntimeErrorO10Foundation13CustomNSErrorAAs0F0
+ _associated conformance 10AppIntents28DynamicMigrationRuntimeErrorOSHAASQ
+ _dispatch_after
+ _dispatch_assert_queue$V2
+ _dispatch_time
+ _get_enum_tag_for_layout_string 10AppIntents17MigrationValue_v1V7StorageOyx_G
+ _symbolic $s10AppIntents12Migration_v1P
+ _symbolic $s10AppIntents17ObviatedIntent_v1P
+ _symbolic $s10AppIntents18StaticMigration_v1P
+ _symbolic $s10AppIntents19DynamicMigration_v1P
+ _symbolic 11NeverResult_____Qz 10AppIntents17ObviatedIntent_v1P
+ _symbolic 2To_____Qz 10AppIntents12Migration_v1P
+ _symbolic 4From_____Qz 10AppIntents12Migration_v1P
+ _symbolic SDy__________G s6UInt32V s5Int32V
+ _symbolic SDyx_____G s5Int32V
+ _symbolic Say_____G 10AppIntents10ShowReasonO
+ _symbolic Say_____G 10AppIntents10SkipReasonO
+ _symbolic SctSg7perform_ScTyyt_____GSg9operationt s5NeverO
+ _symbolic Si______Sgt 10AppIntents21DisplayRepresentationV
+ _symbolic So11LNParameterC
+ _symbolic So21LNActionMigrationNodeC
+ _symbolic So8LNActionCSgSo7NSErrorCSgIeyByy_
+ _symbolic _____ 10AppIntents17MigrationValue_v1V
+ _symbolic _____ 10AppIntents17MigrationValue_v1V7StorageO
+ _symbolic _____ 10AppIntents19ObviatedIntentErrorO
+ _symbolic _____ 10AppIntents23UserIdentityAccessLevelO
+ _symbolic _____ 10AppIntents24InProcessLongRunningTask33_9252267F7014912BD235250E1970668ALLC
+ _symbolic _____ 10AppIntents25StaticMigrationBuilder_v1O
+ _symbolic _____ 10AppIntents25StaticMigrationMapping_v1V
+ _symbolic _____ 10AppIntents28DynamicMigrationRuntimeErrorO
+ _symbolic _____ 10AppIntents8LRUCacheV4Node33_9F738B91F792166B1E1208C8C932B734LLV
+ _symbolic _____ So33LNDisplayRepresentationComponentsV
+ _symbolic _____ s5Int32V
+ _symbolic _____Sg 10AppIntents23UserIdentityAccessLevelO
+ _symbolic _____Sg 10AppIntents24InProcessLongRunningTask33_9252267F7014912BD235250E1970668ALLC
+ _symbolic _____ySSSaySiGG s18_DictionaryStorageC
+ _symbolic _____ySctSg7perform_ScTyyt_____GSg9operationtG 15Synchronization5MutexVAARi_zrlE s5NeverO
+ _symbolic _____ySctSg7perform_ScTyyt_____GSg9operationtG 15Synchronization5_CellVAARi_zrlE s5NeverO
+ _symbolic _____y_____Sg______pG s6ResultOsRi_zRi0_zrlE 10AppIntents21DisplayRepresentationV s5ErrorP
+ _symbolic _____y_____Sg______pGSg s6ResultOsRi_zRi0_zrlE 10AppIntents21DisplayRepresentationV s5ErrorP
+ _symbolic _____y__________G s17_NativeDictionaryV s6UInt32V s5Int32V
+ _symbolic _____y___________G 10AppIntents8LRUCacheV4Node33_9F738B91F792166B1E1208C8C932B734LLV s6UInt32V AA14ViewAnnotationO
+ _symbolic _____y_____y_____Sg______pGSgG s23_ContiguousArrayStorageC s6ResultOsRi_zRi0_zrlE 10AppIntents21DisplayRepresentationV s5ErrorP
+ _symbolic _____y_____y__________GG 15Synchronization5MutexVAARi_zrlE 10AppIntents8LRUCacheV s6UInt32V AD14ViewAnnotationO
+ _symbolic _____y_____y___________GG s23_ContiguousArrayStorageC 10AppIntents8LRUCacheV4Node33_9F738B91F792166B1E1208C8C932B734LLV s6UInt32V AC14ViewAnnotationO
+ _symbolic _____y_____yxq__GG s15ContiguousArrayV 10AppIntents8LRUCacheV4Node33_9F738B91F792166B1E1208C8C932B734LLV
+ _symbolic _____yq_G s14PartialKeyPathC
+ _symbolic _____yxG 10AppIntents17MigrationValue_v1V
+ _symbolic _____yx_G 10AppIntents17MigrationValue_v1V7StorageO
+ _type_layout_string 10AppIntents0A6IntentRzAaBR_r0_lAA25StaticMigrationMapping_v1Vyxq_G
+ _type_layout_string l10AppIntents17MigrationValue_v1V7StorageOyx_G
+ _type_layout_string l10AppIntents17MigrationValue_v1VyxG
- -[LNProcessInstanceRegistryClient makeXPCConnection]
- -[LNProcessInstanceRegistryClient registerWithError:]
- GCC_except_table357
- GCC_except_table361
- GCC_except_table363
- GCC_except_table367
- GCC_except_table378
- GCC_except_table381
- GCC_except_table383
- GCC_except_table62
- _OBJC_CLASS_$_LNNLGDialog
- _OBJC_CLASS_$_LNNLGRepresentation
- _OUTLINED_FUNCTION_555
- _OUTLINED_FUNCTION_556
- _OUTLINED_FUNCTION_557
- _OUTLINED_FUNCTION_558
- _OUTLINED_FUNCTION_559
- _OUTLINED_FUNCTION_560
- _OUTLINED_FUNCTION_561
- _OUTLINED_FUNCTION_562
- _OUTLINED_FUNCTION_563
- _OUTLINED_FUNCTION_564
- _OUTLINED_FUNCTION_565
- _OUTLINED_FUNCTION_566
- _OUTLINED_FUNCTION_567
- _OUTLINED_FUNCTION_568
- _OUTLINED_FUNCTION_569
- _OUTLINED_FUNCTION_570
- _OUTLINED_FUNCTION_571
- _OUTLINED_FUNCTION_572
- _OUTLINED_FUNCTION_573
- _OUTLINED_FUNCTION_574
- _OUTLINED_FUNCTION_575
- _OUTLINED_FUNCTION_576
- _OUTLINED_FUNCTION_577
- _OUTLINED_FUNCTION_578
- _OUTLINED_FUNCTION_579
- _OUTLINED_FUNCTION_580
- _OUTLINED_FUNCTION_581
- _OUTLINED_FUNCTION_582
- _OUTLINED_FUNCTION_583
- _OUTLINED_FUNCTION_584
- _OUTLINED_FUNCTION_585
- _OUTLINED_FUNCTION_586
- _OUTLINED_FUNCTION_587
- _OUTLINED_FUNCTION_588
- _OUTLINED_FUNCTION_589
- _OUTLINED_FUNCTION_590
- _OUTLINED_FUNCTION_591
- _OUTLINED_FUNCTION_592
- _OUTLINED_FUNCTION_593
- _OUTLINED_FUNCTION_594
- _OUTLINED_FUNCTION_595
- _OUTLINED_FUNCTION_596
- _OUTLINED_FUNCTION_597
- _OUTLINED_FUNCTION_598
- _OUTLINED_FUNCTION_599
- _OUTLINED_FUNCTION_600
- _OUTLINED_FUNCTION_601
- _OUTLINED_FUNCTION_602
- _OUTLINED_FUNCTION_603
- _OUTLINED_FUNCTION_604
- _OUTLINED_FUNCTION_605
- _OUTLINED_FUNCTION_606
- _OUTLINED_FUNCTION_607
- _OUTLINED_FUNCTION_608
- __DATA__TtC10AppIntents21EntityDonationManager
- __DATA__TtC10AppIntents30SuggestedEntityDonationManager
- __IVARS__TtCV10AppIntents8LRUCacheP33_9F738B91F792166B1E1208C8C932B7344Node
- __METACLASS_DATA__TtC10AppIntents21EntityDonationManager
- __METACLASS_DATA__TtC10AppIntents30SuggestedEntityDonationManager
- __OBJC_$_INSTANCE_METHODS_LNAppContext(AppIntents|AppIntents1|AppIntents2|AppIntents3|AppIntents4|AppIntents5|AppIntents6|AppIntents7|AppIntents8|AppIntents9|AppIntents10|AppIntents11|AppIntents12|AppIntents13|AppIntents14|AppIntents15|AppIntents16|AppIntents17|AppIntents18|AppIntents19|AppIntents20|AppIntents21|AppIntents22|AppIntents23|AppIntents24|AppIntents25|AppIntents26|AppIntents27|AppIntents28|AppIntents29)
- __OBJC_$_INSTANCE_METHODS_LNProcessInstanceRegistryClient
- ___52-[LNProcessInstanceRegistryClient makeXPCConnection]_block_invoke
- ___53-[LNProcessInstanceRegistryClient registerWithError:]_block_invoke
- ___block_descriptor_40_e8_32r_e17_v16?0"NSError"8lr32l8
- ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
- ___block_descriptor_56_e8_32s40r48r_e30_v24?0"NSString"8"NSError"16lr40l8r48l8s32l8
- ___block_descriptor_56_e8_32s40r48r_e5_v8?0ls32l8r40l8r48l8
- ___swift_closure_destructor.63Tm
- ___swift_exist.box.addr_destructor.523Tm
- ___swift_exist.box.addr_destructor.525Tm
- ___swift_exist.box.addr_destructor.527Tm
- ___swift_exist.box.addr_destructor.572Tm
- ___swift_exist.box.addr_destructor.574Tm
- ___swift_exist.box.addr_destructor.576Tm
- ___swift_exist.box.addr_destructor.824Tm
- ___unnamed_21
- ___unnamed_24
- ___unnamed_33
- _dispatch_get_global_queue
- _objc_unsafeClaimAutoreleasedReturnValue
- _symbolic SDyx_____yxq__GG 10AppIntents8LRUCacheV4Node33_9F738B91F792166B1E1208C8C932B734LLC
- _symbolic _____ 10AppIntents21EntityDonationManagerC
- _symbolic _____ 10AppIntents30SuggestedEntityDonationManagerC
- _symbolic _____ 10AppIntents8LRUCacheV4Node33_9F738B91F792166B1E1208C8C932B734LLC
- _symbolic ______pSg 10AppIntents29PerformActionExecutorDelegateP
- _symbolic _____y___________G 10AppIntents8LRUCacheV4Node33_9F738B91F792166B1E1208C8C932B734LLC s6UInt32V AA14ViewAnnotationO
- _symbolic _____y__________yAB______GG s17_NativeDictionaryV s6UInt32V 10AppIntents8LRUCacheV4Node33_9F738B91F792166B1E1208C8C932B734LLC AE14ViewAnnotationO
- _symbolic _____y_____y__________GG 2os21OSAllocatedUnfairLockV 10AppIntents8LRUCacheV s6UInt32V AD14ViewAnnotationO
- _symbolic _____y_____y__________G_____G s13ManagedBufferCsRi__rlE 10AppIntents8LRUCacheV s6UInt32V AC14ViewAnnotationO So16os_unfair_lock_sV
- _symbolic _____yxq__GSg 10AppIntents8LRUCacheV4Node33_9F738B91F792166B1E1208C8C932B734LLC
- _type_layout_string SHRzr0_l10AppIntents8LRUCacheVyxq_G
CStrings:
+ "App intent migrations are not enabled."
+ "AppIntentMigrations"
+ "AppIntents"
+ "Created a new Process Instance Registry XPC connection (inactive), generation %lu"
+ "Dropped the invalidated Process Instance Registry connection; the next registration will reconnect"
+ "Failed to migrate the Focus Filter saved as %{public}s: %{public}@"
+ "Ignoring interruption of a superseded Process Instance Registry connection (generation %lu)"
+ "Ignoring invalidation of a superseded Process Instance Registry connection (generation %lu)"
+ "Migrated the Focus Filter saved as %{public}s up to %{public}s"
+ "Migrating the saved Focus Filter %{public}s through %{public}ld step(s)"
+ "Migration step %ld→%ld failed; returning highest migrated version. Error: %{public}@"
+ "Migration step %ld→%ld failed; trying another path. Error: %{public}@"
+ "No IntentContext available for background processing"
+ "Registration with the Process Instance Registry is asynchronous; use registerWithCompletionHandler: to obtain the process instance identifier."
+ "Running migration %{public}ld→%{public}ld: %{public}s to %{public}s"
+ "Skipping re-try, a registration has already succeeded"
+ "Skipping re-try, the connection has been replaced"
+ "Timed out after %{public}.2f seconds waiting for linkd to reply to the registration"
+ "Unable to fetch display representations for %s: %s"
+ "Unable to get remoteObjectProxy, error: %{public}@"
+ "Unable to register process with linkd, error: %{public}@"
+ "Unable to register with Process Instance Registry, error: %{public}@"
+ "Unable to resolve entity type %s while fetching display representations"
+ "Unexpectedly called perform() on an ObviatedIntent"
+ "Will re-try to establish the connection in %.1f s (attempt %ld of %ld)"
+ "[%{public}s %{public}s] Cancelled in-process perform and operation tasks with reason: %{public}ld"
+ "_in_outgoingSecurityScope"
+ "com.apple.appintents.process-instance-registry-client.registration"
+ "index entity "
+ "linkd replied without a process instance identifier and without an error"
+ "localizedApplicationName: could not determine application name"
+ "localizedApplicationName: isExtension=%{bool,public}d, contextName=%{public}s, lsName=%{public}s, bundleName=%{public}s"
+ "registerAndSubmitBackgroundTask(identifier:options:operation:inProcessTask:)"
- "Created a new Process Instance Registry XPC connection (inactive)"
- "Unable to get synchronousRemoteObjectProxy, error: %{public}@"
- "[%{public}s %{public}s] No IntentContext available"
- "com.apple.appintents.process-instance-registry-client.retry-%ld"
- "localizedApplicationName: LS lookup succeeded with '%s'"
- "localizedApplicationName: falling back to Bundle.main.localizedName='%s'"
- "localizedApplicationName: isExtension=%{bool}d, displayName=%s, bundleName=%s, contextName=%s"
- "registerAndSubmitBackgroundTask(identifier:options:operation:)"
```
