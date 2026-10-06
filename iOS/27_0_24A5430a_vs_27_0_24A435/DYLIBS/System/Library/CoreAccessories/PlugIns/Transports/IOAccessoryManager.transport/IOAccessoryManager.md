## IOAccessoryManager

> `/System/Library/CoreAccessories/PlugIns/Transports/IOAccessoryManager.transport/IOAccessoryManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d73c` | `0x611dc` | **`+0x3aa0`** |
| `__TEXT.__oslogstring` | `0xbcbc` | `0xc94a` | **`+0xc8e`** |
| `__TEXT.__cstring` | `0x5ffa` | `0x64f3` | **`+0x4f9`** |
| `__AUTH_CONST.__cfstring` | `0x45c0` | `0x4760` | **`+0x1a0`** |
| `__TEXT.__objc_methlist` | `0x2f94` | `0x30bc` | **`+0x128`** |
| `__AUTH_CONST.__objc_const` | `0x4d10` | `0x4e30` | **`+0x120`** |
| `__DATA_CONST.__const` | `0xf08` | `0x1020` | **`+0x118`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f10` | `0x1ff8` | **`+0xe8`** |
| `__TEXT.__unwind_info` | `0xec8` | `0xf18` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x8f4` | `0x938` | **`+0x44`** |
| `__DATA.__objc_ivar` | `0x46c` | `0x484` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x4a8` | `0x4b8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xb00` | `0xb08` | **`+0x8`** |
| `__TEXT.__const` | `0x368` | `0x360` | **`-0x8`** |

### Other Changes

```diff

