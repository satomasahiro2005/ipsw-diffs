## com.apple.iokit.AppleARMIISAudio

> `com.apple.iokit.AppleARMIISAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x15c8c` | `0x15fc0` | **`+0x334`** |
| `__TEXT_EXEC.__auth_stubs` | `0x610` | `0x630` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x308` | `0x318` | **`+0x10`** |

### Other Changes

```text
Functions:
~ sub_fffffff008590c20 -> sub_fffffff0085c80f0 : 144 -> 148
~ sub_fffffff008590cd8 -> sub_fffffff0085c81ac : 300 -> 304
~ sub_fffffff008590e0c -> sub_fffffff0085c82e4 : 144 -> 148
~ sub_fffffff008590e9c -> sub_fffffff0085c8378 : 144 -> 148
~ sub_fffffff008590f2c -> sub_fffffff0085c840c : 64 -> 68
~ sub_fffffff008590f6c -> sub_fffffff0085c8450 : 100 -> 104
~ sub_fffffff00859103c -> sub_fffffff0085c8524 : 72 -> 76
~ sub_fffffff00859108c -> sub_fffffff0085c8578 : 60 -> 64
~ sub_fffffff0085910c8 -> sub_fffffff0085c85b8 : 60 -> 64
~ sub_fffffff008591114 -> sub_fffffff0085c8608 : 68 -> 72
~ sub_fffffff008591180 -> sub_fffffff0085c8678 : 72 -> 76
~ sub_fffffff0085911c8 -> sub_fffffff0085c86c4 : 112 -> 116
~ sub_fffffff00859124c -> sub_fffffff0085c874c : 96 -> 100
~ sub_fffffff0085912ac -> sub_fffffff0085c87b0 : 96 -> 100
~ __ZN22AppleARMIISAudioDevice4initEP12OSDictionaryj : 472 -> 476
~ sub_fffffff008591518 -> sub_fffffff0085c8a24 : 540 -> 544
~ __ZN22AppleARMIISAudioDevice5startEP9IOServiceP17AppleARMIISDevicejjxPK7OSArray : 2332 -> 2336
~ __ZN22AppleARMIISAudioDevice28_initExternalPowerDependencyEP9IOService : 864 -> 868
~ sub_fffffff0085923f8 -> sub_fffffff0085c9910 : 324 -> 328
~ sub_fffffff00859253c -> sub_fffffff0085c9a58 : 120 -> 124
~ __ZN22AppleARMIISAudioDevice22setTransportSampleRateEx : 172 -> 176
~ sub_fffffff008592928 -> sub_fffffff0085c9e4c : 212 -> 216
~ sub_fffffff0085929fc -> sub_fffffff0085c9f24 : 160 -> 164
~ __ZN22AppleARMIISAudioDevice18setTransportFormatEjjjj : 1128 -> 1132
~ __ZN22AppleARMIISAudioDevice22setTransportDataFormatEjN22AppleARMDMAAudioDevice14DataFormatTypeE : 844 -> 848
~ sub_fffffff008593284 -> sub_fffffff0085ca7b8 : 156 -> 160
~ sub_fffffff008593320 -> sub_fffffff0085ca858 : 464 -> 468
~ sub_fffffff0085934f0 -> sub_fffffff0085caa2c : 84 -> 88
~ sub_fffffff008593544 -> sub_fffffff0085caa84 : 124 -> 128
~ _panic : 144 -> 148
~ __ZN22AppleARMIISAudioDevice19getTransportLatencyEj : 140 -> 144
~ sub_fffffff0085936dc -> sub_fffffff0085cac28 : 124 -> 128
~ __ZN22AppleARMIISAudioDevice14startTransportEPKP18IOMemoryDescriptorPKjPKyS7_ : 1124 -> 1128
~ __ZN22AppleARMIISAudioDevice12transferDataEjP18IOMemoryDescriptorPvjyy : 716 -> 720
~ __ZN22AppleARMIISAudioDevice12stopTransferEjj : 412 -> 416
~ __ZN22AppleARMIISAudioDevice16getBytesPerFrameEjj : 276 -> 280
~ __ZN22AppleARMIISAudioDevice25stopAudioAndDataTransfersEv : 1260 -> 1264
~ __ZN22AppleARMIISAudioDevice18setAudioSampleRateExjj : 272 -> 276
~ __ZN22AppleARMIISAudioDevice21setAudioStreamFormatsExPK7OSArray : 1188 -> 1192
~ __ZN22AppleARMIISAudioDevice16gangAudioDevicesEPS_b : 780 -> 784
~ __ZN22AppleARMIISAudioDevice9waitAwakeEv : 1120 -> 1124
~ sub_fffffff00859551c -> sub_fffffff0085cca90 : 336 -> 340
~ sub_fffffff00859566c -> sub_fffffff0085ccbe4 : 172 -> 176
~ sub_fffffff0085957c0 -> sub_fffffff0085ccd3c : 172 -> 176
~ sub_fffffff00859586c -> sub_fffffff0085ccdec : 160 -> 164
~ sub_fffffff00859590c -> sub_fffffff0085cce90 : 188 -> 192
~ sub_fffffff0085959c8 -> sub_fffffff0085ccf50 : 172 -> 176
~ sub_fffffff008595a74 -> sub_fffffff0085cd000 : 188 -> 192
~ __ZN22AppleARMIISAudioDevice17createIOReportersEPK7OSArray : 1320 -> 1324
~ sub_fffffff0085962e8 -> sub_fffffff0085cd87c : 196 -> 200
~ sub_fffffff0085963ac -> sub_fffffff0085cd944 : 332 -> 336
~ sub_fffffff0085964f8 -> sub_fffffff0085cda94 : 128 -> 132
~ __ZN22AppleARMIISAudioDevice19createDebugControlsEP7OSArray : 428 -> 432
~ __ZN14IISAudioDevice6Helper8Delegate19createDebugControlsEP22AppleARMIISAudioDevice : 496 -> 500
~ sub_fffffff008596920 -> sub_fffffff0085cdec8 : 152 -> 156
~ sub_fffffff0085969cc -> sub_fffffff0085cdf78 : 80 -> 84
~ __ZN14IISAudioDevice6Helper8Delegate19createDebugControlsEP22AppleARMIISAudioDevice : 440 -> 444
~ __ZN14IISAudioDevice6Helper22processConfigOverridesEP15IORegistryEntryS2_RN22AppleARMDMAAudioDevice15OverrideConfigsE : 428 -> 432
~ sub_fffffff008596f0c -> sub_fffffff0085ce4c4 : 72 -> 76
~ sub_fffffff008596f5c -> sub_fffffff0085ce518 : 60 -> 64
~ sub_fffffff008596fb0 -> sub_fffffff0085ce570 : 72 -> 76
~ sub_fffffff008597030 -> sub_fffffff0085ce5f4 : 104 -> 108
~ sub_fffffff008597098 -> sub_fffffff0085ce660 : 144 -> 148
~ __ZN22AppleARMDMAAudioDevice27_setSafetyOffsetSeedDivisorEP9IOService : 236 -> 240
~ __ZN22AppleARMDMAAudioDevice14setAudioFormatEjjjj : 672 -> 676
~ __ZN22AppleARMDMAAudioDevice18checkDMACompletionEP18IOTimerEventSource : 424 -> 428
~ __ZN22AppleARMDMAAudioDevice5startEP9IOServicexjjPKjS3_S3_ : 440 -> 444
~ __ZN22AppleARMDMAAudioDevice18setAudioSampleRateEx : 884 -> 888
~ __ZN22AppleARMDMAAudioDevice21setAudioStreamFormatsEPK7OSArrayxPKS2_PKNS_14DataFormatTypeES4_PKjS4_S9_S4_S9_ : 4668 -> 4672
~ sub_fffffff008598dd0 -> sub_fffffff0085d03b4 : 308 -> 312
~ sub_fffffff008598f04 -> sub_fffffff0085d04ec : 612 -> 616
~ sub_fffffff008599168 -> sub_fffffff0085d0754 : 116 -> 120
~ sub_fffffff008599208 -> sub_fffffff0085d07f8 : 68 -> 72
~ sub_fffffff00859924c -> sub_fffffff0085d0840 : 132 -> 136
~ sub_fffffff0085992d0 -> sub_fffffff0085d08c8 : 168 -> 172
~ __ZN22AppleARMDMAAudioDevice18startIOEngineGatedEv : 500 -> 504
~ __ZN22AppleARMDMAAudioDevice21startIOEngineInternalEb : 544 -> 548
~ sub_fffffff00859978c -> sub_fffffff0085d0d90 : 196 -> 200
~ __ZN22AppleARMDMAAudioDevice16startDMAInternalEb : 1328 -> 1332
~ __ZN22AppleARMDMAAudioDevice16restartTransportEv : 448 -> 452
~ __ZN22AppleARMDMAAudioDevice18startDataTransfersEjP18IOMemoryDescriptorjyy : 1436 -> 1440
~ __ZN22AppleARMDMAAudioDevice10sendBufferEjP18IOMemoryDescriptorjyy : 1940 -> 1944
~ __ZN22AppleARMDMAAudioDevice18startIOEngineGatedEv.cold.1 : 168 -> 172
~ __ZN22AppleARMDMAAudioDevice17stopIOEngineGatedEv : 860 -> 864
~ __ZN22AppleARMDMAAudioDevice20stopIOEngineInternalEv : 612 -> 616
~ sub_fffffff00859b4d0 -> sub_fffffff0085d2af4 : 292 -> 296
~ __ZN22AppleARMDMAAudioDevice15setStreamActiveEjj : 492 -> 496
~ __ZN22AppleARMDMAAudioDevice20setStreamActiveGatedEjj : 1512 -> 1516
~ __ZN22AppleARMDMAAudioDevice22handleChangeSampleRateEPxy : 564 -> 568
~ __ZN22AppleARMDMAAudioDevice24handleChangeStreamFormatEjP30IOAudio2StreamBasicDescriptiony : 852 -> 856
~ __ZN22AppleARMDMAAudioDevice19performConfigChangeEP20IOAudio2Notification : 560 -> 564
~ __ZN22AppleARMDMAAudioDevice24performConfigChangeGatedEP20IOAudio2Notification : 716 -> 720
~ sub_fffffff00859cbe0 -> sub_fffffff0085d4220 : 300 -> 304
~ __ZN22AppleARMDMAAudioDevice23performSampleRateChangeEPKx : 820 -> 824
~ __ZN22AppleARMDMAAudioDevice25performStreamFormatChangeEjjPKx : 1708 -> 1712
~ sub_fffffff00859d6ec -> sub_fffffff0085d4d38 : 292 -> 296
~ sub_fffffff00859d810 -> sub_fffffff0085d4e60 : 376 -> 380
~ __ZN22AppleARMDMAAudioDevice20setAudioStreamFormatEjNS_14DataFormatTypeEjjj : 1724 -> 1728
~ sub_fffffff00859e068 -> sub_fffffff0085d56c0 : 124 -> 128
~ __ZNK22AppleARMDMAAudioDevice34getStreamFormatSupportedSampleRateExjj : 1028 -> 1032
~ sub_fffffff00859e4f4 -> sub_fffffff0085d5b54 : 184 -> 188
~ __ZN22AppleARMDMAAudioDevice25getAudioStreamDescriptionEjxNS_14DataFormatTypeEjjj : 264 -> 268
~ sub_fffffff00859e6fc -> sub_fffffff0085d5d64 : 112 -> 116
~ __ZN22AppleARMDMAAudioDevice14completeBufferEPviyy : 1556 -> 1560
~ sub_fffffff00859ed80 -> sub_fffffff0085d63f0 : 348 -> 352
~ __ZN22AppleARMDMAAudioDevice15updateTimestampEyy : 1072 -> 1076
~ __ZN22AppleARMDMAAudioDevice15allocateBuffersEv : 1732 -> 1736
~ __ZN22AppleARMDMAAudioDevice20_addUserSafetyOffsetERji : 460 -> 464
~ __ZN22AppleARMDMAAudioDevice22getTransportBufferSizeEx : 416 -> 420
~ sub_fffffff00859fd3c -> sub_fffffff0085d73c0 : 940 -> 944
~ __ZN22AppleARMDMAAudioDevice28setAudioStreamFormatInternalEjNS_14DataFormatTypeEjjjP12OSDictionaryS2_ : 936 -> 940
~ __ZN22AppleARMDMAAudioDevice16gangAudioDevicesEPS_b : 456 -> 460
~ sub_fffffff0085a06e8 -> sub_fffffff0085d7d78 : 168 -> 172
~ __ZN22AppleARMDMAAudioDevice25zeroFillBufferForStreamIDEj : 396 -> 400
~ sub_fffffff0085a0930 -> sub_fffffff0085d7fc8 : 128 -> 132
~ sub_fffffff0085a09b0 -> sub_fffffff0085d804c : 128 -> 132
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray : 1984 -> 1988
~ sub_fffffff0085a11f0 -> sub_fffffff0085d8894 : 432 -> 436
~ __ZN22AppleARMDMAAudioDevice28_computeSafetyOffsetDivisorsEiRi : 320 -> 324
~ sub_fffffff0085a1500 -> sub_fffffff0085d8bac : 80 -> 84
~ __ZN32AppleAudioStreamFormatterFactory31createAppleAudioStreamFormatterEP9IOServiceP6OSData : 444 -> 448
~ __ZN22AppleARMIISAudioDevice18setupForIsolatedIOEjyj : 416 -> 420
~ sub_fffffff0085a1b54 -> sub_fffffff0085d920c : 68 -> 72
~ __ZN22AppleARMIISAudioDevice13stopTransportEv : 428 -> 432
~ __ZN22AppleARMIISAudioDevice28_initExternalPowerDependencyEP9IOService.cold.1 : 108 -> 112
~ __ZN22AppleARMIISAudioDevice22setTransportSampleRateEx.cold.1 : 320 -> 324
~ __ZN22AppleARMIISAudioDevice18setTransportFormatEjjjj.cold.1 : 300 -> 304
~ __ZN22AppleARMIISAudioDevice23getIISControllerLatencyEj.cold.1 : 112 -> 116
~ __ZN22AppleARMIISAudioDevice19getTransportLatencyEj.cold.1 : 104 -> 108
~ sub_fffffff0085a20f4 -> sub_fffffff0085d97c8 : 248 -> 252
~ __ZN22AppleARMIISAudioDevice14startTransportEPKP18IOMemoryDescriptorPKjPKyS7_.cold.2 : 248 -> 252
~ __ZN22AppleARMIISAudioDevice14startTransportEPKP18IOMemoryDescriptorPKjPKyS7_.cold.3 : 248 -> 252
~ __ZN22AppleARMIISAudioDevice14startTransportEPKP18IOMemoryDescriptorPKjPKyS7_.cold.4 : 248 -> 252
~ __ZN22AppleARMIISAudioDevice14startTransportEPKP18IOMemoryDescriptorPKjPKyS7_.cold.5 : 248 -> 252
~ __ZN22AppleARMIISAudioDevice14startTransportEPKP18IOMemoryDescriptorPKjPKyS7_.cold.6 : 184 -> 188
~ sub_fffffff0085a2684 -> sub_fffffff0085d9d70 : 248 -> 252
~ __ZN22AppleARMIISAudioDevice14startTransportEPKP18IOMemoryDescriptorPKjPKyS7_.cold.8 : 248 -> 252
~ __ZN22AppleARMIISAudioDevice14startTransportEPKP18IOMemoryDescriptorPKjPKyS7_.cold.9 : 340 -> 344
~ __ZN22AppleARMIISAudioDevice14startTransportEPKP18IOMemoryDescriptorPKjPKyS7_.cold.10 : 288 -> 292
~ __ZN22AppleARMIISAudioDevice16getBytesPerFrameEjj.cold.1 : 44 -> 48
~ __ZN22AppleARMIISAudioDevice18setAudioSampleRateExjj.cold.1 : 372 -> 376
~ __ZN22AppleARMIISAudioDevice9waitAwakeEv.cold.1 : 88 -> 92
~ __ZN22AppleARMIISAudioDevice17createIOReportersEPK7OSArray.cold.1 : 300 -> 304
~ __ZN22AppleARMIISAudioDevice17createIOReportersEPK7OSArray.cold.2 : 264 -> 268
~ __ZN22AppleARMIISAudioDevice17createIOReportersEPK7OSArray.cold.3 : 264 -> 268
~ __ZN22AppleARMIISAudioDevice17createIOReportersEPK7OSArray.cold.4 : 264 -> 268
~ __ZN22AppleARMIISAudioDevice17createIOReportersEPK7OSArray.cold.5 : 264 -> 268
~ __ZN22AppleARMIISAudioDevice17createIOReportersEPK7OSArray.cold.6 : 264 -> 268
~ __ZN22AppleARMIISAudioDevice17createIOReportersEPK7OSArray.cold.7 : 264 -> 268
~ __ZN22AppleARMIISAudioDevice17createIOReportersEPK7OSArray.cold.8 : 264 -> 268
~ __ZN22AppleARMIISAudioDevice17createIOReportersEPK7OSArray.cold.9 : 264 -> 268
~ __ZN22AppleARMIISAudioDevice17createIOReportersEPK7OSArray.cold.10 : 272 -> 276
~ __ZN14IISAudioDevice6Helper8Delegate19createDebugControlsEP22AppleARMIISAudioDevice.cold.2 : 64 -> 68
~ __ZN14IISAudioDevice6Helper8Delegate19createDebugControlsEP22AppleARMIISAudioDevice.cold.3 : 64 -> 68
~ __ZN14IISAudioDevice6Helper22processConfigOverridesEP15IORegistryEntryS2_RN22AppleARMDMAAudioDevice15OverrideConfigsE.cold.1 : 64 -> 68
~ __ZN14IISAudioDevice6Helper22processConfigOverridesEP15IORegistryEntryS2_RN22AppleARMDMAAudioDevice15OverrideConfigsE.cold.2 : 64 -> 68
~ __ZN22AppleARMDMAAudioDevice4initEP12OSDictionary : 336 -> 340
~ __ZN22AppleARMDMAAudioDevice13startInternalEP9IOServicexjPKjS3_S3_S3_ : 1188 -> 1232
~ _snprintf : 528 -> 532
~ __ZN22AppleARMDMAAudioDevice5startEP9IOServicexjPKjS3_S3_S3_ : 620 -> 624
~ __ZN22AppleARMDMAAudioDevice5startEP9IOServicePK7OSArrayxjPKjPKS4_PKNS_14DataFormatTypeES8_S6_S8_S6_S8_S6_ : 940 -> 944
~ __ZN22AppleARMDMAAudioDevice12transferDataEjP18IOMemoryDescriptorPvjyy : 80 -> 84
~ __ZN22AppleARMDMAAudioDevice12stopTransferEjj : 80 -> 84
~ __ZN22AppleARMDMAAudioDevice27_setSafetyOffsetSeedDivisorEP9IOService.cold.1 : 172 -> 176
~ __ZN22AppleARMDMAAudioDevice27_setSafetyOffsetSeedDivisorEP9IOService.cold.2 : 180 -> 184
~ __ZN22AppleARMDMAAudioDevice14setAudioFormatEjjjj.cold.1 : 104 -> 108
~ __ZN22AppleARMDMAAudioDevice18startIOEngineGatedEv.cold.1 : 288 -> 292
~ __ZN22AppleARMDMAAudioDevice18startIOEngineGatedEv.cold.2 : 288 -> 292
~ __ZN22AppleARMDMAAudioDevice10sendBufferEjP18IOMemoryDescriptorjyy.cold.1 : 384 -> 388
~ __ZN22AppleARMDMAAudioDevice15allocateBuffersEv.cold.1 : 88 -> 92
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.1 : 272 -> 276
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.2 : 272 -> 276
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.3 : 272 -> 276
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.4 : 272 -> 276
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.5 : 272 -> 276
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.6 : 284 -> 288
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.7 : 272 -> 276
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.8 : 272 -> 276
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.9 : 272 -> 276
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.10 : 284 -> 288
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.11 : 272 -> 276
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.12 : 284 -> 288
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.13 : 272 -> 276
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.14 : 284 -> 288
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.15 : 272 -> 276
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.16 : 284 -> 288
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.17 : 284 -> 288
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.18 : 284 -> 288
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.19 : 284 -> 288
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.20 : 284 -> 288
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.21 : 284 -> 288
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.22 : 284 -> 288
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.23 : 284 -> 288
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.24 : 284 -> 288
~ __ZN22AppleARMDMAAudioDevice17createIOReportersEPK7OSArray.cold.25 : 284 -> 288
```
