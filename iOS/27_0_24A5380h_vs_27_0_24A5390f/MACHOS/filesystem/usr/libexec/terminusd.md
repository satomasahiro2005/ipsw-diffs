## terminusd

> `/usr/libexec/terminusd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fc2a4` | `0x1fcc44` | **`+0x9a0`** |
| `__DATA_CONST.__cfstring` | `0xdf00` | `0xdba0` | **`-0x360`** |
| `__TEXT.__cstring` | `0x5167c` | `0x5185b` | **`+0x1df`** |
| `__TEXT.__objc_stubs` | `0x94c0` | `0x9400` | **`-0xc0`** |
| `__TEXT.__objc_methname` | `0x138f5` | `0x138a5` | **`-0x50`** |
| `__TEXT.__objc_methtype` | `0x44ab` | `0x4467` | **`-0x44`** |
| `__DATA_CONST.__const` | `0x4e60` | `0x4e20` | **`-0x40`** |
| `__DATA.__objc_const` | `0x19c00` | `0x19c38` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x2f10` | `0x2ee0` | **`-0x30`** |
| `__DATA_CONST.__got` | `0xef0` | `0xec0` | **`-0x30`** |
| `__DATA.__bss` | `0xcd8` | `0xcb8` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x3ef0` | `0x3ed0` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x5c04` | `0x5be4` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x1f88` | `0x1f78` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x1fd4` | `0x1fdc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-914.0.14.502.2
+914.0.22.0.1

-  Functions: 4019
-  Symbols:   1544
-  CStrings:  11666
+  Functions: 4016
+  Symbols:   1536
+  CStrings:  11650
Symbols:
+ _nrXPCKeyMeshPreferencesNANPeerList
- _CFUserNotificationCreate
- _CFUserNotificationReceiveResponse
- _OBJC_CLASS_$_LSApplicationWorkspace
- _OBJC_CLASS_$_NSURLComponents
- _OBJC_CLASS_$_NSURLQueryItem
- _kCFUserNotificationAlertHeaderKey
- _kCFUserNotificationAlertMessageKey
- _kCFUserNotificationAlternateButtonTitleKey
- _kCFUserNotificationDefaultButtonTitleKey
CStrings:
+ "%02x%02x%02x%02x.%s"
+ "%s%.30s:%-4d   unknown appId %@ requested, no matching source"
+ "%s%.30s:%-4d NAN bring-up: explicit control enabled, skipping auto-trigger"
+ "%s%.30s:%-4d Null NAN peer at index %zu"
+ "%s%.30s:%-4d Requesting distribution stop for source %@ to neighbour %@"
+ "%s%.30s:%-4d Set multicast subscriptions: address %@, %lu peers, %lu NAN peers"
+ "%s%.30s:%-4d adding interface %@ for application service"
+ "%s%.30s:%-4d removing interface %@ for application service"
+ "%s%.30s:%-4d removing stale listener interface %@ for application service"
+ "%s%.30s:%-4d requestDistributionStart: unknown appId %@ requested, no matching source"
+ "%s%.30s:%-4d requestDistributionStop: unknown appId %@ requested, no matching source"
+ "%s%.30s:%-4d requestDistributionStopForSourceAppIds: scanning %lu sources for %lu requested appIds"
+ "%s%.30s:%-4d updateNANPeerList: requesting distribution start for %lu added peers"
+ "%s%.30s:%-4d updateNANPeerList: requesting distribution stop for %lu removed peers"
+ "-[NRApplicationServiceManager registerInterfaceForApplicationService:]"
+ "-[NRApplicationServiceManager unregisterInterfaceForApplicationService:]"
+ "-[NRBabelManager requestDistributionStopForSourceAppIds:]"
+ "-[NRMeshPreferencesManager setMulticastAddress:peerList:nanPeerList:forConnection:]"
+ "-[NRMeshPreferencesManager updateNANPeerList:]"
+ "21:55:12"
+ "914.0.22.0.1"
+ "Jul 14 2026"
+ "MeshPreferencesManager[%@ peers=%lu nanPeers=%lu]"
+ "Terminus_ExplicitNANControl"
+ "_nanPeerList"
+ "_registeredInterfaceName"
+ "minusSet:"
- "%s%.30s:%-4d NRDTriggerTapToRadar: CFUserNotificationCreate failed: %d"
- "%s%.30s:%-4d NRDTriggerTapToRadar: suppressed for %@ (rate-limited)"
- "%s%.30s:%-4d Set multicast subscriptions: address %@, %lu peers"
- "-[NRMeshPreferencesManager setMulticastAddress:peerList:forConnection:]"
- "212336"
- "21:23:18"
- "675393"
- "914.0.14.502.2"
- "Classification"
- "ComponentID"
- "ComponentName"
- "ComponentVersion"
- "Description"
- "Dismiss"
- "File Radar"
- "Jun 30 2026"
- "Keywords"
- "MeshPreferencesManager[%@]"
- "NRDTTRLastPromptTime"
- "NRDTriggerTapToRadar"
- "NRDTriggerTapToRadar_block_invoke_2"
- "Not Applicable"
- "Other Bug"
- "Reproducibility"
- "Title"
- "URL"
- "[%@] terminusd reported issues"
- "all"
- "an unknown issue (type %u)"
- "com.apple.terminusd.ttr"
- "data stall"
- "data stalled over %sOutput"
- "defaultWorkspace"
- "openURL:configuration:completionHandler:"
- "queryItemWithName:value:"
- "serviceDiscoveryClient:didRequestRemotePayloadForDevice:completion:"
- "setQueryItems:"
- "tap-to-radar://new"
- "terminusd detected a %@. Tap 'File Radar' to capture a sysdiagnose."
- "terminusd detected an issue"
- "terminusd has detected a connectivity issue - %@ (type: %@)\n\nPlease attach a sysdiagnose taken near the time of this prompt."
- "timeIntervalSinceReferenceDate"
- "v40@0:8@\"SDServiceDiscoveryClient\"16@\"NSString\"24@?<v@?@\"NSData\">32"
```
