## com.apple.driver.AppleUSBMike

> `com.apple.driver.AppleUSBMike`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x360` | **`+0x360`** |
| `__TEXT_EXEC.__text` | `0x5fc8` | `0x6068` | **`+0xa0`** |

### Other Changes

```text
Functions:
~ __ZN12AppleUSBMike5startEP9IOService : 4800 -> 4824
~ sub_fffffff009ab25f4 -> sub_fffffff009b1489c : 396 -> 404
~ sub_fffffff009ab2f44 -> sub_fffffff009b151f4 : 316 -> 324
~ sub_fffffff009ab3204 -> sub_fffffff009b154bc : 340 -> 372
~ __ZN12AppleUSBMike10doTransferEv : 552 -> 580
~ __ZN12AppleUSBMike17completeAudioDataEP18IOMemoryDescriptoriP20IOUSBDeviceIsocFramej : 1116 -> 1176
```
