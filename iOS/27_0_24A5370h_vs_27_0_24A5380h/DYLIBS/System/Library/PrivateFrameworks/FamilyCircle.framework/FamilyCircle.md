## FamilyCircle

> `/System/Library/PrivateFrameworks/FamilyCircle.framework/FamilyCircle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc4a78` | `0xc7fa8` | **`+0x3530`** |
| `__AUTH.__objc_data` | `0x1700` | `0x24c8` | **`+0xdc8`** |
| `__DATA_DIRTY.__objc_data` | `0x1390` | `0x5c8` | **`-0xdc8`** |
| `__AUTH.__data` | `0x15c8` | `0x1b68` | **`+0x5a0`** |
| `__DATA_DIRTY.__data` | `0x618` | `0x168` | **`-0x4b0`** |
| `__DATA.__bss` | `0xbb40` | `0xbfc0` | **`+0x480`** |
| `__TEXT.__const` | `0x8478` | `0x87f8` | **`+0x380`** |
| `__TEXT.__eh_frame` | `0x55a8` | `0x57a8` | **`+0x200`** |
| `__TEXT.__oslogstring` | `0x4c33` | `0x4e13` | **`+0x1e0`** |
| `__TEXT.__swift5_typeref` | `0x2380` | `0x2498` | **`+0x118`** |
| `__TEXT.__constg_swiftt` | `0x26f4` | `0x27f8` | **`+0x104`** |
| `__AUTH_CONST.__objc_const` | `0xc900` | `0xc9f8` | **`+0xf8`** |
| `__TEXT.__unwind_info` | `0x3b90` | `0x3c78` | **`+0xe8`** |
| `__AUTH_CONST.__const` | `0x6860` | `0x6928` | **`+0xc8`** |
| `__DATA.__data` | `0x2550` | `0x2610` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x1de8` | `0x1e48` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `0x580` | `0x5c8` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0x155d` | `0x159d` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2850` | `0x2888` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x1388` | `0x13b8` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x630` | `0x658` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x988` | `0x9a0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xdc` | `0xf0` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x738` | `0x74c` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x3cc` | `0x3e0` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x1a4` | `0x1b4` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x1dc` | `0x1ec` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x2d4` | `0x2e0` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x3d8` | `0x3e0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x64` | `0x68` | **`+0x4`** |

### Other Changes

```diff

-282.0.0.0.0
+284.1.0.0.0

-  Functions: 5446
-  Symbols:   4045
-  CStrings:  1310
+  Functions: 5518
+  Symbols:   4069
+  CStrings:  1318
Symbols:
+ __DATA__TtC12FamilyCircle29PersonalInformationController
+ __IVARS__TtC12FamilyCircle29PersonalInformationController
+ __METACLASS_DATA__TtC12FamilyCircle29PersonalInformationController
+ _associated conformance SC15FAAgeRangeErrorLeV10Foundation021_ObjectiveCBridgeableC0SCs0C0
+ _associated conformance SC15FAAgeRangeErrorLeV10Foundation13CustomNSErrorSCs0C0
+ _associated conformance SC15FAAgeRangeErrorLeV10Foundation21_BridgedStoredNSErrorSC4CodeAcDP_8RawValueSYs17FixedWidthInteger
+ _associated conformance SC15FAAgeRangeErrorLeV10Foundation21_BridgedStoredNSErrorSC4CodeAcDP_AC01_cH8Protocol
+ _associated conformance SC15FAAgeRangeErrorLeV10Foundation21_BridgedStoredNSErrorSC4CodeAcDP_SY
+ _associated conformance SC15FAAgeRangeErrorLeV10Foundation21_BridgedStoredNSErrorSCAC021_ObjectiveCBridgeableC0
+ _associated conformance SC15FAAgeRangeErrorLeV10Foundation21_BridgedStoredNSErrorSCAC06CustomG0
+ _associated conformance SC15FAAgeRangeErrorLeV10Foundation21_BridgedStoredNSErrorSCSH
+ _associated conformance SC15FAAgeRangeErrorLeVSHSCSQ
+ _associated conformance So15FAAgeRangeErrorV10Foundation01_C12CodeProtocolSC01_C4TypeAcDP_AC21_BridgedStoredNSError
+ _associated conformance So15FAAgeRangeErrorV10Foundation01_C12CodeProtocolSCSQ
+ _symbolic $s12FamilyCircle26PersonalInformationServiceP
+ _symbolic ScCy_____Sg______pG 10Foundation4DateV s5ErrorP
+ _symbolic So14ACAccountStoreC
+ _symbolic So16AKAccountManagerC
+ _symbolic So33AKAppleIDAuthenticationControllerC
+ _symbolic _____ 12FamilyCircle29PersonalInformationControllerC
+ _symbolic _____ SC15FAAgeRangeErrorLeV
+ _symbolic _____ So15FAAgeRangeErrorV
+ _symbolic _____y_____G s11_SetStorageC 10Foundation8CalendarV9ComponentO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation8CalendarV9ComponentO
CStrings:
+ "Found proto account, returning true"
+ "No Managed or Proto account, returning false"
+ "No pending date of birth, continuing"
+ "PersonalAttestationController: Trying to fetch birthday from Authkit."
+ "PersonalAttestationController: Unable to fetch authkit account."
+ "PersonalAttestationController: Unable to primary authkit account."
+ "Primary AuthKit account is managed, returning true"
+ "There is a pending date of birth"
```
