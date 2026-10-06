## com.apple.driver.AppleHIDTransportSPI

> `com.apple.driver.AppleHIDTransportSPI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x3d0e0` | `0x3d04c` | **`-0x94`** |
| `__TEXT.__cstring` | `0x7d46` | `0x7d47` | **`+0x1`** |

### Other Changes

```diff

-10100.38.1.0.0
+10100.39.0.0.0
Functions:
~ sub_fffffff008efa1ac -> sub_fffffff008ef50bc : 260 -> 256
~ sub_fffffff008efa834 -> sub_fffffff008ef5740 : 436 -> 432
~ __ZN31AppleHIDTransportProtocolHIDSPI9startTestEv : 2992 -> 2984
~ sub_fffffff008f0602c -> sub_fffffff008f00f2c : 16 -> 12
~ sub_fffffff008f072e0 -> sub_fffffff008f021dc : 352 -> 344
~ __ZN26AppleHIDTransportDeviceSPI11handleStartEP9IOService : 2024 -> 1956
~ __ZN26AppleHIDTransportDeviceSPI17cacheDeviceConfigEP12OSDictionary : 1224 -> 1212
~ __ZN27AppleHIDTransportProtocolZ213getDeviceInfoEv : 1056 -> 1048
~ __ZN27AppleHIDTransportProtocolZ219deviceGetReportInfoEhPNS_10ReportInfoE : 824 -> 820
~ __ZN27AppleHIDTransportProtocolZ215deviceGetReportEPNS_12ReportStructE : 1284 -> 1280
~ __ZN27AppleHIDTransportProtocolZ220deviceSetReportShortEPNS_12ReportStructE : 792 -> 788
~ __ZN27AppleHIDTransportProtocolZ219deviceSetReportLongEPNS_12ReportStructE : 1132 -> 1128
~ __ZN27AppleHIDTransportProtocolZ212getCMDStatusEPNS_13CommandStatusE : 600 -> 596
~ __ZN27AppleHIDTransportProtocolZ221deviceGetResultLengthEPt : 720 -> 716
~ __ZN27AppleHIDTransportProtocolZ220deviceReadResultDataEt : 1076 -> 1072
~ sub_fffffff008f1efa0 -> sub_fffffff008f19e20 : 16 -> 12
CStrings:
+ "121111121222121211111211122112111111121112212112111112222212122222222222222222221121"
- "12111112122212121111121112211211111121112212112111112222212122222222222222222221121"
```
