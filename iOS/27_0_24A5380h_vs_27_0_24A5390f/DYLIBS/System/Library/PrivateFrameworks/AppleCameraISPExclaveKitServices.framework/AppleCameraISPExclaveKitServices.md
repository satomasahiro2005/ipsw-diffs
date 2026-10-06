## AppleCameraISPExclaveKitServices

> `/System/Library/PrivateFrameworks/AppleCameraISPExclaveKitServices.framework/AppleCameraISPExclaveKitServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30b60` | `0x30c0c` | **`+0xac`** |

### Other Changes

```diff

-20.55.3.0.0
+20.57.3.0.0

-  Functions: 1174
+  Functions: 1175
Functions:
~ __ZN28ISPExclaveKitHostMetaManager19parseHostMetaSensorEPhP18HostMetaSensorInfo : 128 -> 140
~ __ZN28ISPExclaveKitHostMetaManager26readNextAndParseSensorMetaEP18HostMetaSensorInfoPm : 464 -> 480
~ __Z29ispExclaveKitCommandChInfoSetP20sExclaveKitIspCmdHdr : 2292 -> 2348
~ __Z34ispExclaveKitCommandChSendMetadataP20sExclaveKitIspCmdHdr : 1176 -> 1172
~ __ZL48_convertFrameworkSensorMetaToTightbeamSensorMetaPKN25ISPExclaveKitAutoExposure31sExclaveKitIspCmdChSendMetadataEP57applecamera_ispexclavekitshared_ekchannelsensormetadata_s : 364 -> 368
~ _applecamera_ispexclavekitshared_ekispmanager_channelsensormetadataset : 1088 -> 1100
+ __Z29ispExclaveKitCommandChInfoSetP20sExclaveKitIspCmdHdr.cold.16
```
