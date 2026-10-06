## AppleAccountSettings

> `/System/Library/PreferenceBundles/AccountSettings/AppleAccountSettings.bundle/AppleAccountSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42e98` | `0x4218c` | **`-0xd0c`** |
| `__TEXT.__oslogstring` | `0x5176` | `0x5096` | **`-0xe0`** |
| `__TEXT.__cstring` | `0x20b7` | `0x1fe7` | **`-0xd0`** |
| `__DATA_CONST.__const` | `0x1fa8` | `0x1ee0` | **`-0xc8`** |
| `__DATA_CONST.__cfstring` | `0x1ac0` | `0x1a20` | **`-0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x5d8` | `0x594` | **`-0x44`** |
| `__TEXT.__unwind_info` | `0x1190` | `0x1168` | **`-0x28`** |
| `__TEXT.__objc_stubs` | `0x7f40` | `0x7f60` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x6e0` | `0x6f0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x2b50` | `0x2b40` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x2b18` | `0x2b20` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x54` | `0x5c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x30` | `0x34` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methname`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-584.0.0.0.0
+588.0.0.0.0

-  Functions: 1514
-  Symbols:   645
-  CStrings:  2724
+  Functions: 1505
+  Symbols:   648
+  CStrings:  2710
Symbols:
+ OBJC_IVAR_$_AAUIFMIPHeaderDeviceInfoPageSurrogate._appleAccount
+ OBJC_IVAR_$_AAUIFMIPHeaderDeviceInfoPageSurrogate._device
+ OBJC_IVAR_$_AAUIFMIPHeaderDeviceInfoPageSurrogate._remoteUIPage
CStrings:
+ "RemoteUIControllerHelper: mutable copy failed; fetching unsigned, eligibility-gated content may be missing"
+ "RemoteUIControllerHelper: signing cache-fill request before fetch"
+ "Split-account device: signing out iCloud; Store signed out via signOutServiceAccounts if DSID or altDSID matches."
+ "_refreshSpecifiersForAccountChange"
+ "setInsetsLayoutMarginsFromSafeArea:"
+ "setPreservesSuperviewLayoutMargins:"
- "%s: self is nil"
- "-[AAUIAppleAccountViewController _deleteButtonTapped:]_block_invoke"
- "Apple account and store account have matching DSIDs!"
- "Apple account and store account have matching altDSIDs!"
- "MULTIPLE_SERVICES_CANCEL"
- "MULTIPLE_SERVICES_MESSAGE"
- "MULTIPLE_SERVICES_SIGN_OUT_BOTH"
- "MULTIPLE_SERVICES_SIGN_OUT_CLOUD"
- "MULTIPLE_SERVICES_SIGN_OUT_STORE"
- "Not signing out of any accounts..."
- "Sign out of apple account completed with success: %@, error: %@"
- "Signing out store account %@ now..."
- "Store sign out completed with success %@, error: %@"
- "User opted to cancel sign out!"
- "User opted to sign out of apple account."
- "User opted to sign out of both accounts."
- "User opted to sign out of store account."
- "User signed in to iCloud & Store, prompting for clarification..."
- "_loadSecurityControllerWithoutCacheCheckingNetwork"
- "_promptForAccountSignOutAppleAccount:storeAccount:completion:"
```
