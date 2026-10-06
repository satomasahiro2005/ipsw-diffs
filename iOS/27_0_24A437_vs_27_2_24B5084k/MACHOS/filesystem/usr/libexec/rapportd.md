## rapportd

> `/usr/libexec/rapportd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x198290` | `0x19a63c` | **`+0x23ac`** |
| `__TEXT.__cstring` | `0x36db6` | `0x37286` | **`+0x4d0`** |
| `__TEXT.__objc_methname` | `0x1c840` | `0x1c980` | **`+0x140`** |
| `__TEXT.__objc_stubs` | `0x13620` | `0x13740` | **`+0x120`** |
| `__DATA.__objc_const` | `0x11d88` | `0x11e18` | **`+0x90`** |
| `__TEXT.__const` | `0x6160` | `0x61e0` | **`+0x80`** |
| `__DATA.__objc_data` | `0x2d88` | `0x2de0` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x8498` | `0x84f0` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x1776` | `0x17ca` | **`+0x54`** |
| `__DATA.__objc_selrefs` | `0x5e80` | `0x5ec8` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0xa0d0` | `0xa110` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x3542` | `0x3582` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x4a81` | `0x4ab1` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x5970` | `0x5998` | **`+0x28`** |
| `__DATA.__data` | `0x3af8` | `0x3b18` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x6600` | `0x6620` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x24b0` | `0x24c4` | **`+0x14`** |
| `__DATA.__bss` | `0x4730` | `0x4740` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xac8` | `0xad8` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x10bf` | `0x10cf` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x3a0` | `0x3a8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xe58` | `0xe60` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
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

### Other Changes

```diff

-751.100.2.0.0
+751.200.31.0.0

+  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 8599
-  Symbols:   1455
-  CStrings:  10854
+  Functions: 8609
+  Symbols:   1457
+  CStrings:  10887
Symbols:
+ _$s10Foundation4UUIDV2eeoiySbAC_ACtFZ
+ _OBJC_CLASS_$_NSScanner
+ __swift_FORCE_LOAD_$_swiftIntents
- _swift_coroFrameAlloc
CStrings:
+ "%@ RX Empty response from `%~@`: requestID=%@ appSvc=%@ error=%@\n"
+ "%@ RX Error from `%~@`: requestID=%@ appSvc=%@ error=%@\n"
+ "%@ RX RESP from '%~@': requestID=%@ appSvc=%@ response=%s serverPublicKey=%zu bytes bonjourServiceID=%@ serverPort=%u listener=%@ error=%@\n"
+ "%@ TX REQ to '%~@': requestID=%@ appSvc=%@%@\n"
+ "%@Failed to publish advertisement for service %@: %@"
+ "%@Failed to stop publishing advertisement for service %@: %@"
+ "%@Missing advertisement for service %@"
+ "%@Now %lu pending advertisements after cancelling %@"
+ "%@Now %lu pending advertisements after publishing %@"
+ "%@Pending advertisement for %@ was cancelled"
+ "%@Successfully published advertisement (%lu total) for service %@: %@"
+ "%@Successfully stopped advertisement for service: %@"
+ "%@Unpublished advertisement (%lu total) for service %@"
+ "/System/Library/PrivateFrameworks/AirPlaySupport.framework/AirPlaySupport"
+ "@48@0:8@16@24@32@?40"
+ "APSGetP2PAllow"
+ "BLE NearbyActionV2 device lost for device we were not tracking: %@\n"
+ "Failed to activate cLink %@: %@"
+ "No handler for requestID %{public}s on flags [%{public}s] (registered under: %{public}s)"
+ "RPNWTXTUtils"
+ "RX Empty response from `%~@`: requestID=%@ appSvc=%@ error=%@\n"
+ "RX Error from `%~@`: requestID=%@ appSvc=%@ error=%@\n"
+ "RX RESP from '%~@': requestID=%@ appSvc=%@ response=%s bytes listener=%@ error=%@\n"
+ "RapportDefaultPersonaID"
+ "Register eventID %{public}s registration %s persona %{public}s with handlers: %{public}s"
+ "Register requestID %{public}s registration %s persona %{public}s with handlers: %{public}s"
+ "Setting up cLink %@"
+ "TX REQ to '%~@': requestID=%@ appSvc=%@%@\n"
+ "Unable to find Service Directory request sender %@"
+ "_txtRecordForApplicationService:"
+ "initWithBytes:length:encoding:"
+ "initWithUnsignedLongLong:"
+ "registerEventID:persona:options:handler:"
+ "registerRequestID:persona:options:handler:"
+ "scanUnsignedLongLong:"
+ "statusFlagsForEndpoint:"
+ "statusFlagsForTXTRecord:"
+ "updateStatusFlags:onEndpoint:operation:"
+ "updateStatusFlags:onTXTRecord:operation:"
+ "v40@0:8Q16@24Q32"
- "Failed to activate cLink: %@"
- "No message handler registered for request ID %{public}s"
- "Register eventID %{public}s registration %s with handlers: %{public}s"
- "Register requestID %{public}s registration %s with handlers: %{public}s"
- "Setting up cLink"
- "Unable to find Service Directory sender %@"
- "txtRecordForApplicationService:"
```
