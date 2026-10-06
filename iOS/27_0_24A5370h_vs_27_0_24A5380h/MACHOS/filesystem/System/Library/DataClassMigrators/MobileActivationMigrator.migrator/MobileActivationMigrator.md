## MobileActivationMigrator

> `/System/Library/DataClassMigrators/MobileActivationMigrator.migrator/MobileActivationMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x5220` | `0x5340` | **`+0x120`** |
| `__TEXT.__cstring` | `0x3451` | `0x34c3` | **`+0x72`** |
| `__DATA_CONST.__const` | `0x1030` | `0x1088` | **`+0x58`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1144.0.0.0.0
+1145.0.1.0.0

-  Symbols:   768
-  CStrings:  834
+  Symbols:   779
+  CStrings:  843
Symbols:
+ _kMAOptionsBAABoardId
+ _kMAOptionsBAAChipID
+ _kMAOptionsBAADeviceLocalPolicyCertificate
+ _kMAOptionsBAARequestVersion
+ _kMAOptionsBAASCRT
+ _kMAOptionsBAASecurityDomain
+ _kMAOptionsBAASerialNumber
+ _kMAOptionsBAAUCRT
+ _kMAOptionsBAAUniqueChipID
+ _kMAOptionsBAAUseIM4C
+ _kMAOptionsBAAVMIdentityAttestation
CStrings:
+ "BoardId"
+ "ChipID"
+ "DeviceLocalPolicyCertificate"
+ "RequestVersion"
+ "SecurityDomain"
+ "UseIM4C"
+ "VMIdentityAttestation"
+ "scrt"
+ "ucrt"
```
