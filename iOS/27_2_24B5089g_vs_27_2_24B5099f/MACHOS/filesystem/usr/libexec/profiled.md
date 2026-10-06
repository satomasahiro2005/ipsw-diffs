## profiled

> `/usr/libexec/profiled`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc93bc` | `0xc9784` | **`+0x3c8`** |
| `__TEXT.__oslogstring` | `0xfed0` | `0x100b0` | **`+0x1e0`** |
| `__TEXT.__objc_methname` | `0x16b77` | `0x16c17` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x13400` | `0x13480` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x54b8` | `0x54d8` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x86e0` | `0x8700` | **`+0x20`** |
| `__TEXT.__cstring` | `0xa9ea` | `0xaa0a` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x620c` | `0x6214` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2483.40.14.0.0
+2483.40.19.0.0

-  Functions: 2737
+  Functions: 2738

-  CStrings:  5766
+  CStrings:  5779
CStrings:
+ "Finished updating user auto lock time if necessary"
+ "MCInstaller could not parse installed profile %{public}@: %{public}@"
+ "MCInstaller could not read installed profile %{public}@: %{public}@"
+ "MCInstaller could not read one or more installed profiles. Skipping MDM clean up."
+ "MCInstaller found no stub on disk for installed profile %{public}@"
+ "MCMigrator.MigratePostDataMigrator"
+ "No default value found for auto lock time"
+ "Updating user auto lock time if necessary..."
+ "Updating user auto lock time to %{public}@"
+ "_updateUserAutoLockTimeIfNecessary"
+ "defaultValueForSetting:"
+ "identifiersOfProfilesWithFilterFlags:error:"
+ "installedProfileDataWithIdentifier:error:"
+ "isAuthorizedForOperation:policy:completion:"
- "isAuthorizedForOperation:completion:"
```
