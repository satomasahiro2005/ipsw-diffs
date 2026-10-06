## imagent

> `/System/Library/PrivateFrameworks/IMCore.framework/imagent.app/imagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5fe88` | `0x619d0` | **`+0x1b48`** |
| `__TEXT.__oslogstring` | `0x6b3b` | `0x6d7b` | **`+0x240`** |
| `__TEXT.__objc_methname` | `0xc819` | `0xc9a9` | **`+0x190`** |
| `__DATA_CONST.__const` | `0x2440` | `0x2508` | **`+0xc8`** |
| `__TEXT.__objc_methtype` | `0x3385` | `0x33f7` | **`+0x72`** |
| `__DATA.__data` | `0x17a8` | `0x1810` | **`+0x68`** |
| `__TEXT.__const` | `0x1a00` | `0x1a40` | **`+0x40`** |
| `__DATA.__objc_const` | `0x32b8` | `0x32e8` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x1828` | `0x1858` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x3300` | `0x3330` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x3450` | `0x3474` | **`+0x24`** |
| `__TEXT.__swift5_capture` | `0x7a8` | `0x7cc` | **`+0x24`** |
| `__DATA.__bss` | `0x12e0` | `0x1300` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1aa0` | `0x1ac0` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x8f4` | `0x914` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x9f5` | `0xa15` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x3bc` | `0x3d8` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x2bb0` | `0x2bc8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1d40` | `0x1d58` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x78` | `0x8c` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0xd60` | `0xd70` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x208` | `0x218` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xb08` | `0xb00` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x100` | `0x108` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x926` | `0x92e` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xfc` | `0x104` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x78` | `0x7c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x114` | `0x118` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-1486.100.5.2.1
+1487.100.6.2.2

-  Functions: 1506
-  Symbols:   620
-  CStrings:  2547
+  Functions: 1518
+  Symbols:   621
+  CStrings:  2560
Symbols:
+ _IMDCoreSpotlightDeleteAttachmentGUIDsWithCompletion
+ _swift_retain_x25
+ _swift_retain_x27
- _OBJC_CLASS_$_IMDIndexingContext
- _swift_release_x27
CStrings:
+ "23:08:10"
+ "IMDContactIndexingQueries"
+ "Jul 15 2026"
+ "Request from %@ to persist assistant action calendar item identifier for message GUID: %@"
+ "decisioningMetadata"
+ "deleteAttachment(atFileURL:) received a nil fileURL; dropping request"
+ "generatePreview(forTransferGUID:) received a nil previewURL; dropping request for transfer %s"
+ "generatePreview(forTransferGUID:fileURL:) received a nil fileURL or previewURL; dropping request for transfer %s"
+ "historyQuery:chatID:services:finishedWithResult:limit:hasMessagesBefore:hasMessagesAfter:"
+ "persistAssistantActionSuggestionCalendarItemIdentifier:forActionIdentifier:messagePartIndex:messageGUID:"
+ "runIndexManagementTaskAllowedToInitiateReindexing:canScheduleTasks:overrideUpgradePlan:migrationRequirements:vacuumRequirements:laneRequirement:reason:completion:"
+ "storeAttachment(withSource:) received a nil source URL; dropping request for transfer %s"
+ "updateAssistantActionSuggestionCalendarItemIdentifier:forActionIdentifier:messagePartIndex:messageGUID:"
+ "updateSpamModelMetadataWith:wasJunk:isJunk:"
+ "urlWrapper(forFileURL:) received a nil fileURL; dropping request"
+ "v32@0:8Q16@?24"
+ "v32@0:8Q16@?<v@?B@\"NSError\">24"
+ "v48@0:8@\"NSString\"16@\"NSString\"24q32@\"NSString\"40"
+ "v68@0:8B16B20B24Q28Q36Q44q52@?60"
+ "v68@0:8B16B20B24Q28Q36Q44q52@?<v@?@\"NSError\">60"
+ "v84@0:8@\"NSString\"16@\"NSArray\"24C32@\"NSArray\"36q44@\"NSString\"52@\"NSString\"60@\"NSString\"68@?<v@?@\"NSArray\"@\"NSArray\"BB>76"
+ "vacuumItemsWithRequirements:completionHandler:"
- "17:18:39"
- "Jul  2 2026"
- "contextWithReason:"
- "historyQuery:chatID:services:finishedWithResult:limit:"
- "runIndexManagementTaskAllowedToInitiateReindexing:canScheduleTasks:overrideUpgradePlan:migrationRequirements:laneRequirement:reason:completion:"
- "setSpamModelMetadata:"
- "v60@0:8B16B20B24Q28Q36q44@?52"
- "v60@0:8B16B20B24Q28Q36q44@?<v@?@\"NSError\">52"
- "v84@0:8@\"NSString\"16@\"NSArray\"24C32@\"NSArray\"36q44@\"NSString\"52@\"NSString\"60@\"NSString\"68@?<v@?@\"NSArray\"@\"NSArray\">76"
```
