## Diagnostic-8187

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8187.appex/Diagnostic-8187`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa270` | `0xad44` | **`+0xad4`** |
| `__TEXT.__objc_methname` | `0x3063` | `0x3284` | **`+0x221`** |
| `__TEXT.__oslogstring` | `0xce7` | `0xebd` | **`+0x1d6`** |
| `__TEXT.__objc_stubs` | `0x2760` | `0x28e0` | **`+0x180`** |
| `__DATA_CONST.__cfstring` | `0x7a0` | `0x8a0` | **`+0x100`** |
| `__TEXT.__cstring` | `0x831` | `0x917` | **`+0xe6`** |
| `__DATA.__objc_const` | `0x2160` | `0x2208` | **`+0xa8`** |
| `__TEXT.__objc_methlist` | `0xfe4` | `0x107c` | **`+0x98`** |
| `__DATA.__objc_selrefs` | `0xd38` | `0xda0` | **`+0x68`** |
| `__TEXT.__gcc_except_tab` | `0x878` | `0x8b0` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x3d8` | `0x408` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xe0` | `0x108` | **`+0x28`** |
| `__DATA_CONST.__objc_doubleobj` | `0x30` | `0x50` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x650` | `0x670` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x340` | `0x350` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x18c` | `0x198` | **`+0xc`** |
| `__TEXT.__objc_methtype` | `0xb3d` | `0xb48` | **`+0xb`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-  Functions: 294
-  Symbols:   222
-  CStrings:  861
+  Functions: 313
+  Symbols:   224
+  CStrings:  899
Symbols:
+ _IOPSShippingChargeLimitEnable
+ _IOPSShippingChargeLimitGetState
CStrings:
+ "%1"
+ "B20@0:8f16"
+ "Device is not shipping compliant. Starting drain."
+ "Failed to enable shipping charge limit: 0x%x"
+ "Failed to query shipping charge limit state: 0x%x"
+ "Reached variance target (%.0f%%). Enabling charge limit."
+ "ShipChargeLimitCompliant"
+ "ShipChargeLimitEnabled"
+ "ShipChargeLimitSupported"
+ "Shipping charge limit enable completion failed: 0x%x"
+ "Shipping charge limit not supported on this device"
+ "Shipping compliant at %.0f%%. Completing compliance flow."
+ "Shipping compliant at %.0f%%. Draining to %.0f%% for variance."
+ "Successfully enabled shipping charge limit"
+ "T@\"NSNumber\",&,N,V_shippingComplianceDrainVariance"
+ "TB,N,V_shippingComplianceMode"
+ "Tf,N,V_varianceDrainTarget"
+ "Tf,R"
+ "_shippingComplianceDrainVariance"
+ "_shippingComplianceMode"
+ "_varianceDrainTarget"
+ "completeShippingComplianceFlow"
+ "enableShippingChargeLimit"
+ "handleShippingComplianceCheckAtBatteryLevel:"
+ "handleShippingCompliantAtLevel:"
+ "isShippingChargeLimitSupported"
+ "isShippingCompliant"
+ "minLOD"
+ "s"
+ "setShippingComplianceDrainVariance:"
+ "setShippingComplianceMode:"
+ "setVarianceDrainTarget:"
+ "shipChargeLimitCompliant"
+ "shipChargeLimitEnabled"
+ "shipChargeLimitSupported"
+ "shippingComplianceDrainVariance"
+ "shippingComplianceMode"
+ "v20@?0i8^{__CFDictionary=}12"
+ "varianceDrainTarget"
- "S"
```
