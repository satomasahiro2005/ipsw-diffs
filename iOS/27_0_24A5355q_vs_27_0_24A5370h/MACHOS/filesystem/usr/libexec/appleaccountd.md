## appleaccountd

> `/usr/libexec/appleaccountd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e5d84` | `0x3eaeac` | **`+0x5128`** |
| `__TEXT.__oslogstring` | `0x201e9` | `0x204fd` | **`+0x314`** |
| `__TEXT.__eh_frame` | `0x1436c` | `0x1451c` | **`+0x1b0`** |
| `__TEXT.__unwind_info` | `0x8588` | `0x8430` | **`-0x158`** |
| `__DATA.__objc_const` | `0x1dde0` | `0x1dce8` | **`-0xf8`** |
| `__TEXT.__swift5_typeref` | `0x777c` | `0x7869` | **`+0xed`** |
| `__TEXT.__const` | `0x12fb0` | `0x13070` | **`+0xc0`** |
| `__DATA.__data` | `0x14268` | `0x141d0` | **`-0x98`** |
| `__TEXT.__constg_swiftt` | `0xc538` | `0xc4b0` | **`-0x88`** |
| `__TEXT.__objc_methname` | `0x7725` | `0x76a5` | **`-0x80`** |
| `__DATA_CONST.__const` | `0x13d10` | `0x13ca8` | **`-0x68`** |
| `__TEXT.__cstring` | `0x44d9` | `0x4519` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x2057` | `0x201e` | **`-0x39`** |
| `__TEXT.__swift5_reflstr` | `0x6632` | `0x6665` | **`+0x33`** |
| `__TEXT.__objc_classname` | `0x2e93` | `0x2e6d` | **`-0x26`** |
| `__TEXT.__auth_stubs` | `0x37a0` | `0x37c0` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x1650` | `0x1668` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1558` | `0x1570` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x6578` | `0x6590` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x1184` | `0x119c` | **`+0x18`** |
| `__TEXT.__swift5_acfuncs` | `0xa0` | `0xb4` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0x1bd8` | `0x1be8` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x651c` | `0x6510` | **`-0xc`** |
| `__DATA.__objc_data` | `0x3350` | `0x3348` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x600` | `0x5f8` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0xc58` | `0xc54` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x630` | `0x62c` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x660` | `0x65c` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x85c` | `0x860` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-1059.1.1.0.0
+1061.0.0.0.0

-  Functions: 10148
-  Symbols:   1806
-  CStrings:  4135
+  Functions: 10179
+  Symbols:   1813
+  CStrings:  4138
Symbols:
+ _$s12AppleAccount0aB12ToolXPCErrorO12serviceErroryACSS_tcACmFWC
+ _$s12AppleAccount0aB23ToolXPCServiceInterfaceP20deleteCachedIdentity7accountAA0abC8XPCErrorOSgAA0hB0V_tYaFTq
+ _$s12AppleAccount0aB23ToolXPCServiceInterfaceP20deleteCachedIdentity7accountAA0abC8XPCErrorOSgAA0hB0V_tYaKFTqTE
+ _$s3XPC0A10_TYPE_DATAs13OpaquePointerVvg
+ _$sSo33CKFetchRecordZoneChangesOperationC8CloudKitE21recordWasChangedBlockySo10CKRecordIDC_s6ResultOySo0L0Cs5Error_pGtcSgvs
+ _CKPartialErrorsByItemIDKey
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _xpc_data_get_bytes_ptr
+ _xpc_data_get_length
+ _xpc_dictionary_get_value
+ _xpc_get_type
- _xpc_array_apply
- _xpc_dictionary_get_array
- _xpc_dictionary_get_dictionary
- _xpc_string_get_string_ptr
CStrings:
+ "AAAFoundationBackoff"
+ "Advancing database (%s) change token to: %s"
+ "AppInstallObserver: plist decode failed: %{public}@"
+ "AppleAccountTool requested to delete the cached identity"
+ "Database change token expired (%s); clearing token and re-syncing from scratch"
+ "Deleted cached identity for account: %{private,mask.hash}s"
+ "Failed to delete cached identity for account %{private,mask.hash}s: %@"
+ "Per-record fetch failure for %s in zone %s: %@"
+ "Processing request to delete the cached identity"
+ "Pulling zone changes for %ld zone(s) in database (%s)"
+ "Synthesized partialFailure for %ld record(s) with per-record decryption failures: %@"
+ "Zone %s had %ld per-record decryption failure(s); skipping flush and token update"
+ "com.apple.appleaccountd.identity-xpc-observer"
+ "com.apple.distnoted.matching.trusted"
+ "propertyListWithData:options:format:error:"
+ "record zone fetch complete. Zone: %s, Token: %s, Changed: %ld, Deleted: %ld, DecryptionErrors: %ld"
- "B24@?0q8@\"<OS_xpc_object>\"16"
- "UpdatedRCFlow"
- "_TtC13appleaccountd19PDPAndADPChecksMock"
- "bundleIDs"
- "isForcedUpdate"
- "isPlaceholder"
- "performCDPHealthCheckCalled"
- "performCDPHealthCheckStubbedError"
- "performPDPHealthCheckCalled"
- "performPDPHealthCheckStubbedError"
- "record zone fetch complete. Zone: %s, Token: %s, Changed: %ld, Deleted: %ld"
- "setRecordChangedBlock:"
- "v16@?0@\"CKRecord\"8"
```
