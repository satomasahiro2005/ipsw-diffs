## com.apple.driver.usb.cdc.ncm

> `com.apple.driver.usb.cdc.ncm`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xd6e0` | `0xd950` | **`+0x270`** |

### Other Changes

```text
Functions:
~ sub_fffffff009a90490 -> sub_fffffff009b1b8e0 : 72 -> 76
~ sub_fffffff009a904e0 -> sub_fffffff009b1b934 : 52 -> 56
~ sub_fffffff009a90514 -> sub_fffffff009b1b96c : 52 -> 56
~ sub_fffffff009a90558 -> sub_fffffff009b1b9b4 : 68 -> 72
~ sub_fffffff009a905c4 -> sub_fffffff009b1ba24 : 72 -> 76
~ sub_fffffff009a9060c -> sub_fffffff009b1ba70 : 104 -> 108
~ sub_fffffff009a90688 -> sub_fffffff009b1baf0 : 88 -> 92
~ sub_fffffff009a906e0 -> sub_fffffff009b1bb4c : 88 -> 92
~ sub_fffffff009a90778 -> sub_fffffff009b1bbe8 : 160 -> 164
~ sub_fffffff009a90820 -> sub_fffffff009b1bc94 : 80 -> 84
~ sub_fffffff009a90880 -> sub_fffffff009b1bcf8 : 72 -> 76
~ sub_fffffff009a908d0 -> sub_fffffff009b1bd4c : 52 -> 56
~ sub_fffffff009a90914 -> sub_fffffff009b1bd94 : 68 -> 72
~ sub_fffffff009a90980 -> sub_fffffff009b1be04 : 104 -> 108
~ sub_fffffff009a909fc -> sub_fffffff009b1be84 : 88 -> 92
~ sub_fffffff009a90a54 -> sub_fffffff009b1bee0 : 260 -> 264
~ sub_fffffff009a90b58 -> sub_fffffff009b1bfe8 : 176 -> 180
~ __ZN15AppleUSBNCMData7armReadEv : 328 -> 332
~ sub_fffffff009a90d50 -> sub_fffffff009b1c1e8 : 72 -> 76
~ sub_fffffff009a90da0 -> sub_fffffff009b1c23c : 52 -> 56
~ sub_fffffff009a90dd4 -> sub_fffffff009b1c274 : 52 -> 56
~ sub_fffffff009a90e18 -> sub_fffffff009b1c2bc : 68 -> 72
~ sub_fffffff009a90e84 -> sub_fffffff009b1c32c : 72 -> 76
~ sub_fffffff009a90ecc -> sub_fffffff009b1c378 : 104 -> 108
~ sub_fffffff009a90f48 -> sub_fffffff009b1c3f8 : 88 -> 92
~ sub_fffffff009a90fa0 -> sub_fffffff009b1c454 : 88 -> 92
~ sub_fffffff009a90ff8 -> sub_fffffff009b1c4b0 : 72 -> 76
~ sub_fffffff009a91048 -> sub_fffffff009b1c504 : 88 -> 92
~ sub_fffffff009a910a8 -> sub_fffffff009b1c568 : 88 -> 92
~ sub_fffffff009a91100 -> sub_fffffff009b1c5c4 : 88 -> 92
~ sub_fffffff009a91158 -> sub_fffffff009b1c620 : 108 -> 112
~ sub_fffffff009a911ec -> sub_fffffff009b1c6b8 : 72 -> 76
~ sub_fffffff009a91234 -> sub_fffffff009b1c704 : 52 -> 56
~ sub_fffffff009a91284 -> sub_fffffff009b1c758 : 116 -> 120
~ __ZN15AppleUSBNCMData5startEP9IOService : 2956 -> 2960
~ sub_fffffff009a91e84 -> sub_fffffff009b1d360 : 108 -> 112
~ __ZN15AppleUSBNCMData29setPropertiesForInterfaceRoleEv : 204 -> 208
~ __ZN15AppleUSBNCMData31configureBSDInterfaceThreadCallEPvS0_ : 804 -> 808
~ __ZN15AppleUSBNCMData13willTerminateEP9IOServicej : 552 -> 556
~ __ZN15AppleUSBNCMData4stopEP9IOService : 600 -> 604
~ sub_fffffff009a92760 -> sub_fffffff009b1dc50 : 352 -> 356
~ sub_fffffff009a928c0 -> sub_fffffff009b1ddb4 : 228 -> 232
~ __ZN15AppleUSBNCMData27matchedBSDInterfaceNotifierEPvP9IOServiceP10IONotifier : 184 -> 188
~ __ZN15AppleUSBNCMData16setDataAlternateEv : 144 -> 148
~ __ZN15AppleUSBNCMData9lockNetifEv : 140 -> 144
~ sub_fffffff009a92c40 -> sub_fffffff009b1e144 : 216 -> 220
~ sub_fffffff009a92d94 -> sub_fffffff009b1e29c : 140 -> 144
~ sub_fffffff009a92e20 -> sub_fffffff009b1e32c : 200 -> 204
~ sub_fffffff009a92f90 -> sub_fffffff009b1e4a0 : 184 -> 188
~ sub_fffffff009a93048 -> sub_fffffff009b1e55c : 188 -> 192
~ sub_fffffff009a93160 -> sub_fffffff009b1e678 : 396 -> 400
~ sub_fffffff009a932ec -> sub_fffffff009b1e808 : 232 -> 236
~ __ZN15AppleUSBNCMData17dataWriteCompleteEPvij : 456 -> 460
~ sub_fffffff009a936b0 -> sub_fffffff009b1ebd4 : 120 -> 124
~ __ZN15AppleUSBNCMData16dataReadCompleteEPvij : 448 -> 452
~ sub_fffffff009a9391c -> sub_fffffff009b1ee48 : 292 -> 296
~ __ZN15AppleUSBNCMData7armReadEP15InputPipeRecord : 400 -> 404
~ __ZN15AppleUSBNCMData20setCarPlayPropertiesEv : 1064 -> 1068
~ __ZN15AppleUSBNCMData15selectNTBFormatEv : 456 -> 460
~ sub_fffffff009a941e8 -> sub_fffffff009b1f724 : 200 -> 204
~ sub_fffffff009a942b0 -> sub_fffffff009b1f7f0 : 68 -> 72
~ sub_fffffff009a94624 -> sub_fffffff009b1fb68 : 72 -> 76
~ sub_fffffff009a94674 -> sub_fffffff009b1fbbc : 52 -> 56
~ sub_fffffff009a946a8 -> sub_fffffff009b1fbf4 : 52 -> 56
~ sub_fffffff009a946ec -> sub_fffffff009b1fc3c : 68 -> 72
~ sub_fffffff009a94758 -> sub_fffffff009b1fcac : 72 -> 76
~ sub_fffffff009a947a0 -> sub_fffffff009b1fcf8 : 104 -> 108
~ sub_fffffff009a9481c -> sub_fffffff009b1fd78 : 88 -> 92
~ sub_fffffff009a94874 -> sub_fffffff009b1fdd4 : 88 -> 92
~ sub_fffffff009a948cc -> sub_fffffff009b1fe30 : 140 -> 144
~ sub_fffffff009a94958 -> sub_fffffff009b1fec0 : 200 -> 204
~ __ZN18AppleUSBNCMControl5startEP9IOService : 928 -> 932
~ sub_fffffff009a94dc0 -> sub_fffffff009b20330 : 112 -> 116
~ sub_fffffff009a94e4c -> sub_fffffff009b203c0 : 80 -> 84
~ sub_fffffff009a94ff0 -> sub_fffffff009b20568 : 72 -> 76
~ sub_fffffff009a95040 -> sub_fffffff009b205bc : 52 -> 56
~ sub_fffffff009a95074 -> sub_fffffff009b205f4 : 52 -> 56
~ sub_fffffff009a950b8 -> sub_fffffff009b2063c : 68 -> 72
~ sub_fffffff009a95124 -> sub_fffffff009b206ac : 72 -> 76
~ sub_fffffff009a9516c -> sub_fffffff009b206f8 : 104 -> 108
~ sub_fffffff009a951e8 -> sub_fffffff009b20778 : 88 -> 92
~ sub_fffffff009a95240 -> sub_fffffff009b207d4 : 88 -> 92
~ __ZN20AppleUSBNCM11Control5startEP9IOService : 932 -> 936
~ sub_fffffff009a958e0 -> sub_fffffff009b20e7c : 80 -> 84
~ sub_fffffff009a95c24 -> sub_fffffff009b211c4 : 96 -> 100
~ sub_fffffff009a95c84 -> sub_fffffff009b21228 : 212 -> 216
~ __ZN17AppleUSBNCM11Data25notificationCallbackGatedEP18AppleUSBNCMControlPvP18USBCDCNotification : 348 -> 352
~ __ZN15AppleUSBNCMData4initEP12OSDictionary : 324 -> 328
~ __ZN15AppleUSBNCMData19initStatsIOReporterEv : 544 -> 548
~ sub_fffffff009a96218 -> sub_fffffff009b217cc : 304 -> 308
~ sub_fffffff009a96348 -> sub_fffffff009b21900 : 260 -> 264
~ sub_fffffff009a9644c -> sub_fffffff009b21a08 : 800 -> 804
~ __ZN15AppleUSBNCMData32setAppleInternalCoProcPropertiesEv : 140 -> 144
~ sub_fffffff009a967f8 -> sub_fffffff009b21dbc : 216 -> 220
~ __ZN15AppleUSBNCMData22powerStateWillChangeToEmmP9IOService : 364 -> 368
~ __ZN15AppleUSBNCMData21powerStateDidChangeToEmmP9IOService : 436 -> 440
~ sub_fffffff009a96e00 -> sub_fffffff009b223d0 : 280 -> 284
~ __ZN15AppleUSBNCMData12setAlternateEt : 288 -> 292
~ __ZN15AppleUSBNCMData13configureDataEv : 452 -> 456
~ __ZN15AppleUSBNCMData6enableEP18IONetworkInterface : 760 -> 764
~ __ZN15AppleUSBNCMData18setupDataTransfersEv : 432 -> 436
~ __ZN15AppleUSBNCMData7disableEP18IONetworkInterface : 480 -> 484
~ sub_fffffff009a97990 -> sub_fffffff009b22f78 : 148 -> 152
~ __ZN15AppleUSBNCMData18configureInterfaceEP18IONetworkInterface : 424 -> 428
~ __ZN15AppleUSBNCMData18chooseIdlePoliciesEv : 472 -> 476
~ __ZN15AppleUSBNCMData14transmitRecordEP16OutputPipeRecord : 360 -> 364
~ sub_fffffff009a97f0c -> sub_fffffff009b23504 : 364 -> 368
~ __ZN15AppleUSBNCMData25notificationCallbackGatedEP18AppleUSBNCMControlPvP18USBCDCNotification : 592 -> 596
~ __ZN15AppleUSBNCMData7armReadEv.cold.1 : 140 -> 144
~ sub_fffffff009a98438 -> sub_fffffff009b23a3c : 52 -> 56
~ sub_fffffff009a9846c -> sub_fffffff009b23a74 : 152 -> 156
~ __ZN15AppleUSBNCMData29setPropertiesForInterfaceRoleEv.cold.1 : 184 -> 188
~ __ZN15AppleUSBNCMData29setPropertiesForInterfaceRoleEv.cold.2 : 168 -> 172
~ __ZN15AppleUSBNCMData31configureBSDInterfaceThreadCallEPvS0_.cold.1 : 172 -> 176
~ __ZN15AppleUSBNCMData13willTerminateEP9IOServicej.cold.1 : 168 -> 172
~ __ZN15AppleUSBNCMData4stopEP9IOService.cold.1 : 144 -> 148
~ __ZN15AppleUSBNCMData16setDataAlternateEv.cold.1 : 144 -> 148
~ __ZN15AppleUSBNCMData7armReadEP15InputPipeRecord.cold.1 : 152 -> 156
~ sub_fffffff009a98970 -> sub_fffffff009b23f98 : 140 -> 144
~ __ZN15AppleUSBNCMData7armReadEP15InputPipeRecord.cold.3 : 140 -> 144
~ __ZN18AppleUSBNCMControl5probeEP9IOServicePi : 360 -> 364
~ __ZN18AppleUSBNCMControl17copyDataInterfaceEv : 236 -> 240
~ __ZN18AppleUSBNCMControl27getMACAddressFromDescriptorEh : 496 -> 500
~ __ZN18AppleUSBNCMControl18cacheNTBParametersEv : 692 -> 696
~ __ZN18AppleUSBNCMControl24cacheAppleInterfaceFlagsEv : 504 -> 508
~ sub_fffffff009a99378 -> sub_fffffff009b249bc : 248 -> 252
~ sub_fffffff009a99470 -> sub_fffffff009b24ab8 : 432 -> 436
~ __ZN18AppleUSBNCMControl18setMulticastFilterEP17IOEthernetAddressj : 256 -> 260
~ __ZN18AppleUSBNCMControl15getPacketFilterEPt : 260 -> 264
~ __ZN18AppleUSBNCMControl15setPacketFilterEt : 232 -> 236
~ __ZN18AppleUSBNCMControl17setNetworkAddressEPht : 456 -> 460
~ sub_fffffff009a99c98 -> sub_fffffff009b252f4 : 172 -> 176
~ __ZN18AppleUSBNCMControl12getNTBFormatEPt : 252 -> 256
~ __ZN18AppleUSBNCMControl12setNTBFormatEt : 232 -> 236
~ __ZN18AppleUSBNCMControl15getNTBInputSizeEPj : 252 -> 256
~ __ZN18AppleUSBNCMControl15setNTBInputSizeEj : 244 -> 248
~ sub_fffffff009a9a298 -> sub_fffffff009b25908 : 132 -> 136
~ __ZN18AppleUSBNCMControl16getDatagramLimitEPt : 252 -> 256
~ __ZN18AppleUSBNCMControl16setDatagramLimitEt : 232 -> 236
~ sub_fffffff009a9a584 -> sub_fffffff009b25c00 : 140 -> 144
~ __ZN18AppleUSBNCMControl10getCRCModeEPt : 252 -> 256
~ __ZN18AppleUSBNCMControl10setCRCModeEt : 232 -> 236
~ __ZN20AppleUSBNCM11Control5probeEP9IOServicePi : 432 -> 436
~ __ZN20AppleUSBNCM11Control24cacheExtendedDescriptorsEv : 596 -> 600
~ __ZN20AppleUSBNCM11Control25getExtendedCapabilityModeEP25NCMExtendedCapabilityMode : 368 -> 372
~ __ZN20AppleUSBNCM11Control25setExtendedCapabilityModeE25NCMExtendedCapabilityMode : 380 -> 384
~ __ZN20AppleUSBNCM11Control23getExtendedCapabilitiesEPvPt : 376 -> 380
~ __ZN20AppleUSBNCM11Control32getExtendedFeatureMediumHandlingEP9NCMMedium : 368 -> 372
~ __ZN20AppleUSBNCM11Control32setExtendedFeatureMediumHandlingE9NCMMedium : 376 -> 380
~ __ZN20AppleUSBNCM11Control22getExtendedFeatureWakeE15NCMWakeTypeCodePvPth : 372 -> 376
~ __ZN20AppleUSBNCM11Control22setExtendedFeatureWakeE15NCMWakeTypeCodePvt : 372 -> 376
~ __ZN20AppleUSBNCM11Control33getExtendedFeaturePresenceOffloadE26NCMPresenceOffloadTypeCodePvPt : 368 -> 372
~ __ZN20AppleUSBNCM11Control33setExtendedFeaturePresenceOffloadE26NCMPresenceOffloadTypeCodePvt : 360 -> 364
~ __ZN20AppleUSBNCM11Control32getExtendedFeatureReceiveOffloadE25NCMReceiveOffloadTypeCodePvPt : 368 -> 372
~ __ZN20AppleUSBNCM11Control32setExtendedFeatureReceiveOffloadE25NCMReceiveOffloadTypeCodePvt : 360 -> 364
~ sub_fffffff009a9db38 -> sub_fffffff009b291f4 : 56 -> 60
```
