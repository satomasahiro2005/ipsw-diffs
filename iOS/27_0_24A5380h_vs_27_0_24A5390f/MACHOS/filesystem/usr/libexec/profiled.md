## profiled

> `/usr/libexec/profiled`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc8678` | `0xc88d8` | **`+0x260`** |
| `__TEXT.__oslogstring` | `0xfe30` | `0xfeb0` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x13400` | `0x133e0` | **`-0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x1e0` | `0x1f8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x11f0` | `0x1200` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x624c` | `0x625c` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x16b35` | `0x16b43` | **`+0xe`** |
| `__DATA.__objc_selrefs` | `0x54b8` | `0x54b0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x2118` | `0x2120` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1b58` | `0x1b60` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-2483.0.1.0.0
+2483.0.5.0.0

-  Functions: 2734
-  Symbols:   1797
-  CStrings:  5757
+  Functions: 2735
+  Symbols:   1798
+  CStrings:  5758
Symbols:
+ _MCFeatureAutoCapitalizationAllowed
+ _MCFixPermissionsOfManagedConfigurationDirectoryAndContentsFM
- _MCFixPermissionsOfSystemGroupContainerDirectoryAndContentsFM
CStrings:
+ "Failed to fix permissions of system profile library with errors %{public}@"
+ "Failed to fix permissions of user profile storage with errors %{public}@"
+ "User profiles storage check found errors: %{public}@"
+ "_fixPermissionsOnTheUserProfileStorageDirectoryAndContents"
+ "currentUnlockScreenTypeWithOutSimpleType:"
+ "unlockScreenTypeWithPublicPasscodeDict:isRecovery:deviceHandle:outSimplePasscodeType:"
- "Failed to fix permissions of device profile library with errors %{public}@"
- "currentUnlockScreenType"
- "currentUnlockSimplePasscodeType"
- "unlockScreenTypeWithPublicPasscodeDict:isRecovery:deviceHandle:"
- "unlockSimplePasscodeTypeWithPublicPasscodeDict:isRecovery:deviceHandle:"
```
