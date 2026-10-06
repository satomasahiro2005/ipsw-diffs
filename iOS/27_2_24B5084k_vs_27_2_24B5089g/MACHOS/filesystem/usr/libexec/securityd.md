## securityd

> `/usr/libexec/securityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26d940` | `0x26dd24` | **`+0x3e4`** |
| `__TEXT.__objc_methname` | `0x2e65f` | `0x2e77f` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0x1d9e0` | `0x1da60` | **`+0x80`** |
| `__DATA.__data` | `0x3158` | `0x31b8` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0xa0c8` | `0xa124` | **`+0x5c`** |
| `__DATA.__objc_const` | `0x23cd8` | `0x23d18` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x2ff02` | `0x2ff32` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xb0a4` | `0xb0cf` | **`+0x2b`** |
| `__TEXT.__objc_methlist` | `0x15e98` | `0x15ec0` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x98b8` | `0x98d8` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x2559` | `0x2577` | **`+0x1e`** |
| `__DATA_CONST.__const` | `0x14a40` | `0x14a28` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x6a68` | `0x6a78` | **`+0x10`** |
| `__TEXT.__cstring` | `0x22bd0` | `0x22bde` | **`+0xe`** |
| `__DATA_CONST.__got` | `0x1550` | `0x1558` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x260` | `0x268` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1ae8` | `0x1aec` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__thread_vars`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-62460.40.49.502.1
+62460.40.56.502.1

-  Functions: 9920
-  Symbols:   1894
-  CStrings:  16432
+  Functions: 9922
+  Symbols:   1895
+  CStrings:  16443
Symbols:
+ _AKTelemetryFlowID
CStrings:
+ "@\"<TDLNotificationFlowIDConsumer>\""
+ "@212@0:8@16@24@32@40@48@56@64@72@80@88@96@104@112@120@128@136#144#152@160@168B176B180B184@188@196@204"
+ "T@\"<TDLNotificationFlowIDConsumer>\",R,W,V_tdlNotificationFlowIDConsumer"
+ "TDLNotificationFlowIDConsumer"
+ "Updating trusted device list, flowID source: %s"
+ "_tdlNotificationFlowIDConsumer"
+ "afterAuthKitFetch:userInitiatedRemovals:evictedRemovals:unknownReasonRemovals:trustedDeviceHash:deletedDeviceHash:trustedDevicesUpdateTimestamp:accountIsDemo:version:idmsStableTrustedDevicesVersion:flowID:"
+ "consumeIdMSTDLNotificationFlowID"
+ "idMSTDLNotificationFlowID"
+ "idms"
+ "initForContainer:contextID:activeAccount:stateHolder:flagHandler:sosAdapter:octagonAdapter:accountsAdapter:authKitAdapter:personaAdapter:deviceInfoAdapter:secureBackupAdapter:laContextAdapter:ckksAccountSync:lockStateTracker:cuttlefishXPCWrapper:escrowRequestClass:notifierClass:flowID:deviceSessionID:permittedToSendMetrics:accountIsD:accountIsW:reachabilityTracker:escrowChecker:tdlNotificationFlowIDConsumer:"
+ "initWithFlowID:deviceSessionID:idMSTDLNotificationFlowID:"
+ "not idms"
+ "notificationOfMachineIDListChangeWithFlowID:"
+ "requestTrustedDeviceListRefreshWithFlowID:"
+ "setTelemetryFlowID:"
+ "tdlNotificationFlowIDConsumer"
+ "v100@0:8@16@24@32@40@48@56@64B72@76@84@92"
+ "\xf1b"
- "@204@0:8@16@24@32@40@48@56@64@72@80@88@96@104@112@120@128@136#144#152@160@168B176B180B184@188@196"
- "afterAuthKitFetch:userInitiatedRemovals:evictedRemovals:unknownReasonRemovals:trustedDeviceHash:deletedDeviceHash:trustedDevicesUpdateTimestamp:accountIsDemo:version:idmsStableTrustedDevicesVersion:"
- "initForContainer:contextID:activeAccount:stateHolder:flagHandler:sosAdapter:octagonAdapter:accountsAdapter:authKitAdapter:personaAdapter:deviceInfoAdapter:secureBackupAdapter:laContextAdapter:ckksAccountSync:lockStateTracker:cuttlefishXPCWrapper:escrowRequestClass:notifierClass:flowID:deviceSessionID:permittedToSendMetrics:accountIsD:accountIsW:reachabilityTracker:escrowChecker:"
- "initWithFlowID:deviceSessionID:"
- "notificationOfMachineIDListChange"
- "requestTrustedDeviceListRefresh"
- "v92@0:8@16@24@32@40@48@56@64B72@76@84"
- "\xf1a"
```
