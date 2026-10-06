## com.apple.driver.AppleThunderboltIP

> `com.apple.driver.AppleThunderboltIP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x36cf4` | `0x370c8` | **`+0x3d4`** |

### Other Changes

```text
Functions:
~ sub_fffffff009862bf0 -> sub_fffffff0098ea690 : 72 -> 76
~ sub_fffffff009862c40 -> sub_fffffff0098ea6e4 : 52 -> 56
~ sub_fffffff009862c74 -> sub_fffffff0098ea71c : 52 -> 56
~ sub_fffffff009862cb8 -> sub_fffffff0098ea764 : 68 -> 72
~ sub_fffffff009862d24 -> sub_fffffff0098ea7d4 : 72 -> 76
~ sub_fffffff009862d6c -> sub_fffffff0098ea820 : 104 -> 108
~ sub_fffffff009862de8 -> sub_fffffff0098ea8a0 : 88 -> 92
~ sub_fffffff009862e40 -> sub_fffffff0098ea8fc : 88 -> 92
~ __ZN25AppleThunderboltIPService5startEP9IOService : 3152 -> 3156
~ __ZN25AppleThunderboltIPService11createPortsEv : 2400 -> 2404
~ __ZN25AppleThunderboltIPService24protocolListenerCallbackEPvP27IOThunderboltReceiveCommand : 2028 -> 2032
~ __ZN25AppleThunderboltIPService16publishIPServiceEb : 1396 -> 1400
~ __ZN25AppleThunderboltIPService8finalizeEj : 1884 -> 1888
~ __ZN25AppleThunderboltIPService19handleXDomainPacketEP28IOThunderboltDispatchContext : 2064 -> 2068
~ sub_fffffff009866114 -> sub_fffffff0098edbec : 56 -> 60
~ __ZN25AppleThunderboltIPService27getIPPortForThunderboltPortEP17IOThunderboltPort : 3636 -> 3640
~ __ZN25AppleThunderboltIPService15reserveForLoginEbP29AppleThunderboltIPTransmitter : 2144 -> 2148
~ sub_fffffff0098678ac -> sub_fffffff0098ef390 : 80 -> 84
~ sub_fffffff00986790c -> sub_fffffff0098ef3f4 : 56 -> 60
~ sub_fffffff009867944 -> sub_fffffff0098ef430 : 56 -> 60
~ sub_fffffff00986797c -> sub_fffffff0098ef46c : 52 -> 56
~ sub_fffffff0098679b0 -> sub_fffffff0098ef4a4 : 52 -> 56
~ _kprintHexDump : 500 -> 504
~ sub_fffffff009867bd8 -> sub_fffffff0098ef6d4 : 48 -> 52
~ sub_fffffff009867c20 -> sub_fffffff0098ef720 : 72 -> 76
~ sub_fffffff009867c70 -> sub_fffffff0098ef774 : 52 -> 56
~ sub_fffffff009867ca4 -> sub_fffffff0098ef7ac : 52 -> 56
~ sub_fffffff009867ce8 -> sub_fffffff0098ef7f4 : 68 -> 72
~ sub_fffffff009867d54 -> sub_fffffff0098ef864 : 72 -> 76
~ sub_fffffff009867d9c -> sub_fffffff0098ef8b0 : 104 -> 108
~ sub_fffffff009867e18 -> sub_fffffff0098ef930 : 88 -> 92
~ sub_fffffff009867e70 -> sub_fffffff0098ef98c : 88 -> 92
~ __ZN30AppleThunderboltIPMSMInterface21attachToDataLinkLayerEjPv : 288 -> 292
~ __ZN30AppleThunderboltIPMSMInterface29configureIPv6LinkLayerAddressEb : 1412 -> 1416
~ __ZN30AppleThunderboltIPMSMInterface23detachFromDataLinkLayerEjPv : 284 -> 288
~ sub_fffffff009868778 -> sub_fffffff0098f02a4 : 80 -> 84
~ sub_fffffff0098687e0 -> sub_fffffff0098f0310 : 76 -> 80
~ sub_fffffff00986882c -> sub_fffffff0098f0360 : 180 -> 184
~ __ZN25AppleThunderboltIPGlobalsC2Ev : 232 -> 236
~ sub_fffffff0098689c8 -> sub_fffffff0098f0504 : 76 -> 80
~ sub_fffffff009868a14 -> sub_fffffff0098f0554 : 92 -> 96
~ sub_fffffff009868ab4 -> sub_fffffff0098f05f8 : 72 -> 76
~ sub_fffffff009868b04 -> sub_fffffff0098f064c : 52 -> 56
~ sub_fffffff009868b38 -> sub_fffffff0098f0684 : 52 -> 56
~ sub_fffffff009868b7c -> sub_fffffff0098f06cc : 68 -> 72
~ sub_fffffff009868be8 -> sub_fffffff0098f073c : 72 -> 76
~ sub_fffffff009868c30 -> sub_fffffff0098f0788 : 104 -> 108
~ sub_fffffff009868cac -> sub_fffffff0098f0808 : 88 -> 92
~ sub_fffffff009868d04 -> sub_fffffff0098f0864 : 88 -> 92
~ __ZN29AppleThunderboltIPTransmitter5startEP9IOService : 4404 -> 4408
~ __ZN29AppleThunderboltIPTransmitter8setStateEj : 572 -> 576
~ __ZN29AppleThunderboltIPTransmitter29ipServiceNotificationCallbackEPvP9IOService : 1212 -> 1216
~ __ZN29AppleThunderboltIPTransmitter20setupPowerManagementEP9IOService : 468 -> 472
~ __ZN29AppleThunderboltIPTransmitter8finalizeEj : 4920 -> 4924
~ sub_fffffff00986ba94 -> sub_fffffff0098f360c : 56 -> 60
~ __ZN29AppleThunderboltIPTransmitter21prepareForTerminationEv : 2032 -> 2036
~ __ZN29AppleThunderboltIPTransmitter8setTimerEj : 1780 -> 1784
~ __ZN29AppleThunderboltIPTransmitter4freeEv : 352 -> 356
~ __ZN29AppleThunderboltIPTransmitter13setPowerStateEmP9IOService : 3788 -> 3792
~ __ZN29AppleThunderboltIPTransmitter25dispatchLogoutWithRequestEb : 1736 -> 1740
~ __ZN29AppleThunderboltIPTransmitter24dispatchLoginWithRequestEb : 1808 -> 1812
~ __ZN29AppleThunderboltIPTransmitter18systemWillShutdownEj : 1344 -> 1348
~ __ZN29AppleThunderboltIPTransmitter17logoutWithRequestEv : 648 -> 652
~ __ZN29AppleThunderboltIPTransmitter28processIPServiceNotificationEP28IOThunderboltDispatchContext : 3756 -> 3760
~ sub_fffffff00986fe8c -> sub_fffffff0098f7a2c : 88 -> 92
~ __ZN29AppleThunderboltIPTransmitter12createTxPathEv : 3136 -> 3140
~ __ZN29AppleThunderboltIPTransmitter12newTxCommandEb : 572 -> 576
~ __ZN29AppleThunderboltIPTransmitter15returnTxCommandEP33AppleThunderboltIPTransmitCommandb : 468 -> 472
~ __ZN29AppleThunderboltIPTransmitter13destroyTxPathEv : 2640 -> 2644
~ __ZN29AppleThunderboltIPTransmitter15configureTxPathEv : 2944 -> 2948
~ sub_fffffff009872514 -> sub_fffffff0098fa0cc : 140 -> 144
~ sub_fffffff0098725a0 -> sub_fffffff0098fa15c : 244 -> 248
~ __ZN29AppleThunderboltIPTransmitter17txCommandCallbackEPviP28IOThunderboltTransmitCommand : 1272 -> 1276
~ __ZN29AppleThunderboltIPTransmitter20timerCommandCallbackEPviP25IOThunderboltTimerCommand : 2584 -> 2588
~ __ZN29AppleThunderboltIPTransmitter14processTimeoutEP28IOThunderboltDispatchContext : 6936 -> 6940
~ __ZN29AppleThunderboltIPTransmitter16sendLoginRequestEv : 2776 -> 2780
~ __ZN29AppleThunderboltIPTransmitter17sendLogoutRequestEv : 1732 -> 1736
~ __ZN29AppleThunderboltIPTransmitter34dispatchProcessLoginResponsePacketEP24IOBufferMemoryDescriptor : 1568 -> 1572
~ __ZN29AppleThunderboltIPTransmitter26processLoginResponsePacketEP28IOThunderboltDispatchContext : 4640 -> 4644
~ __ZN29AppleThunderboltIPTransmitter35dispatchProcessLogoutResponsePacketEP24IOBufferMemoryDescriptor : 1568 -> 1572
~ __ZN29AppleThunderboltIPTransmitter27processLogoutResponsePacketEP28IOThunderboltDispatchContext : 2292 -> 2296
~ __ZN29AppleThunderboltIPTransmitter16loginWithRequestEv : 1108 -> 1112
~ __ZN29AppleThunderboltIPTransmitter5loginEb : 3388 -> 3392
~ __ZN29AppleThunderboltIPTransmitter6logoutEb : 2776 -> 2780
~ __ZN29AppleThunderboltIPTransmitter12outputPacketEP6__mbufPv : 2820 -> 2824
~ __ZN29AppleThunderboltIPTransmitter13submitHeadersEP40AppleThunderboltIPPacketHeaderAggregatedj : 216 -> 220
~ sub_fffffff00987b260 -> sub_fffffff009902e58 : 276 -> 280
~ sub_fffffff00987b374 -> sub_fffffff009902f70 : 88 -> 92
~ __ZN29AppleThunderboltIPTransmitter13getTxE2EHopIDEPt : 936 -> 940
~ sub_fffffff00987b774 -> sub_fffffff009903378 : 88 -> 92
~ sub_fffffff00987b7e0 -> sub_fffffff0099033e8 : 80 -> 84
~ sub_fffffff00987b840 -> sub_fffffff00990344c : 72 -> 76
~ sub_fffffff00987b890 -> sub_fffffff0099034a0 : 52 -> 56
~ sub_fffffff00987b8c4 -> sub_fffffff0099034d8 : 52 -> 56
~ sub_fffffff00987b908 -> sub_fffffff009903520 : 68 -> 72
~ sub_fffffff00987b974 -> sub_fffffff009903590 : 72 -> 76
~ sub_fffffff00987b9bc -> sub_fffffff0099035dc : 104 -> 108
~ sub_fffffff00987ba38 -> sub_fffffff00990365c : 88 -> 92
~ sub_fffffff00987ba90 -> sub_fffffff0099036b8 : 88 -> 92
~ __ZN33AppleThunderboltIPTransmitCommand14withControllerEP23IOThunderboltControllery : 148 -> 152
~ __ZN33AppleThunderboltIPTransmitCommand18initWithControllerEP23IOThunderboltControllery : 360 -> 364
~ __ZN33AppleThunderboltIPTransmitCommand22withControllerAndQueueEP23IOThunderboltControllerP26IOThunderboltTransmitQueueby : 232 -> 236
~ __ZN33AppleThunderboltIPTransmitCommand38initWithControllerAndQueueAllocateDescEP23IOThunderboltControllerP26IOThunderboltTransmitQueuey : 560 -> 564
~ __ZN33AppleThunderboltIPTransmitCommand26initWithControllerAndQueueEP23IOThunderboltControllerP26IOThunderboltTransmitQueue : 356 -> 360
~ __ZN33AppleThunderboltIPTransmitCommand27addMemoryDescriptorMultipleEPP18IOMemoryDescriptorjy : 488 -> 492
~ sub_fffffff00987c348 -> sub_fffffff009903f8c : 152 -> 156
~ __ZN33AppleThunderboltIPTransmitCommand11BuildPacketEjttjP6__mbufj : 560 -> 564
~ __ZN33AppleThunderboltIPTransmitCommand18BuildHeadersPacketEP40AppleThunderboltIPPacketHeaderAggregatedj : 512 -> 516
~ sub_fffffff00987c810 -> sub_fffffff009904460 : 180 -> 184
~ sub_fffffff00987c8cc -> sub_fffffff009904520 : 80 -> 84
~ sub_fffffff00987c92c -> sub_fffffff009904584 : 72 -> 76
~ sub_fffffff00987c97c -> sub_fffffff0099045d8 : 52 -> 56
~ sub_fffffff00987c9b0 -> sub_fffffff009904610 : 52 -> 56
~ sub_fffffff00987c9f4 -> sub_fffffff009904658 : 68 -> 72
~ sub_fffffff00987ca60 -> sub_fffffff0099046c8 : 72 -> 76
~ sub_fffffff00987caa8 -> sub_fffffff009904714 : 104 -> 108
~ sub_fffffff00987cb24 -> sub_fffffff009904794 : 88 -> 92
~ sub_fffffff00987cb7c -> sub_fffffff0099047f0 : 88 -> 92
~ sub_fffffff00987cbd4 -> sub_fffffff00990484c : 156 -> 160
~ __ZN32AppleThunderboltIPReceiveCommand18initWithControllerEP23IOThunderboltController : 548 -> 552
~ __ZN32AppleThunderboltIPReceiveCommand22withControllerAndQueueEP23IOThunderboltControllerP25IOThunderboltReceiveQueueP18IOMemoryDescriptory : 156 -> 160
~ __ZN32AppleThunderboltIPReceiveCommand26initWithControllerAndQueueEP23IOThunderboltControllerP25IOThunderboltReceiveQueueP18IOMemoryDescriptory : 884 -> 888
~ sub_fffffff00987d2a4 -> sub_fffffff009904f2c : 136 -> 140
~ __ZN32AppleThunderboltIPReceiveCommand17ExtractFromPacketEPjPtS1_S0_PPh : 648 -> 652
~ __ZN32AppleThunderboltIPReceiveCommand27ExtractFromPacketAggregatedEPPhbP40AppleThunderboltIPPacketHeaderAggregatedPj : 828 -> 832
~ sub_fffffff00987d8f8 -> sub_fffffff00990558c : 80 -> 84
~ sub_fffffff00987d958 -> sub_fffffff0099055f0 : 72 -> 76
~ sub_fffffff00987d9a8 -> sub_fffffff009905644 : 52 -> 56
~ sub_fffffff00987d9dc -> sub_fffffff00990567c : 52 -> 56
~ sub_fffffff00987da20 -> sub_fffffff0099056c4 : 68 -> 72
~ sub_fffffff00987da8c -> sub_fffffff009905734 : 72 -> 76
~ sub_fffffff00987dad4 -> sub_fffffff009905780 : 104 -> 108
~ sub_fffffff00987db50 -> sub_fffffff009905800 : 88 -> 92
~ sub_fffffff00987dba8 -> sub_fffffff00990585c : 88 -> 92
~ __ZN32AppleThunderboltIPControlCommand10withParamsEP23IOThunderboltController8EFI_GUIDS2_P24IOThunderboltXDomainLink : 196 -> 200
~ __ZN32AppleThunderboltIPControlCommand14initWithParamsEP23IOThunderboltController8EFI_GUIDS2_P24IOThunderboltXDomainLink : 760 -> 764
~ sub_fffffff00987dfc8 -> sub_fffffff009905c88 : 160 -> 164
~ __ZN32AppleThunderboltIPControlCommand16BuildLoginPacketEjjb : 488 -> 492
~ __ZN32AppleThunderboltIPControlCommand29BuildThunderboltIPLoginPacketEP24IOBufferMemoryDescriptor8EFI_GUIDS2_jjb : 428 -> 432
~ __ZN32AppleThunderboltIPControlCommand24BuildLoginResponsePacketEjjPhj : 464 -> 468
~ __ZN32AppleThunderboltIPControlCommand37BuildThunderboltIPLoginResponsePacketEP24IOBufferMemoryDescriptor8EFI_GUIDS2_jjPhj : 456 -> 460
~ __ZN32AppleThunderboltIPControlCommand17BuildLogoutPacketEj : 464 -> 468
~ __ZN32AppleThunderboltIPControlCommand25BuildLogoutResponsePacketEjj : 468 -> 472
~ __ZN32AppleThunderboltIPControlCommand38BuildThunderboltIPLogoutResponsePacketEP24IOBufferMemoryDescriptor8EFI_GUIDS2_jj : 396 -> 400
~ __ZN32AppleThunderboltIPControlCommand9LogPacketEv : 272 -> 276
~ sub_fffffff00987ef24 -> sub_fffffff009906c08 : 80 -> 84
~ sub_fffffff00987ef74 -> sub_fffffff009906c5c : 80 -> 84
~ __ZN32AppleThunderboltIPControlCommand32BuildThunderboltIPProtocolHeaderEP24IOBufferMemoryDescriptorj8EFI_GUIDS2_j : 636 -> 640
~ __ZN32AppleThunderboltIPControlCommand38ExtractFromThunderboltIPProtocolHeaderEP24IOBufferMemoryDescriptorPjP8EFI_GUIDS4_S2_ : 812 -> 816
~ __ZN32AppleThunderboltIPControlCommand35ExtractFromThunderboltIPLoginPacketEP24IOBufferMemoryDescriptorP8EFI_GUIDS3_PjS4_Pb : 672 -> 676
~ __ZN32AppleThunderboltIPControlCommand43ExtractFromThunderboltIPLoginResponsePacketEP24IOBufferMemoryDescriptorP8EFI_GUIDS3_PjS4_PhS4_ : 696 -> 700
~ __ZN32AppleThunderboltIPControlCommand36ExtractFromThunderboltIPLogoutPacketEP24IOBufferMemoryDescriptorP8EFI_GUIDS3_Pj : 556 -> 560
~ __ZN32AppleThunderboltIPControlCommand44ExtractFromThunderboltIPLogoutResponsePacketEP24IOBufferMemoryDescriptorP8EFI_GUIDS3_PjS4_ : 624 -> 628
~ sub_fffffff00987ff68 -> sub_fffffff009907c6c : 80 -> 84
~ sub_fffffff00987ffc8 -> sub_fffffff009907cd0 : 72 -> 76
~ sub_fffffff009880018 -> sub_fffffff009907d24 : 52 -> 56
~ sub_fffffff00988004c -> sub_fffffff009907d5c : 52 -> 56
~ sub_fffffff009880090 -> sub_fffffff009907da4 : 68 -> 72
~ sub_fffffff0098800fc -> sub_fffffff009907e14 : 72 -> 76
~ sub_fffffff009880144 -> sub_fffffff009907e60 : 104 -> 108
~ sub_fffffff0098801c0 -> sub_fffffff009907ee0 : 88 -> 92
~ sub_fffffff009880218 -> sub_fffffff009907f3c : 88 -> 92
~ __ZN22AppleThunderboltIPPort18withPortAndServiceEP17IOThunderboltPortP25AppleThunderboltIPService : 680 -> 684
~ __ZN22AppleThunderboltIPPort18initPortAndServiceEP17IOThunderboltPortP25AppleThunderboltIPService : 1208 -> 1212
~ __ZN22AppleThunderboltIPPort5startEP9IOService : 1312 -> 1316
~ __ZN22AppleThunderboltIPPort16createMACAddressEv : 2072 -> 2076
~ __ZN22AppleThunderboltIPPort17createMediumStateEv : 940 -> 944
~ __ZN22AppleThunderboltIPPort16updateLinkStatusEv : 1112 -> 1116
~ __ZN22AppleThunderboltIPPort8finalizeEj : 1608 -> 1612
~ sub_fffffff009882554 -> sub_fffffff00990a298 : 56 -> 60
~ __ZN22AppleThunderboltIPPort4freeEv : 352 -> 356
~ sub_fffffff009882710 -> sub_fffffff00990a45c : 76 -> 80
~ __ZN22AppleThunderboltIPPort6enableEP18IONetworkInterface : 1752 -> 1756
~ __ZN22AppleThunderboltIPPort7disableEP18IONetworkInterface : 1076 -> 1080
~ __ZN22AppleThunderboltIPPort17outputStartLegacyEP18IONetworkInterfacej : 3828 -> 3832
~ __ZN22AppleThunderboltIPPort28outputStartAggregatedPacketsEP18IONetworkInterfacej : 2472 -> 2476
~ __ZN22AppleThunderboltIPPort8tickleTxEv : 328 -> 332
~ __ZN22AppleThunderboltIPPort15createInterfaceEv : 340 -> 344
~ sub_fffffff009884ed8 -> sub_fffffff00990cc40 : 184 -> 188
~ __ZN22AppleThunderboltIPPort15addIPConnectionEP28AppleThunderboltIPConnection : 1264 -> 1268
~ __ZN22AppleThunderboltIPPort18removeIPConnectionEP28AppleThunderboltIPConnection : 1796 -> 1800
~ __ZN22AppleThunderboltIPPort27createIPConnectionForXDLinkEP24IOThunderboltXDomainLinkP29AppleThunderboltIPTransmitter : 3416 -> 3420
~ __ZN22AppleThunderboltIPPort28getIPConnectionForRemoteUUIDE8EFI_GUID : 472 -> 476
~ __ZN22AppleThunderboltIPPort13receivePacketEP6__mbufm : 420 -> 424
~ sub_fffffff009886c7c -> sub_fffffff00990e9fc : 120 -> 124
~ sub_fffffff009886cf4 -> sub_fffffff00990ea78 : 120 -> 124
~ sub_fffffff009886d6c -> sub_fffffff00990eaf4 : 56 -> 60
~ sub_fffffff009886db8 -> sub_fffffff00990eb44 : 80 -> 84
~ sub_fffffff009886e18 -> sub_fffffff00990eba8 : 72 -> 76
~ sub_fffffff009886e68 -> sub_fffffff00990ebfc : 52 -> 56
~ sub_fffffff009886e9c -> sub_fffffff00990ec34 : 52 -> 56
~ sub_fffffff009886ee0 -> sub_fffffff00990ec7c : 68 -> 72
~ sub_fffffff009886f4c -> sub_fffffff00990ecec : 72 -> 76
~ sub_fffffff009886f94 -> sub_fffffff00990ed38 : 104 -> 108
~ sub_fffffff009887010 -> sub_fffffff00990edb8 : 88 -> 92
~ sub_fffffff009887068 -> sub_fffffff00990ee14 : 88 -> 92
~ __ZN28AppleThunderboltIPConnection10withParamsE8EFI_GUIDP25AppleThunderboltIPServiceP24IOThunderboltXDomainLinkP22AppleThunderboltIPPort : 180 -> 184
~ __ZN28AppleThunderboltIPConnection14initWithParamsE8EFI_GUIDP25AppleThunderboltIPServiceP24IOThunderboltXDomainLinkP22AppleThunderboltIPPort : 1800 -> 1804
~ __ZN28AppleThunderboltIPConnection5startEP9IOService : 1832 -> 1836
~ __ZN28AppleThunderboltIPConnection8setStateEj : 848 -> 852
~ __ZN28AppleThunderboltIPConnection21createControlCommandsEv : 860 -> 864
~ __ZN28AppleThunderboltIPConnection20setupPowerManagementEP9IOService : 468 -> 472
~ __ZN28AppleThunderboltIPConnection8finalizeEj : 4844 -> 4848
~ sub_fffffff009889e1c -> sub_fffffff009911be8 : 56 -> 60
~ __ZN28AppleThunderboltIPConnection21prepareForTerminationEv : 1628 -> 1632
~ __ZN28AppleThunderboltIPConnection4freeEv : 392 -> 396
~ __ZN28AppleThunderboltIPConnection13setPowerStateEmP9IOService : 3756 -> 3760
~ __ZN28AppleThunderboltIPConnection14dispatchLogoutEb : 1964 -> 1968
~ sub_fffffff00988bcf4 -> sub_fffffff009913ad4 : 84 -> 88
~ __ZN28AppleThunderboltIPConnection15returnRxCommandEP32AppleThunderboltIPReceiveCommand : 644 -> 648
~ __ZN28AppleThunderboltIPConnection18systemWillShutdownEj : 1256 -> 1260
~ __ZN28AppleThunderboltIPConnection6logoutEv : 3456 -> 3460
~ __ZN28AppleThunderboltIPConnection26xdLinkNotificationCallbackEPvP9IOService : 1260 -> 1264
~ __ZN28AppleThunderboltIPConnection25processXDLinkNotificationEP28IOThunderboltDispatchContext : 3200 -> 3204
~ __ZN28AppleThunderboltIPConnection13dispatchLoginEb : 1964 -> 1968
~ __ZN28AppleThunderboltIPConnection12createRxPathEv : 5040 -> 5044
~ __ZN28AppleThunderboltIPConnection12newRxCommandEP18IOMemoryDescriptory : 264 -> 268
~ __ZN28AppleThunderboltIPConnection13destroyRxPathEv : 3680 -> 3684
~ __ZN28AppleThunderboltIPConnection15configureRxPathEv : 2448 -> 2452
~ __ZN28AppleThunderboltIPConnection27rxCommandCallbackAggregatedEPviP27IOThunderboltReceiveCommand : 900 -> 904
~ __ZN28AppleThunderboltIPConnection17rxCommandCallbackEPviP27IOThunderboltReceiveCommand : 4236 -> 4240
~ __ZN28AppleThunderboltIPConnection17newControlCommandEv : 180 -> 184
~ __ZN28AppleThunderboltIPConnection20returnControlCommandEP32AppleThunderboltIPControlCommand : 644 -> 648
~ sub_fffffff009892f3c -> sub_fffffff00991ad58 : 84 -> 88
~ __ZN28AppleThunderboltIPConnection22controlCommandCallbackEPviP26IOThunderboltConfigCommand : 988 -> 992
~ __ZN28AppleThunderboltIPConnection17sendRequestPacketEjjb : 3076 -> 3080
~ __ZN28AppleThunderboltIPConnection18sendResponsePacketEjj : 3284 -> 3288
~ __ZN28AppleThunderboltIPConnection20processXDomainPacketEP24IOBufferMemoryDescriptor : 2176 -> 2180
~ __ZN28AppleThunderboltIPConnection18processLoginPacketEP24IOBufferMemoryDescriptor : 3916 -> 3920
~ __ZN28AppleThunderboltIPConnection19processLogoutPacketEP24IOBufferMemoryDescriptor : 2076 -> 2080
~ __ZN28AppleThunderboltIPConnection5loginEv : 6176 -> 6180
~ sub_fffffff00989844c -> sub_fffffff009920288 : 116 -> 120
~ __ZN28AppleThunderboltIPConnection18connectionIsActiveEv : 392 -> 396
~ __ZN28AppleThunderboltIPConnection14getTransmitterEv : 308 -> 312
~ __ZN28AppleThunderboltIPConnection14setTransmitterEP29AppleThunderboltIPTransmitter : 692 -> 696
~ __ZN28AppleThunderboltIPConnection19setRemoteMACAddressEPhj : 1456 -> 1460
~ __ZN28AppleThunderboltIPConnection17compareMacAddressEPhj : 668 -> 672
~ __ZN28AppleThunderboltIPConnection17compareRemoteUUIDE8EFI_GUID : 680 -> 684
~ sub_fffffff009899550 -> sub_fffffff0099213a8 : 88 -> 92
~ sub_fffffff0098995c0 -> sub_fffffff00992141c : 80 -> 84
~ __ZN33AppleThunderboltIPTransmitCommand18BuildHeadersPacketEP40AppleThunderboltIPPacketHeaderAggregatedj.cold.1 : 44 -> 48
~ sub_fffffff0098996dc -> sub_fffffff009921540 : 148 -> 152
~ sub_fffffff009899770 -> sub_fffffff0099215d8 : 108 -> 112
~ sub_fffffff0098997dc -> sub_fffffff009921648 : 96 -> 100
~ sub_fffffff00989983c -> sub_fffffff0099216ac : 168 -> 172
```
