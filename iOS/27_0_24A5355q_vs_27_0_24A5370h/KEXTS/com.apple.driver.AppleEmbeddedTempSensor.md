## com.apple.driver.AppleEmbeddedTempSensor

> `com.apple.driver.AppleEmbeddedTempSensor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x460` | **`+0x460`** |
| `__TEXT_EXEC.__text` | `0x15420` | `0x155cc` | **`+0x1ac`** |

### Other Changes

```text
Functions:
~ __ZN23AppleT8020MTRTempSensor21_timeoutOccurredGatedEP8OSObjectP18IOTimerEventSource : 1132 -> 1184
~ __ZN19ApplePMGRTempSensor5startEP9IOService : 3912 -> 3956
~ sub_fffffff008b99274 -> sub_fffffff008bb6a34 : 472 -> 492
~ __ZN22AppleDieTempController14handleBootArgsEv : 1160 -> 1176
~ __ZN22AppleDieTempController16printLoopConfigsEv : 320 -> 316
~ __ZN22AppleDieTempController21loopTimerHandlerGatedEP18IOTimerEventSource : 928 -> 948
~ __ZN22AppleDieTempController31calculateLoopMaxDieTemperaturesEv : 472 -> 468
~ sub_fffffff008b9b06c -> sub_fffffff008bb885c : 104 -> 120
~ __ZN22AppleDieTempController22registerSensorInstanceEP9IOServiceij : 452 -> 448
~ __ZN22AppleDieTempController18setPropertiesGatedEP8OSObject : 1424 -> 1444
~ sub_fffffff008b9c190 -> sub_fffffff008bb99a0 : 56 -> 84
~ sub_fffffff008b9c1c8 -> sub_fffffff008bb99f4 : 76 -> 104
~ sub_fffffff008b9c704 -> sub_fffffff008bb9f4c : 40 -> 48
~ __ZN11AppleSocHot5startEP9IOService : 5188 -> 5232
~ sub_fffffff008ba1c38 -> sub_fffffff008bbf4b4 : 324 -> 336
~ __ZN23AppleT8020MTRTempSensor5startEP9IOService : 2516 -> 2560
~ __ZN20AppleT700XTempSensor5startEP9IOService : 5948 -> 5992
~ __ZN20AppleT8015TempSensor5startEP9IOService : 6620 -> 6664
```
