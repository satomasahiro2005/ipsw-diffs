## com.apple.driver.AppleUSBXDCI

> `com.apple.driver.AppleUSBXDCI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x570` | **`+0x570`** |
| `__TEXT_EXEC.__text` | `0x1ec84` | `0x1eeac` | **`+0x228`** |

### Other Changes

```diff

-891.0.0.0.0
+896.0.0.0.0
Functions:
~ sub_fffffff00a4dc190 -> sub_fffffff00a56ca00 : 144 -> 164
~ sub_fffffff00a4de2cc -> sub_fffffff00a56eb50 : 232 -> 228
~ __ZN12AppleUSBXDCI26setEndpointAllocationOrderEv : 448 -> 440
~ sub_fffffff00a4deff4 -> sub_fffffff00a56f86c : 280 -> 292
~ __ZN12AppleUSBXDCI17startIsocEndpointEi : 444 -> 512
~ __ZN12AppleUSBXDCI16activateEndpointEiiii33tIOUSBDeviceInterfacePipeProperty : 3520 -> 3568
~ __ZN12AppleUSBXDCI7goOnBusEb : 6112 -> 6116
~ __ZN12AppleUSBXDCI18filterOccurredIsocEP28IOFilterInterruptEventSource : 2612 -> 2756
~ __ZN12AppleUSBXDCI16applyTunablesTagEyPKc : 1196 -> 1208
~ __ZN12AppleUSBXDCI16applySDBTunablesEP11IOMemoryMapjPKc : 2892 -> 3016
~ __ZN12AppleUSBXDCI20initDeviceControllerEv : 4300 -> 4304
~ __ZN12AppleUSBXDCI20stopDeviceControllerEv : 2372 -> 2376
~ __ZN12AppleUSBXDCI34provideEndpointIDsForConfigurationEP7OSArrayPh : 2144 -> 2136
~ __ZN12AppleUSBXDCI32isocXferInProgressFilterOccurredEPN7USBXDCI9tEventTRBEy : 928 -> 1020
~ _panic : 92 -> 120
~ __ZN12AppleUSBXDCI23scheduleNextIsocRequestEP20AppleUSBXDCIEndpoint : 968 -> 964
~ __ZN20AppleUSBXDCIEndpoint28initWithControllerAndOptionsEP21IOUSBDeviceControllerhhtjjb33tIOUSBDeviceInterfacePipePropertyjP8IOMapper : 2236 -> 2240
~ sub_fffffff00a4f76b0 -> sub_fffffff00a58813c : 200 -> 212
```
