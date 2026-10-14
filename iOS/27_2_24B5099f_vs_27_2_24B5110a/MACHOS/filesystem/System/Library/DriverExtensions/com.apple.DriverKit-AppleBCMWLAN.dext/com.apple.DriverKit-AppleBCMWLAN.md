## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x291d04` | `0x291dec` | **`+0xe8`** |
| `__TEXT.__cstring` | `0x834c7` | `0x834d7` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5ff0` | `0x5ff8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-1582.8.0.0.0
+1582.9.0.0.0

-  CStrings:  13143
+  CStrings:  13144
Functions:
~ __ZN28AppleBCMWLANBusInterfacePCIe24PortErrorMsgHandler_ImplEP8OSActionP8OSNumberS3_P6OSData : 1076 -> 1108
~ __ZN28AppleBCMWLANBusInterfacePCIe24PortEventMsgHandlerGatedEjP8OSNumberP6OSData : 1576 -> 1612
~ __ZN28AppleBCMWLANBusInterfacePCIe24PortErrorMsgHandlerGatedEjP6OSData : 788 -> 856
~ __ZN28AppleBCMWLANBusInterfacePCIe25SetPowerStateGated_InvokeE5IORPCP15OSMetaClassBasePFiS2_10PowerStateE : 156 -> 204
~ __ZN28AppleBCMWLANBusInterfacePCIe29SetPowerStateGatedAMFM_InvokeE5IORPCP15OSMetaClassBasePFiS2_10PowerStateE : 156 -> 204
CStrings:
+ "\"AppleBCMWLANV3_driverkit-1582.9\""
+ "AppleBCMWLANV3_driverkit-1582.9"
+ "Oct  3 2026 20:55:39"
+ "af/link timeout"
- "\"AppleBCMWLANV3_driverkit-1582.8\""
- "AppleBCMWLANV3_driverkit-1582.8"
- "Sep 26 2026 03:37:36"
```
