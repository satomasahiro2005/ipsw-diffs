## com.apple.driver.AppleBluetoothModule

> `com.apple.driver.AppleBluetoothModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x7b94` | `0x7d14` | **`+0x180`** |

### Other Changes

```text
Functions:
~ sub_fffffff00893ef90 -> sub_fffffff008986ac0 : 72 -> 76
~ sub_fffffff00893efe0 -> sub_fffffff008986b14 : 52 -> 56
~ sub_fffffff00893f014 -> sub_fffffff008986b4c : 52 -> 56
~ sub_fffffff00893f058 -> sub_fffffff008986b94 : 68 -> 72
~ sub_fffffff00893f0c4 -> sub_fffffff008986c04 : 72 -> 76
~ sub_fffffff00893f10c -> sub_fffffff008986c50 : 104 -> 108
~ sub_fffffff00893f188 -> sub_fffffff008986cd0 : 88 -> 92
~ sub_fffffff00893f1e0 -> sub_fffffff008986d2c : 88 -> 92
~ __ZN20AppleBluetoothModule5startEP9IOService : 2352 -> 2356
~ __ZN20AppleBluetoothModule15initCoreCaptureE16CCStreamLogLevelS0_ : 552 -> 556
~ __ZN20AppleBluetoothModule13setupTimeSyncEP9IOService : 380 -> 384
~ __ZN20AppleBluetoothModule19amfmServiceNotifierEPvP9IOServiceP10IONotifier : 1048 -> 1052
~ __ZN20AppleBluetoothModule23interruptActionTimeSyncEP22IOInterruptEventSourcei : 260 -> 264
~ sub_fffffff008940464 -> sub_fffffff008987fc8 : 72 -> 76
~ sub_fffffff0089404ac -> sub_fffffff008988014 : 144 -> 148
~ sub_fffffff0089405b8 -> sub_fffffff008988124 : 152 -> 156
~ __ZN20AppleBluetoothModule4stopEP9IOService : 948 -> 952
~ sub_fffffff008940a34 -> sub_fffffff0089885a8 : 152 -> 156
~ sub_fffffff008940b1c -> sub_fffffff008988694 : 96 -> 100
~ __ZN20AppleBluetoothModule12quiesceGatedEv : 416 -> 420
~ __ZN20AppleBluetoothModule14unquiesceGatedEv : 384 -> 388
~ __ZN20AppleBluetoothModule11resetWorkerEv : 156 -> 160
~ __ZN20AppleBluetoothModule31setInitialModulePowerStateGatedEv : 380 -> 384
~ sub_fffffff008941158 -> sub_fffffff008988ce4 : 116 -> 120
~ __ZN20AppleBluetoothModule22powerStateWillChangeToEmmP9IOService : 408 -> 412
~ __ZN20AppleBluetoothModule27powerStateWillChangeToGatedEmmP9IOService : 348 -> 352
~ sub_fffffff0089414f4 -> sub_fffffff00898908c : 284 -> 288
~ __ZN20AppleBluetoothModule18setPowerStateGatedEmP9IOService : 504 -> 508
~ __ZN20AppleBluetoothModule20claimAOTExitIfBTWakeEv : 772 -> 776
~ sub_fffffff008941b40 -> sub_fffffff0089896e4 : 272 -> 276
~ sub_fffffff008941cd4 -> sub_fffffff00898987c : 184 -> 188
~ sub_fffffff008941d8c -> sub_fffffff008989938 : 272 -> 276
~ __ZN20AppleBluetoothModule16generateMacGatedEPKc : 500 -> 504
~ sub_fffffff0089420c4 -> sub_fffffff008989c78 : 268 -> 272
~ __ZN20AppleBluetoothModule21pciDriverBlockerGatedEv : 808 -> 812
~ sub_fffffff00894252c -> sub_fffffff00898a0e8 : 272 -> 276
~ sub_fffffff008942694 -> sub_fffffff00898a254 : 272 -> 276
~ __ZN20AppleBluetoothModule8flrGatedEPKc : 1200 -> 1204
~ sub_fffffff008942c88 -> sub_fffffff00898a850 : 284 -> 288
~ __ZN20AppleBluetoothModule16powerModuleGatedEbPKc : 860 -> 864
~ sub_fffffff008943134 -> sub_fffffff00898ad04 : 272 -> 276
~ __ZN20AppleBluetoothModule21powerCycleModuleGatedEPKc : 1460 -> 1464
~ __ZN20AppleBluetoothModule17waitForWiFiDriverEv : 488 -> 492
~ __ZN20AppleBluetoothModule13deepSleepVoteEb : 276 -> 280
~ __ZN20AppleBluetoothModule13setPropertiesEP8OSObject : 1992 -> 1996
~ __ZN20AppleBluetoothModule20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_ : 608 -> 612
~ __ZN20AppleBluetoothModule14copyPrimaryPMUEv : 348 -> 352
~ __ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm : 5360 -> 5364
~ sub_fffffff008945bd4 -> sub_fffffff00898d7c4 : 80 -> 84
~ sub_fffffff008945cc4 -> sub_fffffff00898d8b8 : 72 -> 76
~ sub_fffffff008945d14 -> sub_fffffff00898d90c : 52 -> 56
~ sub_fffffff008945d48 -> sub_fffffff00898d944 : 52 -> 56
~ sub_fffffff008945d8c -> sub_fffffff00898d98c : 68 -> 72
~ sub_fffffff008945df8 -> sub_fffffff00898d9fc : 72 -> 76
~ sub_fffffff008945e40 -> sub_fffffff00898da48 : 104 -> 108
~ sub_fffffff008945ebc -> sub_fffffff00898dac8 : 88 -> 92
~ sub_fffffff008945f14 -> sub_fffffff00898db24 : 88 -> 92
~ __ZN30AppleBluetoothModuleUserClient5startEP9IOService : 176 -> 180
~ sub_fffffff0089461b4 -> sub_fffffff00898ddcc : 148 -> 152
~ sub_fffffff008946248 -> sub_fffffff00898de64 : 332 -> 336
~ sub_fffffff0089463b4 -> sub_fffffff00898dfd4 : 80 -> 84
~ sub_fffffff008946404 -> sub_fffffff00898e028 : 140 -> 144
~ sub_fffffff0089464c8 -> sub_fffffff00898e0f0 : 80 -> 84
~ _panic : 32 -> 36
~ __ZN20AppleBluetoothModule21pciDriverBlockerGatedEv.cold.1 : 44 -> 48
~ __ZN11CCLogStream3logE16CCStreamLogLevelPKcz : 52 -> 56
~ _OUTLINED_FUNCTION_6 : 44 -> 48
~ _OUTLINED_FUNCTION_5 : 44 -> 48
~ sub_fffffff008946684 -> sub_fffffff00898e2c4 : 52 -> 56
~ __ZN20AppleBluetoothModule21powerCycleModuleGatedEPKc.cold.2 : 44 -> 48
~ sub_fffffff0089466e4 -> sub_fffffff00898e32c : 44 -> 48
~ sub_fffffff008946710 -> sub_fffffff00898e35c : 44 -> 48
~ sub_fffffff00894673c -> sub_fffffff00898e38c : 32 -> 36
~ sub_fffffff00894675c -> sub_fffffff00898e3b0 : 32 -> 36
~ __ZN20AppleBluetoothModule13setPropertiesEP8OSObject.cold.1 : 44 -> 48
~ __ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.1 : 44 -> 48
~ __ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.2 : 80 -> 84
~ __ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.3 : 44 -> 48
~ __ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.4 : 44 -> 48
~ _OUTLINED_FUNCTION_7 : 44 -> 48
~ __ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.6 : 44 -> 48
~ sub_fffffff0089468d4 -> sub_fffffff00898e548 : 52 -> 56
~ sub_fffffff008946908 -> sub_fffffff00898e580 : 32 -> 36
~ __ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.9 : 44 -> 48
~ sub_fffffff008946954 -> sub_fffffff00898e5d4 : 32 -> 36
~ sub_fffffff008946974 -> sub_fffffff00898e5f8 : 32 -> 36
~ sub_fffffff008946994 -> sub_fffffff00898e61c : 32 -> 36
~ __ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.13 : 44 -> 48
~ __ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.14 : 44 -> 48
~ sub_fffffff008946a0c -> sub_fffffff00898e6a0 : 44 -> 48
~ sub_fffffff008946a38 -> sub_fffffff00898e6d0 : 32 -> 36
~ sub_fffffff008946a58 -> sub_fffffff00898e6f4 : 52 -> 56
~ __ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.18 : 44 -> 48
~ sub_fffffff008946ab8 -> sub_fffffff00898e75c : 32 -> 36
~ sub_fffffff008946ad8 -> sub_fffffff00898e780 : 32 -> 36
~ __ZN20AppleBluetoothModule23amfmMessageHandlerGatedEjP9IOServicePvm.cold.21 : 44 -> 48
```
