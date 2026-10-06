## assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistantd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x372924` | `0x372e38` | **`+0x514`** |
| `__TEXT.__objc_methname` | `0x61cb0` | `0x61dac` | **`+0xfc`** |
| `__TEXT.__objc_stubs` | `0x474c0` | `0x47540` | **`+0x80`** |
| `__DATA.__objc_const` | `0x34c78` | `0x34cf0` | **`+0x78`** |
| `__TEXT.__cstring` | `0x52ede` | `0x52f49` | **`+0x6b`** |
| `__TEXT.__objc_methlist` | `0x23730` | `0x23798` | **`+0x68`** |
| `__TEXT.__objc_methtype` | `0xff75` | `0xffaf` | **`+0x3a`** |
| `__DATA.__objc_selrefs` | `0x15610` | `0x15638` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x3850` | `0x3870` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1c38` | `0x1c48` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2698` | `0x26a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.68.61.11.9
+3600.68.61.11.11

-  Functions: 14634
-  Symbols:   3005
-  CStrings:  27900
+  Functions: 14642
+  Symbols:   3007
+  CStrings:  27910
Symbols:
+ __AFPreferencesAdvanceSiriDataSharingOptInStatusVersionWithContext
+ __AFPreferencesSiriDataSharingOptInStatusVersionWithContext
CStrings:
+ " companionDesiredOrchestrationMode: %@ dataSharingOptInVersion: %ld"
+ "-[ADSettingsClient advanceSiriDataSharingOptInStatusVersionTo:completion:]"
+ "2"
+ "MobileAssistantDaemons-3600.68.61.11.11"
+ "TI,N,V_dataSharingOptInVersion"
+ "TQ,N,V_dataSharingOptInVersion"
+ "Vv32@0:8Q16@?<v@?@\"NSError\">24"
+ "_dataSharingOptInVersion"
+ "advanceSiriDataSharingOptInStatusVersionTo:completion:"
+ "dataSharingOptInVersion"
+ "data_sharing_opt_in_version"
+ "hasDataSharingOptInVersion"
+ "setDataSharingOptInVersion:"
+ "setHasDataSharingOptInVersion:"
+ "{?=\"companionDesiredOrchestrationMode\"b1\"dataSharingOptInVersion\"b1\"activityContinuationAllowed\"b1\"cloudSyncEnabled\"b1\"dictationEnabled\"b1\"fullUodEnabled\"b1\"isLocationSharingDevice\"b1\"isRemotePlaybackDevice\"b1\"shouldCensorSpeech\"b1\"siriEnabled\"b1}"
- " companionDesiredOrchestrationMode: %@"
- "5"
- "MobileAssistantDaemons-3600.68.61.11.9"
- "https://seed.siri.apple.com"
- "{?=\"activityContinuationAllowed\"b1\"companionDesiredOrchestrationMode\"b1\"cloudSyncEnabled\"b1\"dictationEnabled\"b1\"fullUodEnabled\"b1\"isLocationSharingDevice\"b1\"isRemotePlaybackDevice\"b1\"shouldCensorSpeech\"b1\"siriEnabled\"b1}"
```
