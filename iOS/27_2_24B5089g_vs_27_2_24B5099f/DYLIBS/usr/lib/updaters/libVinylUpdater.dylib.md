## libVinylUpdater.dylib

> `/usr/lib/updaters/libVinylUpdater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xaf2d` | `0xa6c3` | **`-0x86a`** |
| `__TEXT.__text` | `0x4dc6c` | `0x4d590` | **`-0x6dc`** |
| `__TEXT.__gcc_except_tab` | `0x47bc` | `0x47b4` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1988` | `0x1990` | **`+0x8`** |

### Other Changes

```diff

-  CStrings:  1365
+  CStrings:  1279
CStrings:
+ "VinylRestore-178~9513"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/VinylRestore/CommandDrivers/eUICCVinylICEValve.cpp"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/VinylRestore/CommandDrivers/eUICCVinylValve.cpp"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/VinylRestore/Communication/Eureka/VinylETLEUICC.cpp"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/VinylRestore/Support/BBUPurpleReverseProxy.cpp"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/VinylRestore/Update/Perso/eUICCPerso.cpp"
- "AuthPerso"
- "AuthenticatePersoDevice"
- "BBUFDRLogHandler"
- "BBULogPrintBinaryDelegate"
- "BBUReadNVRAM"
- "BBUReadNVRAM_block_invoke"
- "CreateDictionaryFromPlistData"
- "CreateValidationBlob"
- "DeleteProfile"
- "FinalizePerso"
- "FinalizePersoDevice"
- "ForcePerso"
- "GetData"
- "GetData_EoS"
- "GetNonceServer"
- "GetSIMSKUString"
- "GetSimMuxCfg"
- "GetValve"
- "GetVinylType"
- "GetWrapKeyServer"
- "HardwareHasESIM_block_invoke"
- "HowToProceed"
- "InitPerso"
- "InitPersoDevice"
- "InitPersoServer"
- "InstallPairingMSM"
- "InstallTicket"
- "LpaSigningRequest"
- "ManagePairingAuthenticate"
- "ManagePairingGetNonce"
- "Perform"
- "PostDataSync"
- "PowerDownSE"
- "PowerUpSE"
- "Refurb"
- "ResetCard"
- "ReverseProxyGetSettings"
- "ReverseProxyGetSettings_block_invoke"
- "Run"
- "SendReceiptServer"
- "SerializeKeyValuePairsIntoPlistData"
- "SetCardMode"
- "Step"
- "StoreData"
- "StreamFirmware"
- "SwitchSimMuxCfgPolled"
- "ValidatePerso"
- "ValidatePersoDevice"
- "VinylControllerObjDestroy"
- "VinylRestore-178~8717"
- "bbupdater_log"
- "checkEOSDev"
- "collectCoreDump"
- "createTransportNoEvents"
- "createTransport_block_invoke_2"
- "decodeConfigIdFromResponse"
- "decodeEuuidFromResponse"
- "freeTransport"
- "freeTransportSync"
- "freeTransportSync_block_invoke"
- "freeTransportSync_block_invoke_2"
- "getConfigIdBootstrapV2"
- "getECID_block_invoke"
- "getEID"
- "getPairingIdentifier"
- "getParamUpdateOperation"
- "get_info"
- "geteUUIDBootstrapV2"
- "inRestoreOS_block_invoke"
- "inRestoreOS_block_invoke_2"
- "isAbsentOkay"
- "isLETOCapable"
- "isNVRAMKeyPresent"
- "logEUICCData"
- "openChannel"
- "operator()"
- "perform"
- "startRouterServer"
- "statusCallback"
- "stopRouterServer"
- "supportsVinylUpdate"
- "waitForeSIMBoot"
```
