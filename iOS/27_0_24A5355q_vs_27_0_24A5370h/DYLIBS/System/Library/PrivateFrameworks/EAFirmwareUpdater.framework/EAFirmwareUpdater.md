## EAFirmwareUpdater

> `/System/Library/PrivateFrameworks/EAFirmwareUpdater.framework/EAFirmwareUpdater`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb790` | `0xb788` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2a0` | `0x2a8` | **`+0x8`** |

### Other Changes

```diff

-1576.0.0.0.0
+1587.0.3.0.3
Functions:
~ -[HSModel getHSModelForEngineMajorVersion:minorVersion:numHSModels:modelBuffer:length:] : 1028 -> 1024
~ -[iAUPServer sendCommand:payload:payload_length:] : 312 -> 320
~ -[iAUPServer processManifestProperties:length:] : 1124 -> 1120
~ +[EAFirmwareUpdater findAccessoryWithProtocolString:serialNum:] : 520 -> 516
~ -[EAFirmwareUpdater processPersonalizationInfoFromAccessory:] : 2696 -> 2692
~ -[EAFirmwareUpdater writeData:] : 396 -> 392
~ _generateHashForDataAtLocation : 168 -> 164
~ -[EAFirmwareUpdater supportedProtocolForAccessory:] : 380 -> 376
~ -[EAFirmwareUpdater assetWithMaxVersion:] : 440 -> 436
~ -[EAFirmwareUpdater validateAsset] : 1108 -> 1112
~ -[EAFirmwareUpdater handleInputData] : 252 -> 268
~ -[FirmwareBundle initWithBundle:] : 1144 -> 1140
```
