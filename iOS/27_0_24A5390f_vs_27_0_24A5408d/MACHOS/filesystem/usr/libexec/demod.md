## demod

> `/usr/libexec/demod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf66fc` | `0xf6b40` | **`+0x444`** |
| `__TEXT.__cstring` | `0x10d22` | `0x10ed2` | **`+0x1b0`** |
| `__TEXT.__oslogstring` | `0x1cc3c` | `0x1cd8c` | **`+0x150`** |
| `__DATA_CONST.__cfstring` | `0xeca0` | `0xed80` | **`+0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x4750` | `0x4790` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1b6c0` | `0x1b6a0` | **`-0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x4b0` | `0x4c8` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x21321` | `0x2130c` | **`-0x15`** |
| `__DATA.__objc_selrefs` | `0x8200` | `0x81f8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
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
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1871.0.42.0.0
+1871.0.51.0.0

-  Functions: 6088
+  Functions: 6092

-  CStrings:  10924
+  CStrings:  10934
CStrings:
+ "/var/mobile/Library/AgentSessionKitBackupStaging"
+ "/var/mobile/Library/IdentityServices/Persistence/com.apple.identityservices.dailyDeviceAddedNotificationData"
+ "/var/mobile/Library/IdentityServices/Persistence/com.apple.identityservicesd.offgrid.provisioning.store"
+ "/var/mobile/Library/IdentityServices/Persistence/com.apple.identityservicesd.waking-push-priority"
+ "Backup AgentSessionKitBackupStaging - Cannot find RelativePathsNotToBackupInMegaBackup under HomeDomain."
+ "Backup AgentSessionKitBackupStaging - Cannot find RelativePathsNotToBackupToService under HomeDomain."
+ "Backup AgentSessionKitBackupStaging - Cannot find RelativePathsToOnlyBackupEncrypted under HomeDomain."
+ "CleanHomeConfig"
+ "Library/AgentSessionKitBackupStaging"
+ "No primary home.  Carry on."
+ "com.apple.CompanionSetupKit"
- "standardUserDefaults"
```
