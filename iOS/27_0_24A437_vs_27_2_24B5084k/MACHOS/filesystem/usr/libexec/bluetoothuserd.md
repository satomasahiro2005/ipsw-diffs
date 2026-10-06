## bluetoothuserd

> `/usr/libexec/bluetoothuserd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6fe28` | `0x711c8` | **`+0x13a0`** |
| `__TEXT.__oslogstring` | `0x2fd0` | `0x30d0` | **`+0x100`** |
| `__TEXT.__cstring` | `0x23d1` | `0x2461` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x1ea0` | `0x1f00` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x14b8` | `0x1500` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0xf58` | `0xf88` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x2ad5` | `0x2b05` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x33d0` | `0x33f8` | **`+0x28`** |
| `__DATA.__data` | `0x2580` | `0x2590` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xc48` | `0xc58` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x13e0` | `0x13f0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x618` | `0x620` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x558` | `0x560` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x165c` | `0x1664` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2700.51.1.3.0
+2701.3.0.0.0

+  - /System/Library/PrivateFrameworks/IconServices.framework/IconServices

-  Functions: 1822
-  Symbols:   837
-  CStrings:  1108
+  Functions: 1827
+  Symbols:   845
+  CStrings:  1116
Symbols:
+ _$s22UniformTypeIdentifiers6UTTypeV10identifierSSvg
+ _$s22UniformTypeIdentifiers6UTTypeV22_rawBluetoothProductID0e6VendorH0ACSgs6UInt32V_s6UInt16VtcfC
+ _$s22UniformTypeIdentifiers6UTTypeVMa
+ _$s22UniformTypeIdentifiers6UTTypeVMn
+ _$sSo28CKModifyRecordZonesOperationC8CloudKitE03perB13ZoneSaveBlockySo08CKRecordH2IDC_s6ResultOySo0kH0Cs5Error_pGtcSgvs
+ _$ss11AnyHashableV10FoundationE19_bridgeToObjectiveCSo8NSObjectCyF
+ _OBJC_CLASS_$_ISSymbol
+ _swift_getObjCClassFromMetadata
CStrings:
+ "Already created cloud zones"
+ "BU-SubscriptionSetup"
+ "BU-fetchDatabaseGroup"
+ "Created Zones: %s"
+ "Created the Zone: %@"
+ "Error creating the Zone %@: %@"
+ "Error creating zones: %@"
+ "Zone no longer exists on server, clearing created flag: %@"
+ "bluetoothuser-cloudkit-retryfetch-pending"
+ "bluetoothuser-cloudkit-zone-created-"
+ "rectangle.and.hand.point.up.left.fill"
+ "retryFetch activity was left pending from a previous run, re-registering on launch"
+ "symbolForTypeIdentifier:withResolutionStrategy:variantOptions:error:"
- "Created Zone: %s"
- "Error creating zone: %@"
- "SubscriptionSetup"
- "fetchDatabaseGroup"
- "getImageURLForAppleProductID:andColor:"
```
