## com.apple.iokit.IOUSBDeviceFamily

> `com.apple.iokit.IOUSBDeviceFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x700` | **`+0x700`** |
| `__TEXT_EXEC.__text` | `0x2accc` | `0x2ad48` | **`+0x7c`** |

### Other Changes

```diff

-891.0.0.0.0
+896.0.0.0.0
Functions:
~ __ZN20IOUSBDeviceInterface19copyDescriptorGatedEPNS_33tInternalCopyDescriptorParametersERi : 960 -> 952
~ sub_fffffff00a4bd510 -> sub_fffffff00a54d5f8 : 244 -> 240
~ sub_fffffff00a4c0214 -> sub_fffffff00a5502f8 : 64 -> 68
~ sub_fffffff00a4c0254 -> sub_fffffff00a55033c : 68 -> 72
~ sub_fffffff00a4c0298 -> sub_fffffff00a550384 : 68 -> 72
~ sub_fffffff00a4c0a0c -> sub_fffffff00a550afc : 124 -> 156
~ __ZN21IOUSBDeviceController15prepareDefaultsEP9IOService : 4384 -> 4380
~ __ZN21IOUSBDeviceController27addDevCapabilityDescriptorsEv : 1140 -> 1148
~ __ZN21IOUSBDeviceController38addFailedFunctionsCapabilityDescriptorEv : 2812 -> 2820
~ __ZN21IOUSBDeviceController13startUSBStackEv : 1752 -> 1836
~ sub_fffffff00a4d4d68 -> sub_fffffff00a564ed8 : 236 -> 232
```
