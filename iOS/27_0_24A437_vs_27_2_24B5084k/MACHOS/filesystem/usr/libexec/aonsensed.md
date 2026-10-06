## aonsensed

> `/usr/libexec/aonsensed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x407b44` | `0x407f7c` | **`+0x438`** |
| `__TEXT.__oslogstring` | `0x317a` | `0x31da` | **`+0x60`** |
| `__TEXT.__cstring` | `0x152ee` | `0x1529e` | **`-0x50`** |
| `__TEXT.__auth_stubs` | `0x3370` | `0x33b0` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x5d4d` | `0x5d8d` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0xf40` | `0xf80` | **`+0x40`** |
| `__DATA.__data` | `0x1ee18` | `0x1ee38` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x19c8` | `0x19e8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xd689` | `0xd6a9` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xd9c4` | `0xd9dc` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x11998` | `0x119b0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x598` | `0x5a8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x878` | `0x888` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-118.0.2.0.0
+131.0.0.0.0

-  Functions: 27120
-  Symbols:   1280
-  CStrings:  4477
+  Functions: 27125
+  Symbols:   1286
+  CStrings:  4478
Symbols:
+ _$s11ALDataTypes17ALBtAdvertisementV10_colorCodes5UInt8VSgvs
+ _$s11ALDataTypes17ALBtAdvertisementV17accessoryCategorys5UInt8VSgvg
+ _$s11ALDataTypes17ALBtAdvertisementV18_accessoryCategorys5UInt8VSgvs
+ _$s11ALDataTypes17ALBtAdvertisementV9colorCodes5UInt8VSgvg
+ _$s11ALDataTypes31ProximityLaunchXPCDataEventKeysO17accessoryCategoryyA2CmFWC
+ _$s11ALDataTypes31ProximityLaunchXPCDataEventKeysO9colorCodeyA2CmFWC
CStrings:
+ "#WiFi,exceptionHandling,scan aborted"
+ "Fired XPC event with btuuid: %s for client: %llu productId: %s vendorId: %s subType: %s txPower: %d ppServiceData: %s pairingCapabilities:%llu colorCode:%s accessoryCategory:%s"
+ "proximityServiceAccessoryCategory"
+ "proximityServiceColorCode"
- ", BSSID or channel missing in scan "
- "Fired XPC event with btuuid: %s for client: %llu productId: %s vendorId: %s subType: %s txPower: %d ppServiceData: %s pairingCapabilities:%llu"
- "processResultArray(_:bg:)"
```
