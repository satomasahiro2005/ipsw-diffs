## callservicesd

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x50dca4` | `0x510b90` | **`+0x2eec`** |
| `__TEXT.__eh_frame` | `0xa638` | `0xa728` | **`+0xf0`** |
| `__TEXT.__objc_methname` | `0x6e82f` | `0x6e907` | **`+0xd8`** |
| `__DATA.__objc_data` | `0xe158` | `0xe218` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0x3c880` | `0x3c920` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x27678` | `0x276f8` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x518c3` | `0x51943` | **`+0x80`** |
| `__DATA.__objc_const` | `0x3f538` | `0x3f5a8` | **`+0x70`** |
| `__TEXT.__const` | `0xf3c8` | `0xf438` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0xeb28` | `0xeb80` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x29178` | `0x291c0` | **`+0x48`** |
| `__DATA.__data` | `0xff98` | `0xffd8` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x6c60` | `0x6c94` | **`+0x34`** |
| `__TEXT.__auth_stubs` | `0x5a00` | `0x5a30` | **`+0x30`** |
| `__TEXT.__cstring` | `0x1b76c` | `0x1b79c` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x95f0` | `0x961c` | **`+0x2c`** |
| `__DATA.__objc_selrefs` | `0x13570` | `0x13598` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x2828` | `0x2850` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x9524` | `0x954c` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x8690` | `0x86b0` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x90fa` | `0x9118` | **`+0x1e`** |
| `__DATA_CONST.__auth_got` | `0x2d10` | `0x2d28` | **`+0x18`** |
| `__TEXT.__objc_classname` | `0x58b2` | `0x58c2` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x12d76` | `0x12d86` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x14b0` | `0x14a8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xcb0` | `0xcb8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x68c` | `0x690` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1614.100.3.2.1
+1616.100.2.2.1

+  - /System/Library/PrivateFrameworks/DeviceAccess.framework/DeviceAccess

-  Functions: 28294
-  Symbols:   2926
-  CStrings:  24107
+  Functions: 28330
+  Symbols:   2934
+  CStrings:  24117
Symbols:
+ _$s10Foundation4DateV11distantPastACvgZ
+ _$s16CallIntelligence09ProactiveA17ContextControllerC05fetchaD5Cards10queryItems14currentContact17includeDuplicates5flagsSayAA0aD4CardVGSayAA0aD15SearchQueryTypeOG_So9CNContactCSgSbAA0aD5FlagsVtYaF
+ _$s16CallIntelligence09ProactiveA17ContextControllerC05fetchaD5Cards10queryItems14currentContact17includeDuplicates5flagsSayAA0aD4CardVGSayAA0aD15SearchQueryTypeOG_So9CNContactCSgSbAA0aD5FlagsVtYaFTu
+ _$s16CallIntelligence0A12ContextFlagsV8incomingACvgZ
+ _$s16CallIntelligence0A12ContextFlagsVMa
+ _$s16CallIntelligence0A12ContextFlagsVMn
+ _$s16CallIntelligence0A12ContextFlagsVs10SetAlgebraAAMc
+ _OBJC_CLASS_$_DADaemonSession
+ _OBJC_CLASS_$_DADevice
+ _OBJC_CLASS_$_DADeviceAppAccessInfo
- _$s16CallIntelligence09ProactiveA17ContextControllerC05fetchaD5Cards10queryItems14currentContact17includeDuplicatesSayAA0aD4CardVGSayAA0aD15SearchQueryTypeOG_So9CNContactCSgSbtYaF
- _$s16CallIntelligence09ProactiveA17ContextControllerC05fetchaD5Cards10queryItems14currentContact17includeDuplicatesSayAA0aD4CardVGSayAA0aD15SearchQueryTypeOG_So9CNContactCSgSbtYaFTu
CStrings:
+ "%s: Removing notifications for read call, count: %ld"
+ "%s: Seeded %ld posted call identifier(s) on startup"
+ "CSDBluetoothAccessorySetupAuthorization"
+ "CSDContextCardsTypeLastSentDate"
+ "_handleAudioSessionMediaServicesWereResetNotification:"
+ "_subscribeToRecordingStateChangeNotifications"
+ "accessoryOptions"
+ "appAccessInfoMap"
+ "getDevicesWithFlags:session:error:"
+ "isAuthorizedForBundleIdentifier:"
+ "postedCallIdentifiers"
+ "updatePostedNotifications(unreadCalls:)"
- "outgoingCallCallerIDEnabled"
- "updatePostedNotifications()"
```
