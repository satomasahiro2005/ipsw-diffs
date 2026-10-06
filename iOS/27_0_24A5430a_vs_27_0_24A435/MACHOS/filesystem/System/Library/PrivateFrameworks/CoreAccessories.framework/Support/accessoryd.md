## accessoryd

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19cc00` | `0x19fdb0` | **`+0x31b0`** |
| `__TEXT.__oslogstring` | `0x3809a` | `0x390eb` | **`+0x1051`** |
| `__TEXT.__cstring` | `0xe323` | `0xe5f5` | **`+0x2d2`** |
| `__DATA_CONST.__const` | `0xa230` | `0xa2d8` | **`+0xa8`** |
| `__DATA_CONST.__cfstring` | `0x7340` | `0x73c0` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x47e0` | `0x4830` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x321c` | `0x324c` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0xfeab` | `0xfed6` | **`+0x2b`** |
| `__DATA_CONST.__got` | `0xed8` | `0xef8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x6e8c` | `0x6eac` | **`+0x20`** |
| `__DATA.__objc_const` | `0xb078` | `0xb080` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x33b8` | `0x33c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-  Functions: 8661
-  Symbols:   11669
-  CStrings:  8652
+  Functions: 8706
+  Symbols:   11697
+  CStrings:  8722
Symbols:
+ -[ACCTransportPluginManager endpointForConnectionWithUUID:forProtocol:]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-decrypt-019ae603d8dc1916f3f174dbee15c627.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-encrypt-9e7ae0279713610c45dd45353c559a7e.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-3ddfda8a63119859f5b14b3f1b605f6c.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-b63500f7e934b6af4db0708ea018a493.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_cmp-80c32cc5c01954b7c782c8d4a2058b8f.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-19ad6d8be147053e768386ae23119c7a.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-6ab91b4ee8a78c8edf57750bf9d931d4.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_n-85618de6e74bd8ca5a62508d02e09c6a.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_set-f463c0553cb4abcbc5e87cd3c4e2078d.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-21bd53e832b4d5d2c14dc98f2899be5f.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-f0c64433c05768d694ca1414363320cd.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-8c74001941e320c1fd60df76badb29da.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-a4e2ec8b55a562dca16e81f81fcd042e.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub1-4fecf7636e482b76ad79003cfdd0d64e.o)
+ GCC_except_table224
+ GCC_except_table241
+ GCC_except_table252
+ ____configStream_endpoint_copyOOBPairingEndpointUUID_block_invoke
+ ____configStream_endpoint_handleInternalCategoriesRequest_block_invoke
+ ____configStream_endpoint_sendOOBPairingConfigStreamMessage_block_invoke
+ ___acc_endpoint2_setParentEndpointDataSendTypeHandler_block_invoke
+ ___block_descriptor_32_e59_v48?0^v8^{__CFString=}16^{__CFString=}24^?32^{__CFData=}40l
+ ___configStream_endpoint_create_block_invoke
+ __acc_endpoint2_setParentEndpointDataSendTypeHandler_block_invoke
+ __configStream_endpoint_copyExpectedInternalClient
+ __configStream_endpoint_oobPairingSendHandler
+ __configStream_endpoint_sendMessageToOOBPairingEndpoint
+ __configStream_endpoint_sendOOBPairingConfigStreamMessage
+ __configStream_endpoint_setupOOBPairingEndpointPath
+ __oobPairing_endpoint_handlePairingInfo
+ __oobPairing_endpoint_processOOBPairingEarlyInfo
+ _acc_connection2_getOOBPairingPlatformID_internal
+ _acc_endpoint2_setParentEndpointDataSendTypeHandler
+ _configStream_endpoint_copyExpectedInternalClient
+ _configStream_endpoint_oobPairingSendHandler
+ _configStream_endpoint_sendMessageToOOBPairingEndpoint
+ _kCFACCProperties_Connection_Inductive_ExtendedID
+ _kCFACCProperties_Connection_Inductive_FamilyID
+ _kCFACCProperties_Connection_OOBPairingEarlyInfoBDADDR
+ _kCFACCProperties_Connection_OOBPairingEarlyInfoSessionState
+ _kCFACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _kCFACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _kCFACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _kCFACCUserDefaultsKey_PlatformIDOverride
+ _oobPairing_endpoint_clearOOBPairingEarlyInfo
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-decrypt-ccc7cff5b191b013cf5fb35cb64a23b0.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-encrypt-dee892b8a883442591a56193ff213ab1.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-0643ae0983c6d6a4b3c8c09ad4d5f8af.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-7396cdf04cf0e11a5ee1deb7adf6cf6b.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_cmp-c7f8fa4991bd458cc9b68fe2b4a1b5be.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-154366ba21740639469c9f8dcb9992fd.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-b9ae2bf717c00f2781f7da0d14f0b822.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_n-0ccae82d708f96c89af9206b7d4cda6e.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_set-e613a10ccab0c60846c4010594257edb.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-4138e314e6afe7b9cda759c0c4f4f735.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-aa8122ee8b98ff5a46cb63f6ce2104cc.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-572af56cf296e19afd74df043de6f50b.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-66c9125dc4d0d3bb1cab06c98eb40567.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub1-aa8e6840769a65199b0616daf60f729c.o)
- GCC_except_table221
- GCC_except_table232
- GCC_except_table249
- ____configStream_endpoint_connectionInfo_categoryListReady_block_invoke
CStrings:
+ "%s: %@, accessoryPlatformID 0x%x -> 0x%lx"
+ "%s: %@, accessoryPlatformID 0x%x -> 0x%x, override %ld"
+ "%s: %@, defer configStream RequestGetProperty(%d) : OOBInfo(%d) : AccessoryOOBData(%d)"
+ "%s: %@, delay between SetPropertyValue and RequestGetProperty %ld ms"
+ "%s: %@, familyID %@, extendedID %@, deviceType %@, accessoryPlatformID 0x%x"
+ "%s: %@, messageID %d, pairingType %d, paylaodLen %ld"
+ "%s: %@, overridePlatformID %ld"
+ "%s: %@, send configStream SetPropertyValue(%d) : OOBInfo(%d) : DeviceBDADDR(%d), %ld bytes"
+ "%s: BDADDR %@ -> %@, sessionState %d -> %d"
+ "%s: BD_ADDR cleared, releasing stale cachedOOBPairingInfo %@"
+ "%s: No change: BDADDR %@, sessionState %d"
+ "%s: bdAddr %@ is invalid!!"
+ "%s: bdAddrChanged %d, everUpdated %d, pairType %d, payload %@ pairInfoList %@"
+ "%s: cfSessionState %@ is invalid!!"
+ "%s: clientStarted %d, everUpdated %d, newSessionState %d, newBDADDR %@"
+ "%s: clientStarted %d, wasFirstBDADDRUpdate %d, sessionStateChanged %d, bdAddrChanged %d"
+ "%s: connectionUUID %@, endpointUUID %@, protocol %{coreacc:ACCEndpoint_Protocol_t}d"
+ "%s: didn't find endpoint of protocol %{coreacc:ACCEndpoint_Protocol_t}d for connectionUUID %@"
+ "%s: endpoint: %@, oobPairing not supported"
+ "%s: failed to set parent endpoint UUID %@ for OOBPairing endpoint %@"
+ "%s: failed to setParentEndpointDataSendTypeHandler for oobPairing endpoint %@, parent %@"
+ "%s: sessionStateChanged %d, everUpdated %d -> %d, needFirstBDADDRUpdate %d -> %d"
+ "%s:%d platformID = %d, accessoryPlatformID = %@, accInfoOverrideDict = %@"
+ "-[ACCTransportPluginManager endpointForConnectionWithUUID:forProtocol:]"
+ "@\"NSString\"28@0:8@\"NSString\"16i24"
+ "@28@0:8@16i24"
+ "BLEPairingConfigRequestDelayMs"
+ "BLEPairingDisableOOBPPlusFlow"
+ "BLEPairingDontEarlyInfoAsDeviceUID"
+ "ERROR: Invalid messageID (%d) for OOBPairing transmit, sourceEndpointUUID %@, parentEndpointUUID %@"
+ "ERROR: Unable to match connection for sourceEndpointUUID %@, parentEndpointUUID %@"
+ "Forwarding data from endpoint %@ to parent endpoint %@, dataSendHandler %d, data length %ld"
+ "Parent endpoint %@ not found"
+ "PlatformIDOverride"
+ "Resetting parentEndpoint(%@) data send handler for endpoint %@"
+ "Send OOBPairing Info for endpoint: %@ bleUUID: %@, save to cachedDeviceBDADDR %@"
+ "Setting parentEndpoint(%@) data send handler for endpoint %@"
+ "_configStream_endpoint_createOOBPairingEndpoint"
+ "_configStream_endpoint_sendOOBPairingConfigStreamMessage"
+ "_configStream_endpoint_sendOOBPairingConfigStreamMessage_block_invoke"
+ "_configStream_endpoint_setupOOBPairingEndpointPath"
+ "_oobPairing_endpoint_copyConnectionEarlyInfoBDADDR"
+ "_oobPairing_endpoint_getConnectionEarlyInfoSessionState"
+ "_oobPairing_endpoint_processOOBPairingEarlyInfo"
+ "acc_connection2_getOOBPairingPlatformID_internal"
+ "configStream %@: oobPairing messageID %d from sourceEndpoint %@, data length %ld"
+ "configStream (manager2) createOOBPairingEndpoint for configStream endpoint: %@"
+ "configStream (manager2) created and published oobPairing endpoint %@ with parent %@, success %d"
+ "configStream (manager2) failed to create OOBPairing endpoint for connection %@"
+ "configStream (manager2) failed to get OOBPairing endpoint struct %@"
+ "configStream (manager2) failed to publish oobPairing endpoint %@"
+ "configStream (manager2) failed to set parent endpoint UUID %@ for OOBPairing endpoint %@"
+ "configStream (manager2) sendMessageToOOBPairingEndpoint: OOB endpoint %@ not on same connection as configStream endpoint %@"
+ "configStream checkOOBPairingMessage for configStream endpoint: %@, categoryID 0x%x / propertyID 0x%x"
+ "configStream checkOOBPairingMessage for configStream endpoint: %@, categoryID 0x%x / propertyID 0x%x -> oobPairingMessage 0x%x"
+ "configStream checkOOBPairingSupport for endpoint: %@, supportsOOBPairing %d"
+ "configStream handleInternalCategoriesRequest for endpoint: %@, Failed to get endpoint struct for oobPairingEndpoint %@ !!!"
+ "configStream handleInternalCategoriesRequest for endpoint: %@, create new oobPairingEndpoint!"
+ "configStream handleInternalCategoriesRequest for endpoint: %@, oobPairingEndpoint %@ already exists!"
+ "configStream processIncomingPairingInfoData: Invalid propertyValue length %lu"
+ "configStream processOOBPairingInfoData for endpoint: %@, clientUID %@, categoryID 0x%x, propertyID %u, propertyValue %@, unknown messageID %u !!!"
+ "configStream processOOBPairingInfoData for endpoint: %@, clientUID %@, internal request: categoryID 0x%x, propertyID %u, propertyValue %@"
+ "configStream sendMessageToOOBPairingEndpoint: %@, messageID %d, pairingType %d, oobPairingValueLen %d, dataIn %@"
+ "configStream sendMessageToOOBPairingEndpoint: Failed to send!!! oobPairingEndpointUUID %@, messageID %d, pairingType %d, oobPairingValueLen %d"
+ "configStream setupOOBPairingEndpointPath for configStream endpoint: %@"
+ "configStream: oobPairing endpoint %@ sending data through configStream endpoint %@, data length %ld"
+ "endpointForConnectionWithUUID:forProtocol:"
+ "oobPairing data received from endpoint %@, converted to configStream operation... ignored %d"
+ "oobPairing_endpoint_clearOOBPairingEarlyInfo"
+ "v48@?0^v8^{__CFString=}16^{__CFString=}24^?32^{__CFData=}40"
```
