## vmd

> `/System/Library/PrivateFrameworks/VisualVoicemail.framework/vmd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb97cc` | `0xbb3c8` | **`+0x1bfc`** |
| `__DATA.__objc_const` | `0x123a0` | `0x127b8` | **`+0x418`** |
| `__TEXT.__oslogstring` | `0x15d57` | `0x16107` | **`+0x3b0`** |
| `__TEXT.__objc_methname` | `0x1262f` | `0x12963` | **`+0x334`** |
| `__TEXT.__objc_stubs` | `0xdf60` | `0xe0e0` | **`+0x180`** |
| `__TEXT.__gcc_except_tab` | `0xc920` | `0xca98` | **`+0x178`** |
| `__TEXT.__objc_methlist` | `0x7b1c` | `0x7c24` | **`+0x108`** |
| `__DATA.__objc_selrefs` | `0x46f0` | `0x4778` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x3fa0` | `0x4028` | **`+0x88`** |
| `__TEXT.__cstring` | `0x478a` | `0x47fa` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x7c8` | `0x820` | **`+0x58`** |
| `__DATA_CONST.__cfstring` | `0x54e0` | `0x5520` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x33c8` | `0x3400` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x34e0` | `0x34f4` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x798` | `0x79c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-952.0.0.0.0
+954.0.0.0.0

-  Functions: 3522
+  Functions: 3551

-  CStrings:  5795
+  CStrings:  5832
CStrings:
+ "%s#E Active context has nil labelID, skipping: %@"
+ "%s#E Failed to fetch QuickSwitch voicemail controller data: %@"
+ "%s#I %s%sCarrierService, Received quickSwitchCarrierContextDidChange"
+ "%s#I %s%sQuickSwitch carrier context changed for account UUID %@; twin: %@ -> %@, role: %s -> %s"
+ "%s#I Adding cellular availability for public network, labelID: %@, available: %@"
+ "%s#I Cleared QuickSwitch voicemail controller data lost status"
+ "%s#I Fetched QuickSwitch voicemail controller data: %lu item(s)"
+ "%s#I QuickSwitch carrier context has changed; updating the cached carrier context."
+ "%s#I QuickSwitch data from device %@ - payload timestamp %llu is not newer than cached %llu, processing anyway"
+ "%s#I QuickSwitch disabled, returning nil data"
+ "%s#I QuickSwitch disabled, skipping data lost status clear"
+ "%s#I QuickSwitch voicemail controller data changed: %lu device(s)"
+ "%s#I QuickSwitch voicemail controller data lost, republishing"
+ "%s#I Skipping QuickSwitch data from device %@ - payload timestamp %llu is not newer than cached %llu"
+ "Active context labelID is nil"
+ "ActiveContext"
+ "T@\"NSMutableDictionary\",&,N,V_devicePayloadTimestampCache"
+ "VMQuickSwitchDataTypeNetworkAvailable"
+ "VMQuickSwitchDataTypePendingPublish"
+ "VMQuickSwitchDataTypeRepublish"
+ "_devicePayloadTimestampCache"
+ "clearQuickSwitchVoicemailControllerDataLostStatus"
+ "clearVoicemailQuickSwitchDataLostStatus"
+ "devicePayloadTimestampCache"
+ "fetchQuickSwitchVoicemailControllerData"
+ "fetchQuickSwitchVoicemailControllerData_async"
+ "getQuickSwitchVoicemailControllerDataWithCompletion:"
+ "getVoicemailQuickSwitchDataWithCompletion:"
+ "handleQuickSwitchCarrierContextDidChange"
+ "handleQuickSwitchVoicemailControllerDataChanged:"
+ "handleQuickSwitchVoicemailControllerDataLost"
+ "notifyQuickSwitchCarrierContextDidChange"
+ "notifyQuickSwitchVoicemailControllerDataChanged:"
+ "notifyQuickSwitchVoicemailControllerDataLost"
+ "processQuickSwitchData:deviceID:isSelfDevice:enforceTimestamp:"
+ "processQuickSwitchVoicemailControllerData:"
+ "setDevicePayloadTimestampCache:"
+ "v40@0:8@16@24B32B36"
+ "voicemailQuickSwitchDataChanged:"
+ "voicemailQuickSwitchDataLost"
- "%s#I Adding cellular availability for public network: %@, labelID: %@"
- "VMQuickSwitchDataTypeOperation"
- "processQuickSwitchData:isSelfDevice:"
```
