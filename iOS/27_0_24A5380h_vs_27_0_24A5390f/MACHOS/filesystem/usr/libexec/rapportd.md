## rapportd

> `/usr/libexec/rapportd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x194e64` | `0x197b1c` | **`+0x2cb8`** |
| `__TEXT.__cstring` | `0x36ed6` | `0x36bb6` | **`-0x320`** |
| `__DATA_CONST.__cfstring` | `0x67a0` | `0x6600` | **`-0x1a0`** |
| `__TEXT.__objc_methname` | `0x1c730` | `0x1c800` | **`+0xd0`** |
| `__DATA.__objc_const` | `0x11cd0` | `0x11d88` | **`+0xb8`** |
| `__TEXT.__oslogstring` | `0x3492` | `0x3542` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x1710` | `0x1776` | **`+0x66`** |
| `__DATA_CONST.__objc_intobj` | `0x378` | `0x3c0` | **`+0x48`** |
| `__TEXT.__objc_methtype` | `0x4ab1` | `0x4a81` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x8470` | `0x8448` | **`-0x28`** |
| `__DATA.__data` | `0x3ad8` | `0x3af8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xa0e8` | `0xa0c8` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x112c` | `0x113c` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x5e60` | `0x5e70` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x39e0` | `0x39f0` | **`+0x10`** |
| `__TEXT.__const` | `0x5fb0` | `0x5fa0` | **`-0x10`** |
| `__DATA.__objc_data` | `0x2d80` | `0x2d88` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1d00` | `0x1d08` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xac0` | `0xac8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xe50` | `0xe58` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-745.100.4.0.0
+747.100.2.0.0

-  Functions: 8583
-  Symbols:   1453
-  CStrings:  10861
+  Functions: 8590
+  Symbols:   1455
+  CStrings:  10843
Symbols:
+ _$s10Foundation4UUIDVs23CustomStringConvertibleAAMc
+ _swift_coroFrameAlloc
CStrings:
+ "Deregistered eventID: %{public}s registration %s"
+ "Deregistered requestID: %{public}s registration %s"
+ "EventID: %{public}s handled by %s"
+ "No message handler registered for event ID %{public}s"
+ "No message handler registered for request ID %{public}s"
+ "Register eventID %{public}s registration %s with handlers: %{public}s"
+ "Register requestID %{public}s registration %s with handlers: %{public}s"
+ "RequestID: %{public}s handled by %s"
+ "T@\"NSMutableDictionary\",R,N,V_registeredEventRegistrationIDs"
+ "T@\"NSMutableDictionary\",R,N,V_registeredRequestRegistrationIDs"
+ "T@\"NSUUID\",&,N,V_registrationID"
+ "_registeredEventRegistrationIDs"
+ "_registeredRequestRegistrationIDs"
+ "_registrationID"
+ "deregisterEventID:registrationID:"
+ "deregisterRequestID:registrationID:"
+ "registeredEventRegistrationIDs"
+ "registeredRequestRegistrationIDs"
+ "registrationID"
+ "setRegistrationID:"
- "### RegisterEventID: a handler already exists for eventID '%{public}s'"
- "### RegisterRequestID: a handler already exists for request ID:'%{public}s'"
- "%@ Using IP transport over wireless or wired ethernet"
- "%@ Using P2P transport over BLE"
- "%@ Using P2P transport over WiFi"
- "%@ Using unknown transport"
- "%@ cnx state no transport\n"
- "%@ cnx state: %s\n"
- "%@ unable to evaluate cnx state, power info may be inaccurate\n"
- "-[RPCompanionLinkDaemon _logConnectionStateInformation:connection:]"
- "-[RPCompanionLinkXPCConnection logXPCConnectionInformation:]"
- "-[RPRemoteDisplayXPCConnection logXPCConnectionInformation:]"
- "AudioAccessory1,"
- "AudioAccessory5,"
- "AudioAccessory6,"
- "Deregistered event ID: %s"
- "Deregistered request ID: %s"
- "Ready"
- "Register event ID %{public}s with handlers: %{public}s"
- "Register request ID %{public}s with handlers: %{public}s"
- "XPC Cnx %@: not transmitting without source"
- "XPC Cnx %@: peer to peer source device %@"
- "XPC Cnx %@: transmitting"
- "XPC Cnx %@: transmitting from source %@"
- "_logConnectionStateInformation:connection:"
- "authCompletion"
- "daemonInvalidation"
- "errorFlagsChanged"
- "invalidated"
- "logConnectionInformation:options:"
- "logXPCConnectionInformation:"
- "netConnectionStart"
- "onDemandStart"
- "serviceDiscoveryClient:didRequestRemotePayloadForDevice:completion:"
- "sessionStart"
- "sessionStop"
- "stateChange"
- "v40@0:8@\"SDServiceDiscoveryClient\"16@\"NSString\"24@?<v@?@\"NSData\">32"
```
