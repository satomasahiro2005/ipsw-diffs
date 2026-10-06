## idcredd

> `/usr/libexec/idcredd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ad1c8` | `0x1add94` | **`+0xbcc`** |
| `__TEXT.__oslogstring` | `0xa7a9` | `0xa849` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xdb9b` | `0xdb1b` | **`-0x80`** |
| `__DATA_CONST.__const` | `0x5dd0` | `0x5e48` | **`+0x78`** |
| `__TEXT.__auth_stubs` | `0x40c0` | `0x4130` | **`+0x70`** |
| `__DATA.__data` | `0x40f0` | `0x4158` | **`+0x68`** |
| `__TEXT.__constg_swiftt` | `0x220c` | `0x225c` | **`+0x50`** |
| `__DATA.__objc_const` | `0x26c8` | `0x2708` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x16e7` | `0x1727` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x2068` | `0x20a0` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x16b0` | `0x16e0` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x2144` | `0x2174` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x13ffc` | `0x14024` | **`+0x28`** |
| `__TEXT.__const` | `0x55a8` | `0x55c8` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x2e15` | `0x2e35` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1624` | `0x163c` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x9c0` | `0x9c8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x2766` | `0x276e` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5488` | `0x5480` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-9.31.0.0.0
+9.34.0.0.0

-  Functions: 4067
-  Symbols:   1898
-  CStrings:  2123
+  Functions: 4071
+  Symbols:   1912
+  CStrings:  2124
Symbols:
+ _$s13CoreIDVShared0A14IDVFeatureFlagO26presentmentKeyACLHardeningyA2CmFWC
+ _$s13CoreIDVShared0A14IDVFeatureFlagOMa
+ _$s13CoreIDVShared16AppleIDVManagingP19addCredentialMaxAge_5toACLySd_So19SecAccessControlRefatKFTj
+ _$s13CoreIDVShared19FeatureFlagProviderVAA0cD9ProvidingAAWP
+ _$s13CoreIDVShared19FeatureFlagProviderVACycfC
+ _$s13CoreIDVShared19FeatureFlagProviderVMa
+ _$s13CoreIDVShared20FeatureFlagProvidingMp
+ _$s13CoreIDVShared20FeatureFlagProvidingP9isEnabledySbAA0a10IDVFeatureD0OFTj
+ _$s13CoreIDVShared8DIPErrorV4CodeO33idcsMissingPresentmentEntitlementyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO35idcsPresentmentSessionNotConfiguredyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO36idcsMissingBiometricStoreEntitlementyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO37idcsMissingCredentialStoreEntitlementyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO39idcsCredentialStoreSessionNotConfiguredyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO42idcsWildcardPartitionRequiresInternalBuildyA2EmFWC
+ _$s2os6LoggerV13CoreIDVSharedE7defaultACvgZ
+ _$sSo19SecAccessControlRefa13CoreIDVSharedE11constraintsSDySSypGvs
- _$s13CoreIDVShared8DIPErrorV4CodeO18missingEntitlementyA2EmFWC
- _$s13CoreIDVShared8DIPErrorV4CodeO21unexpectedDaemonStateyA2EmFWC
CStrings:
+ "Applying credential max-age of %f seconds"
+ "Applying presentment key ACL constraints: pcma=%ld pmuc=%ld"
+ "Could not parse ACL from data: %@"
+ "featureFlagProvider"
- "Unknown session encryption mode"
- "Unrecognized session encryption mode"
- "debug.allow-apple-test-reader-certs"
```
