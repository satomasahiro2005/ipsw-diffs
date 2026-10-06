## jetpackassetd

> `/System/Library/PrivateFrameworks/JetCore.framework/Support/jetpackassetd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb4548` | `0xba58c` | **`+0x6044`** |
| `__TEXT.__cstring` | `0x5f34` | `0x6314` | **`+0x3e0`** |
| `__TEXT.__eh_frame` | `0x8568` | `0x8880` | **`+0x318`** |
| `__DATA.__bss` | `0x4100` | `0x4280` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x2fa8` | `0x3108` | **`+0x160`** |
| `__TEXT.__swift5_reflstr` | `0xfa8` | `0x1098` | **`+0xf0`** |
| `__TEXT.__const` | `0x3e08` | `0x3ed8` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x2970` | `0x2a18` | **`+0xa8`** |
| `__TEXT.__swift5_fieldmd` | `0x12a8` | `0x133c` | **`+0x94`** |
| `__TEXT.__auth_stubs` | `0x2e90` | `0x2ed0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x790` | `0x7c8` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x8ec` | `0x924` | **`+0x38`** |
| `__TEXT.__swift_as_ret` | `0x534` | `0x560` | **`+0x2c`** |
| `__DATA.__data` | `0x1ca0` | `0x1cc8` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x1207` | `0x1229` | **`+0x22`** |
| `__DATA_CONST.__auth_got` | `0x1750` | `0x1770` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xac0` | `0xae0` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x10e8` | `0x1104` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x350` | `0x368` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x748` | `0x758` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0xe6e` | `0xe7e` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x274` | `0x280` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x3b8` | `0x3c0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x174` | `0x178` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x24c` | `0x250` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-10.0.47.0.0
+10.1.8.0.0

-  Functions: 2163
-  Symbols:   1154
-  CStrings:  722
+  Functions: 2208
+  Symbols:   1165
+  CStrings:  745
Symbols:
+ _$s7JetCore18AssetPendingOriginO10checkpointyA2CmFWC
+ _$s7JetCore18AssetPendingOriginO12apsReconnectyA2CmFWC
+ _$s7JetCore18AssetPendingOriginO12push304RetryyA2CmFWC
+ _$s7JetCore18AssetPendingOriginO4pushyA2CmFWC
+ _$s7JetCore18AssetPendingOriginOMa
+ _$s7JetCore18AssetPendingOriginOMn
+ _$s7JetCore18AssetPendingOriginOSQAAMc
+ _$s7JetCore20PushSubscriptionInfoV2id14assetURLString9channelID06bundleJ005usageJ09isPending0M12SystemClient16scheduleFromDate0q2ToS006serverS0010modifiedAtS08priority16downloadAttempts14requestHeaders13pendingOriginACs5Int32VSg_SSSgA3VS2b10Foundation0S0VSgA3z2USDyS2SGAVtcfC
+ _$s7JetCore26AssetPushSubscriptionStoreP15updateToPending9channelID13scheduleAfter0L6Before8priority9timestamp6originSiSS_S2dSi10Foundation4DateVAA0cI6OriginOtKFTj
+ _$s7JetCore26AssetPushSubscriptionStoreP25rescheduleForPush304Retry2id13scheduleAfter0L6Beforeys5Int32V_S2dtKFTj
+ _$s7JetCore27AssetPushSubscriptionRecordV13pendingOriginAA0c7PendingH0OSgvg
+ _$s7JetCore27AssetPushSubscriptionRecordV16pendingOriginRawSSSgvg
+ _OBJC_CLASS_$_AMSEphemeralDefaults
- _$s7JetCore20PushSubscriptionInfoV2id14assetURLString9channelID06bundleJ005usageJ09isPending0M12SystemClient16scheduleFromDate0q2ToS006serverS0010modifiedAtS08priority16downloadAttempts14requestHeadersACs5Int32VSg_SSSgA3US2b10Foundation0S0VSgA3y2TSDyS2SGtcfC
- _$s7JetCore26AssetPushSubscriptionStoreP15updateToPending9channelID13scheduleAfter0L6Before8priority9timestampSiSS_S2dSi10Foundation4DateVtKFTj
CStrings:
+ " still returned 304, giving up and clearing pending state"
+ " unexpectedly got a 304, scheduling a single retry in "
+ "Attempting to subscribe to channel "
+ "Download failed, but encountered an error while trying to increment the download counter. Error: "
+ "Error during missing channel re-subscription: "
+ "Error occurred while trying to reschedule for push 304 retry. Error: "
+ "Error occurred while trying to reset push subscription pending state. Error: "
+ "Missing channel re-subscription completed. Re-subscribed to "
+ "Post-install Bag pre-load failed, continuing: "
+ "Post-install control channel subscription failed, continuing: "
+ "Push 304-retry for "
+ "Push-triggered refresh for "
+ "Starting re-subscription of missing channels"
+ "Suppressing AMS engagement metrics"
+ "apsReconnect"
+ "maintenance"
+ "networkRevalidated"
+ "push304Retry"
+ "request"
+ "scheduled"
+ "schedulingConfig/push304RetryDelay"
+ "schedulingConfig/push304RetryEnabled"
+ "schedulingConfig/push304RetryScheduleWindow"
+ "setSuppressEngagement:"
- "Error occurred while trying to reset push subscription pending state"
```
