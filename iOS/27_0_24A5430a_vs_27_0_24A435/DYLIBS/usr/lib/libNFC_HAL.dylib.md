## libNFC_HAL.dylib

> `/usr/lib/libNFC_HAL.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17edc` | `0x196b8` | **`+0x17dc`** |
| `__TEXT.__cstring` | `0x2dc6` | `0x3029` | **`+0x263`** |
| `__TEXT.__oslogstring` | `0x24fc` | `0x2644` | **`+0x148`** |
| `__DATA_CONST.__const` | `0x268` | `0x280` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x248` | `0x258` | **`+0x10`** |

### Other Changes

```diff

-  Functions: 178
-  Symbols:   273
-  CStrings:  644
+  Functions: 190
+  Symbols:   283
+  CStrings:  676
Symbols:
+ _NFHardwareGPIOGetBootStopState
+ _NFHardwareGPIORegisterBootStopInterruptCallback
+ _NFHardwareGPIOSetNFCCBootMeasurements
+ _NFHardwareGPIOSetSEBootMeasurements
+ _NFHardwareInterfaceGetBootStopState
+ _NFHardwareInterfaceRegisterBootStopInterruptCallback
+ _NFHardwareInterfaceSetNFCCBootMeasurements
+ _NFHardwareInterfaceSetSEBootMeasurements
+ _NFPlatformHasLoadSwitchWorkaround
+ _phTmlNfc_RegisterBootStopInterruptCallback
CStrings:
+ "%s:%i Failed to register Boot stop interrupt callback"
+ "%s:%i NFC FWBM = 0"
+ "%s:%i NFC FWBM = 1"
+ "%s:%i NFC+SE FWBM = 0"
+ "%s:%i NFC+SE FWBM = 1"
+ "%s:%i Null gpio"
+ "%s:%i Null gpio internals"
+ "%s:%i SE FWBM = 0"
+ "%s:%i SE FWBM = 1"
+ "%s:%i selector=%d : Not connected"
+ "%{public}s:%i Failed to register Boot stop interrupt callback"
+ "%{public}s:%i NFC FWBM = 0"
+ "%{public}s:%i NFC FWBM = 1"
+ "%{public}s:%i NFC+SE FWBM = 0"
+ "%{public}s:%i NFC+SE FWBM = 1"
+ "%{public}s:%i Null gpio"
+ "%{public}s:%i Null gpio internals"
+ "%{public}s:%i SE FWBM = 0"
+ "%{public}s:%i SE FWBM = 1"
+ "%{public}s:%i selector=%d : Not connected"
+ "Boot-Stop-State"
+ "NFCC-Measurements"
+ "NFHardwareGPIOGetBootStopState"
+ "NFHardwareGPIORegisterBootStopInterruptCallback"
+ "NFHardwareGPIOSetNFCCBootMeasurements"
+ "NFHardwareGPIOSetSEBootMeasurements"
+ "SE-Measurements"
+ "_NFHardwareGPIOBootStopInterrupt"
+ "_NFHardwareGPIOGetValue"
+ "_phTmlNfc_NFCCBootMeasurements"
+ "_phTmlNfc_SEBootMeasurements"
+ "phTmlNfc_RegisterBootStopInterruptCallback"
```
