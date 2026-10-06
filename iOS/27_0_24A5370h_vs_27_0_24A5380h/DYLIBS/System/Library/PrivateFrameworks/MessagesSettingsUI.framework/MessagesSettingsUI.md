## MessagesSettingsUI

> `/System/Library/PrivateFrameworks/MessagesSettingsUI.framework/MessagesSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33884` | `0x36018` | **`+0x2794`** |
| `__AUTH_CONST.__objc_const` | `0x3170` | `0x33a8` | **`+0x238`** |
| `__TEXT.__const` | `0x2554` | `0x26f4` | **`+0x1a0`** |
| `__AUTH.__objc_data` | `0xaa0` | `0xbf0` | **`+0x150`** |
| `__TEXT.__oslogstring` | `0x925` | `0xa65` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0xdf8` | `0xf00` | **`+0x108`** |
| `__TEXT.__cstring` | `0x1fb0` | `0x20b0` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0xbc` | `0x18c` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0xe38` | `0xef8` | **`+0xc0`** |
| `__DATA.__bss` | `0x2380` | `0x2430` | **`+0xb0`** |
| `__DATA.__data` | `0xcac` | `0xd4c` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x163c` | `0x16cc` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x906` | `0x986` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x2e2c` | `0x2e8c` | **`+0x60`** |
| `__AUTH.__data` | `0x1678` | `0x16d0` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x11c0` | `0x1218` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x6d0` | `0x71c` | **`+0x4c`** |
| `__TEXT.__gcc_except_tab` | `0x98c` | `0x9d4` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x164` | `0x198` | **`+0x34`** |
| `__DATA_CONST.__objc_selrefs` | `0x14e8` | `0x1518` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x6c0` | `0x6e8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1540` | `0x1560` | **`+0x20`** |
| `__DATA.__common` | `0x40` | `0x58` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0xae8` | `0xaf8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x30` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xb0` | `0xb8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xf0` | `0xf4` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0x108` | `0x10c` | **`+0x4`** |

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  Functions: 1262
-  Symbols:   1518
-  CStrings:  345
+  Functions: 1343
+  Symbols:   1540
+  CStrings:  354
Symbols:
+ -[CKiCloudSettingsSyncController assetDownloadPresentableStatus]
+ -[CKiCloudSettingsSyncController cachedAttachmentDuration]
+ -[CKiCloudSettingsSyncController cachedSyncState]
+ -[CKiCloudSettingsSyncController notifySyncStatusHandlerWithStatusUpdate]
+ -[CKiCloudSettingsSyncController setCachedAttachmentDuration:]
+ -[CKiCloudSettingsSyncController setCachedSyncState:]
+ -[CKiCloudSettingsViewModel isAttachmentTimeRangeRequestInProgress]
+ -[CKiCloudSettingsViewModel priorAttachmentTimeRange]
+ -[CKiCloudSettingsViewModel setAttachmentTimeRangeRequestInProgress:]
+ GCC_except_table13
+ GCC_except_table40
+ GCC_except_table41
+ _OBJC_CLASS_$_CKAttachmentAssetDownloadPresentableStatus
+ _OBJC_CLASS_$__TtC18MessagesSettingsUI27AttachmentDownloadViewModel
+ _OBJC_IVAR_$_CKiCloudSettingsSyncController._assetDownloadPresentableStatus
+ _OBJC_IVAR_$_CKiCloudSettingsSyncController._cachedAttachmentDuration
+ _OBJC_IVAR_$_CKiCloudSettingsSyncController._cachedSyncState
+ _OBJC_IVAR_$_CKiCloudSettingsViewModel._attachmentTimeRangeRequestInProgress
+ _OBJC_METACLASS_$_CKAttachmentAssetDownloadPresentableStatus
+ _OBJC_METACLASS_$__TtC18MessagesSettingsUI27AttachmentDownloadViewModel
+ __DATA_CKAttachmentAssetDownloadPresentableStatus
+ __DATA__TtC18MessagesSettingsUI27AttachmentDownloadViewModel
+ __INSTANCE_METHODS_CKAttachmentAssetDownloadPresentableStatus
+ __INSTANCE_METHODS__TtC18MessagesSettingsUI27AttachmentDownloadViewModel
+ __IVARS_CKAttachmentAssetDownloadPresentableStatus
+ __IVARS__TtC18MessagesSettingsUI27AttachmentDownloadViewModel
+ __METACLASS_DATA_CKAttachmentAssetDownloadPresentableStatus
+ __METACLASS_DATA__TtC18MessagesSettingsUI27AttachmentDownloadViewModel
+ __PROPERTIES_CKAttachmentAssetDownloadPresentableStatus
+ __PROTOCOLS__TtC18MessagesSettingsUI27AttachmentDownloadViewModel
+ ___53-[CKiCloudSettingsViewModel priorAttachmentTimeRange]_block_invoke
+ ___53-[CKiCloudSettingsViewModel priorAttachmentTimeRange]_block_invoke_2
+ _objc_retain_x27
+ _symbolic So19IMCloudKitSyncStateC
+ _symbolic So42CKAttachmentAssetDownloadPresentableStatusC
+ _symbolic _____ 18MessagesSettingsUI27AttachmentDownloadViewModelC
+ _symbolic _____ So41CKAttachmentAssetDownloadPresentablePhaseV
+ _symbolic _____SgXw 18MessagesSettingsUI27AttachmentDownloadViewModelC
+ _symbolic _____SgXwz_Xx 18MessagesSettingsUI27AttachmentDownloadViewModelC
- -[CKCloudSettingsViewController earliestKeptAttachmentDuration]
- -[CKCloudSettingsViewController isAttachmentTimeRangeRequestInProgress]
- -[CKCloudSettingsViewController setAttachmentTimeRangeRequestInProgress:]
- -[CKCloudSettingsViewController setEarliestKeptAttachmentDuration:]
- -[CKiCloudSettingsViewModel _attachmentDownloadTimeFrameDisplayString]
- -[CKiCloudSettingsViewModel cachedAttachmentDownloadTimeFrame]
- -[CKiCloudSettingsViewModel setCachedAttachmentDownloadTimeFrame:]
- GCC_except_table38
- GCC_except_table39
- _IMCloudKitGetSyncStateDictionary
- _OBJC_IVAR_$_CKCloudSettingsViewController._attachmentTimeRangeRequestInProgress
- _OBJC_IVAR_$_CKCloudSettingsViewController._earliestKeptAttachmentDuration
- _OBJC_IVAR_$_CKiCloudSettingsViewModel._cachedAttachmentDownloadTimeFrame
- ___80-[CKCloudSettingsViewController(SyncStateSpecifiers) _priorAttachmentTimeRange:]_block_invoke
- ___80-[CKCloudSettingsViewController(SyncStateSpecifiers) _priorAttachmentTimeRange:]_block_invoke_2
- _swift_dynamicCastObjCClass
- _symbolic _____SgXwz_Xx 18MessagesSettingsUI38CKDownloadAttachmentsDetailsControllerC
CStrings:
+ "Attachment download status update — phase=%ld, remaining=%ld, finished=%@, timeFrame=%ld"
+ "Attachment download status update — phase=%lu, remaining=%ld, finished=%{bool}d, timeFrame=%ld"
+ "Attachment download time frame changed: %ld -> %ld"
+ "MessagesSettingsUI.CKAttachmentAssetDownloadPresentableStatus"
+ "SYNC_ALL_ATTACHMENTS_DOWNLOADED"
+ "SYNC_BEFORE_ALL_BUTTON"
+ "SYNC_BEFORE_SHORT_N_DOWNLOADING"
+ "SYNC_DOWNLOADING_N_ATTACHMENTS"
+ "SYNC_PENDING_ATTACHMENT_DOWNLOAD"
+ "User tapped Download All Attachments"
+ "iCloudSettings_Messages"
- "\""
- "SYNC_BEFORE_N_DAYS"
```
