## libnfshared.dylib

> `/usr/lib/libnfshared.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24ec8` | `0x25b20` | **`+0xc58`** |
| `__AUTH_CONST.__cfstring` | `0x47a0` | `0x48e0` | **`+0x140`** |
| `__TEXT.__cstring` | `0x4cf0` | `0x4de0` | **`+0xf0`** |
| `__TEXT.__const` | `0x220` | `0x2c0` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x4210` | `0x4258` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x2384` | `0x23ac` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x5e0` | `0x600` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x220` | `0x240` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x5f0` | `0x610` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x700` | `0x720` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x18bd` | `0x18dc` | **`+0x1f`** |
| `__DATA_CONST.__objc_selrefs` | `0x1418` | `0x1430` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x2bc` | `0x2c4` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x108` | `0x110` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 757
-  Symbols:   405
-  CStrings:  946
+  Functions: 776
+  Symbols:   423
+  CStrings:  961
Symbols:
+ _CFNumberGetTypeID
+ _CFNumberGetValue
+ _CFNumberIsFloatType
+ _CFPreferencesCopyValue
+ _NFPlatformHasAlternateRFSettings
+ _NFPlatformHasBootMeasurements
+ _NFPlatformHasLoadSwitchWorkaround
+ _NFPlatformHasSecureBoot
+ _NFProductGetFactoryPageGPIODefaultConfig
+ _NFProductGetFactoryPageGPIODriveConfig
+ _NFProductGetFactoryPageGPIOPullConfig
+ _NFProductGetFactoryPageLoadSwitchConfig
+ _NFProductGetFactoryPagePlatformConfig
+ _NFProductGetFactoryPageVGPIOEventsConfig
+ _NFProductGetFactoryPageVGPIOTargetsConfig
+ _NFProductHasFactoryPage
+ _NFProductIsRTIDEnabledByDefault
+ _NFProductSupportsRTID
+ _kCFPreferencesAnyHost
- ___NSDictionary0__struct
CStrings:
+ "%s:%i %s doesn't exist"
+ "%{public}s:%i %s doesn't exist"
+ "1"
+ "AppleStockholmSPMI"
+ "BootMeasurements"
+ "NFPlatformHasBootMeasurements"
+ "NFPlatformHasLoadSwitchWorkaround"
+ "YES"
+ "com.apple.stockholm"
+ "hasAlternateRFSettings"
+ "mobile"
+ "nfcDeviceAngle"
+ "nfcDeviceModeDefault"
+ "sn450WithLoadSwitch"
+ "true"
```
