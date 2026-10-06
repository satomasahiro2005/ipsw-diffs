## com.apple.driver.AppleH16CameraInterface

> `com.apple.driver.AppleH16CameraInterface`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x10d0` | **`+0x10d0`** |
| `__TEXT_EXEC.__text` | `0x9a698` | `0x9ae74` | **`+0x7dc`** |

### Other Changes

```diff

-6.10.3.0.0
+6.12.2.0.0
Functions:
~ sub_fffffff008d78c9c -> sub_fffffff008d9de7c : 248 -> 272
~ __ZN23AppleExclaveCameraProxy5startEP9IOService : 1536 -> 1552
~ __ZN15H16CamInChannel12EnableSensorEv : 400 -> 448
~ __ZN15H16CamInChannel13DisableSensorEv : 428 -> 512
~ __ZN13AppleH16CamIn10ispCmdSendEPvjPjjbyjbb : 3568 -> 3548
~ __ZN15H16CamInChannel23SendDatafilesToFirmwareEv : 832 -> 888
~ sub_fffffff008d7f7e4 -> sub_fffffff008da4a94 : 4656 -> 4708
~ sub_fffffff008d80a1c -> sub_fffffff008da5d00 : 7008 -> 7036
~ sub_fffffff008d8257c -> sub_fffffff008da787c : 7008 -> 7036
~ sub_fffffff008d841ec -> sub_fffffff008da9508 : 4676 -> 4728
~ sub_fffffff008d854d0 -> sub_fffffff008daa820 : 64 -> 80
~ sub_fffffff008d85510 -> sub_fffffff008daa870 : 64 -> 72
~ __ZN13AppleH16CamIn26H16ISPSharedMemorySurfaces15allocateSurfaceEyPP31H16ISPSharedMemorySurfaceParamsbjbjb : 3752 -> 3748
~ __ZN13AppleH16CamIn37ISP_ShowSharedMemoryAllocations_gatedEby : 19464 -> 19256
~ __ZN13AppleH16CamIn28ReleaseFirmwareWorkProcessorEP8ipc_port : 2752 -> 2948
~ __ZN13AppleH16CamIn21HandleFirmwareTimeoutEht : 1484 -> 1508
~ __ZN13AppleH16CamIn27ISP_InitializeSoCParametersE13H16ISPVersionjj : 23612 -> 23592
~ __ZN13AppleH16CamIn28ISP_InitializeClassVariablesEv : 4836 -> 4840
~ __ZN13AppleH16CamIn18setPowerStateGatedEmP9IOService : 14228 -> 14272
~ __ZL24DARTErrorHandlerCallbackPvPK15IODARTErrorInfo : 2380 -> 2372
~ __ZN13AppleH16CamIn15mapFwCTRRRegionEv : 7168 -> 7264
~ __ZN13AppleH16CamIn18power_off_hardwareEbb : 2804 -> 2836
~ __ZN13AppleH16CamIn17power_on_hardwareEb : 3392 -> 3408
~ __ZN13AppleH16CamIn24ISP_ForgetFirmware_gatedEv : 1568 -> 1576
~ __ZN13AppleH16CamIn4stopEP9IOService : 888 -> 900
~ __ZN13AppleH16CamIn28processTargetToHostIOCommandEyyyPv : 8576 -> 8844
~ __ZN13AppleH16CamIn22ISP_ScheduleWork_gatedER44AppleH16CamInFirmwareWorkProcessorRPCRequest : 1200 -> 1232
~ __ZN18McacheDriverClient18mcacheEnableStreamE14MCDataStreamIdj : 292 -> 304
~ __ZN13AppleH16CamIn37processTargetToHostBufferNotificationEyyyPv : 2924 -> 2956
~ __ZN13AppleH16CamIn30EnableSensorRefClockForChannelEj : 1248 -> 1272
~ __ZN13AppleH16CamIn31DisableSensorRefClockForChannelEj : 1176 -> 1200
~ __ZN13AppleH16CamIn29InitializeAOPMotionDataParamsEv : 2264 -> 2152
~ __ZN13AppleH16CamIn16MotionDataEnableEv : 692 -> 720
~ __ZN13AppleH16CamIn25ISP_LoadOverrideNVM_gatedEP27H16ISPLoadOverrideNVMParamsb : 2016 -> 2020
~ __ZN13AppleH16CamIn11ISP_SuspendEb : 9560 -> 9672
~ __ZN13AppleH16CamIn32EnableISPCPUMotionDataProcessingEv : 316 -> 328
~ __ZN13AppleH16CamIn17MotionDataDisableEv : 568 -> 604
~ __ZN13AppleH16CamIn16ISP_ResetTlimitsEb : 1644 -> 1636
~ __ZN18McacheDriverClient21powerOffMcacheRequestEv : 488 -> 492
~ __ZN13AppleH16CamIn11ISP_I2CInitEj : 524 -> 528
~ __ZN13AppleH16CamIn11ISP_I2CReadEjjjjPjj : 1112 -> 1096
~ __ZN13AppleH16CamIn25ISP_UserClientClose_gatedEPv19H16ISPClientProcessbb : 2044 -> 2096
~ __ZN13AppleH16CamIn20ISP_StopCamera_gatedEj : 1076 -> 1096
~ __ZN13AppleH16CamIn10ISP_deInitEv : 840 -> 836
~ __ZN13AppleH16CamIn21ISP_SendBuffers_gatedEP26H16ISPSendBufferArgsStructjP12IOUserClientPy : 3328 -> 3344
~ __ZN13AppleH16CamIn21ISP_StartCamera_gatedEj : 824 -> 840
~ __ZL13_LogKeyBufferPKcPKhm : 296 -> 304
~ __ZN13AppleH16CamIn26ISP_SecureCheckRPCCommandsER44AppleH16CamInFirmwareWorkProcessorRPCRequest : 308 -> 332
~ sub_fffffff008dc12a4 -> sub_fffffff008de6918 : 172 -> 176
~ sub_fffffff008dc160c -> sub_fffffff008de6c84 : 3620 -> 3636
~ sub_fffffff008dc2430 -> sub_fffffff008de7ab8 : 1308 -> 1260
~ sub_fffffff008dc2a70 -> sub_fffffff008de80c8 : 176 -> 180
~ __ZN13AppleH16CamIn38ISP_SelectBestMIPIFrequencyIndex_gatedEjPj : 484 -> 488
~ sub_fffffff008dc2e0c -> sub_fffffff008de846c : 324 -> 332
~ sub_fffffff008dc3298 -> sub_fffffff008de8900 : 260 -> 264
~ sub_fffffff008dc33f8 -> sub_fffffff008de8a64 : 260 -> 264
~ __ZN13AppleH16CamIn34ISP_CreateMultiCameraSession_gatedEPvP30H16ISPMultiCameraSessionStruct : 3208 -> 3308
~ sub_fffffff008dc54e8 -> sub_fffffff008deabbc : 1052 -> 1060
~ __ZN13AppleH16CamIn38ISP_GetFirmwareWorkProcessorItem_gatedEPyPvjP4task : 2544 -> 2628
~ sub_fffffff008dc75fc -> sub_fffffff008decd2c : 1928 -> 2052
~ sub_fffffff008dc8028 -> sub_fffffff008ded7d4 : 688 -> 740
~ sub_fffffff008dc8330 -> sub_fffffff008dedb10 : 668 -> 784
~ __ZN13AppleH16CamIn32ISP_GeneralProcess_Generic_gatedEP37H16ISPGeneralProcessGenericArgsStructP12IOUserClientPy : 8372 -> 8156
~ __ZN13AppleH16CamIn24ISP_GeneralProcess_gatedEP30H16ISPGeneralProcessArgsStructP12IOUserClientPy : 9964 -> 9852
~ __ZN13AppleH16CamIn31ISP_GeneralProcessBuffers_gatedEP37H16ISPGeneralProcessBuffersArgsStructP12IOUserClientPy : 10356 -> 10372
~ __ZN13AppleH16CamIn16ISP_ConfigureSACEjjP12ISPSACParamsj : 1488 -> 1480
~ __ZN13AppleH16CamIn26ISP_ConfigureChargePumpSACEjP12ISPSACParams : 1088 -> 1064
~ __ZN13AppleH16CamIn24ISP_ConfigurePixClockSACEjP12ISPSACParams : 1088 -> 1056
~ sub_fffffff008dd2e90 -> sub_fffffff008df856c : 1224 -> 1256
~ __ZN13AppleH16CamIn26ISP_InitialSensorDetectionEv : 12324 -> 12372
~ __ZN13AppleH16CamIn22ISP_LoadDataFile_gatedEP24H16ISPLoadDataFileParams : 2792 -> 2820
~ __ZN13AppleH16CamIn28ISP_LoadIspAneAFPPFile_gatedEP23H16ISPANEAFPPFileParams : 2704 -> 2708
~ __ZN13AppleH16CamIn23AllocateFwMemorySurfaceEjj : 2300 -> 2296
~ sub_fffffff008ddb408 -> sub_fffffff008e00b50 : 276 -> 272
~ sub_fffffff008ddba4c -> sub_fffffff008e01190 : 164 -> 172
~ sub_fffffff008ddc00c -> sub_fffffff008e01758 : 736 -> 756
~ sub_fffffff008ddc5a0 -> sub_fffffff008e01d00 : 684 -> 676
~ __ZN13AppleH16CamIn21drainEndpointsMessageEv : 676 -> 672
~ __ZN13AppleH16CamIn18ISP_ResumeFirmwareEv : 2208 -> 2204
~ __ZN13AppleH16CamIn17ISP_StartFirmwareEv : 10164 -> 10232
~ __ZN13AppleH16CamIn33ISP_GeneralFirmwareInitializationEb : 2012 -> 2016
~ __ZN13AppleH16CamIn41ISP_ChannelSpecificFirmwareInitializationEjb : 1444 -> 1552
~ __ZN13AppleH16CamIn26ReleaseFwHeapMemorySurfaceEv : 216 -> 212
~ __ZN18IspAneIPCEndPoints19enableFWIPCEP_gatedE19AneIspEndpointIndexb : 984 -> 1012
~ sub_fffffff008de6284 -> sub_fffffff008e0baa0 : 120 -> 124
~ __ZN18McacheDriverClient20findStreamObjectByIDE14MCDataStreamId : 412 -> 408
~ sub_fffffff008dee0e0 -> sub_fffffff008e138fc : 628 -> 664
~ sub_fffffff008dee3e8 -> sub_fffffff008e13c28 : 204 -> 228
~ sub_fffffff008dee5b0 -> sub_fffffff008e13e08 : 136 -> 148
~ sub_fffffff008dee65c -> sub_fffffff008e13ec0 : 632 -> 724
~ sub_fffffff008dee8d4 -> sub_fffffff008e14194 : 36 -> 68
~ sub_fffffff008dee8f8 -> sub_fffffff008e141d8 : 76 -> 80
~ sub_fffffff008dee944 -> sub_fffffff008e14228 : 44 -> 48
~ sub_fffffff008dee9a4 -> sub_fffffff008e1428c : 180 -> 208
~ sub_fffffff008deeaf4 -> sub_fffffff008e143f8 : 76 -> 80
~ sub_fffffff008deeb40 -> sub_fffffff008e14448 : 168 -> 188
~ sub_fffffff008deebe8 -> sub_fffffff008e14504 : 44 -> 72
~ sub_fffffff008deecd0 -> sub_fffffff008e14608 : 44 -> 48
~ sub_fffffff008deecfc -> sub_fffffff008e14638 : 44 -> 48
~ sub_fffffff008deeea0 -> sub_fffffff008e147e0 : 56 -> 48
~ sub_fffffff008deef54 -> sub_fffffff008e1488c : 180 -> 188
~ sub_fffffff008deffe0 -> sub_fffffff008e15920 : 96 -> 92
~ sub_fffffff008dfe784 -> sub_fffffff008e240c0 : 5708 -> 5704
~ sub_fffffff008e01834 -> sub_fffffff008e2716c : 10968 -> 10976
~ sub_fffffff008e06814 -> sub_fffffff008e2c154 : 332 -> 336
~ sub_fffffff008e06960 -> sub_fffffff008e2c2a4 : 2448 -> 2524
~ sub_fffffff008e0a8f0 -> sub_fffffff008e30280 : 2548 -> 2544
~ sub_fffffff008e0be94 -> sub_fffffff008e31820 : 196 -> 188
~ sub_fffffff008e0bf6c -> sub_fffffff008e318f0 : 132 -> 124
~ sub_fffffff008e0cd84 -> sub_fffffff008e32700 : 404 -> 420
~ __ZN26AppleH16CamInFrameReceiver25ReFillFirmwareBufferPoolsEb : 1176 -> 1224
```
