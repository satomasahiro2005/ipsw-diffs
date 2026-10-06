## com.apple.driver.AppleSPMIPMU

> `com.apple.driver.AppleSPMIPMU`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xcb7c` | `0xcd88` | **`+0x20c`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ sub_fffffff009616a60 -> sub_fffffff009697d00 : 72 -> 76
~ sub_fffffff009616ab0 -> sub_fffffff009697d54 : 124 -> 128
~ sub_fffffff009616b44 -> sub_fffffff009697dec : 68 -> 72
~ sub_fffffff009616bb0 -> sub_fffffff009697e5c : 72 -> 76
~ sub_fffffff009616bf8 -> sub_fffffff009697ea8 : 52 -> 56
~ sub_fffffff009616c48 -> sub_fffffff009697efc : 160 -> 164
~ __ZN18AppleDialogSPMIPMU5startEP9IOService : 3512 -> 3516
~ __ZN18AppleDialogSPMIPMU25_initUpsiFailureInjectionEv : 240 -> 244
~ __ZN18AppleDialogSPMIPMU16_interruptActionEP22IOInterruptEventSourcei : 192 -> 196
~ sub_fffffff009617c50 -> sub_fffffff009698f14 : 204 -> 208
~ sub_fffffff009617d1c -> sub_fffffff009698fe4 : 1008 -> 1012
~ __ZN18AppleDialogSPMIPMU23_resetLpemInRestoreModeEv : 368 -> 372
~ __ZN18AppleDialogSPMIPMU26_checkUpsiFailureInjectionEh : 188 -> 192
~ __ZN18AppleDialogSPMIPMU20_handlePEHaltRestartEj : 248 -> 252
~ sub_fffffff009618430 -> sub_fffffff009699708 : 480 -> 484
~ sub_fffffff009618610 -> sub_fffffff0096998ec : 112 -> 116
~ __ZN18AppleDialogSPMIPMU15updatePMSettingEhh : 356 -> 360
~ sub_fffffff0096187e4 -> sub_fffffff009699ac8 : 204 -> 208
~ __ZN18AppleDialogSPMIPMU18registerPMCallbackEv : 352 -> 356
~ __ZN18AppleDialogSPMIPMU20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 1156 -> 1160
~ sub_fffffff009618f00 -> sub_fffffff00969a1f0 : 88 -> 92
~ sub_fffffff009618f58 -> sub_fffffff00969a24c : 204 -> 208
~ __ZN18AppleDialogSPMIPMU18_readConfigurationEP9IOService : 3412 -> 3416
~ sub_fffffff009619ec0 -> sub_fffffff00969b1bc : 140 -> 144
~ __ZN18AppleDialogSPMIPMU17copyDebugPropertyEPKc : 296 -> 300
~ __ZN18AppleDialogSPMIPMU18setDebugPropertiesEPK12OSDictionary : 472 -> 476
~ __ZN18AppleDialogSPMIPMU16_handleSpmiErrorEij : 296 -> 300
~ __ZN18AppleDialogSPMIPMU10_writeRegsEtPht : 312 -> 316
~ __ZN18AppleDialogSPMIPMU9_readRegsEtPht : 312 -> 316
~ __ZN18AppleDialogSPMIPMU6modRegEthh : 408 -> 412
~ __ZN18AppleDialogSPMIPMU9_writeMemEbtPht : 604 -> 608
~ __ZN18AppleDialogSPMIPMU8_readMemEbtPht : 604 -> 608
~ sub_fffffff00961ac34 -> sub_fffffff00969bf54 : 208 -> 212
~ sub_fffffff00961ad04 -> sub_fffffff00969c028 : 152 -> 156
~ sub_fffffff00961ad9c -> sub_fffffff00969c0c4 : 284 -> 288
~ __ZN18AppleDialogSPMIPMU12_readBootKeyEhPhh : 208 -> 212
~ __ZN18AppleDialogSPMIPMU13_writeBootKeyEhPhh : 208 -> 212
~ __ZN18AppleDialogSPMIPMU13_readFaultLogEPhhb : 488 -> 492
~ __ZN18AppleDialogSPMIPMU19_readOff2WakeSourceEPhhb : 268 -> 272
~ __ZN18AppleDialogSPMIPMU13setPropertiesEP8OSObject : 4148 -> 4152
~ __ZN18AppleDialogSPMIPMU13_setLpemStateEhhhhhhh : 420 -> 424
~ __ZN18AppleDialogSPMIPMU21_setLpemBluetoothFWOKEh : 360 -> 364
~ __ZN18AppleDialogSPMIPMU21_updateBootPropertiesEb : 2148 -> 2152
~ __ZN18AppleDialogSPMIPMU13_getLpemStateEPhS0_S0_ : 192 -> 196
~ _panic : 276 -> 280
~ __ZN18AppleDialogSPMIPMU13_lpemCtrlDictEhhhhhhh : 772 -> 776
~ __ZN18AppleDialogSPMIPMU21_populateSOCDPropertyEv : 460 -> 464
~ __ZN18AppleDialogSPMIPMU17_writeLpemLogDataEv : 488 -> 492
~ sub_fffffff00961d870 -> sub_fffffff00969ebd0 : 132 -> 136
~ __ZN18AppleDialogSPMIPMU21_updateFaultRegistersEb : 1276 -> 1280
~ __ZN18AppleDialogSPMIPMU30_updateOff2WakeSourceRegistersEv : 1176 -> 1180
~ sub_fffffff00961e288 -> sub_fffffff00969f5f4 : 80 -> 84
~ __ZN18AppleDialogSPMIPMU14_shutdownGatedEv : 2404 -> 2408
~ sub_fffffff00961ec48 -> sub_fffffff00969ffbc : 308 -> 312
~ __ZN18AppleDialogSPMIPMU14_enterTestModeEv : 148 -> 152
~ __ZN18AppleDialogSPMIPMU13_exitTestModeEv : 148 -> 152
~ sub_fffffff00961eefc -> sub_fffffff0096a027c : 72 -> 76
~ sub_fffffff00961ef4c -> sub_fffffff0096a02d0 : 52 -> 56
~ sub_fffffff00961ef80 -> sub_fffffff0096a0308 : 52 -> 56
~ sub_fffffff00961efc4 -> sub_fffffff0096a0350 : 68 -> 72
~ sub_fffffff00961f030 -> sub_fffffff0096a03c0 : 72 -> 76
~ sub_fffffff00961f078 -> sub_fffffff0096a040c : 104 -> 108
~ sub_fffffff00961f0e0 -> sub_fffffff0096a0478 : 88 -> 92
~ __ZN26AppleDialogSPMIPMUFunction12callFunctionEPvS0_S0_ : 484 -> 488
~ __ZN26AppleDialogSPMIPMUFunction27initWithTargetDataAndSymbolEP9IOServicePK6OSDataPK8OSSymbol : 236 -> 240
~ __GLOBAL__sub_I_AppleDialogSPMIPMU.cpp : 360 -> 364
~ sub_fffffff00961f598 -> sub_fffffff0096a0940 : 56 -> 60
~ _IOLog : 316 -> 320
~ __ZN22AppleDialogSPMIPMUSOCD12readAndClearEP6OSDataRtS2_tPPh : 456 -> 460
~ sub_fffffff00961f904 -> sub_fffffff0096a0cb8 : 336 -> 340
~ sub_fffffff00961fa64 -> sub_fffffff0096a0e1c : 188 -> 192
~ __ZN22AppleDialogSPMIPMUSOCD19readContainerDataV0EP6OSDataRtS2_ : 292 -> 296
~ __ZN22AppleDialogSPMIPMUSOCD19readContainerDataV1EP6OSDataRtS2_ : 284 -> 288
~ __ZN22AppleDialogSPMIPMUSOCD17getSOCDContainersEP7OSArray : 484 -> 488
~ sub_fffffff00961ff94 -> sub_fffffff0096a135c : 72 -> 76
~ sub_fffffff00961ffe4 -> sub_fffffff0096a13b0 : 56 -> 60
~ sub_fffffff00962001c -> sub_fffffff0096a13ec : 56 -> 60
~ sub_fffffff009620064 -> sub_fffffff0096a1438 : 68 -> 72
~ sub_fffffff0096200d0 -> sub_fffffff0096a14a8 : 72 -> 76
~ sub_fffffff009620118 -> sub_fffffff0096a14f4 : 108 -> 112
~ sub_fffffff009620198 -> sub_fffffff0096a1578 : 92 -> 96
~ sub_fffffff0096201f4 -> sub_fffffff0096a15d8 : 92 -> 96
~ __ZN21AppleDialogSPMIPMURTC11handleStartEP9IOService : 1952 -> 1956
~ sub_fffffff0096209f0 -> sub_fffffff0096a1ddc : 108 -> 112
~ sub_fffffff009620a5c -> sub_fffffff0096a1e4c : 368 -> 372
~ sub_fffffff009620bcc -> sub_fffffff0096a1fc0 : 288 -> 292
~ sub_fffffff009620cec -> sub_fffffff0096a20e4 : 420 -> 424
~ __ZN21AppleDialogSPMIPMURTC22_handleSMCNotificationEPv : 196 -> 200
~ __ZN21AppleDialogSPMIPMURTC25_sysctlNVRAMOffsetHandlerEP10sysctl_oidPviP10sysctl_req : 324 -> 328
~ __ZN21AppleDialogSPMIPMURTC18_readConfigurationEP9IOService : 1496 -> 1500
~ __ZN21AppleDialogSPMIPMURTC23_readCurrentOffsetTicksEPx : 492 -> 496
~ sub_fffffff009621878 -> sub_fffffff0096a2c84 : 284 -> 288
~ sub_fffffff009621994 -> sub_fffffff0096a2da4 : 168 -> 172
~ __ZN17PMURTCNVRAMHelper14nvramWriteSI64Exb : 356 -> 360
~ __ZN21AppleDialogSPMIPMURTC20_setClockOffsetTicksEx : 184 -> 188
~ sub_fffffff009621c90 -> sub_fffffff0096a30ac : 88 -> 92
~ sub_fffffff009621ce8 -> sub_fffffff0096a3108 : 108 -> 112
~ sub_fffffff009621df0 -> sub_fffffff0096a3214 : 152 -> 156
~ __ZN17PMURTCNVRAMHelper13nvramReadSI64EPx : 620 -> 624
~ sub_fffffff0096220f4 -> sub_fffffff0096a3520 : 180 -> 184
~ sub_fffffff0096221a8 -> sub_fffffff0096a35d8 : 120 -> 124
~ __ZN21AppleDialogSPMIPMURTC15programRTCAlarmEj : 612 -> 616
~ sub_fffffff009622484 -> sub_fffffff0096a38bc : 132 -> 136
~ sub_fffffff009622520 -> sub_fffffff0096a395c : 60 -> 64
~ __ZN21AppleDialogSPMIPMURTC20_readRTCUpcountTicksEv : 836 -> 840
~ __ZN21AppleDialogSPMIPMURTC20scheduleRTCWakeAlarmEb : 416 -> 420
~ __ZN21AppleDialogSPMIPMURTC20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 228 -> 232
~ sub_fffffff009622b24 -> sub_fffffff0096a3f70 : 128 -> 132
~ sub_fffffff009622bac -> sub_fffffff0096a3ffc : 116 -> 120
~ sub_fffffff009622c20 -> sub_fffffff0096a4074 : 80 -> 84
~ sub_fffffff009622c80 -> sub_fffffff0096a40d8 : 72 -> 76
~ sub_fffffff009622cd0 -> sub_fffffff0096a412c : 52 -> 56
~ sub_fffffff009622d04 -> sub_fffffff0096a4164 : 52 -> 56
~ sub_fffffff009622d48 -> sub_fffffff0096a41ac : 68 -> 72
~ sub_fffffff009622db4 -> sub_fffffff0096a421c : 72 -> 76
~ sub_fffffff009622dfc -> sub_fffffff0096a4268 : 104 -> 108
~ sub_fffffff009622e78 -> sub_fffffff0096a42e8 : 88 -> 92
~ sub_fffffff009622ed0 -> sub_fffffff0096a4344 : 88 -> 92
~ sub_fffffff009622f28 -> sub_fffffff0096a43a0 : 172 -> 176
~ sub_fffffff009622fd4 -> sub_fffffff0096a4450 : 128 -> 132
~ sub_fffffff009623054 -> sub_fffffff0096a44d4 : 200 -> 204
~ sub_fffffff00962311c -> sub_fffffff0096a45a0 : 200 -> 204
~ sub_fffffff0096231ec -> sub_fffffff0096a4674 : 80 -> 84
~ __ZN18AppleDialogSPMIPMU20_handlePEHaltRestartEj.cold.1 : 116 -> 120
~ __ZN18AppleDialogSPMIPMU20_handlePEHaltRestartEj.cold.2 : 188 -> 192
~ __ZN18AppleDialogSPMIPMU28_updateLpemLogDataPropertiesEPh.cold.1 : 44 -> 48
~ __ZN18AppleDialogSPMIPMU14_shutdownGatedEv.cold.1 : 44 -> 48
~ __ZN18AppleDialogSPMIPMU14_shutdownGatedEv.cold.2 : 44 -> 48
~ __ZN18AppleDialogSPMIPMU14_shutdownGatedEv.cold.3 : 204 -> 208
~ __ZN21AppleDialogSPMIPMURTC18getCurrentDateTimeEP11RTCDateTime : 44 -> 48
~ __ZN21AppleDialogSPMIPMURTC18setCurrentDateTimeEPK11RTCDateTime : 44 -> 48
CStrings:
+ "%s::handleStart: %s _pmuNub: %p ** configuration not found ** built 21:25:33 Aug 13 2026\n"
+ "%s::handleStart: ro=%d nvram=%d helper=%d %s _pmuNub: %p 0x%04x:0x%04x-0x%04x built 21:25:33 Aug 13 2026\n"
+ "%s::start: %s _pmuNub: %p ** configuration not found ** built 21:25:33 Aug 13 2026\n"
+ "%s::start: %s _pmuNub: %p built 21:25:33 Aug 13 2026\n"
- "%s::handleStart: %s _pmuNub: %p ** configuration not found ** built 22:11:26 Aug 13 2026\n"
- "%s::handleStart: ro=%d nvram=%d helper=%d %s _pmuNub: %p 0x%04x:0x%04x-0x%04x built 22:11:26 Aug 13 2026\n"
- "%s::start: %s _pmuNub: %p ** configuration not found ** built 22:11:27 Aug 13 2026\n"
- "%s::start: %s _pmuNub: %p built 22:11:27 Aug 13 2026\n"
```
