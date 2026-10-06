## coreidvd

> `/usr/libexec/coreidvd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e5f84` | `0x6e7e0c` | **`+0x1e88`** |
| `__DATA_CONST.__const` | `0x24300` | `0x24490` | **`+0x190`** |
| `__TEXT.__oslogstring` | `0x2dad9` | `0x2dbd9` | **`+0x100`** |
| `__TEXT.__constg_swiftt` | `0xd88c` | `0xd944` | **`+0xb8`** |
| `__TEXT.__eh_frame` | `0x47508` | `0x475c0` | **`+0xb8`** |
| `__DATA.__data` | `0x17f30` | `0x17fe0` | **`+0xb0`** |
| `__TEXT.__const` | `0x323c0` | `0x32460` | **`+0xa0`** |
| `__DATA.__bss` | `0x37d30` | `0x37db0` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0xd1a0` | `0xd1f0` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x6334` | `0x6384` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x378c` | `0x37c8` | **`+0x3c`** |
| `__DATA_CONST.__got` | `0x41d0` | `0x4208` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x15ef0` | `0x15f20` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x68e0` | `0x6908` | **`+0x28`** |
| `__DATA_CONST.__auth_ptr` | `0x2378` | `0x2388` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-9.31.0.0.0
+9.34.0.0.0

-  Functions: 18739
-  Symbols:   5907
-  CStrings:  8471
+  Functions: 18756
+  Symbols:   5919
+  CStrings:  8476
Symbols:
+ _$s11Distributed0A5ActorP15unownedExecutorScevgTj
+ _$s13CoreIDVShared8DIPErrorV4CodeO27docUploadMissingEntitlementyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO28dipSessionMissingEntitlementyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO32documentReaderMissingEntitlementyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO34identityProofingMissingEntitlementyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO36digitalPresentmentMissingEntitlementyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO36identityManagementMissingEntitlementyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO38identityProvisioningMissingEntitlementyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO45identityProofingDataSharingMissingEntitlementyA2EmFWC
+ _$s2os6LoggerV13CoreIDVSharedE7defaultACvgZ
+ _$s7CoreIDV40IdentityDocumentPresentmentConfigurationV12RelyingPartyV0gH4TypeO03WebF0V13displayOriginSSvg
+ _$s7CoreIDV40IdentityDocumentPresentmentConfigurationV12RelyingPartyV0gH4TypeO03WebF0VMa
+ _objc_retain_x10
- _$s13CoreIDVShared8DIPErrorV4CodeO18missingEntitlementyA2EmFWC
CStrings:
+ "Could not schedule uploads: %@"
+ "Delete account key signing key failed with error: %@"
+ "Error occurred whilst removing proofing session: %{public}@"
+ "Failed to fetch NPK companion header: %@"
+ "Failed to fetch pending watch proofing sessions count: %@"
+ "Failed to store PII hash on watch with error: %{public}@"
- "(Non terminal error): Failed to store PII hash on watch with error: %{public}@"
```
