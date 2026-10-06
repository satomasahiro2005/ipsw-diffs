## CorePrescription

> `/System/Library/PrivateFrameworks/CorePrescription.framework/CorePrescription`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49780` | `0x4a814` | **`+0x1094`** |
| `__AUTH_CONST.__objc_const` | `0x88e0` | `0x8bb8` | **`+0x2d8`** |
| `__TEXT.__objc_methlist` | `0x3ad8` | `0x3bf8` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x2060` | `0x2150` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x3b4e` | `0x3bec` | **`+0x9e`** |
| `__TEXT.__const` | `0x80f4` | `0x8184` | **`+0x90`** |
| `__DATA.__data` | `0x870` | `0x8e8` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x1738` | `0x1798` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x16c8` | `0x1728` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x1030` | `0x108c` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0x13f0` | `0x1438` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x964` | `0x9a8` | **`+0x44`** |
| `__TEXT.__swift5_typeref` | `0x59c` | `0x5d2` | **`+0x36`** |
| `__TEXT.__oslogstring` | `0x4a9` | `0x4de` | **`+0x35`** |
| `__AUTH.__data` | `0x528` | `0x558` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xa11` | `0xa31` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x318` | `0x328` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x38` | `0x48` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x20` | `0x30` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x440` | `0x44c` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x9d0` | `0x9d8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x248` | `0x250` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xdc` | `0xe0` | **`+0x4`** |

### Other Changes

```diff

-230.0.0.0.0
+230.0.1.0.0

-  Functions: 2493
-  Symbols:   2329
-  CStrings:  607
+  - /usr/lib/swift/libswiftsimd.dylib
+  Functions: 2534
+  Symbols:   2367
+  CStrings:  611
Symbols:
+ -[CRXFCorePrescriptionServiceClient scanEnrollmentDidProgress:error:reply:]
+ -[CRXFCorePrescriptionServiceClient scanEnrollmentProgressHandler]
+ -[CRXFCorePrescriptionServiceClient setScanEnrollmentProgressHandler:]
+ -[CRXFServiceConnection exportedInterface]
+ -[CRXFServiceConnection exportedObject]
+ -[CRXFServiceConnection setExportedInterface:]
+ -[CRXFServiceConnection setExportedObject:]
+ _OBJC_CLASS_$_CRXCAppClipCodeAnchorData
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSSet
+ _OBJC_IVAR_$_CRXFCorePrescriptionServiceClient._scanEnrollmentProgressHandler
+ _OBJC_IVAR_$_CRXFServiceConnection._exportedInterface
+ _OBJC_IVAR_$_CRXFServiceConnection._exportedObject
+ _OBJC_METACLASS_$_CRXCAppClipCodeAnchorData
+ __CLASS_METHODS_CRXCAppClipCodeAnchorData
+ __CLASS_PROPERTIES_CRXCAppClipCodeAnchorData
+ __DATA_CRXCAppClipCodeAnchorData
+ __INSTANCE_METHODS_CRXCAppClipCodeAnchorData
+ __IVARS_CRXCAppClipCodeAnchorData
+ __METACLASS_DATA_CRXCAppClipCodeAnchorData
+ __OBJC_$_PROP_LIST_CRXFServiceConnection
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CorePrescriptionServiceClientProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CorePrescriptionServiceClientProtocol
+ __OBJC_LABEL_PROTOCOL_$_CorePrescriptionServiceClientProtocol
+ __OBJC_PROTOCOL_$_CorePrescriptionServiceClientProtocol
+ __OBJC_PROTOCOL_REFERENCE_$_CorePrescriptionServiceClientProtocol
+ __PROPERTIES_CRXCAppClipCodeAnchorData
+ __PROTOCOLS_CRXCAppClipCodeAnchorData
+ __PROTOCOL_CorePrescriptionServiceClientProtocol
+ __PROTOCOL_INSTANCE_METHODS_CorePrescriptionServiceClientProtocol
+ __PROTOCOL_METHOD_TYPES_CorePrescriptionServiceClientProtocol
+ ___75-[CRXFCorePrescriptionServiceClient scanEnrollmentDidProgress:error:reply:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48bs56bs_e5_v8?0ls48l8s32l8s40l8s56l8
+ __swift_FORCE_LOAD_$_swiftsimd
+ __swift_FORCE_LOAD_$_swiftsimd_$_CorePrescription
+ _swift_release_x23
+ _symbolic $s16CorePrescription0aB21ServiceClientProtocolP
+ _symbolic _____ 16CorePrescription25CRXCAppClipCodeAnchorDataC
CStrings:
+ "%s @%d: Received scan progress callback from service"
+ "-[CRXFCorePrescriptionServiceClient scanEnrollmentDidProgress:error:reply:]"
+ "AppClipCodeAnchorData(radius: "
+ "CorePrescription.CRXCAppClipCodeAnchorData"
```
