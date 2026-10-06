## BatteryUsageUI

> `/System/Library/PreferenceBundles/BatteryUsageUI.bundle/BatteryUsageUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10bc88` | `0x10d0d0` | **`+0x1448`** |
| `__DATA_CONST.__const` | `0x69d8` | `0x6b18` | **`+0x140`** |
| `__DATA_CONST.__cfstring` | `0x90a0` | `0x91a0` | **`+0x100`** |
| `__TEXT.__cstring` | `0x91d9` | `0x92d9` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x3315` | `0x3405` | **`+0xf0`** |
| `__DATA.__data` | `0x5060` | `0x5110` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0xa176` | `0xa226` | **`+0xb0`** |
| `__DATA.__bss` | `0xa3a0` | `0xa430` | **`+0x90`** |
| `__TEXT.__const` | `0x8ec4` | `0x8f54` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x8740` | `0x87c0` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0xe294` | `0xe314` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x38ec` | `0x3944` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x2554` | `0x25ac` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x2b38` | `0x2b88` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x2ac0` | `0x2af8` | **`+0x38`** |
| `__DATA_CONST.__objc_dictobj` | `0xa78` | `0xaa0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x3238` | `0x3258` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x9d0` | `0x9e8` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x870` | `0x880` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x3bd0` | `0x3be0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x834` | `0x844` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1df8` | `0x1e00` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x4a8` | `0x4ac` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x28c` | `0x290` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3486.0.81.502.4
+3486.2.4.0.0

-  Functions: 4982
-  Symbols:   735
-  CStrings:  3883
+  Functions: 5014
+  Symbols:   736
+  CStrings:  3904
Symbols:
+ _IOPSShippingChargeLimitGetState
CStrings:
+ "CHARGING_LIMIT_SHIP_MODE_FOOTER"
+ "CHARGING_LIMIT_SHIP_MODE_URL"
+ "CHARGING_OPTIMIZED_BATTERY_CHARGING_FOOTER"
+ "Could not open url: %@"
+ "Recalibrating Maximum Capacity is not available."
+ "ShipChargeLimitEnabled"
+ "ShipChargeLimitSupported"
+ "ShippingChargeLimit dict: %@"
+ "ShippingChargeLimit failed to retrieve is enabled"
+ "ShippingChargeLimit failed to retrieve is supported"
+ "ShippingChargeLimit get failed: %d"
+ "currentMaxCap"
+ "disable:"
+ "getShippingChargeLimitState"
+ "ipad997da965#iPad4643be23"
+ "iph63eecc618#iphdbd1c7b83"
+ "isRecalibrating"
+ "isShippingChargeLimitEnabled"
+ "q24@?0@\"BatteryHealthUIPackInformation\"8@\"BatteryHealthUIPackInformation\"16"
+ "setAboutShipModeLink"
+ "supportsShippingChargeLimit"
+ "supportsShippingChargeLimit:"
- "CHARGING_OPTIMIZED_BATTERY_CHARGING_FOOTER_WITH_CHARGE_LIMIT"
```
