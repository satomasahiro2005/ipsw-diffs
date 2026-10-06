## uarphidd

> `/usr/libexec/uarphidd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5230` | `0x58c8` | **`+0x698`** |
| `__TEXT.__objc_stubs` | `0xc20` | `0xd80` | **`+0x160`** |
| `__TEXT.__objc_methname` | `0xe1b` | `0xeea` | **`+0xcf`** |
| `__DATA.__objc_selrefs` | `0x3b0` | `0x418` | **`+0x68`** |
| `__DATA.__objc_const` | `0x9a8` | `0xa08` | **`+0x60`** |
| `__TEXT.__cstring` | `0x7e8` | `0x846` | **`+0x5e`** |
| `__DATA_CONST.__objc_intobj` | `0x48` | `0x90` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x3dc` | `0x424` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x8be` | `0x8f9` | **`+0x3b`** |
| `__TEXT.__objc_methtype` | `0x259` | `0x26a` | **`+0x11`** |
| `__TEXT.__auth_stubs` | `0x570` | `0x580` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x188` | `0x198` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2c0` | `0x2c8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xc0` | `0xc8` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__objc_classname` | `0x6f` | `0x74` | **`+0x5`** |
| `__DATA.__objc_ivar` | `0xc0` | `0xc4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1587.2.3.0.0
+1587.40.26.502.1

-  Functions: 148
-  Symbols:   118
-  CStrings:  373
+  Functions: 155
+  Symbols:   120
+  CStrings:  388
Symbols:
+ _OBJC_CLASS_$_UARPDeviceProperties
+ _objc_retain_x25
CStrings:
+ "%s: Report length %lu is too small from UARP HID Device %@"
+ "-[UARPHIDDevice deviceInactivityTimeout:]"
+ "-[UARPHIDDevice deviceNoFirmwareUpdateAvailable:]"
+ "@\"UARPDeviceProperties\""
+ "@32@0:8@16@24"
+ "@44@0:8I16@20@28@36"
+ "UARP"
+ "_deviceProperties"
+ "_uarpProperties"
+ "deviceAvailable"
+ "deviceInactivityTimeout:"
+ "deviceNoFirmwareUpdateAvailable:"
+ "deviceTransportAvailable"
+ "initWithService:hidManager:uuid:deviceProperties:"
+ "initWithTempFolder:deviceProperties:"
+ "initWithUUID:delegate:delegateQueue:deviceProperties:"
+ "noSleepWhileStaging"
+ "numPacketRetries"
+ "setAppleModelNumber:"
+ "setNoSleepWhileStaging:"
+ "setNumPacketRetries:"
+ "setPowerAssertion"
+ "setProductGroup:"
+ "setProductNumber:"
+ "setSupportsCharging"
+ "setSupportsCharging:"
+ "setTimeoutActivity:"
+ "setTimeoutPacketRetry:"
+ "setTransportDomain:"
+ "setTransportForStagingOnly:"
+ "timeoutActivity"
+ "timeoutPacketRetry"
+ "transportForStagingOnly"
- "@32@0:8@16q24"
- "@36@0:8I16@20@28"
- "Tq,R,V_transportReleasePolicy"
- "_supportsChargingChimeDebounce"
- "_transportReleasePolicy"
- "deviceAvailable:"
- "deviceTransportAvailable:"
- "initWithService:hidManager:uuid:"
- "initWithTempFolder:transportReleasePolicy:"
- "initWithUUID:delegate:delegateQueue:"
- "q"
- "q16@0:8"
- "setDeviceAppleModelNumber:"
- "setDeviceProductGroup:productNumber:"
- "setDeviceSupportsCharging:"
- "setDeviceTransportDomain:"
- "setSupportsChargingChimeDebounce"
- "transportReleasePolicy"
```
