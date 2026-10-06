## com.apple.iokit.IOUSBDeviceFamily

> `com.apple.iokit.IOUSBDeviceFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x2ad48` | `0x2ae08` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x33f8` | `0x3414` | **`+0x1c`** |

### Other Changes

```diff

-896.0.0.0.0
+896.0.3.0.0

-  CStrings:  420
+  CStrings:  421
Functions:
~ __ZN20IOUSBDeviceInterface19copyDescriptorGatedEPNS_33tInternalCopyDescriptorParametersERi : 952 -> 1028
~ __ZN21IOUSBDeviceController15prepareDefaultsEP9IOService : 4380 -> 4496
CStrings:
+ "driver-registration-timeout"
```
