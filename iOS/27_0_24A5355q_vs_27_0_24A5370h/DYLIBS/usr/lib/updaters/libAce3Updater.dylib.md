## libAce3Updater.dylib

> `/usr/lib/updaters/libAce3Updater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0x798` | `0x7a8` | **`+0x10`** |
| `__TEXT.__text` | `0x1ef4c` | `0x1ef50` | **`+0x4`** |

### Other Changes

```diff

-1576.0.0.0.0
+1587.0.3.0.3
Functions:
~ _CoreUARPRestoreQueryOutstandingInfoProperties : 312 -> 296
~ _fAssetReady : 264 -> 268
~ _fPayloadReady : 204 -> 208
~ _fPayloadMetaDataComplete : 232 -> 236
~ _fPayloadData : 300 -> 304
~ _fPayloadDataComplete : 432 -> 428
~ _UarpRestoreInitializeCommon : 640 -> 636
~ -[NSDictionary(KeyPrefixSearch) keyWithPrefix:] : 304 -> 300
~ _fPersonalizedFirmwarePayloadData : 52 -> 56
~ -[UARPSoCUpdaterController firmwareTags] : 340 -> 336
~ -[UARPSoCUpdaterController ticketNameTags] : 340 -> 336
~ -[UARPSoCUpdaterController queryInfo] : 580 -> 576
~ -[UARPSoCUpdaterController offerFirmwareDataWithDictionary:] : 488 -> 484
~ -[UARPSoCUpdaterController offerPersonalizationDataWithDictionary:] : 452 -> 448
~ -[UARPSoCUpdaterController applyStagedFirmware] : 452 -> 448
~ _uarpPlatformEndpointStreamingRecvBytes : 272 -> 280
~ _UARPLayer2RequestTransmitMsgBuffer : 112 -> 136
~ _UARPPlatformDownstreamEndpointByID : 80 -> 88
~ _UARPPlatformDownstreamEndpointByDelegate : 76 -> 84
~ _uarpPlatformRemoteEndpointAddEntry : 228 -> 232
~ _uarpPlatformReleaseEndpointIDs : 140 -> 132
~ _uarpSendVendorSpecific : 232 -> 228
~ _uarpPlatformEndpointRecvMessage : 7260 -> 7256
~ _uarpLogToken : 124 -> 120
~ _uarpPlatformRemoteEndpointRemove : 144 -> 148
~ _uarpPlatformEndpointBulkInfoQuery : 260 -> 268
~ _uarpPlatformConfigureEndpointIDs : 156 -> 168
~ _uarpPlatformConfigureEndpointTags : 224 -> 228
~ _flash : 1240 -> 1236
~ _print_fw_update_regs : 304 -> 308
~ _OUTLINED_FUNCTION_4 : 20 -> 16
~ _OUTLINED_FUNCTION_10 : 12 -> 16
~ _fAssetAllHeadersAndMetaDataComplete : 2500 -> 2488
~ _CRCBuffer : 108 -> 104
~ _apBoardForAceBoard : 60 -> 68
~ _apChipForAceBoard : 60 -> 64
~ _FWImageDestroy : 124 -> 140
~ _FWImageCreateImageBuffer : 388 -> 392
~ _get_number_of_uart_hpms : 500 -> 504
~ _internalBackendFlash : 2808 -> 2760
~ _externalBackendCreate : 1360 -> 1364
```