-  Functions: 1950
-  Symbols:   2846
-  CStrings:  1710
+  Functions: 1992
+  Symbols:   2897
+  CStrings:  1773
Symbols:
+ -[ACCTransportIOAccessoryAuthCP _handleBusyComponentAuth]
+ -[ACCTransportIOAccessoryManager _clearOOBPairingEarlyInfo]
+ -[ACCTransportIOAccessoryManager _handleOOBPairingEarlyInfo:]
+ -[ACCTransportIOAccessoryManager _processOOBPairingAccessoryInfoDataProperty]
+ -[ACCTransportIOAccessoryManager _processOOBPairingEarlyInfoChange]
+ -[ACCTransportIOAccessoryManager _processOOBPairingEarlyInfo]
+ -[ACCTransportIOAccessoryManager _processOOBPairingProperty:label:existingData:messageID:completion:]
+ -[ACCTransportIOAccessoryManager oobPairingAccessoryData]
+ -[ACCTransportIOAccessoryManager oobPairingAccessoryInfo]
+ -[ACCTransportIOAccessoryManager oobPairingEarlyInfoBDADDR]
+ -[ACCTransportIOAccessoryManager oobPairingEarlyInfoEndpointUUID]
+ -[ACCTransportIOAccessoryManager oobPairingEarlyInfoSessionState]
+ -[ACCTransportIOAccessoryManager oobPairingEarlyInfo]
+ -[ACCTransportIOAccessoryManager setOobPairingAccessoryData:]
+ -[ACCTransportIOAccessoryManager setOobPairingAccessoryInfo:]
+ -[ACCTransportIOAccessoryManager setOobPairingEarlyInfo:]
+ -[ACCTransportIOAccessoryManager setOobPairingEarlyInfoBDADDR:]
+ -[ACCTransportIOAccessoryManager setOobPairingEarlyInfoEndpointUUID:]
+ -[ACCTransportIOAccessoryManager setOobPairingEarlyInfoSessionState:]
+ -[ACCTransportIOAccessorySharedManager _blePairingTransportTypeForConnectionType:]
+ -[ACCTransportIOAccessorySharedManager _createBLEPairingEndpointForManager:publish:]
+ -[ACCTransportIOAccessorySharedManager _destroyBLEPairingEndpointForManager:]
+ -[ACCTransportIOAccessorySharedManager _handleInductiveOOBPairingTransmitData:forEndpointUUID:manager:]
+ -[ACCTransportIOAccessorySharedManager _managerForInductiveOOBPairingEndpointUUID:]
+ -[ACCTransportIOAccessorySharedManager handleOOBPairingEarlyInfoNotification:]
+ GCC_except_table112
+ GCC_except_table116
+ GCC_except_table38
+ GCC_except_table72
+ _ACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _ACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _ACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _ACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _ACCUserDefaultsKey_PlatformIDOverride
+ _ACCUserDefaultsKey_TestCreateBLEPairingOnInductive
+ _IOAccessoryManagerSetInductiveOOBPairingHostInfo
+ _OBJC_IVAR_$_ACCTransportIOAccessoryManager._oobPairingAccessoryData
+ _OBJC_IVAR_$_ACCTransportIOAccessoryManager._oobPairingAccessoryInfo
+ _OBJC_IVAR_$_ACCTransportIOAccessoryManager._oobPairingEarlyInfo
+ _OBJC_IVAR_$_ACCTransportIOAccessoryManager._oobPairingEarlyInfoBDADDR
+ _OBJC_IVAR_$_ACCTransportIOAccessoryManager._oobPairingEarlyInfoEndpointUUID
+ _OBJC_IVAR_$_ACCTransportIOAccessoryManager._oobPairingEarlyInfoSessionState
+ ___77-[ACCTransportIOAccessoryManager _processOOBPairingAccessoryInfoDataProperty]_block_invoke
+ ___77-[ACCTransportIOAccessoryManager _processOOBPairingAccessoryInfoDataProperty]_block_invoke_2
+ ___83-[ACCTransportIOAccessorySharedManager _managerForInductiveOOBPairingEndpointUUID:]_block_invoke
+ ___83-[ACCTransportIOAccessorySharedManager _managerForInductiveOOBPairingEndpointUUID:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40s_e27_v24?0"NSData"8"NSData"16ls32l8s40l8
+ ___block_descriptor_80_e8_32s40r48r56r64r72r_e36_v36?0B8"NSData"12"NSData"20B28i32lr40l8r48l8r56l8r64l8r72l8s32l8
+ _kACCProperties_Connection_OOBPairingEarlyInfoBDADDR
+ _kACCProperties_Connection_OOBPairingEarlyInfoSessionState
+ _kCFACCUserDefaultsKey_BLEPairingConfigRequestDelayMs
+ _kCFACCUserDefaultsKey_BLEPairingDisableOOBPPlusFlow
+ _kCFACCUserDefaultsKey_BLEPairingDontEarlyInfoAsDeviceUID
+ _kCFACCUserDefaultsKey_BLEPairingIgnoreZeroEarlyInfo
+ _kCFACCUserDefaultsKey_PlatformIDOverride
+ _kCFACCUserDefaultsKey_TestCreateBLEPairingOnInductive
- GCC_except_table104
- GCC_except_table108
- GCC_except_table39
- GCC_except_table64
- ___block_descriptor_72_e8_32s40r48r56r64r_e36_v36?0B8"NSData"12"NSData"20B28i32lr40l8r48l8r56l8r64l8s32l8
CStrings:
+ "%02x:%02x:%02x:%02x:%02x:%02x"
+ "%s: %@ create OOBPairingEndpoint for manager service %d, inductiveDeviceType %@, oobPairingEarlyInfo %@"
+ "%s: %@ destroy connection for OOBPairingEndpoint for manager service %d, inductiveDeviceType %@, oobPairingEarlyInfo %@"
+ "%s: %@ destroy endpoint for OOBPairingEndpoint for manager service %d, inductiveDeviceType %@, oobPairingEarlyInfo %@, oobPairingEarlyInfoEndpointUUID %@"
+ "%s: %s changed, %lu bytes, endpointUUID %@, %@ -> %@"
+ "%s: %s is zero-length, ignoring"
+ "%s: Create Endpoint ioAccMgr.oobPairingEarlyInfo = %@ (%@, %d), ioAccMgr.connectionUUID = %@,  %{coreacc:ACCConnection_Type_t}d, transportType %{coreacc:ACCEndpoint_TransportType_t}d, accInfoDictionary = %@"
+ "%s: IOAccessoryManagerSetInductiveOOBPairingHostInfo failed 0x%X, endpointUUID %@"
+ "%s: IOAccessoryManagerSetInductiveOOBPairingHostInfo success, endpointUUID %@, payloadLen %lu"
+ "%s: IOServiceOpen failed 0x%X, service %d, endpointUUID %@"
+ "%s: Not enough bytes (%lu) for message header, endpointUUID %@"
+ "%s: Test cfOOBPairingEarlyInfo %@ -> %@"
+ "%s: Unsupported messageID %d for inductive OOBPairing, endpointUUID %@"
+ "%s: connectionType %{coreacc:ACCConnection_Type_t}d -> transportType %{coreacc:ACCEndpoint_TransportType_t}d"
+ "%s: could not find manager object for service %d"
+ "%s: deviceUID %@"
+ "%s: deviceUID %@ -> %@"
+ "%s: endpoint %@ on connection %@ is the manager's OOBPairingEarlyInfo endpoint — connection stays alive until inductiveDeviceType -> 0"
+ "%s: endpointUUID %@, already created for connectionUUID %@"
+ "%s: endpointUUID %@, messageID %d, payloadLen %lu, manager service %d"
+ "%s: familyID %@, extendedID %@, deviceType %@"
+ "%s: found manager service %d for endpointUUID %@"
+ "%s: inductiveDeviceType %@, cfOOBPairingEarlyInfo %@, oobPairingEarlyInfo %@"
+ "%s: inductiveDeviceType %@, oobPairingEarlyInfo %@, self.oobPairingEarlyInfo %@"
+ "%s: inductiveDeviceType %@, oobPairingEarlyInfo: %@, BDADDR %@, SessionState %d, self.connectionUUID %@"
+ "%s: ioAccMgr.oobPairingEarlyInfo = %@ (%@, %d), ioAccMgr.inductiveDeviceType %@, ioAccMgr.connectionUUID = %@, connectionType %{coreacc:ACCConnection_Type_t}d, publish %d"
+ "%s: ioAccMgr.oobPairingEarlyInfo = %@, ioAccMgr.inductiveDeviceType %@, ioAccMgr.connectionUUID = %@, connectionType %{coreacc:ACCConnection_Type_t}d, endpointUUID %@"
+ "%s: oobPairingEarlyInfo SAME: %@ -> %@, BDADDR %@ -> %@, SessionState %d -> %d"
+ "%s: oobPairingEarlyInfo: %@ -> %@, BDADDR %@ -> %@, SessionState %d -> %d"
+ "%s: oobPairingEarlyInfoBDADDR %@"
+ "%s: unexpected CFTypeID for %s property: %lu"
+ "%s: unexpected CFTypeID for oobPairingEarlyInfo property: %lu"
+ "%s: unexpectedly found %lu managers for endpointUUID %@ — returning nil to avoid arbitrary routing"
+ "-[ACCTransportIOAccessoryManager _handleOOBPairingEarlyInfo:]"
+ "-[ACCTransportIOAccessoryManager _processOOBPairingEarlyInfoChange]"
+ "-[ACCTransportIOAccessoryManager _processOOBPairingEarlyInfo]"
+ "-[ACCTransportIOAccessoryManager _processOOBPairingProperty:label:existingData:messageID:completion:]"
+ "-[ACCTransportIOAccessorySharedManager _blePairingTransportTypeForConnectionType:]"
+ "-[ACCTransportIOAccessorySharedManager _createBLEPairingEndpointForManager:publish:]"
+ "-[ACCTransportIOAccessorySharedManager _destroyBLEPairingEndpointForManager:]"
+ "-[ACCTransportIOAccessorySharedManager _handleInductiveOOBPairingTransmitData:forEndpointUUID:manager:]"
+ "-[ACCTransportIOAccessorySharedManager _managerForInductiveOOBPairingEndpointUUID:]"
+ "-[ACCTransportIOAccessorySharedManager handleOOBPairingEarlyInfoNotification:]"
+ "AccessoryData"
+ "AccessoryInfo"
+ "BLEPairingConfigRequestDelayMs"
+ "BLEPairingDisableOOBPPlusFlow"
+ "BLEPairingDontEarlyInfoAsDeviceUID"
+ "BLEPairingIgnoreZeroEarlyInfo"
+ "CertificateSupportsRCAM"
+ "ComponentBusyError"
+ "Got kIOMessageServicePropertyChange (svc:%d) for manager, Insufficient bytes (or all 0) for oobPairingEarlyInfo: %lu, expected valid %d bytes!!!"
+ "IOAccessoryManagerInductiveOOBPairingAccessoryData"
+ "IOAccessoryManagerInductiveOOBPairingAccessoryInfo"
+ "IOAccessoryManagerInductiveOOBPairingEarlyInfo"
+ "PlatformIDOverride"
+ "RCAM"
+ "TestCreateBLEPairingOnInductive"
+ "Transient port-level detach (svc:%d): inductiveDeviceType=%@ still non-zero and OOBPairingEarlyInfo endpoint %@ live; skipping detach propagation. Real detach will arrive via inductiveDeviceType -> 0."
+ "kAppleAuthCPMessageDeferredSignatureReceived received.  Re-Starting authentication process."
+ "prpc"
+ "setFeaturesFromAuthStatus: [%d] authStatus %d, _bIsInductive %d, inductiveFwMode %d, isEspressoOutAccessory %d, supportInductivePowerTX %d -> %d"
+ "v24@?0@\"NSData\"8@\"NSData\"16"
```
