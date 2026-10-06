## vmd

> `/System/Library/PrivateFrameworks/VisualVoicemail.framework/vmd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbb3c8` | `0xc0fa4` | **`+0x5bdc`** |
| `__TEXT.__gcc_except_tab` | `0xca98` | `0x10d1c` | **`+0x4284`** |
| `__TEXT.__unwind_info` | `0x4028` | `0x49a0` | **`+0x978`** |
| `__DATA.__objc_const` | `0x127b8` | `0x12cf0` | **`+0x538`** |
| `__TEXT.__objc_methname` | `0x12963` | `0x12d7f` | **`+0x41c`** |
| `__TEXT.__objc_methlist` | `0x7c24` | `0x7e74` | **`+0x250`** |
| `__TEXT.__oslogstring` | `0x16107` | `0x16337` | **`+0x230`** |
| `__TEXT.__objc_stubs` | `0xe0e0` | `0xe2a0` | **`+0x1c0`** |
| `__DATA_CONST.__cfstring` | `0x5520` | `0x5640` | **`+0x120`** |
| `__TEXT.__cstring` | `0x47fa` | `0x491a` | **`+0x120`** |
| `__DATA.__objc_data` | `0x1d20` | `0x1e10` | **`+0xf0`** |
| `__TEXT.__objc_methtype` | `0x34f4` | `0x35da` | **`+0xe6`** |
| `__DATA_CONST.__const` | `0x3400` | `0x34e0` | **`+0xe0`** |
| `__DATA.__objc_selrefs` | `0x4778` | `0x4820` | **`+0xa8`** |
| `__TEXT.__objc_classname` | `0xe0a` | `0xe4a` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x79c` | `0x7d0` | **`+0x34`** |
| `__DATA.__bss` | `0x620` | `0x640` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x2e0` | `0x2f8` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x18b0` | `0x18a0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xc70` | `0xc68` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x820` | `0x828` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2b8` | `0x2c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-954.0.0.0.0
+956.0.0.0.0

-  Functions: 3551
-  Symbols:   710
-  CStrings:  5832
+  Functions: 3605
+  Symbols:   709
+  CStrings:  5898
Symbols:
- ___memcpy_chk
CStrings:
+ "%s#E %s%sGet QuickSwitch mode failed for account UUID %@, could not find service"
+ "%s#E %s%sGet QuickSwitch parameters failed for account UUID %@, could not find subscription"
+ "%s#E Fetch failed, executing completion"
+ "%s#I %s Get QuickSwitch mode %s for accountUUID %@"
+ "%s#I %s%s%@ is notifying delegates about voicemail store changed"
+ "%s#I Fetch already in progress, %@ (pending: %lu)"
+ "%s#I Fetch failed, executing %lu pending completion(s)"
+ "%s#I Fetch succeeded, executing %lu pending completion(s)"
+ "%s#I Fetch succeeded, executing completion"
+ "%s#I Store saved but carrier services controller is not set, skipping"
+ "%s#I [%s] Get QuickSwitch parameters for accountUUID %@"
+ "@56@0:8@16@24@32@40@48"
+ "T@\"NSMutableArray\",&,N,V_pendingFetchCompletions"
+ "T@\"NSString\",C,N,V_accountID"
+ "T@\"NSString\",C,N,V_device"
+ "T@\"NSString\",C,N,V_mode"
+ "T@\"NSString\",R,C,N,V_accountID"
+ "T@\"NSString\",R,N,V_version"
+ "T@\"VMServiceNotificationObserver\",W,N,V_notificationObserver"
+ "TB,N,V_dataReceived"
+ "TB,N,V_roleManual"
+ "TB,N,V_twinManual"
+ "VMCarrierServicesController.mm"
+ "VMQuickSwitchCache"
+ "VMQuickSwitchParameters"
+ "VMSharedStore"
+ "VoicemailStore.mm"
+ "_accountID"
+ "_dataReceived"
+ "_device"
+ "_pendingFetchCompletions"
+ "_roleManual"
+ "_twinManual"
+ "dataReceived"
+ "deserializeFromPayload:"
+ "device"
+ "executePendingFetchCompletions:data:error:"
+ "getQuickSwitchDataCache:"
+ "getQuickSwitchDataCacheWithCompletion:"
+ "getQuickSwitchDataCacheWithReply:"
+ "getQuickSwitchModeParameterForAccountUUID:completion:"
+ "getQuickSwitchModeParameterForAccountUUID:reply:"
+ "getQuickSwitchParametersForAccountUUID:completion:"
+ "getQuickSwitchParametersForAccountUUID:reply:"
+ "getQuickSwitchRoleParameterForAccountUUID:completion:"
+ "getQuickSwitchTwinParameterForAccountUUID:completion:"
+ "handleVoicemailStoreChanged"
+ "handleVoicemailStoreChanged:"
+ "initWithStateRequestController:transcriptionService:telephonyClient:queue:voicemailStore:notificationObserver:"
+ "initWithTranscriptionService:queue:telephonyClient:voicemailStore:notificationObserver:"
+ "notificationObserver != nil"
+ "notifyVoicemailsUpdated:"
+ "notifyVoicemailsUpdated_sync:"
+ "pendingFetchCompletions"
+ "prepareVoicemailsWithCompletion:"
+ "queuing"
+ "roleManual"
+ "setAccountID:"
+ "setDataReceived:"
+ "setDevice:"
+ "setNotificationObserver:"
+ "setPendingFetchCompletions:"
+ "setRoleManual:"
+ "setTwinManual:"
+ "skipping"
+ "storeSaved"
+ "twinManual"
+ "v16@?0@\"NSOrderedSet\"8"
+ "v16@?0@\"NSString\"8"
+ "v16@?0@\"VMQuickSwitchParameters\"8"
+ "v20@?0@\"NSArray\"8B16"
+ "v20@?0@\"NSString\"8B16"
+ "v24@0:8@\"NSOrderedSet\"16"
+ "v24@0:8@?<v@?@\"NSArray\"B>16"
+ "v24@0:8@?<v@?B@\"NSArray\"@\"NSError\">16"
+ "v24@0:8@?<v@?BQ@\"NSError\">16"
+ "v28@?0B8@\"NSArray\"12@\"NSError\"20"
+ "v32@0:8@\"NSUUID\"16@?<v@?@\"NSString\"@\"NSError\">24"
+ "v32@0:8@\"NSUUID\"16@?<v@?@\"VMQuickSwitchParameters\"@\"NSError\">24"
+ "v36@0:8B16@20@28"
+ "vm.shared.store"
+ "voicemailStore != nil"
- "%s#I %s%s%@ is notifying delegates about voicemail store saved"
- "%s#I Fetch already in progress, skipping"
- "@32@0:8@16^B24"
- "VMCarrierServicesController.m"
- "VoicemailStore.m"
- "getQuickSwitchRoleParameterForAccountUUID:isManual:"
- "getQuickSwitchTwinParameterForAccountUUID:isManual:"
- "handleVoicemailStoreSaved"
- "initWithStateRequestController:transcriptionService:telephonyClient:queue:"
- "initWithTranscriptionService:queue:telephonyClient:"
- "isDataAvailable"
- "isDeleted"
- "isTemporary"
- "notifyVoicemailStoreSaved"
- "notifyVoicemailStoreSaved_sync"
- "v24@0:8@?<v@?B@\"NSError\">16"
```
