## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/iMessage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1106fc` | `0x116a80` | **`+0x6384`** |
| `__TEXT.__oslogstring` | `0x1c89b` | `0x1ceab` | **`+0x610`** |
| `__TEXT.__objc_methname` | `0x15d0e` | `0x1603e` | **`+0x330`** |
| `__TEXT.__cstring` | `0x3fcd` | `0x41dd` | **`+0x210`** |
| `__TEXT.__objc_stubs` | `0xf200` | `0xf400` | **`+0x200`** |
| `__DATA.__data` | `0xef8` | `0xff8` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x5550` | `0x5618` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0x2620` | `0x26b0` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0x4368` | `0x43f0` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0x3414` | `0x348c` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x2cb0` | `0x2d28` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0xe6e` | `0xed4` | **`+0x66`** |
| `__DATA_CONST.__cfstring` | `0x3e60` | `0x3ec0` | **`+0x60`** |
| `__DATA.__objc_const` | `0x4138` | `0x4190` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x1388` | `0x13d8` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x1320` | `0x1368` | **`+0x48`** |
| `__TEXT.__objc_classname` | `0x83f` | `0x87f` | **`+0x40`** |
| `__TEXT.__const` | `0x1618` | `0x15e8` | **`-0x30`** |
| `__TEXT.__gcc_except_tab` | `0x97e0` | `0x9804` | **`+0x24`** |
| `__TEXT.__swift5_capture` | `0x9d0` | `0x9f4` | **`+0x24`** |
| `__DATA.__bss` | `0x1080` | `0x10a0` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x88` | `0xa8` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x362e` | `0x364e` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x18` | `0x28` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1491.200.63.2.1
+1491.200.73.0.0

-  Functions: 2520
-  Symbols:   1003
-  CStrings:  5443
+  Functions: 2553
+  Symbols:   1009
+  CStrings:  5501
Symbols:
+ _OBJC_CLASS_$_ABCRemoteDebuggingRequest
+ _OBJC_CLASS_$_EndpointRemoteDebuggingDestination
+ _OBJC_CLASS_$_ExistingRadarRemoteDebuggingRequest
+ _OBJC_CLASS_$_IDSHandle
+ _OBJC_CLASS_$_IMTapToRadarDraft
+ _OBJC_CLASS_$_NewRadarRemoteDebuggingRequest
CStrings:
+ " hit a bug in your conversation and is asking you to add to a radar from this device."
+ " hit a bug in your conversation and is asking you to file a radar from this device."
+ "@\"NSSet\"16@0:8"
+ "CKV failure"
+ "Discarding a TTR request identifier, it has characters outside [A-Za-z0-9-_.]"
+ "Discarding a TTR request identifier, it is longer than %ld characters"
+ "Discarding a TTR request radar number, it is not a plain number"
+ "Failed sending TTR request %s to %s, error: %u"
+ "Finished sending TTR request %s to %s"
+ "Ignoring a TTR request from %s, could not decode its payload"
+ "Ignoring a TTR request from %s, disabled by %s"
+ "Ignoring a TTR request from %s, no known debug request included"
+ "Ignoring a TTR request from %s, not an internal install"
+ "Ignoring a TTR request, disabled by the %s server bag"
+ "No known remote debugging request type, not sending request"
+ "Not sending CKV failure remote debugging request, could not build a prefixed URI from %@"
+ "Not sending a TTR request %s, could not encode %s"
+ "Not sending a TTR request %s, device is not registered for account %s"
+ "Not sending a TTR request %s, disabled by the %s server bag"
+ "Not sending a TTR request %s, no destination"
+ "Not sending a TTR request %s, not an internal install"
+ "Please describe what you saw on this device."
+ "Received a TTR request from %s for a new radar, asking whether to file"
+ "Received a TTR request from %s for radar %s, asking whether to file"
+ "Received an ABC request from %s"
+ "Received an invalid existing radar number in a TTR request from %s"
+ "Received generic command for remote debugging"
+ "RemoteDebugging"
+ "RemoteDebuggingDestination"
+ "RemoteDebuggingReceiveEnabled"
+ "RemoteDebuggingRequest"
+ "Sending TTR request %s to %s for %s"
+ "T@\"NSSet\",R,N"
+ "[Messages] Remote TTR Request"
+ "_requestRemoteDebuggingIfNeededForPolicyResult:account:fromIdentifier:messageIdentifier:"
+ "ckv-failure"
+ "com.apple.Messages.RemoteDebuggingRequest."
+ "com.apple.MobileSMS"
+ "defaults"
+ "existingRadarNumber"
+ "extractCKVFailedEndpointsExcluding:"
+ "handler:remoteDebuggingRequest:fromIdentifier:fromIDSID:"
+ "handles"
+ "iMessageServerBag"
+ "initWithEndpoints:"
+ "initWithReason:relatedGUID:relatedGUIDType:identifier:version:"
+ "initWithUnprefixedURI:"
+ "invalid payload, no usable identifier or debuggingRequestVersion in remote debugging request"
+ "lockdownManager"
+ "openExistingRadarNumber:notificationIdentifier:notificationTitle:notificationBody:rateLimitInterval:rateLimitKeySuffix:version:"
+ "receivedRemoteDebuggingRequest:fromIdentifier:fromIDSID:"
+ "relatedGUID"
+ "relatedGUIDType"
+ "remote-debugging-receive-enabled"
+ "remote-debugging-send-enabled"
+ "remoteDebugging-allowAll-v1"
+ "sendRemoteDebuggingRequest:destination:fromIdentifier:idsAccount:"
+ "skippedAllDestinationsCache"
+ "submitAndOpenTapToRadarWithNotificationIdentifier:notificationTitle:notificationBody:draftTitle:problemDescription:attachments:deviceClasses:classification:reproducibility:rateLimitInterval:rateLimitKeySuffix:version:"
+ "toURIs"
- "noEligibleDestinationsCache"
- "setHadNoEligibleDestinations:forMessageGUID:"
```
