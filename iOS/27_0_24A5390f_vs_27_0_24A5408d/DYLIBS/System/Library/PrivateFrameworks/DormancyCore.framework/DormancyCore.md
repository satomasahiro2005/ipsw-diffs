## DormancyCore

> `/System/Library/PrivateFrameworks/DormancyCore.framework/DormancyCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b800` | `0x2d49c` | **`+0x1c9c`** |
| `__DATA.__bss` | `0x6880` | `0x6a00` | **`+0x180`** |
| `__TEXT.__const` | `0x3ddc` | `0x3f2c` | **`+0x150`** |
| `__AUTH_CONST.__const` | `0x26c8` | `0x27a8` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x862` | `0x923` | **`+0xc1`** |
| `__TEXT.__swift5_reflstr` | `0x761` | `0x81a` | **`+0xb9`** |
| `__TEXT.__constg_swiftt` | `0xd88` | `0xe40` | **`+0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0xd24` | `0xdcc` | **`+0xa8`** |
| `__AUTH.__data` | `0x758` | `0x7c8` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x950` | `0x9b0` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0xb78` | `0xbd8` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0xe13` | `0xe73` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xadd` | `0xb2d` | **`+0x50`** |
| `__DATA.__data` | `0x968` | `0x998` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xc30` | `0xc60` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x858` | `0x870` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1a8` | `0x1b8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x168` | `0x178` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x374` | `0x384` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x118` | `0x120` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x24` | `0x28` | **`+0x4`** |

### Other Changes

```diff

-27.0.57.0.0
+27.0.60.0.0

+  - /System/Library/PrivateFrameworks/PairedDeviceRegistry.framework/PairedDeviceRegistry

-  Functions: 1212
-  Symbols:   590
-  CStrings:  119
+  Functions: 1245
+  Symbols:   600
+  CStrings:  125
Symbols:
+ _OBJC_CLASS_$_PDRRegistry
+ ___swift_memcpy35_8
+ _associated conformance 12DormancyCore0A7MonitorC14ExcludedReasonO26RemotelyDisabledCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 12DormancyCore0A7MonitorC14ExcludedReasonO26RemotelyDisabledCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0H3KeyAAs28CustomDebugStringConvertible
+ _swift_retain_x24
+ _symbolic $s12DormancyCore20TinkerDeviceDetectorP
+ _symbolic _____ 12DormancyCore0A7MonitorC14ExcludedReasonO26RemotelyDisabledCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____ 12DormancyCore27DefaultTinkerDeviceDetectorV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore0D7MonitorC14ExcludedReasonO26RemotelyDisabledCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore0D7MonitorC14ExcludedReasonO26RemotelyDisabledCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
CStrings:
+ "ApplicationSurface.AppIntentExecution"
+ "ApplicationSurface.CarouselAlert"
+ "DormancyStatusManager bundleID %s, context: %s, isTinker: %{bool}d"
+ "Remotely disabled"
+ "Set promotion date to %s for %s:%s"
+ "remotelyDisabled"
+ "tinkerDefaultValue"
- "DormancyStatusManager bundleID %s, context: %s"
```
