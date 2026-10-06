## com.apple.driver.usb.AppleUSBXHCI

> `com.apple.driver.usb.AppleUSBXHCI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x484b4` | `0x483e4` | **`-0xd0`** |
| `__TEXT.__cstring` | `0x5743` | `0x5722` | **`-0x21`** |

### Other Changes

```diff

-1617.0.3.0.0
+1617.0.9.0.0

-  CStrings:  550
+  CStrings:  548
Functions:
~ __ZN30AppleUSBXHCIIsochronousRequest7prepareEv : 12496 -> 12592
~ __ZN16AppleUSBXHCIPort20initWithDeviceMemoryEP14IODeviceMemoryPN15StandardUSBXHCI33StandardUSBXHCIProtocolCapabilityEP15IORegistryEntry : 1516 -> 1364
~ sub_fffffff00a75a020 -> sub_fffffff00a7801b8 : 1128 -> 976
CStrings:
- "UsbCPortNumber"
- "usb-c-port-number"
```
