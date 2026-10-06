## NFCUISceneService

> `/Applications/NFCUISceneService.app/NFCUISceneService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd8ac` | `0xf1b4` | **`+0x1908`** |
| `__TEXT.__objc_methname` | `0x1c27` | `0x1f97` | **`+0x370`** |
| `__TEXT.__objc_stubs` | `0x1360` | `0x1600` | **`+0x2a0`** |
| `__DATA.__objc_const` | `0xea8` | `0x1110` | **`+0x268`** |
| `__TEXT.__cstring` | `0x13bd` | `0x160e` | **`+0x251`** |
| `__TEXT.__oslogstring` | `0x1006` | `0x11a8` | **`+0x1a2`** |
| `__TEXT.__objc_methlist` | `0x93c` | `0xa5c` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x818` | `0x900` | **`+0xe8`** |
| `__DATA.__objc_selrefs` | `0x7b0` | `0x840` | **`+0x90`** |
| `__DATA.__objc_data` | `0x5a0` | `0x5f0` | **`+0x50`** |
| `__DATA_CONST.__objc_intobj` | `0xd8` | `0x120` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x308` | `0x350` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0xb40` | `0xb80` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x4c` | `0x74` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x5a8` | `0x5c8` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0xa38` | `0xa58` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x3a9` | `0x3c2` | **`+0x19`** |
| `__DATA_CONST.__got` | `0x200` | `0x208` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__const` | `0x2e8` | `0x2f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-370.33.1.0.0
+370.37.0.0.0

-  - /System/Library/PrivateFrameworks/NearFieldPrivateServices.framework/NearFieldPrivateServices

-  Functions: 254
-  Symbols:   296
-  CStrings:  666
+  Functions: 287
+  Symbols:   301
+  CStrings:  725
Symbols:
+ _OBJC_CLASS_$_BSServiceConnectionListenerConfiguration
+ _OBJC_CLASS_$_BSServiceDispatchQueue
+ _dispatch_async
+ _dispatch_get_global_queue
+ _objc_storeWeak
+ _os_signpost_id_generate
- __dispatch_main_q
CStrings:
+ "!"
+ "%s:%i Initial set for %@=%@"
+ "%s:%i No extensions found for %@"
+ "%s:%i Process pending background tag reading messages (count=%lu)"
+ "%s:%i Processing error: %{public}@"
+ "%s:%i Queue background tag reading message"
+ "%s:%i Unexpected extension system state; dropping message"
+ "%s:%i XPC to extension process (%{public}@) interrupted"
+ "%s:%i XPC to extension process (%{public}@) invalidated"
+ "%s:%i ignore message due to active remote alert (%{public}@)"
+ "%{public}s:%i Initial set for %@=%@"
+ "%{public}s:%i No extensions found for %@"
+ "%{public}s:%i Process pending background tag reading messages (count=%lu)"
+ "%{public}s:%i Processing error: %{public}@"
+ "%{public}s:%i Queue background tag reading message"
+ "%{public}s:%i Unexpected extension system state; dropping message"
+ "%{public}s:%i XPC to extension process (%{public}@) interrupted"
+ "%{public}s:%i XPC to extension process (%{public}@) invalidated"
+ "%{public}s:%i ignore message due to active remote alert (%{public}@)"
+ "-[NFBSListener_BackgroundTagReading _processTagReadResult:reply:]_block_invoke"
+ "-[NFBSListener_BackgroundTagReading extensionListDidUpdate:]"
+ "-[NFBSListener_BackgroundTagReading extensionListDidUpdate:]_block_invoke"
+ "-[NFBSListener_BackgroundTagReading processNDEF:tag:reply:]_block_invoke"
+ "@\"<NFExtensionPointManagerDelegate>\""
+ "@\"BSServiceDispatchQueue\""
+ "@\"NFNdefMessageInternal\""
+ "@\"NFTagInternal\""
+ "@\"NSData\""
+ "@\"NSMutableArray\""
+ "Extension manager initializing"
+ "Find extension error"
+ "Message drop due to existing active remote alert"
+ "NFBackgroundTagReadingResult"
+ "NFExtensionPointManagerDelegate"
+ "T@\"<NFExtensionPointManagerDelegate>\",W,N,V_delegate"
+ "T@\"BSServiceDispatchQueue\",&,N,V_bsQueue"
+ "T@\"NFExtensionKitWrapper\",&,N,V_extensionInActiveRemoteAlert"
+ "T@\"NFNdefMessageInternal\",&,N,V_ndefInternal"
+ "T@\"NFTagInternal\",&,N,V_tagInternal"
+ "T@\"NSData\",&,N,V_ndef"
+ "T@\"NSData\",&,N,V_tag"
+ "T@\"NSMutableArray\",&,N,V_pendingNDEFMessages"
+ "TB,N,V_nonUIExtensionManagerStarted"
+ "TB,N,V_uiExtensionManagerStarted"
+ "Vv40@0:8@\"NSData\"16@\"NSData\"24@?<v@?@\"NSError\">32"
+ "Vv40@0:8@16@24@?32"
+ "[NFBSListener_BackgroundTagReading] connection invalidated (pid=%d)"
+ "[NFBSListener_BackgroundTagReading] processPendingNDEF"
+ "_bsQueue"
+ "_delegate"
+ "_extensionInActiveRemoteAlert"
+ "_ndef"
+ "_ndefInternal"
+ "_nonUIExtensionManagerStarted"
+ "_pendingNDEFMessages"
+ "_processTagReadResult:reply:"
+ "_tag"
+ "_tagInternal"
+ "_uiExtensionManagerStarted"
+ "activateUIRemoteAlertWithExtension:tagReadResult:"
+ "appExtensionIdentity"
+ "bsQueue"
+ "configurationWithDomain:service:"
+ "configure:"
+ "delegate"
+ "didReceiveConnection:"
+ "error=%@"
+ "extensionInActiveRemoteAlert"
+ "extensionListDidUpdate:"
+ "hostVCXPCListener"
+ "initWithIdentifier:delegate:"
+ "initWithURLPrefixList:identifier:delegate:"
+ "listenerWithConfiguration:handler:"
+ "ndefInternal"
+ "nonUIExtensionManagerStarted"
+ "pendingNDEFMessages"
+ "queueWithName:serviceQuality:"
+ "remoteToken"
+ "setBsQueue:"
+ "setExtensionInActiveRemoteAlert:"
+ "setLocalTarget:"
+ "setNdef:"
+ "setNdefInternal:"
+ "setNonUIExtensionManagerStarted:"
+ "setPendingNDEFMessages:"
+ "setQueue:"
+ "setTag:"
+ "setTagInternal:"
+ "setUiExtensionManagerStarted:"
+ "tagInternal"
+ "uiExtensionManagerStarted"
+ "userInteractive"
+ "v16@?0@\"<BSServiceListenerConnectionConfiguring>\"8"
+ "v16@?0@\"BSServiceListenerConnection\"8"
+ "v24@0:8@\"NFExtensionPointManager\"16"
- "%s:%i Initial set: %@"
- "%s:%i No extensions found"
- "%s:%i XPC to extension process (%@) interrupted"
- "%s:%i XPC to extension process (%@) invalidated"
- "%s:%i urlProcessor=%@"
- "%{public}s:%i Initial set: %@"
- "%{public}s:%i No extensions found"
- "%{public}s:%i XPC to extension process (%@) interrupted"
- "%{public}s:%i XPC to extension process (%@) invalidated"
- "%{public}s:%i urlProcessor=%@"
- "@\"BSServiceConnection<BSServiceConnectionHost>\""
- "BSServiceConnectionListenerDelegate"
- "T@\"BSServiceConnection<BSServiceConnectionHost>\",&,N,V_connection"
- "[NFBSListener_BackgroundTagReading] (NonUI) processNDEF"
- "[NFBSListener_BackgroundTagReading] processNDEF find extension error"
- "_connection"
- "activateUIRemoteAlertWithExtension:ndefMessage:tag:"
- "configureConnection:"
- "connection"
- "initWithIdentifier:"
- "initWithURLPrefixList:Identifier:"
- "listener:didReceiveConnection:withContext:"
- "listenerWithConfigurator:"
- "remoteProcess"
- "remoteUIXpcConnection"
- "setConnection:"
- "setDomain:"
- "setInterfaceTarget:"
- "setService:"
- "setServiceQuality:"
- "setTargetQueue:"
- "userInitiated"
- "v16@?0@\"<BSServiceConnectionConfiguring>\"8"
- "v16@?0@\"<BSServiceConnectionListenerConfiguring>\"8"
- "v40@0:8@\"BSServiceConnectionListener\"16@\"BSServiceConnection<BSServiceConnectionHost>\"24@\"<BSXPCDecoding>\"32"
- "v40@0:8@\"NSData\"16@\"NSData\"24@?<v@?@\"NSError\">32"
```
