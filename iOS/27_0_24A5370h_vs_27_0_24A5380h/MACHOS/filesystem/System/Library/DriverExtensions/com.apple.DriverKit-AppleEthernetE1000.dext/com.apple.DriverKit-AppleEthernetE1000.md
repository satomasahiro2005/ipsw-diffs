## com.apple.DriverKit-AppleEthernetE1000

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleEthernetE1000.dext/com.apple.DriverKit-AppleEthernetE1000`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30a88` | `0x30a70` | **`-0x18`** |

### Same-size Content Changes

- `__DATA_CONST.__const`

### Other Changes

```diff

-168.0.0.0.0
+169.0.0.0.0
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/ApplePCINetworking_driverkit/install/TempContent/Objects/ApplePCINetworking.build/AppleEthernetE1000.build/Objects-normal/arm64e/DriverKit_AppleEthernetE1000-2d5d382f241969092b0d23472b4dc731.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/ApplePCINetworking_driverkit/install/TempContent/Objects/ApplePCINetworking.build/AppleEthernetE1000.build/Objects-normal/arm64e/DriverKit_AppleEthernetE1000-a7f55903b078fa07dd14ba65d188db77.o
Functions:
~ __ZN34DriverKit_AppleEthernetE1000_IVars5probeEP11IOPCIDevice : 576 -> 580
~ __ZN34DriverKit_AppleEthernetE1000_IVars17setMcastAddressesEPhj : 2904 -> 2880
~ __Z28flasher_need_to_erase_sectorPKhS0_ : 100 -> 96
```
