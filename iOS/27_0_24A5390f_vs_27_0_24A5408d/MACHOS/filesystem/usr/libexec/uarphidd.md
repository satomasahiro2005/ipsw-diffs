## uarphidd

> `/usr/libexec/uarphidd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x485c` | `0x5230` | **`+0x9d4`** |
| `__TEXT.__oslogstring` | `0x79f` | `0x8be` | **`+0x11f`** |
| `__TEXT.__objc_methname` | `0xd01` | `0xe1b` | **`+0x11a`** |
| `__TEXT.__objc_stubs` | `0xb20` | `0xc20` | **`+0x100`** |
| `__TEXT.__cstring` | `0x6f7` | `0x7e8` | **`+0xf1`** |
| `__DATA_CONST.__cfstring` | `0x740` | `0x7e0` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x120` | `0x178` | **`+0x58`** |
| `__DATA.__objc_selrefs` | `0x370` | `0x3b0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x39c` | `0x3dc` | **`+0x40`** |
| `__DATA.__objc_const` | `0x978` | `0x9a8` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x560` | `0x570` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2b8` | `0x2c0` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x253` | `0x259` | **`+0x6`** |
| `__DATA.__objc_ivar` | `0xbc` | `0xc0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1587.0.27.0.0
+1587.2.2.0.0

-  Functions: 136
-  Symbols:   117
-  CStrings:  351
+  Functions: 148
+  Symbols:   118
+  CStrings:  373
Symbols:
+ _objc_retain_x24
+ _objc_retain_x26
- _objc_retain_x25
CStrings:
+ "%s: endpointUUID %@ is already instantiated as a UARPHIDDevice, ignoring"
+ "%s: endpointUUID %@ is not a known HID device, ignoring"
+ "%s: endpointUUID %s is not a valid UUID"
+ "%s: endpointUUID = %s, uarpTransportDomain = %s"
+ "%s: endpointUUID missing from event"
+ "%s: known entrey matching dict %@"
+ "-[UARPHIDManager handleEndpointAssetAvailable:]"
+ "-[UARPHIDManager matchAndStartServiceForKnownEntry:]"
+ "@56@0:8@16@24@32@40@48"
+ "ServiceName"
+ "T@\"NSString\",R,V_serviceName"
+ "VID <%@>, PID <%@>, Serial Number <%@>, UUID <%@>, Service Name <%@>"
+ "_serviceName"
+ "checkDatabaseForKnownVendorID:productID:serialNumber:serviceName:"
+ "com.apple.uarp.endpoint.assetavailable"
+ "com.apple.uarp.endpoint.assetavailable.subscriber"
+ "deviceForUUID:"
+ "handleEndpointAssetAvailable:"
+ "initWithUUIDString:"
+ "initWithVendorID:productID:serialNumber:serviceName:"
+ "initWithVendorID:productID:serialNumber:uuid:serviceName:"
+ "knownDatabaseEntryForUUID:"
+ "matchAndStartServiceForKnownEntry:"
+ "serviceName"
+ "setDeviceTransportDomain:"
+ "startEndpointAssetAvailabilityMatching"
+ "uarpTransportDomain"
- "@40@0:8@16@24@32"
- "VID <%@>, PID <%@>, Serial Number <%@>, UUID <%@>"
- "checkDatabaseForKnownVendorID:productID:serialNumber:"
- "initWithVendorID:productID:serialNumber:"
- "initWithVendorID:productID:serialNumber:uuid:"
```
