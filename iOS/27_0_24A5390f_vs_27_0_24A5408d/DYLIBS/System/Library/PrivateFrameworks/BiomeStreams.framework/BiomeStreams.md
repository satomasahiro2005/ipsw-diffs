## BiomeStreams

> `/System/Library/PrivateFrameworks/BiomeStreams.framework/BiomeStreams`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x9400` | `0x9540` | **`+0x140`** |
| `__TEXT.__text` | `0x3f8c3c` | `0x3f8b5c` | **`-0xe0`** |
| `__TEXT.__cstring` | `0x31123` | `0x311f3` | **`+0xd0`** |
| `__DATA_CONST.__objc_arraydata` | `0xb8` | `0x108` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xc3e0` | `0xc428` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0xbe40` | `0xbe20` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1278` | `0x125c` | **`-0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x6078` | `0x6070` | **`-0x8`** |

### Other Changes

```diff

-247.0.1.0.0
+250.0.0.1.0

-  Functions: 21919
+  Functions: 21918

-  CStrings:  9174
+  CStrings:  9182
CStrings:
+ "Accessibility.VoiceControl"
+ "Accessibility.VoiceOver"
+ "Carousel.Connection.Companion"
+ "ContextualUnderstanding.AmbientLight"
+ "Device.Display.AlwaysOn"
+ "Device.Display.Backlight"
+ "Device.Wireless.CellularQualityStatus"
+ "Device.Wireless.ConnectivityContext"
+ "Diagnostics.Panic"
+ "NanoSettings.ControlCenter.Usage"
+ "Siri.Remembers.Intent"
+ "Siri.Service"
- "Device.Wireless.APSDInterfaceStatus"
- "Device.Wireless.WiFiAvailabilityStatus"
- "ERROR: Unable access to AppleKeyStore"
- "OSAnalytics.Hardware.Reliability"
```
