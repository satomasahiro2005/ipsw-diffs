## DeveloperSettings

> `/System/Library/PreferenceBundles/DeveloperSettings.bundle/DeveloperSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23138` | `0x22edc` | **`-0x25c`** |
| `__TEXT.__objc_methname` | `0x5e21` | `0x5da0` | **`-0x81`** |
| `__TEXT.__objc_stubs` | `0x50e0` | `0x5080` | **`-0x60`** |
| `__DATA_CONST.__const` | `0xfc0` | `0xff0` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x1b98` | `0x1b70` | **`-0x28`** |
| `__DATA_CONST.__got` | `0x678` | `0x668` | **`-0x10`** |
| `__TEXT.__cstring` | `0x2c4a` | `0x2c3d` | **`-0xd`** |
| `__TEXT.__unwind_info` | `0x8a8` | `0x8b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.0.2.0.0
+2027.0.3.0.0

-  Symbols:   499
-  CStrings:  1668
+  Symbols:   498
+  CStrings:  1663
Symbols:
- _OBJC_CLASS_$_ASFeatureManager
CStrings:
+ "AUTHENTICATION_SERVICES_DEVELOPER_SETTINGS"
+ "AUTHENTICATION_SERVICES_DEVELOPER_SETTINGS_GROUP"
+ "AuthenticationServicesDeveloperSettings"
+ "PASSWORDS_DEVELOPER_SETTINGS"
+ "PASSWORDS_DEVELOPER_SETTINGS_GROUP"
+ "PasswordsDeveloperSettings"
+ "_isAuthenticationServicesDeveloperSettingsAvailable"
+ "_isPasswordsDeveloperSettingsAvailable"
- "AUTHENTICATION_SERVICES_GROUP"
- "AUTHENTICATION_SERVICES_QUIRKS_BUTTON"
- "AUTHENTICATION_SERVICES_QUIRK_IMPORT_COMMIT_BUTTON_FORMAT"
- "AUTHENTICATION_SERVICES_TESTING_FOOTER"
- "AUTHENTICATION_SERVICES_TESTING_FOOTER_FORMAT"
- "AUTHENTICATION_SERVICES_TESTING_LEARN_MORE"
- "localizedStandardRangeOfString:"
- "passwordManagerResourcesProjectImportCommit"
- "passwordManagerResourcesProjectImportCommitURL"
- "passwordManagerResourcesProjectURL"
- "sharedManager"
- "tappedOnQuirksButton:"
- "tappedOnQuirksRepoButton:"
```
