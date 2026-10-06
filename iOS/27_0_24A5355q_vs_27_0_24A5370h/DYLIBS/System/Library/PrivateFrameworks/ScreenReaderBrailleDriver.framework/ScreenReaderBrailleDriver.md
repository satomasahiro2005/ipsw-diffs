## ScreenReaderBrailleDriver

> `/System/Library/PrivateFrameworks/ScreenReaderBrailleDriver.framework/ScreenReaderBrailleDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc1ac` | `0xc1b4` | **`+0x8`** |

### Other Changes

```diff

-455.1.1.0.0
+458.0.0.0.0
Functions:
~ _SCRDBaumCreateDisplayRequest : 284 -> 276
~ _SCRDBaumCreatePacketFromBuffer : 636 -> 632
~ _SCRDBaumAppendEventsFromRoutingKeyGroupPacket : 472 -> 464
~ _SCRDBaumAppendEventsFromBrailleAndFrontPanelPacket : 1016 -> 1008
~ _SCRDBrailleNoteCreateDisplayRequest : 296 -> 320
~ _SCRDCygnalCP2110SetUARTSettings : 248 -> 252
~ _SCRDAdvanceBufferToPacketStart : 144 -> 140
~ _SCRDEasyLinkCreatePacketFromBuffer : 500 -> 516
~ _SCRDFTDISetBaudRate : 156 -> 152
~ -[SCRDFileReader _readHandler:] : 448 -> 444
~ _SCRDFreedomScientificCreatePacketFromBuffer : 368 -> 376
~ _SCRDFreedomScientificCreateWriteRequestPacket : 288 -> 296
~ _SCRDHIMSCreateRequest : 276 -> 308
~ _SCRDHandyTechExtractEventsFromBuffer : 572 -> 580
~ _SCRDMDVSerialCreateRequest : 224 -> 232
~ _SCRDMDVSerialExtractEventsFromBuffer : 524 -> 520
~ _SCRDNinepointSystemsNinepointCreateWriteBuffer : 276 -> 280
~ _SCRDPapenmeierCreateBrailleBufferA : 504 -> 500
~ _SCRDPapenmeierCreatePacketFromBuffer : 788 -> 744
~ _SCRDPapenmeierExtractEventsFromBuffer : 1592 -> 1588
~ _SCRDSeikaCreateWriteRequestPacket : 472 -> 468
~ _SCRDSeikaExtractEventsFromBuffer : 1448 -> 1444
~ -[SCRDUSBDevice openWithSeize:] : 108 -> 104
~ -[SCRDUSBDevice clearPipe:bothEnds:] : 76 -> 72
~ _SCRDKGSConvertBrailleCellsToKGSOrder : 80 -> 88
```
