## PrivacyAndSecuritySettings

> `/System/Library/PreferenceBundles/PrivacyAndSecuritySettings.bundle/PrivacyAndSecuritySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8dc48` | `0x8efbc` | **`+0x1374`** |
| `__TEXT.__oslogstring` | `0xbe1` | `0xea1` | **`+0x2c0`** |
| `__TEXT.__swift5_typeref` | `0x7e36` | `0x7d8a` | **`-0xac`** |
| `__TEXT.__auth_stubs` | `0x2c10` | `0x2c80` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x1618` | `0x1650` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x3900` | `0x3928` | **`+0x28`** |
| `__TEXT.__cstring` | `0x4446` | `0x4466` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1f55` | `0x1f75` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x5a9` | `0x5c9` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xf40` | `0xf60` | **`+0x20`** |
| `__DATA.__common` | `0xe0` | `0xf8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1ed8` | `0x1ef0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xb38` | `0xb48` | **`+0x10`** |
| `__TEXT.__const` | `0x7404` | `0x73f4` | **`-0x10`** |
| `__DATA.__data` | `0x3e68` | `0x3e70` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x668` | `0x670` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xd40` | `0xd48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.0.4.0.0
+2027.0.6.101.0

-  Functions: 2517
+  Functions: 2525

-  CStrings:  874
+  CStrings:  884
CStrings:
+ "Communication Safety background setup complete; forcing initial data model rebuild."
+ "Communication Safety revalidation"
+ "Connection error to ProxiedCrashCopier: %{public}s"
+ "Search Analytics Logs"
+ "handleOnSettingsExperienceOpenURL: blocking deep link into Sensitive Content Warning; row is disabled by Communication Safety."
+ "handleURL: blocking deep link into Sensitive Content Warning; row is disabled by Communication Safety."
+ "initAsynchronousWithErrorHandler:"
+ "revalidateCommunicationSafety: invalidating to re-read live Communication Safety policy."
+ "revalidateCommunicationSafety: setup not yet complete; skipping (rebuild is forced on completion)."
+ "toDataModel: nudityDetectionRowEnabled=%{bool,public}d -> overrideIsSelectable=%{bool,public}d"
+ "v16@?0@\"NSError\"8"
- "com.apple.application-icon.apple-intelligence"
```
