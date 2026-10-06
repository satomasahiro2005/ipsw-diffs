## ReminderKit

> `/System/Library/PrivateFrameworks/ReminderKit.framework/ReminderKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13bedc` | `0x13bfbc` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x11b68` | `0x11bbc` | **`+0x54`** |
| `__AUTH_CONST.__const` | `0x2ce0` | `0x2d00` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x15bf0` | `0x15c10` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6ad8` | `0x6af0` | **`+0x18`** |
| `__TEXT.__cstring` | `0xe532` | `0xe51d` | **`-0x15`** |
| `__DATA_CONST.__objc_selrefs` | `0x7ba0` | `0x7bb0` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x24818` | `0x24820` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x2a48` | `0x2a40` | **`-0x8`** |

### Other Changes

```diff

-4043.0.0.0.0
+4046.11.0.0.0

-  Functions: 8804
-  Symbols:   14302
-  CStrings:  2972
+  Functions: 8808
+  Symbols:   14307
+  CStrings:  2973
Symbols:
+ +[CKAllowedSharingOptions(ReminderKitAdditions) rem_remindersAllowedSharingOptionsIncludingAnyoneWithLink:]
+ -[REMStore(IntelligentGrocery) requestPrewarmGroceryCategorizationModel]
+ GCC_except_table220
+ GCC_except_table252
+ GCC_except_table284
+ GCC_except_table297
+ GCC_except_table313
+ GCC_except_table316
+ __OBJC_$_CLASS_METHODS_REMStore(CalDAVSharing|ChangeTrackingSupport|IndentingUnsupportedSubtasks|ChangeTrackingProvider_IntegrationTestsOnlyAPIsSupport|iMessageInteractionSPI|TipKit|NewsRecipeCard|FamilyChecklist|IntelligentFeatures|TrialClient|IntelligentGrocery|AppStore|EventKitBridging|SiriSearch|CalendarDataAccess|EventKitCompatibility|REMAssignment_ChangeTrackingInternalSupport|REMHashtag_ChangeTrackingInternalSupport|UserActivity|AccountManagement_PrivateSPIs|AccountManagement_Internal|Templates|Sharing|ReplicaManagerProviders|ClientConnections|PhantomObjectRepairing|Debugging|UnitTest|REMListSection|REMSmartListSection|REMTemplateSection)
+ __OBJC_$_INSTANCE_METHODS_REMStore(CalDAVSharing|ChangeTrackingSupport|IndentingUnsupportedSubtasks|ChangeTrackingProvider_IntegrationTestsOnlyAPIsSupport|iMessageInteractionSPI|TipKit|NewsRecipeCard|FamilyChecklist|IntelligentFeatures|TrialClient|IntelligentGrocery|AppStore|EventKitBridging|SiriSearch|CalendarDataAccess|EventKitCompatibility|REMAssignment_ChangeTrackingInternalSupport|REMHashtag_ChangeTrackingInternalSupport|UserActivity|AccountManagement_PrivateSPIs|AccountManagement_Internal|Templates|Sharing|ReplicaManagerProviders|ClientConnections|PhantomObjectRepairing|Debugging|UnitTest|REMListSection|REMSmartListSection|REMTemplateSection)
+ __OBJC_CLASS_PROTOCOLS_$_REMStore(CalDAVSharing|ChangeTrackingSupport|IndentingUnsupportedSubtasks|ChangeTrackingProvider_IntegrationTestsOnlyAPIsSupport|iMessageInteractionSPI|TipKit|NewsRecipeCard|FamilyChecklist|IntelligentFeatures|TrialClient|IntelligentGrocery|AppStore|EventKitBridging|SiriSearch|CalendarDataAccess|EventKitCompatibility|REMAssignment_ChangeTrackingInternalSupport|REMHashtag_ChangeTrackingInternalSupport|UserActivity|AccountManagement_PrivateSPIs|AccountManagement_Internal|Templates|Sharing|ReplicaManagerProviders|ClientConnections|PhantomObjectRepairing|Debugging|UnitTest|REMListSection|REMSmartListSection|REMTemplateSection)
+ ___72-[REMStore(IntelligentGrocery) requestPrewarmGroceryCategorizationModel]_block_invoke
- GCC_except_table250
- GCC_except_table311
- GCC_except_table317
- _RDAutoCategorizationGroceryOperationAuthor
- __OBJC_$_CLASS_METHODS_REMStore(CalDAVSharing|ChangeTrackingSupport|IndentingUnsupportedSubtasks|ChangeTrackingProvider_IntegrationTestsOnlyAPIsSupport|iMessageInteractionSPI|TipKit|NewsRecipeCard|FamilyChecklist|IntelligentFeatures|TrialClient|AppStore|EventKitBridging|SiriSearch|CalendarDataAccess|EventKitCompatibility|REMAssignment_ChangeTrackingInternalSupport|REMHashtag_ChangeTrackingInternalSupport|UserActivity|AccountManagement_PrivateSPIs|AccountManagement_Internal|Templates|Sharing|ReplicaManagerProviders|ClientConnections|PhantomObjectRepairing|Debugging|UnitTest|REMListSection|REMSmartListSection|REMTemplateSection)
- __OBJC_$_INSTANCE_METHODS_REMStore(CalDAVSharing|ChangeTrackingSupport|IndentingUnsupportedSubtasks|ChangeTrackingProvider_IntegrationTestsOnlyAPIsSupport|iMessageInteractionSPI|TipKit|NewsRecipeCard|FamilyChecklist|IntelligentFeatures|TrialClient|AppStore|EventKitBridging|SiriSearch|CalendarDataAccess|EventKitCompatibility|REMAssignment_ChangeTrackingInternalSupport|REMHashtag_ChangeTrackingInternalSupport|UserActivity|AccountManagement_PrivateSPIs|AccountManagement_Internal|Templates|Sharing|ReplicaManagerProviders|ClientConnections|PhantomObjectRepairing|Debugging|UnitTest|REMListSection|REMSmartListSection|REMTemplateSection)
- __OBJC_CLASS_PROTOCOLS_$_REMStore(CalDAVSharing|ChangeTrackingSupport|IndentingUnsupportedSubtasks|ChangeTrackingProvider_IntegrationTestsOnlyAPIsSupport|iMessageInteractionSPI|TipKit|NewsRecipeCard|FamilyChecklist|IntelligentFeatures|TrialClient|AppStore|EventKitBridging|SiriSearch|CalendarDataAccess|EventKitCompatibility|REMAssignment_ChangeTrackingInternalSupport|REMHashtag_ChangeTrackingInternalSupport|UserActivity|AccountManagement_PrivateSPIs|AccountManagement_Internal|Templates|Sharing|ReplicaManagerProviders|ClientConnections|PhantomObjectRepairing|Debugging|UnitTest|REMListSection|REMSmartListSection|REMTemplateSection)
CStrings:
+ "XPC error while requesting grocery categorization model prewarm {error: %{public}@}"
+ "requestPrewarmGroceryCategorizationModel"
- "com.apple.remindd.RDAutoCategorizationGroceryOperation.author"
```
