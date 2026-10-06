## rapportd

> `/usr/libexec/rapportd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1940b8` | `0x194e64` | **`+0xdac`** |
| `__TEXT.__cstring` | `0x36cb6` | `0x36ed6` | **`+0x220`** |
| `__TEXT.__objc_methname` | `0x1c650` | `0x1c730` | **`+0xe0`** |
| `__TEXT.__objc_stubs` | `0x13520` | `0x135e0` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0xa28` | `0xac0` | **`+0x98`** |
| `__DATA.__objc_const` | `0x11c90` | `0x11cd0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x39a0` | `0x39e0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x4c7c` | `0x4c44` | **`-0x38`** |
| `__TEXT.__objc_methlist` | `0xa0b0` | `0xa0e8` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x5e30` | `0x5e60` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x8448` | `0x8470` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x1ce0` | `0x1d00` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x5948` | `0x5968` | **`+0x20`** |
| `__DATA.__bss` | `0x4720` | `0x4730` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x4aa1` | `0x4ab1` | **`+0x10`** |
| `__DATA.__common` | `0xc8` | `0xd0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1124` | `0x112c` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x24ac` | `0x24b0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
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
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-743.100.4.0.0
+745.100.4.0.0

-  Functions: 8571
-  Symbols:   1449
-  CStrings:  10842
+  Functions: 8583
+  Symbols:   1453
+  CStrings:  10861
Symbols:
+ _nw_advertise_descriptor_get_advertise_scope
+ _nw_array_is_empty
+ _nw_endpoint_copy_dictionary
+ _nw_endpoint_create_from_dictionary
+ _nw_endpoint_get_application_service_alias
+ _nw_endpoint_set_application_service_alias
- _nw_framer_connection_state_copy_object_value
- _nw_framer_connection_state_set_object_value
CStrings:
+ "### Activation of BLE CBServer failed: %@"
+ "+[QRServiceDiscoveryEndpointInfo resolvedEndpointFromBrowseEndpoint:sessionUUID:]"
+ "-[QRServiceDiscoveryEndpointInfo browseEndpointForService:agentClientID:]"
+ "-[QRServiceDiscoveryQueryResult browseEndpointForAgentClientID:]"
+ "-[RPCompanionLinkDaemon _miscHandleLaunchAppRequest:responseHandler:]_block_invoke_4"
+ "-[RPCompanionLinkDaemon _restartBLECBServer]"
+ "-[RPCompanionLinkDaemon _startBLECBServer]_block_invoke_3"
+ "-[RPServiceDiscoveryClient _systemMonitorStart]_block_invoke_3"
+ "B28@0:8@16I24"
+ "BackgroundLow"
+ "Failed to obtain advertise descriptor for service\n"
+ "FindNearbyLocalFindableAccessoryExtendedRange"
+ "Rejecting unauthorized request\n"
+ "Resolved QR endpoint to %@ from browse %@"
+ "Restart BLE CBServer after %lu seconds"
+ "Unable to resolve QR endpoint - no alias"
+ "Unable to resolve QR endpoint - no placeholder"
+ "_bleCBServerRestartInterval"
+ "_bleCBServerRestartTimer"
+ "_restartBLECBServer"
+ "_stopBLECBServer"
+ "advertiseScopeForDevice:"
+ "browseEndpointForAgentClientID:"
+ "browseEndpointForService:agentClientID:"
+ "canIncomingRequestFromDevice:accessAdvertiseScope:"
+ "intersectSet:"
+ "resolvedEndpointFromBrowseEndpoint:sessionUUID:"
- "-[QRServiceDiscoveryEndpointInfo endpointForService:sessionUUID:]"
- "-[QRServiceDiscoveryQueryResult endpointWithSessionUUID:]"
- "-[RPCompanionLinkDaemon _miscHandleLaunchAppRequest:responseHandler:]_block_invoke_2"
- "-[RPServiceDiscoveryClient _systemMonitorStart]_block_invoke_2"
- "endpointForService:sessionUUID:"
- "endpointWithSessionUUID:"
- "started"
- "true"
```
