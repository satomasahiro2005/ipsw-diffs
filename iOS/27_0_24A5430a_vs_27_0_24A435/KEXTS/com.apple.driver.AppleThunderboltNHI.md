## com.apple.driver.AppleThunderboltNHI

> `com.apple.driver.AppleThunderboltNHI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x3b1d4` | `0x3ba3c` | **`+0x868`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ sub_fffffff009899f20 -> sub_fffffff009921d90 : 72 -> 76
~ sub_fffffff009899f70 -> sub_fffffff009921de4 : 52 -> 56
~ sub_fffffff009899fa4 -> sub_fffffff009921e1c : 52 -> 56
~ sub_fffffff009899fe8 -> sub_fffffff009921e64 : 68 -> 72
~ sub_fffffff00989a054 -> sub_fffffff009921ed4 : 72 -> 76
~ sub_fffffff00989a09c -> sub_fffffff009921f20 : 104 -> 108
~ sub_fffffff00989a118 -> sub_fffffff009921fa0 : 88 -> 92
~ sub_fffffff00989a170 -> sub_fffffff009921ffc : 88 -> 92
~ sub_fffffff00989a1c8 -> sub_fffffff009922058 : 180 -> 184
~ sub_fffffff00989a284 -> sub_fffffff009922118 : 80 -> 84
~ sub_fffffff00989a2e4 -> sub_fffffff00992217c : 72 -> 76
~ sub_fffffff00989a334 -> sub_fffffff0099221d0 : 52 -> 56
~ sub_fffffff00989a368 -> sub_fffffff009922208 : 52 -> 56
~ sub_fffffff00989a3ac -> sub_fffffff009922250 : 68 -> 72
~ sub_fffffff00989a418 -> sub_fffffff0099222c0 : 72 -> 76
~ sub_fffffff00989a460 -> sub_fffffff00992230c : 104 -> 108
~ sub_fffffff00989a4dc -> sub_fffffff00992238c : 88 -> 92
~ sub_fffffff00989a534 -> sub_fffffff0099223e8 : 88 -> 92
~ sub_fffffff00989a58c -> sub_fffffff009922444 : 180 -> 184
~ sub_fffffff00989a648 -> sub_fffffff009922504 : 80 -> 84
~ sub_fffffff00989a6a8 -> sub_fffffff009922568 : 72 -> 76
~ sub_fffffff00989a6f8 -> sub_fffffff0099225bc : 52 -> 56
~ sub_fffffff00989a72c -> sub_fffffff0099225f4 : 52 -> 56
~ sub_fffffff00989a770 -> sub_fffffff00992263c : 68 -> 72
~ sub_fffffff00989a7dc -> sub_fffffff0099226ac : 72 -> 76
~ sub_fffffff00989a824 -> sub_fffffff0099226f8 : 104 -> 108
~ sub_fffffff00989a8a0 -> sub_fffffff009922778 : 88 -> 92
~ sub_fffffff00989a8f8 -> sub_fffffff0099227d4 : 88 -> 92
~ sub_fffffff00989a950 -> sub_fffffff009922830 : 180 -> 184
~ sub_fffffff00989aa0c -> sub_fffffff0099228f0 : 80 -> 84
~ sub_fffffff00989aa6c -> sub_fffffff009922954 : 72 -> 76
~ sub_fffffff00989aabc -> sub_fffffff0099229a8 : 52 -> 56
~ sub_fffffff00989aaf0 -> sub_fffffff0099229e0 : 52 -> 56
~ sub_fffffff00989ab34 -> sub_fffffff009922a28 : 68 -> 72
~ sub_fffffff00989aba0 -> sub_fffffff009922a98 : 72 -> 76
~ sub_fffffff00989abe8 -> sub_fffffff009922ae4 : 104 -> 108
~ sub_fffffff00989ac64 -> sub_fffffff009922b64 : 88 -> 92
~ sub_fffffff00989acbc -> sub_fffffff009922bc0 : 88 -> 92
~ __ZN30AppleThunderboltNHIGenericACIO5startEP9IOService : 1008 -> 1012
~ __ZN30AppleThunderboltNHIGenericACIO14unpoweredStartEv : 2224 -> 2228
~ __ZN30AppleThunderboltNHIGenericACIO12poweredStartEv : 920 -> 924
~ sub_fffffff00989bd68 -> sub_fffffff009923c7c : 168 -> 172
~ __ZN30AppleThunderboltNHIGenericACIO8finalizeEj : 496 -> 500
~ __ZN30AppleThunderboltNHIGenericACIO4freeEv : 284 -> 288
~ __ZN30AppleThunderboltNHIGenericACIO14resolvePHandleEP9IOServicePKcS3_ : 2168 -> 2172
~ __ZN30AppleThunderboltNHIGenericACIO8setupPHYEv : 996 -> 1000
~ __ZN30AppleThunderboltNHIGenericACIO10destroyPHYEv : 392 -> 396
~ __ZN30AppleThunderboltNHIGenericACIO20createPhyOwnerStringEv : 1044 -> 1048
~ __ZN30AppleThunderboltNHIGenericACIO11setPhyStateENS_7HWStateE : 5120 -> 5124
~ sub_fffffff00989e7e0 -> sub_fffffff009926714 : 92 -> 96
~ __ZN30AppleThunderboltNHIGenericACIO16setupEmbeddedCPUEv : 1216 -> 1220
~ __ZN30AppleThunderboltNHIGenericACIO18destroyEmbeddedCPUEv : 308 -> 312
~ __ZN30AppleThunderboltNHIGenericACIO17enableEmbeddedCPUEb : 8188 -> 8192
~ __ZN30AppleThunderboltNHIGenericACIO13applyTunablesEPKNS_16TunableReferenceEi : 2164 -> 2168
~ sub_fffffff0098a16e8 -> sub_fffffff009929630 : 76 -> 80
~ __ZN30AppleThunderboltNHIGenericACIO20setupPowerManagementEv : 296 -> 300
~ __ZN30AppleThunderboltNHIGenericACIO10setHWStateENS_7HWStateE : 1148 -> 1152
~ __ZN30AppleThunderboltNHIGenericACIO15forcePowerStateEb : 324 -> 328
~ __ZN30AppleThunderboltNHIGenericACIO28createPowerDomainClientArrayEv : 4004 -> 4008
~ __ZN30AppleThunderboltNHIGenericACIO29destroyPowerDomainClientArrayEv : 304 -> 308
~ __ZN30AppleThunderboltNHIGenericACIO36ensurePowerDomainClientArrayCapacityEj : 732 -> 736
~ __ZN30AppleThunderboltNHIGenericACIO23removePowerDomainClientEP9IOServicej : 444 -> 448
~ __ZN30AppleThunderboltNHIGenericACIO20addPowerDomainClientEP9IOServicej : 516 -> 520
~ __ZN30AppleThunderboltNHIGenericACIO22disableAllPowerDomainsEb : 336 -> 340
~ __ZN30AppleThunderboltNHIGenericACIO20evaluatePowerDomainsEv : 852 -> 856
~ __ZN30AppleThunderboltNHIGenericACIO26powerDomainShouldBeEnabledEj : 664 -> 668
~ __ZN30AppleThunderboltNHIGenericACIO24setARMIODevicePowerStateEN16AppleARMIODevice16DevicePowerStateEj : 2844 -> 2848
~ __ZN30AppleThunderboltNHIGenericACIO17enablePowerDomainEjb : 1232 -> 1236
~ sub_fffffff0098a4cec -> sub_fffffff00992cc6c : 228 -> 232
~ __ZN30AppleThunderboltNHIGenericACIO17earlyWakeInternalEv : 288 -> 292
~ __ZN30AppleThunderboltNHIGenericACIO11processWakeEv : 1072 -> 1076
~ __ZN30AppleThunderboltNHIGenericACIO4wakeEv : 2008 -> 2012
~ __ZN30AppleThunderboltNHIGenericACIO10earlySleepEv : 288 -> 292
~ __ZN30AppleThunderboltNHIGenericACIO4dozeEv : 836 -> 840
~ __ZN30AppleThunderboltNHIGenericACIO8shutdownEv : 864 -> 868
~ __ZN30AppleThunderboltNHIGenericACIO5sleepEv : 828 -> 832
~ __ZN30AppleThunderboltNHIGenericACIO20lateShutdownInternalEv : 472 -> 476
~ sub_fffffff0098a6c38 -> sub_fffffff00992ebdc : 652 -> 656
~ __ZN30AppleThunderboltNHIGenericACIO17hostDeviceConnectEi : 1216 -> 1220
~ __ZN30AppleThunderboltNHIGenericACIO24setDevicesConnectedStateEbb : 540 -> 544
~ sub_fffffff0098a75d0 -> sub_fffffff00992f580 : 108 -> 112
~ __ZN30AppleThunderboltNHIGenericACIO23setupCableStateTrackingEv : 880 -> 884
~ __ZN30AppleThunderboltNHIGenericACIO25destroyCableStateTrackingEv : 440 -> 444
~ __ZN30AppleThunderboltNHIGenericACIO24checkForCableStateChangeEv : 3384 -> 3388
~ __ZN30AppleThunderboltNHIGenericACIO20powerStateChangeDoneEv : 1048 -> 1052
~ __ZN30AppleThunderboltNHIGenericACIO12loadFirmwareEv : 964 -> 968
~ __ZN30AppleThunderboltNHIGenericACIO12writeToRangeEyPvy : 528 -> 532
~ __ZN30AppleThunderboltNHIGenericACIO15publishTunablesEv : 1632 -> 1636
~ __ZN30AppleThunderboltNHIGenericACIO17requestExitPDModeEj : 348 -> 352
~ __ZN30AppleThunderboltNHIGenericACIO10exitPDModeEj : 332 -> 336
~ sub_fffffff0098a9cf0 -> sub_fffffff009931cc8 : 80 -> 84
~ sub_fffffff0098a9d50 -> sub_fffffff009931d2c : 72 -> 76
~ sub_fffffff0098a9da0 -> sub_fffffff009931d80 : 52 -> 56
~ sub_fffffff0098a9dd4 -> sub_fffffff009931db8 : 52 -> 56
~ sub_fffffff0098a9e18 -> sub_fffffff009931e00 : 68 -> 72
~ sub_fffffff0098a9e84 -> sub_fffffff009931e70 : 72 -> 76
~ sub_fffffff0098a9ecc -> sub_fffffff009931ebc : 104 -> 108
~ sub_fffffff0098a9f48 -> sub_fffffff009931f3c : 88 -> 92
~ sub_fffffff0098a9fa0 -> sub_fffffff009931f98 : 88 -> 92
~ __ZN26AppleThunderboltGenericHAL5probeEP9IOServicePi : 728 -> 732
~ __ZN26AppleThunderboltGenericHAL5startEP9IOService : 1292 -> 1296
~ __ZN26AppleThunderboltGenericHAL14unpoweredStartEv : 724 -> 728
~ __ZN26AppleThunderboltGenericHAL12poweredStartEv : 608 -> 612
~ __ZN26AppleThunderboltGenericHAL10fatalErrorEPKci : 340 -> 344
~ __ZN26AppleThunderboltGenericHAL4stopEP9IOService : 412 -> 416
~ __ZN26AppleThunderboltGenericHAL8finalizeEj : 436 -> 440
~ __ZN26AppleThunderboltGenericHAL4freeEv : 680 -> 684
~ __ZN26AppleThunderboltGenericHAL6enableEv : 340 -> 344
~ sub_fffffff0098ab5c0 -> sub_fffffff0099335e0 : 152 -> 156
~ sub_fffffff0098ab658 -> sub_fffffff00993367c : 196 -> 200
~ sub_fffffff0098ab71c -> sub_fffffff009933744 : 120 -> 124
~ sub_fffffff0098ab7b4 -> sub_fffffff0099337e0 : 204 -> 208
~ sub_fffffff0098ab898 -> sub_fffffff0099338c8 : 56 -> 60
~ sub_fffffff0098ab8d0 -> sub_fffffff009933904 : 48 -> 52
~ __ZN26AppleThunderboltGenericHAL15acquireHardwareEP9IOService : 1980 -> 1984
~ __ZN26AppleThunderboltGenericHAL15releaseHardwareEP9IOService : 1416 -> 1420
~ sub_fffffff0098ac7a0 -> sub_fffffff0099347e0 : 144 -> 148
~ __ZN26AppleThunderboltGenericHAL20setupPowerManagementEv : 720 -> 724
~ __ZN26AppleThunderboltGenericHAL21enablePowerManagementEv : 316 -> 320
~ __ZN26AppleThunderboltGenericHAL22destroyPowerManagementEv : 392 -> 396
~ sub_fffffff0098acde0 -> sub_fffffff009934e30 : 72 -> 76
~ __ZN26AppleThunderboltGenericHAL15enableDeepSleepEb : 700 -> 704
~ __ZN26AppleThunderboltGenericHAL15forcePowerStateEm : 1664 -> 1668
~ __ZN26AppleThunderboltGenericHAL13setPowerStateEmP9IOService : 896 -> 900
~ __ZN26AppleThunderboltGenericHAL22powerStateWillChangeToEmmP9IOService : 360 -> 364
~ __ZN26AppleThunderboltGenericHAL10earlySleepEv : 512 -> 516
~ __ZN26AppleThunderboltGenericHAL20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 660 -> 664
~ __ZN26AppleThunderboltGenericHAL9lateSleepEv : 1116 -> 1120
~ __ZN26AppleThunderboltGenericHAL10prePCIWakeEv : 744 -> 748
~ __ZN26AppleThunderboltGenericHAL9earlyWakeEv : 1192 -> 1196
~ __ZN26AppleThunderboltGenericHAL18systemWillShutdownEj : 764 -> 768
~ sub_fffffff0098af064 -> sub_fffffff0099370e0 : 80 -> 84
~ sub_fffffff0098af0c4 -> sub_fffffff009937144 : 72 -> 76
~ sub_fffffff0098af114 -> sub_fffffff009937198 : 52 -> 56
~ sub_fffffff0098af148 -> sub_fffffff0099371d0 : 52 -> 56
~ sub_fffffff0098af18c -> sub_fffffff009937218 : 68 -> 72
~ sub_fffffff0098af1f8 -> sub_fffffff009937288 : 72 -> 76
~ sub_fffffff0098af240 -> sub_fffffff0099372d4 : 104 -> 108
~ sub_fffffff0098af2bc -> sub_fffffff009937354 : 88 -> 92
~ sub_fffffff0098af314 -> sub_fffffff0099373b0 : 88 -> 92
~ __ZN19AppleThunderboltNHI5startEP9IOService : 1916 -> 1920
~ sub_fffffff0098afba0 -> sub_fffffff009937c44 : 484 -> 488
~ __ZN19AppleThunderboltNHI12poweredStartEv : 976 -> 980
~ sub_fffffff0098b0154 -> sub_fffffff009938200 : 168 -> 172
~ __ZN19AppleThunderboltNHI7messageEjP9IOServicePv : 2396 -> 2400
~ __ZN19AppleThunderboltNHI20controllerIsQuiescedEv : 468 -> 472
~ __ZN19AppleThunderboltNHI8finalizeEj : 808 -> 812
~ __ZN19AppleThunderboltNHI4freeEv : 656 -> 660
~ __ZN19AppleThunderboltNHI8resetNHIEv : 364 -> 368
~ sub_fffffff0098b1548 -> sub_fffffff00993960c : 76 -> 80
~ sub_fffffff0098b1594 -> sub_fffffff00993965c : 112 -> 116
~ __ZN19AppleThunderboltNHI20allocateTransmitRingEPP28IOThunderboltNHITransmitRingP26IOThunderboltTransmitQueue : 396 -> 400
~ __ZN19AppleThunderboltNHI22deallocateTransmitRingEP28IOThunderboltNHITransmitRing : 380 -> 384
~ __ZN19AppleThunderboltNHI19allocateReceiveRingEPP27IOThunderboltNHIReceiveRingP25IOThunderboltReceiveQueue : 396 -> 400
~ __ZN19AppleThunderboltNHI21deallocateReceiveRingEP27IOThunderboltNHIReceiveRing : 380 -> 384
~ sub_fffffff0098b1c90 -> sub_fffffff009939d6c : 64 -> 68
~ __ZN19AppleThunderboltNHI20setupPowerManagementEv : 316 -> 320
~ __ZN19AppleThunderboltNHI24setDevicesConnectedStateEbb : 356 -> 360
~ __ZN19AppleThunderboltNHI10setPMStateEm : 1328 -> 1332
~ __ZN19AppleThunderboltNHI17processSetPMStateEP28IOThunderboltDispatchContext : 4012 -> 4016
~ __ZN19AppleThunderboltNHI4dozeEv : 372 -> 376
~ __ZN19AppleThunderboltNHI5pauseEv : 316 -> 320
~ __ZN19AppleThunderboltNHI7unpauseEv : 312 -> 316
~ __ZN19AppleThunderboltNHI5sleepEv : 432 -> 436
~ __ZN19AppleThunderboltNHI9lateSleepEv : 364 -> 368
~ __ZN19AppleThunderboltNHI17lateSleepInternalEv : 648 -> 652
~ __ZN19AppleThunderboltNHI10prePCIWakeEv : 312 -> 316
~ __ZN19AppleThunderboltNHI9earlyWakeEv : 364 -> 368
~ __ZN19AppleThunderboltNHI17earlyWakeInternalEv : 560 -> 564
~ __ZN19AppleThunderboltNHI11processWakeEv : 484 -> 488
~ __ZN19AppleThunderboltNHI4wakeEv : 540 -> 544
~ __ZN19AppleThunderboltNHI8shutdownEv : 828 -> 832
~ sub_fffffff0098b4b08 -> sub_fffffff00993cc28 : 80 -> 84
~ sub_fffffff0098b4b68 -> sub_fffffff00993cc8c : 72 -> 76
~ sub_fffffff0098b4bb8 -> sub_fffffff00993cce0 : 52 -> 56
~ sub_fffffff0098b4bec -> sub_fffffff00993cd18 : 52 -> 56
~ sub_fffffff0098b4c30 -> sub_fffffff00993cd60 : 68 -> 72
~ sub_fffffff0098b4c9c -> sub_fffffff00993cdd0 : 72 -> 76
~ sub_fffffff0098b4ce4 -> sub_fffffff00993ce1c : 104 -> 108
~ sub_fffffff0098b4d60 -> sub_fffffff00993ce9c : 88 -> 92
~ sub_fffffff0098b4db8 -> sub_fffffff00993cef8 : 88 -> 92
~ __ZN30AppleThunderboltHALGenericACIO5startEP9IOService : 564 -> 568
~ __ZN30AppleThunderboltHALGenericACIO14unpoweredStartEv : 3056 -> 3060
~ __ZNK30AppleThunderboltHALGenericACIO24determineSIDPartitioningEPK9IOService : 364 -> 368
~ __ZN30AppleThunderboltHALGenericACIO18setupDARTAllocatorEP8IOMapper : 564 -> 568
~ __ZN30AppleThunderboltHALGenericACIO17initializeMappersEv : 2352 -> 2356
~ __ZN30AppleThunderboltHALGenericACIO12poweredStartEv : 1460 -> 1464
~ __ZN30AppleThunderboltHALGenericACIO19setupRegisterRangesEv : 484 -> 488
~ __ZN30AppleThunderboltHALGenericACIO21destroyRegisterRangesEv : 560 -> 564
~ __ZN30AppleThunderboltHALGenericACIO26createDeviceMemoryForRangeEjmm : 668 -> 672
~ __ZN30AppleThunderboltHALGenericACIO8finalizeEj : 716 -> 720
~ __ZN30AppleThunderboltHALGenericACIO4freeEv : 544 -> 548
~ sub_fffffff0098b7b24 -> sub_fffffff00993fc94 : 152 -> 156
~ sub_fffffff0098b7c54 -> sub_fffffff00993fdc8 : 292 -> 296
~ sub_fffffff0098b7d78 -> sub_fffffff00993fef0 : 168 -> 172
~ sub_fffffff0098b7e20 -> sub_fffffff00993ff9c : 168 -> 172
~ __ZN30AppleThunderboltHALGenericACIO10enableDARTEb : 1308 -> 1312
~ __ZN30AppleThunderboltHALGenericACIO20setupPowerManagementEv : 344 -> 348
~ __ZN30AppleThunderboltHALGenericACIO21enablePowerManagementEv : 348 -> 352
~ sub_fffffff0098b86c0 -> sub_fffffff00994084c : 72 -> 76
~ __ZN30AppleThunderboltHALGenericACIO22destroyPowerManagementEv : 288 -> 292
~ __ZN30AppleThunderboltHALGenericACIO22portChangeNotificationEPvjP9IOServiceS0_m : 996 -> 1000
~ __ZN30AppleThunderboltHALGenericACIO15portChangeEventEP28IOThunderboltDispatchContext : 1052 -> 1056
~ __ZN30AppleThunderboltHALGenericACIO20getDesiredCableStateEP23IOThunderboltCableState : 1116 -> 1120
~ __ZN30AppleThunderboltHALGenericACIO13getCableStateEP23IOThunderboltCableState : 4536 -> 4540
~ __ZN30AppleThunderboltHALGenericACIO19waitForAppleHPMWakeEv : 548 -> 552
~ sub_fffffff0098bab88 -> sub_fffffff009942d30 : 132 -> 136
~ sub_fffffff0098bac60 -> sub_fffffff009942e0c : 1080 -> 1084
~ __ZN30AppleThunderboltHALGenericACIO15handleInterruptEP22IOInterruptEventSourcei : 396 -> 400
~ __ZN30AppleThunderboltHALGenericACIO24handleDedicatedInterruptEP22IOInterruptEventSourcei : 372 -> 376
~ __ZN30AppleThunderboltHALGenericACIO14registerRead32Ej : 564 -> 568
~ __ZN30AppleThunderboltHALGenericACIO14registerRead16Ej : 316 -> 320
~ __ZN30AppleThunderboltHALGenericACIO22registerRead32ForRangeEjj : 688 -> 692
~ sub_fffffff0098bc0a4 -> sub_fffffff009944268 : 80 -> 84
~ __ZN30AppleThunderboltHALGenericACIO26getForceUpdateModePropertyEv : 176 -> 180
~ sub_fffffff0098bc1e4 -> sub_fffffff0099443b0 : 80 -> 84
~ sub_fffffff0098bc28c -> sub_fffffff00994445c : 72 -> 76
~ sub_fffffff0098bc2dc -> sub_fffffff0099444b0 : 52 -> 56
~ sub_fffffff0098bc310 -> sub_fffffff0099444e8 : 52 -> 56
~ sub_fffffff0098bc354 -> sub_fffffff009944530 : 68 -> 72
~ sub_fffffff0098bc3c0 -> sub_fffffff0099445a0 : 72 -> 76
~ sub_fffffff0098bc408 -> sub_fffffff0099445ec : 104 -> 108
~ sub_fffffff0098bc484 -> sub_fffffff00994466c : 88 -> 92
~ sub_fffffff0098bc4dc -> sub_fffffff0099446c8 : 88 -> 92
~ sub_fffffff0098bc534 -> sub_fffffff009944724 : 180 -> 184
~ __ZN31AppleThunderboltNHITransmitRing11initWithNHIEP19AppleThunderboltNHIj : 548 -> 552
~ __ZN31AppleThunderboltNHITransmitRing4freeEv : 568 -> 572
~ sub_fffffff0098bcaac -> sub_fffffff009944ca8 : 836 -> 840
~ sub_fffffff0098bce24 -> sub_fffffff009945024 : 288 -> 292
~ __ZN31AppleThunderboltNHITransmitRing5startEv : 2780 -> 2784
~ sub_fffffff0098bda20 -> sub_fffffff009945c28 : 180 -> 184
~ __ZN31AppleThunderboltNHITransmitRing4stopEv : 956 -> 960
~ __ZN31AppleThunderboltNHITransmitRing8shutdownEv : 332 -> 336
~ sub_fffffff0098be030 -> sub_fffffff009946244 : 268 -> 272
~ sub_fffffff0098be13c -> sub_fffffff009946354 : 140 -> 144
~ sub_fffffff0098be1c8 -> sub_fffffff0099463e4 : 140 -> 144
~ __ZN31AppleThunderboltNHITransmitRing16processInterruptEv : 456 -> 460
~ __ZN31AppleThunderboltNHITransmitRing20writeNextDescriptorsEv : 144 -> 148
~ __ZN31AppleThunderboltNHITransmitRing19writeNextDescriptorEPbS0_ : 5540 -> 5544
~ __ZN31AppleThunderboltNHITransmitRing18submitCommandToNHIEP28IOThunderboltTransmitCommand : 572 -> 576
~ sub_fffffff0098c0260 -> sub_fffffff009948490 : 620 -> 624
~ sub_fffffff0098c04cc -> sub_fffffff009948700 : 164 -> 168
~ __ZN31AppleThunderboltNHITransmitRing18shouldDoubleBufferEyyy : 580 -> 584
~ __ZN31AppleThunderboltNHITransmitRing14setMidPDFRulesEPN28IOThunderboltTransmitCommand18TxBufferDescriptorEbby : 3472 -> 3476
~ sub_fffffff0098c1594 -> sub_fffffff0099497d4 : 480 -> 484
~ __ZN31AppleThunderboltNHITransmitRing8logRingsEyPN28IOThunderboltTransmitCommand18TxBufferDescriptorE : 3108 -> 3112
~ __ZN31AppleThunderboltNHITransmitRing26writeProducerIndexInternalEj : 532 -> 536
~ sub_fffffff0098c25c0 -> sub_fffffff00994a80c : 160 -> 164
~ sub_fffffff0098c2668 -> sub_fffffff00994a8b8 : 80 -> 84
~ sub_fffffff0098c26c8 -> sub_fffffff00994a91c : 72 -> 76
~ sub_fffffff0098c2718 -> sub_fffffff00994a970 : 52 -> 56
~ sub_fffffff0098c274c -> sub_fffffff00994a9a8 : 52 -> 56
~ sub_fffffff0098c2790 -> sub_fffffff00994a9f0 : 68 -> 72
~ sub_fffffff0098c27fc -> sub_fffffff00994aa60 : 72 -> 76
~ sub_fffffff0098c2844 -> sub_fffffff00994aaac : 104 -> 108
~ sub_fffffff0098c28c0 -> sub_fffffff00994ab2c : 88 -> 92
~ sub_fffffff0098c2918 -> sub_fffffff00994ab88 : 88 -> 92
~ sub_fffffff0098c2970 -> sub_fffffff00994abe4 : 180 -> 184
~ sub_fffffff0098c2a24 -> sub_fffffff00994ac9c : 368 -> 372
~ sub_fffffff0098c2b94 -> sub_fffffff00994ae10 : 152 -> 156
~ sub_fffffff0098c2c70 -> sub_fffffff00994aef0 : 80 -> 84
~ sub_fffffff0098c2cd0 -> sub_fffffff00994af54 : 72 -> 76
~ sub_fffffff0098c2d20 -> sub_fffffff00994afa8 : 52 -> 56
~ sub_fffffff0098c2d54 -> sub_fffffff00994afe0 : 52 -> 56
~ sub_fffffff0098c2d98 -> sub_fffffff00994b028 : 68 -> 72
~ sub_fffffff0098c2e04 -> sub_fffffff00994b098 : 72 -> 76
~ sub_fffffff0098c2e4c -> sub_fffffff00994b0e4 : 104 -> 108
~ sub_fffffff0098c2ec8 -> sub_fffffff00994b164 : 88 -> 92
~ sub_fffffff0098c2f20 -> sub_fffffff00994b1c0 : 88 -> 92
~ sub_fffffff0098c2f78 -> sub_fffffff00994b21c : 156 -> 160
~ sub_fffffff0098c310c -> sub_fffffff00994b3b4 : 100 -> 104
~ __ZN38AppleThunderboltNHITransmitRingManager15enableInterruptEjb : 1384 -> 1388
~ __ZN38AppleThunderboltNHITransmitRingManager22handleInterruptForRingEi : 456 -> 460
~ __ZN38AppleThunderboltNHITransmitRingManager31handleDedicatedInterruptForRingEi : 472 -> 476
~ sub_fffffff0098c3ae8 -> sub_fffffff00994bda0 : 188 -> 192
~ sub_fffffff0098c3ba4 -> sub_fffffff00994be60 : 72 -> 76
~ __ZN38AppleThunderboltNHITransmitRingManager20allocateTransmitRingEPP28IOThunderboltNHITransmitRingP26IOThunderboltTransmitQueue : 1512 -> 1516
~ __ZN38AppleThunderboltNHITransmitRingManager22deallocateTransmitRingEP28IOThunderboltNHITransmitRing : 472 -> 476
~ sub_fffffff0098c4644 -> sub_fffffff00994c90c : 80 -> 84
~ sub_fffffff0098c46a4 -> sub_fffffff00994c970 : 72 -> 76
~ sub_fffffff0098c46f4 -> sub_fffffff00994c9c4 : 52 -> 56
~ sub_fffffff0098c4728 -> sub_fffffff00994c9fc : 52 -> 56
~ sub_fffffff0098c476c -> sub_fffffff00994ca44 : 68 -> 72
~ sub_fffffff0098c47d8 -> sub_fffffff00994cab4 : 72 -> 76
~ sub_fffffff0098c4820 -> sub_fffffff00994cb00 : 104 -> 108
~ sub_fffffff0098c489c -> sub_fffffff00994cb80 : 88 -> 92
~ sub_fffffff0098c48f4 -> sub_fffffff00994cbdc : 88 -> 92
~ sub_fffffff0098c494c -> sub_fffffff00994cc38 : 156 -> 160
~ sub_fffffff0098c49e8 -> sub_fffffff00994ccd8 : 188 -> 192
~ sub_fffffff0098c4aac -> sub_fffffff00994cda0 : 80 -> 84
~ sub_fffffff0098c4b0c -> sub_fffffff00994ce04 : 72 -> 76
~ sub_fffffff0098c4b5c -> sub_fffffff00994ce58 : 52 -> 56
~ sub_fffffff0098c4b90 -> sub_fffffff00994ce90 : 52 -> 56
~ sub_fffffff0098c4bd4 -> sub_fffffff00994ced8 : 68 -> 72
~ sub_fffffff0098c4c40 -> sub_fffffff00994cf48 : 72 -> 76
~ sub_fffffff0098c4c88 -> sub_fffffff00994cf94 : 104 -> 108
~ sub_fffffff0098c4d04 -> sub_fffffff00994d014 : 88 -> 92
~ sub_fffffff0098c4d5c -> sub_fffffff00994d070 : 88 -> 92
~ sub_fffffff0098c4db4 -> sub_fffffff00994d0cc : 76 -> 80
~ sub_fffffff0098c4e00 -> sub_fffffff00994d11c : 168 -> 172
~ sub_fffffff0098c4eb0 -> sub_fffffff00994d1d0 : 80 -> 84
~ sub_fffffff0098c4f10 -> sub_fffffff00994d234 : 72 -> 76
~ sub_fffffff0098c4f60 -> sub_fffffff00994d288 : 52 -> 56
~ sub_fffffff0098c4f94 -> sub_fffffff00994d2c0 : 52 -> 56
~ sub_fffffff0098c4fd8 -> sub_fffffff00994d308 : 68 -> 72
~ sub_fffffff0098c5044 -> sub_fffffff00994d378 : 72 -> 76
~ sub_fffffff0098c508c -> sub_fffffff00994d3c4 : 104 -> 108
~ sub_fffffff0098c5108 -> sub_fffffff00994d444 : 88 -> 92
~ sub_fffffff0098c5160 -> sub_fffffff00994d4a0 : 88 -> 92
~ sub_fffffff0098c51b8 -> sub_fffffff00994d4fc : 152 -> 156
~ __ZN24AppleThunderboltHALType519setupRegisterRangesEv : 940 -> 944
~ sub_fffffff0098c5604 -> sub_fffffff00994d950 : 80 -> 84
~ sub_fffffff0098c5664 -> sub_fffffff00994d9b4 : 72 -> 76
~ sub_fffffff0098c56b4 -> sub_fffffff00994da08 : 52 -> 56
~ sub_fffffff0098c56e8 -> sub_fffffff00994da40 : 52 -> 56
~ sub_fffffff0098c572c -> sub_fffffff00994da88 : 68 -> 72
~ sub_fffffff0098c5798 -> sub_fffffff00994daf8 : 72 -> 76
~ sub_fffffff0098c57e0 -> sub_fffffff00994db44 : 104 -> 108
~ sub_fffffff0098c585c -> sub_fffffff00994dbc4 : 88 -> 92
~ sub_fffffff0098c58b4 -> sub_fffffff00994dc20 : 88 -> 92
~ sub_fffffff0098c590c -> sub_fffffff00994dc7c : 180 -> 184
~ sub_fffffff0098c59c0 -> sub_fffffff00994dd34 : 188 -> 192
~ sub_fffffff0098c5a7c -> sub_fffffff00994ddf4 : 700 -> 704
~ sub_fffffff0098c5d38 -> sub_fffffff00994e0b4 : 116 -> 120
~ sub_fffffff0098c5dac -> sub_fffffff00994e12c : 252 -> 256
~ sub_fffffff0098c5ee0 -> sub_fffffff00994e264 : 80 -> 84
~ sub_fffffff0098c5f40 -> sub_fffffff00994e2c8 : 72 -> 76
~ sub_fffffff0098c5f90 -> sub_fffffff00994e31c : 52 -> 56
~ sub_fffffff0098c5fc4 -> sub_fffffff00994e354 : 52 -> 56
~ sub_fffffff0098c6008 -> sub_fffffff00994e39c : 68 -> 72
~ sub_fffffff0098c6074 -> sub_fffffff00994e40c : 72 -> 76
~ sub_fffffff0098c60bc -> sub_fffffff00994e458 : 104 -> 108
~ sub_fffffff0098c6138 -> sub_fffffff00994e4d8 : 88 -> 92
~ sub_fffffff0098c6190 -> sub_fffffff00994e534 : 88 -> 92
~ sub_fffffff0098c61e8 -> sub_fffffff00994e590 : 156 -> 160
~ sub_fffffff0098c6284 -> sub_fffffff00994e630 : 188 -> 192
~ sub_fffffff0098c6348 -> sub_fffffff00994e6f8 : 80 -> 84
~ sub_fffffff0098c63a8 -> sub_fffffff00994e75c : 72 -> 76
~ sub_fffffff0098c63f8 -> sub_fffffff00994e7b0 : 52 -> 56
~ sub_fffffff0098c642c -> sub_fffffff00994e7e8 : 52 -> 56
~ sub_fffffff0098c6470 -> sub_fffffff00994e830 : 68 -> 72
~ sub_fffffff0098c64dc -> sub_fffffff00994e8a0 : 72 -> 76
~ sub_fffffff0098c6524 -> sub_fffffff00994e8ec : 104 -> 108
~ sub_fffffff0098c65a0 -> sub_fffffff00994e96c : 88 -> 92
~ sub_fffffff0098c65f8 -> sub_fffffff00994e9c8 : 88 -> 92
~ sub_fffffff0098c6688 -> sub_fffffff00994ea5c : 80 -> 84
~ sub_fffffff0098c66e8 -> sub_fffffff00994eac0 : 72 -> 76
~ sub_fffffff0098c6738 -> sub_fffffff00994eb14 : 52 -> 56
~ sub_fffffff0098c676c -> sub_fffffff00994eb4c : 52 -> 56
~ sub_fffffff0098c67b0 -> sub_fffffff00994eb94 : 68 -> 72
~ sub_fffffff0098c681c -> sub_fffffff00994ec04 : 72 -> 76
~ sub_fffffff0098c6864 -> sub_fffffff00994ec50 : 104 -> 108
~ sub_fffffff0098c68e0 -> sub_fffffff00994ecd0 : 88 -> 92
~ sub_fffffff0098c6938 -> sub_fffffff00994ed2c : 88 -> 92
~ sub_fffffff0098c6990 -> sub_fffffff00994ed88 : 156 -> 160
~ sub_fffffff0098c6b24 -> sub_fffffff00994ef20 : 100 -> 104
~ __ZN37AppleThunderboltNHIReceiveRingManager15enableInterruptEjb : 1392 -> 1396
~ __ZN37AppleThunderboltNHIReceiveRingManager22handleInterruptForRingEi : 456 -> 460
~ __ZN37AppleThunderboltNHIReceiveRingManager31handleDedicatedInterruptForRingEi : 456 -> 460
~ sub_fffffff0098c7508 -> sub_fffffff00994f914 : 188 -> 192
~ sub_fffffff0098c75c4 -> sub_fffffff00994f9d4 : 72 -> 76
~ __ZN37AppleThunderboltNHIReceiveRingManager19allocateReceiveRingEPP27IOThunderboltNHIReceiveRingP25IOThunderboltReceiveQueue : 1512 -> 1516
~ __ZN37AppleThunderboltNHIReceiveRingManager21deallocateReceiveRingEP27IOThunderboltNHIReceiveRing : 404 -> 408
~ sub_fffffff0098c8020 -> sub_fffffff00995043c : 80 -> 84
~ sub_fffffff0098c8080 -> sub_fffffff0099504a0 : 72 -> 76
~ sub_fffffff0098c80d0 -> sub_fffffff0099504f4 : 52 -> 56
~ sub_fffffff0098c8104 -> sub_fffffff00995052c : 52 -> 56
~ sub_fffffff0098c8148 -> sub_fffffff009950574 : 68 -> 72
~ sub_fffffff0098c81b4 -> sub_fffffff0099505e4 : 72 -> 76
~ sub_fffffff0098c81fc -> sub_fffffff009950630 : 104 -> 108
~ sub_fffffff0098c8278 -> sub_fffffff0099506b0 : 88 -> 92
~ sub_fffffff0098c82d0 -> sub_fffffff00995070c : 88 -> 92
~ sub_fffffff0098c8328 -> sub_fffffff009950768 : 180 -> 184
~ __ZN30AppleThunderboltNHIReceiveRing11initWithNHIEP19AppleThunderboltNHIj : 544 -> 548
~ __ZN30AppleThunderboltNHIReceiveRing4freeEv : 672 -> 676
~ sub_fffffff0098c8904 -> sub_fffffff009950d50 : 1168 -> 1172
~ __ZN30AppleThunderboltNHIReceiveRing11unconfigureEv : 676 -> 680
~ __ZN30AppleThunderboltNHIReceiveRing5startEv : 2832 -> 2836
~ sub_fffffff0098c9ba8 -> sub_fffffff009952000 : 172 -> 176
~ __ZN30AppleThunderboltNHIReceiveRing4stopEv : 784 -> 788
~ __ZN30AppleThunderboltNHIReceiveRing8shutdownEv : 332 -> 336
~ __ZN30AppleThunderboltNHIReceiveRing8startDMAEv : 1392 -> 1396
~ sub_fffffff0098ca63c -> sub_fffffff009952aa4 : 332 -> 336
~ sub_fffffff0098cbec4 -> sub_fffffff009954330 : 268 -> 272
~ sub_fffffff0098cbfd0 -> sub_fffffff009954440 : 140 -> 144
~ sub_fffffff0098cc05c -> sub_fffffff0099544d0 : 140 -> 144
~ __ZN30AppleThunderboltNHIReceiveRing16processInterruptEv : 532 -> 536
~ __ZN30AppleThunderboltNHIReceiveRing20writeNextDescriptorsEv : 144 -> 148
~ __ZN30AppleThunderboltNHIReceiveRing14setPDFBitmasksEtt : 404 -> 408
~ __ZN30AppleThunderboltNHIReceiveRing18submitCommandToNHIEP27IOThunderboltReceiveCommand : 572 -> 576
~ sub_fffffff0098cc780 -> sub_fffffff009954c08 : 376 -> 380
~ sub_fffffff0098cc8f8 -> sub_fffffff009954d84 : 164 -> 168
~ __ZN30AppleThunderboltNHIReceiveRing18shouldDoubleBufferEyyy : 420 -> 424
~ __ZN30AppleThunderboltNHIReceiveRing19writeNextDescriptorEPbS0_ : 4376 -> 4380
~ __ZN30AppleThunderboltNHIReceiveRing26writeConsumerIndexInternalEj : 528 -> 532
~ sub_fffffff0098cdecc -> sub_fffffff009956368 : 152 -> 156
~ sub_fffffff0098cdf6c -> sub_fffffff00995640c : 80 -> 84
~ sub_fffffff0098cdfcc -> sub_fffffff009956470 : 72 -> 76
~ sub_fffffff0098ce01c -> sub_fffffff0099564c4 : 52 -> 56
~ sub_fffffff0098ce050 -> sub_fffffff0099564fc : 52 -> 56
~ sub_fffffff0098ce094 -> sub_fffffff009956544 : 68 -> 72
~ sub_fffffff0098ce100 -> sub_fffffff0099565b4 : 72 -> 76
~ sub_fffffff0098ce148 -> sub_fffffff009956600 : 104 -> 108
~ sub_fffffff0098ce1c4 -> sub_fffffff009956680 : 88 -> 92
~ sub_fffffff0098ce21c -> sub_fffffff0099566dc : 88 -> 92
~ sub_fffffff0098ce274 -> sub_fffffff009956738 : 156 -> 160
~ sub_fffffff0098ce39c -> sub_fffffff009956864 : 100 -> 104
~ __ZN49AppleThunderboltNHITransmitRingManagerGenericACIO15enableInterruptEjb : 1360 -> 1364
~ __ZN49AppleThunderboltNHITransmitRingManagerGenericACIO10setupRingsEv : 76 -> 80
~ __ZN49AppleThunderboltNHITransmitRingManagerGenericACIO20allocateSharedBufferEv : 2180 -> 2184
~ sub_fffffff0098cf220 -> sub_fffffff0099576f8 : 188 -> 192
~ sub_fffffff0098cf2e4 -> sub_fffffff0099577c0 : 80 -> 84
~ sub_fffffff0098cf344 -> sub_fffffff009957824 : 72 -> 76
~ sub_fffffff0098cf394 -> sub_fffffff009957878 : 52 -> 56
~ sub_fffffff0098cf3c8 -> sub_fffffff0099578b0 : 52 -> 56
~ sub_fffffff0098cf40c -> sub_fffffff0099578f8 : 68 -> 72
~ sub_fffffff0098cf478 -> sub_fffffff009957968 : 72 -> 76
~ sub_fffffff0098cf4c0 -> sub_fffffff0099579b4 : 104 -> 108
~ sub_fffffff0098cf53c -> sub_fffffff009957a34 : 88 -> 92
~ sub_fffffff0098cf594 -> sub_fffffff009957a90 : 88 -> 92
~ sub_fffffff0098cf5ec -> sub_fffffff009957aec : 180 -> 184
~ __ZN42AppleThunderboltNHITransmitRingGenericACIO11initWithNHIEP19AppleThunderboltNHIj : 524 -> 528
~ __ZN42AppleThunderboltNHITransmitRingGenericACIO4freeEv : 320 -> 324
~ __ZN42AppleThunderboltNHITransmitRingGenericACIO21configureSharedBufferEv : 352 -> 356
~ __ZN42AppleThunderboltNHITransmitRingGenericACIO25setSharedBufferAllocationEj : 308 -> 312
~ __ZN42AppleThunderboltNHITransmitRingGenericACIO22waitForRingDisableDoneEv : 796 -> 800
~ __ZN42AppleThunderboltNHITransmitRingGenericACIO18shouldDoubleBufferEyyy : 592 -> 596
~ __ZN42AppleThunderboltNHITransmitRingGenericACIO19createDoubleBuffersEv : 720 -> 724
~ sub_fffffff0098d04bc -> sub_fffffff0099589dc : 176 -> 180
~ sub_fffffff0098d056c -> sub_fffffff009958a90 : 152 -> 156
~ sub_fffffff0098d060c -> sub_fffffff009958b34 : 80 -> 84
~ sub_fffffff0098d066c -> sub_fffffff009958b98 : 72 -> 76
~ sub_fffffff0098d06bc -> sub_fffffff009958bec : 52 -> 56
~ sub_fffffff0098d06f0 -> sub_fffffff009958c24 : 52 -> 56
~ sub_fffffff0098d0734 -> sub_fffffff009958c6c : 68 -> 72
~ sub_fffffff0098d07a0 -> sub_fffffff009958cdc : 72 -> 76
~ sub_fffffff0098d07e8 -> sub_fffffff009958d28 : 104 -> 108
~ sub_fffffff0098d0864 -> sub_fffffff009958da8 : 88 -> 92
~ sub_fffffff0098d08bc -> sub_fffffff009958e04 : 88 -> 92
~ sub_fffffff0098d0914 -> sub_fffffff009958e60 : 156 -> 160
~ __ZN48AppleThunderboltNHIReceiveRingManagerGenericACIO15enableInterruptEjb : 1492 -> 1496
~ sub_fffffff0098d0fc8 -> sub_fffffff00995951c : 188 -> 192
~ sub_fffffff0098d108c -> sub_fffffff0099595e4 : 80 -> 84
~ sub_fffffff0098d10ec -> sub_fffffff009959648 : 72 -> 76
~ sub_fffffff0098d113c -> sub_fffffff00995969c : 52 -> 56
~ sub_fffffff0098d1170 -> sub_fffffff0099596d4 : 52 -> 56
~ sub_fffffff0098d11b4 -> sub_fffffff00995971c : 68 -> 72
~ sub_fffffff0098d1220 -> sub_fffffff00995978c : 72 -> 76
~ sub_fffffff0098d1268 -> sub_fffffff0099597d8 : 104 -> 108
~ sub_fffffff0098d12e4 -> sub_fffffff009959858 : 88 -> 92
~ sub_fffffff0098d133c -> sub_fffffff0099598b4 : 88 -> 92
~ sub_fffffff0098d1394 -> sub_fffffff009959910 : 180 -> 184
~ __ZN41AppleThunderboltNHIReceiveRingGenericACIO11initWithNHIEP19AppleThunderboltNHIj : 536 -> 540
~ __ZN41AppleThunderboltNHIReceiveRingGenericACIO4freeEv : 320 -> 324
~ __ZN41AppleThunderboltNHIReceiveRingGenericACIO22waitForRingDisableDoneEv : 796 -> 800
~ __ZN41AppleThunderboltNHIReceiveRingGenericACIO18shouldDoubleBufferEyyy : 596 -> 600
~ __ZN41AppleThunderboltNHIReceiveRingGenericACIO19createDoubleBuffersEv : 712 -> 716
~ sub_fffffff0098d1fd8 -> sub_fffffff00995a56c : 176 -> 180
~ sub_fffffff0098d2088 -> sub_fffffff00995a620 : 152 -> 156
~ sub_fffffff0098d2128 -> sub_fffffff00995a6c4 : 80 -> 84
~ sub_fffffff0098d2188 -> sub_fffffff00995a728 : 72 -> 76
~ sub_fffffff0098d21d8 -> sub_fffffff00995a77c : 52 -> 56
~ sub_fffffff0098d220c -> sub_fffffff00995a7b4 : 52 -> 56
~ sub_fffffff0098d2250 -> sub_fffffff00995a7fc : 68 -> 72
~ sub_fffffff0098d22bc -> sub_fffffff00995a86c : 72 -> 76
~ sub_fffffff0098d2304 -> sub_fffffff00995a8b8 : 104 -> 108
~ sub_fffffff0098d2380 -> sub_fffffff00995a938 : 88 -> 92
~ sub_fffffff0098d23d8 -> sub_fffffff00995a994 : 88 -> 92
~ __ZN34AppleThunderboltNHIDARTVMAllocator9forMapperEP8IOMapperj : 340 -> 344
~ __ZN34AppleThunderboltNHIDARTVMAllocator4initEP8IOMapperj : 1284 -> 1288
~ __ZN34AppleThunderboltNHIDARTVMAllocator7vmAllocEjjjP12IODMACommandjjb : 1572 -> 1576
~ sub_fffffff0098d30cc -> sub_fffffff00995b698 : 36 -> 40
~ sub_fffffff0098d30f0 -> sub_fffffff00995b6c0 : 80 -> 84
~ sub_fffffff0098d3150 -> sub_fffffff00995b724 : 72 -> 76
~ sub_fffffff0098d31a0 -> sub_fffffff00995b778 : 52 -> 56
~ sub_fffffff0098d31d4 -> sub_fffffff00995b7b0 : 52 -> 56
~ sub_fffffff0098d3218 -> sub_fffffff00995b7f8 : 68 -> 72
~ sub_fffffff0098d3284 -> sub_fffffff00995b868 : 72 -> 76
~ sub_fffffff0098d32cc -> sub_fffffff00995b8b4 : 104 -> 108
~ sub_fffffff0098d3348 -> sub_fffffff00995b934 : 88 -> 92
~ sub_fffffff0098d33a0 -> sub_fffffff00995b990 : 88 -> 92
~ sub_fffffff0098d33f8 -> sub_fffffff00995b9ec : 76 -> 80
~ sub_fffffff0098d3444 -> sub_fffffff00995ba3c : 168 -> 172
~ sub_fffffff0098d34f4 -> sub_fffffff00995baf0 : 80 -> 84
~ sub_fffffff0098d3554 -> sub_fffffff00995bb54 : 72 -> 76
~ sub_fffffff0098d35a4 -> sub_fffffff00995bba8 : 52 -> 56
~ sub_fffffff0098d35d8 -> sub_fffffff00995bbe0 : 52 -> 56
~ sub_fffffff0098d361c -> sub_fffffff00995bc28 : 68 -> 72
~ sub_fffffff0098d3688 -> sub_fffffff00995bc98 : 72 -> 76
~ sub_fffffff0098d36d0 -> sub_fffffff00995bce4 : 104 -> 108
~ sub_fffffff0098d374c -> sub_fffffff00995bd64 : 88 -> 92
~ sub_fffffff0098d37a4 -> sub_fffffff00995bdc0 : 88 -> 92
~ sub_fffffff0098d37fc -> sub_fffffff00995be1c : 156 -> 160
~ sub_fffffff0098d3898 -> sub_fffffff00995bebc : 188 -> 192
~ sub_fffffff0098d395c -> sub_fffffff00995bf84 : 80 -> 84
~ sub_fffffff0098d39bc -> sub_fffffff00995bfe8 : 72 -> 76
~ sub_fffffff0098d3a0c -> sub_fffffff00995c03c : 52 -> 56
~ sub_fffffff0098d3a40 -> sub_fffffff00995c074 : 52 -> 56
~ sub_fffffff0098d3a84 -> sub_fffffff00995c0bc : 68 -> 72
~ sub_fffffff0098d3af0 -> sub_fffffff00995c12c : 72 -> 76
~ sub_fffffff0098d3b38 -> sub_fffffff00995c178 : 104 -> 108
~ sub_fffffff0098d3bb4 -> sub_fffffff00995c1f8 : 88 -> 92
~ sub_fffffff0098d3c0c -> sub_fffffff00995c254 : 88 -> 92
~ sub_fffffff0098d3c64 -> sub_fffffff00995c2b0 : 152 -> 156
~ __ZN24AppleThunderboltHALType719setupRegisterRangesEv : 1060 -> 1064
~ __ZN24AppleThunderboltHALType724setupSRAMParityInterruptEv : 660 -> 664
~ sub_fffffff0098d448c -> sub_fffffff00995cae4 : 80 -> 84
~ sub_fffffff0098d44ec -> sub_fffffff00995cb48 : 72 -> 76
~ sub_fffffff0098d453c -> sub_fffffff00995cb9c : 52 -> 56
~ sub_fffffff0098d4570 -> sub_fffffff00995cbd4 : 52 -> 56
~ sub_fffffff0098d45b4 -> sub_fffffff00995cc1c : 68 -> 72
~ sub_fffffff0098d4620 -> sub_fffffff00995cc8c : 72 -> 76
~ sub_fffffff0098d4668 -> sub_fffffff00995ccd8 : 104 -> 108
~ sub_fffffff0098d46e4 -> sub_fffffff00995cd58 : 88 -> 92
~ sub_fffffff0098d473c -> sub_fffffff00995cdb4 : 88 -> 92
~ sub_fffffff0098d4794 -> sub_fffffff00995ce10 : 180 -> 184
~ __ZN35AppleThunderboltNHIReceiveRingType514setPDFBitmasksEtt : 404 -> 408
~ sub_fffffff0098d49e4 -> sub_fffffff00995d068 : 80 -> 84
~ sub_fffffff0098d4a44 -> sub_fffffff00995d0cc : 72 -> 76
~ sub_fffffff0098d4a94 -> sub_fffffff00995d120 : 52 -> 56
~ sub_fffffff0098d4ac8 -> sub_fffffff00995d158 : 52 -> 56
~ sub_fffffff0098d4b0c -> sub_fffffff00995d1a0 : 68 -> 72
~ sub_fffffff0098d4b78 -> sub_fffffff00995d210 : 72 -> 76
~ sub_fffffff0098d4bc0 -> sub_fffffff00995d25c : 104 -> 108
~ sub_fffffff0098d4c3c -> sub_fffffff00995d2dc : 88 -> 92
~ sub_fffffff0098d4c94 -> sub_fffffff00995d338 : 88 -> 92
~ sub_fffffff0098d4cec -> sub_fffffff00995d394 : 156 -> 160
~ sub_fffffff0098d4d88 -> sub_fffffff00995d434 : 188 -> 192
~ sub_fffffff0098d4e4c -> sub_fffffff00995d4fc : 80 -> 84
~ __ZN9os_detail21panic_trapping_policy4trapEPKc : 48 -> 52
~ __ZNK30AppleThunderboltHALGenericACIO24determineSIDPartitioningEPK9IOService.cold.1 : 104 -> 108
~ __ZNK30AppleThunderboltHALGenericACIO24determineSIDPartitioningEPK9IOService.cold.2 : 80 -> 84
~ __ZNK30AppleThunderboltHALGenericACIO24determineSIDPartitioningEPK9IOService.cold.3 : 44 -> 48
~ __ZN30AppleThunderboltHALGenericACIO17initializeMappersEv.cold.1 : 16 -> 20
~ __ZN9os_detail21panic_trapping_policy4trapEPKc : 16 -> 20
~ __ZN30AppleThunderboltHALGenericACIO17initializeMappersEv.cold.5 : 16 -> 20
~ __ZN34AppleThunderboltNHIDARTVMAllocator4initEP8IOMapperj.cold.1 : 76 -> 80
~ __ZN24AppleThunderboltHALType725handleSRAMParityInterruptEv : 52 -> 56
CStrings:
+ "21:25:16"
- "22:11:03"
```
