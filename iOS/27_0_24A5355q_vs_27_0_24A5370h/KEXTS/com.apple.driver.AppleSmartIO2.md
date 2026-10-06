## com.apple.driver.AppleSmartIO2

> `com.apple.driver.AppleSmartIO2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x3b0` | **`+0x3b0`** |
| `__TEXT_EXEC.__text` | `0xb3ac` | `0xb488` | **`+0xdc`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ sub_fffffff0096fb574 -> sub_fffffff00974fb94 : 80 -> 76
~ __ZN20AppleSmartIOEndpoint11sendMessageEPvS0_b : 188 -> 196
~ sub_fffffff0096fc0b0 -> sub_fffffff0097506d4 : 256 -> 264
~ __ZN19AppleSmartIOControl14setupMapRangesEv : 744 -> 708
~ __ZN19AppleSmartIOControl31populateShimPowerGatePropertiesEv : 488 -> 508
~ __ZN19AppleSmartIOControl10setupShimsEv : 780 -> 772
~ __ZN19AppleSmartIOControl12setupDevicesEv : 628 -> 624
~ __ZN19AppleSmartIOControl16sendSIORegistersEv : 752 -> 736
~ __ZN25AppleSmartIODMAController20_initDMAChannelGatedEPK21AppleSmartIODMAConfigP16IODMAEventSourcePj : 360 -> 368
~ sub_fffffff0096ff11c -> sub_fffffff009753724 : 56 -> 60
~ sub_fffffff0096ff230 -> sub_fffffff00975383c : 220 -> 224
~ __ZN25AppleSmartIODMAController15startDMACommandEjP12IODMACommandjyy : 140 -> 144
~ sub_fffffff0096ff53c -> sub_fffffff009753b50 : 136 -> 140
~ sub_fffffff0096ff628 -> sub_fffffff009753c40 : 200 -> 204
~ sub_fffffff0096ff760 -> sub_fffffff009753d7c : 168 -> 172
~ sub_fffffff0096ff808 -> sub_fffffff009753e28 : 168 -> 172
~ sub_fffffff0096ff8b0 -> sub_fffffff009753ed4 : 172 -> 176
~ sub_fffffff0096ff95c -> sub_fffffff009753f84 : 168 -> 172
~ __ZN15AppleSmartIODMA16_startDMACommandEP12IODMACommandPyS2_ : 1320 -> 1424
~ __ZN15AppleSmartIODMA14_notifyCommandEP19AppleSmartIOCommand : 304 -> 356
~ _OUTLINED_FUNCTION_0_5 : 628 -> 680
CStrings:
+ "19:32:47"
+ "Jun 18 2026"
- "22:45:40"
- "May 27 2026"
```
