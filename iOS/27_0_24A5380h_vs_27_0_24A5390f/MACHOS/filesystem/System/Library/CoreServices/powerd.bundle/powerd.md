## powerd

> `/System/Library/CoreServices/powerd.bundle/powerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77744` | `0x77d44` | **`+0x600`** |
| `__TEXT.__oslogstring` | `0xe0b2` | `0xe24a` | **`+0x198`** |
| `__TEXT.__const` | `0x4e0` | `0x540` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x76e0` | `0x76a0` | **`-0x40`** |
| `__TEXT.__cstring` | `0x6ec2` | `0x6e93` | **`-0x2f`** |
| `__TEXT.__unwind_info` | `0x1668` | `0x1690` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x71e8` | `0x720c` | **`+0x24`** |
| `__DATA_CONST.__const` | `0x26a0` | `0x26c0` | **`+0x20`** |
| `__DATA.__bss` | `0xdc0` | `0xdd8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x2c54` | `0x2c6c` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0xa8e` | `0xaa0` | **`+0x12`** |
| `__DATA.__objc_const` | `0x56a8` | `0x56b0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x1c28` | `0x1c30` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-2043.0.13.502.1
+2043.0.31.0.0

-  Functions: 2632
+  Functions: 2648

-  CStrings:  4066
+  CStrings:  4074
CStrings:
+ "3.2"
+ "Battery P0 threshold is not set (packId=%u)\n"
+ "Failed to get Battery health P0 threshold value (packId=%u)\n"
+ "Received notification for batteryHealthP0Threshold. Value set to %llu\n"
+ "Retrieved p0 threshold for pack (packId=%u packThreshold=%d batteryHealthP0Threshold=%llu)"
+ "ShipChargeLimit: Cleared battery level limit\n"
+ "ShipChargeLimit: Failed to %s battery limit: %#x\n"
+ "ShipChargeLimit: Failed to clear battery level limit %#x\n"
+ "ShipChargeLimit: Failed to register battery limit token: %#x\n"
+ "ShipChargeLimit: Failed to set battery level limit: %#x\n"
+ "ShipChargeLimit: Set battery level limit\n"
+ "WeightedRa(%d) is >= threshold(%d) (packId=%u)\n"
+ "batteryHealthP0Threshold set to %llu\n"
+ "clear"
+ "getPowerModeUserInitiatedWithReply:"
+ "set"
+ "v24@0:8@?<v@?B>16"
- "3.1"
- "Battery P0 threshold is not set\n"
- "Failed to get Battery health P0 threshold value\n"
- "Received notification for batteryHealthP0Threshold. Value set to %lld\n"
- "ShipChargeLimitCompliant"
- "ShipChargeLimitData incomplete\n"
- "ShippingChargeLimitSystemStatus"
- "WeightedRa(%d) is >= threshold(%llu)\n"
- "batteryHealthP0Threshold set to %lld\n"
```
