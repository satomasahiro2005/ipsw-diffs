## Bridge

> `/private/var/staged_system_apps/Bridge.app/Bridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23f034` | `0x240040` | **`+0x100c`** |
| `__TEXT.__eh_frame` | `0x41c4` | `0x426c` | **`+0xa8`** |
| `__DATA_CONST.__const` | `0xbcc0` | `0xbd58` | **`+0x98`** |
| `__TEXT.__oslogstring` | `0x15d4a` | `0x15dda` | **`+0x90`** |
| `__TEXT.__objc_methname` | `0x3d315` | `0x3d365` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x22680` | `0x226c0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x8440` | `0x8480` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x139c` | `0x13d0` | **`+0x34`** |
| `__DATA.__objc_selrefs` | `0xd3c0` | `0xd3d8` | **`+0x18`** |
| `__DATA.__bss` | `0xa508` | `0xa518` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x5ae0` | `0x5ad0` | **`-0x10`** |
| `__TEXT.__const` | `0x28da6` | `0x28db6` | **`+0x10`** |
| `__TEXT.__cstring` | `0x180de` | `0x180ee` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x354` | `0x364` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2d88` | `0x2d80` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1610` | `0x1618` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2bc8` | `0x2bd0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1694c` | `0x16954` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x82f9` | `0x8301` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x264` | `0x268` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x254` | `0x258` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_nlclslist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1359.7.0.0.0
+1359.9.0.0.0

+  - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices

-  - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels

-  Functions: 12473
+  Functions: 12488

-  CStrings:  15550
+  CStrings:  15556
Symbols:
+ _BPSIsPhoneAppStoreAutoUpdateEnabled
+ _BPSSetPhoneAppStoreAutoUpdate
+ _OBJC_CLASS_$_AFSystemAssistantExperienceStatusManager
- _$s16GenerativeModels0aB12AvailabilityV13shouldBeShown19inSettingsReturningSbSpySo20GMAvailabilityStatusVG_tFZ
- _BPSIsAppStoreAccountAutoUpdateEnabled
- _BPSSetAppStoreAccountAutoUpdate
CStrings:
+ "(AppStoreAutoUpdate) reconcile skipped: already offered and nothing pending"
+ "(AppStoreAutoUpdate) reconcile: autoUpdateOn=%{BOOL}d alreadyShown=%{BOOL}d pending=%{BOOL}d"
+ "(COSAppStoreAutoUpdateOptin) user accepted; enabled iPhone App Store auto-update"
+ "(COSAppStoreAutoUpdateOptin) user declined; dismissing without write"
+ "App Store auto-update follow-up cleared, reloading root settings specifiers"
+ "COSAppStoreAutoUpdateFollowUpClearedNotification"
+ "Presenting device picker on launch"
+ "SiriSetupWatchIntroViewController"
+ "appStoreAutoUpdateFollowUpCleared:"
+ "com.apple.Bridge.appStoreAutoUpdateReconcile"
+ "desiredOrchestrationModeIfEnabled"
+ "resolveFollowUp"
+ "siriAvailability"
- "(AppStoreAutoUpdate) offer bail: could not resolve opt-in pane class"
- "(AppStoreAutoUpdate) reconcile: autoUpdateOn=%{BOOL}d paneMarked=%{BOOL}d"
- "(COSAppStoreAutoUpdateOptin) requested App Store auto-update enabled=%{BOOL}d (applied=%{BOOL}d)"
- "Presenting device picker for revision lock update"
- "SiriVoiceTraining"
- "com.apple.appstored.NanoSettingsStateChanged"
- "skippedSetupPaneClassesForDevice:"
```
