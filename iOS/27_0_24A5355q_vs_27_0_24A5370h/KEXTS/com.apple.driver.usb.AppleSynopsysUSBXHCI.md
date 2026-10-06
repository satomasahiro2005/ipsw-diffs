## com.apple.driver.usb.AppleSynopsysUSBXHCI

> `com.apple.driver.usb.AppleSynopsysUSBXHCI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x5e0` | **`+0x5e0`** |
| `__TEXT_EXEC.__text` | `0x41420` | `0x41598` | **`+0x178`** |

### Other Changes

```diff

-714.0.0.0.0
+716.0.0.0.0
Functions:
~ __ZN15AppleUSBXHCIARM24waitForExternalResourcesEv : 1500 -> 1532
~ __ZN15AppleUSBXHCIARM13applyTunablesEP6OSData : 1904 -> 1956
~ _panic : 2856 -> 2916
~ __ZN23AppleSynopsysDRDUSBXHCI21printPeriodicScheduleEv : 1640 -> 1632
~ sub_fffffff00a63a1c4 -> sub_fffffff00a6cca6c : 1252 -> 1284
~ __ZN28AppleT8027USBXHCICommandRing20addEndpointWithDummyEjjPN15StandardUSBXHCI26StandardUSBXHCISlotContextEPNS0_30StandardUSBXHCIEndpointContextE : 4256 -> 4336
~ sub_fffffff00a63b748 -> sub_fffffff00a6ce060 : 1764 -> 1796
~ sub_fffffff00a63be2c -> sub_fffffff00a6ce764 : 932 -> 972
~ __ZN28AppleT8027USBXHCICommandRing21dropEndpointWithDummyEjjPN15StandardUSBXHCI26StandardUSBXHCISlotContextEPNS0_30StandardUSBXHCIEndpointContextE : 1860 -> 1888
~ sub_fffffff00a64cbfc -> sub_fffffff00a6df578 : 2428 -> 2424
~ sub_fffffff00a64ea90 -> sub_fffffff00a6e1408 : 1316 -> 1336
~ sub_fffffff00a65d328 -> sub_fffffff00a6efcb4 : 2404 -> 2400
~ sub_fffffff00a66bed8 -> sub_fffffff00a6fe860 : 2428 -> 2424
~ __ZN17AppleT8140USBXHCI25getPeriodicBandwidthUsageEv : 1616 -> 1636
```
