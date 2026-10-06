## ManagedConfiguration

> `/System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf7284` | `0xf79f8` | **`+0x774`** |
| `__TEXT.__oslogstring` | `0x96c3` | `0x9892` | **`+0x1cf`** |
| `__TEXT.__objc_methlist` | `0xb2ec` | `0xb35c` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0xd7e8` | `0xd850` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e00` | `0x5e48` | **`+0x48`** |
| `__TEXT.__cstring` | `0x1878f` | `0x187d2` | **`+0x43`** |
| `__AUTH_CONST.__cfstring` | `0x19720` | `0x19760` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x1048` | `0x1080` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x3250` | `0x3288` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x4dd8` | `0x4e00` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x994` | `0x99c` | **`+0x8`** |

### Other Changes

```diff

-2483.40.14.0.0
+2483.40.19.0.0

-  Functions: 5814
-  Symbols:   9726
-  CStrings:  4629
+  Functions: 5824
+  Symbols:   9740
+  CStrings:  4637
Symbols:
+ +[MCManifest _fileDataIfPresentAtPath:error:]
+ +[MCManifest installedProfileDataWithIdentifier:error:]
+ +[MCManifest installedSystemProfileDataWithIdentifier:error:]
+ +[MCManifest installedUserProfileDataWithIdentifier:error:]
+ -[MCManifest identifiersOfProfilesWithFilterFlags:error:]
+ -[MCManifest setSystemManifestLoadError:]
+ -[MCManifest setUserManifestLoadError:]
+ -[MCManifest systemManifestLoadError]
+ -[MCManifest userManifestLoadError]
+ _OBJC_IVAR_$_MCManifest._systemManifestLoadError
+ _OBJC_IVAR_$_MCManifest._userManifestLoadError
+ __OBJC_$_PROP_LIST_MCManifest
+ ___57-[MCManifest identifiersOfProfilesWithFilterFlags:error:]_block_invoke
+ ___block_descriptor_72_e8_32s40r48r56r64r_e5_v8?0lr40l8s32l8r48l8r56l8r64l8
CStrings:
+ "Account %{public}@ is already owned by %{public}@; nothing to transfer"
+ "ERROR_ACCOUNT_TAKEOVER_ALREADY_MANAGED_P_ID"
+ "MCManifest could not load the system manifest at %{public}@: %{public}@"
+ "MCManifest could not load the user manifest at %{public}@: %{public}@"
+ "MCManifest could not parse the system manifest at %{public}@: %{public}@"
+ "MCManifest could not parse the user manifest at %{public}@: %{public}@"
+ "MCManifest not writing the system manifest because the one on disk could not be loaded."
+ "MCManifest not writing the user manifest because the one on disk could not be loaded."
+ "com.apple.NanoMessages"
- "Account %{public}@ already owned by %{public}@; nothing to transfer"
```
