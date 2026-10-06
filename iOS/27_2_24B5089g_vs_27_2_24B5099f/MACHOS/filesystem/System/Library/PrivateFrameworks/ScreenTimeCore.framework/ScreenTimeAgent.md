## ScreenTimeAgent

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x170c1c` | `0x172d04` | **`+0x20e8`** |
| `__TEXT.__oslogstring` | `0x172f0` | `0x174d0` | **`+0x1e0`** |
| `__DATA_CONST.__const` | `0xce70` | `0xcf60` | **`+0xf0`** |
| `__DATA.__objc_const` | `0x21778` | `0x21848` | **`+0xd0`** |
| `__TEXT.__objc_methname` | `0x1f365` | `0x1f425` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x7a50` | `0x7acc` | **`+0x7c`** |
| `__TEXT.__swift5_reflstr` | `0x2cd9` | `0x2d29` | **`+0x50`** |
| `__DATA.__data` | `0x8bb0` | `0x8bf0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x2fd0` | `0x3010` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xa864` | `0xa8a4` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x13b20` | `0x13b60` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x2a08` | `0x2a48` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x2360` | `0x2384` | **`+0x24`** |
| `__DATA_CONST.__auth_got` | `0x17f8` | `0x1818` | **`+0x20`** |
| `__TEXT.__const` | `0x7770` | `0x7790` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x53d8` | `0x53f8` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x5b88` | `0x5b98` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1710` | `0x1720` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x3bb0` | `0x3bba` | **`+0xa`** |
| `__DATA.__objc_data` | `0x5418` | `0x5420` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x9c0` | `0x9c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-655.1.9.1.0
+655.1.12.0.0

-  Functions: 7386
-  Symbols:   1659
-  CStrings:  7797
+  Functions: 7407
+  Symbols:   1666
+  CStrings:  7808
Symbols:
+ _$s10Foundation10CocoaErrorV4CodeV014fileNoSuchFileC0AEvgZ
+ _$s10Foundation10CocoaErrorV4CodeVSQAAMc
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$s15ScreenTimeSwift0aB16SettingsMigratorV27isShareAcrossDevicesEnabledSbvg
+ _$s26ScreenTimeSettingsServices0abC0C6UpdateV9migrationAC9MigrationVADVvM
+ _$s26ScreenTimeSettingsServices0abC0C6UpdateVAEycfC
+ _$s26ScreenTimeSettingsServices0abC0C9MigrationV6UpdateV5stateAE5StateOSgvs
+ _OBJC_CLASS_$_STAppDataMigrator
- _$sSL2leoiySbx_xtFZTj
CStrings:
+ "Cleared migration journal at %{public}s"
+ "Failed to clear migration journal: %{public}s"
+ "Failed to migrate app data from %{public}@ to %{public}@: %{public}@"
+ "Failed to reassert migration state: %{public}@"
+ "Handling account change; isSignedIn=%{bool,public}d"
+ "Migrated app data from %{public}@ to %{public}@"
+ "Re-asserted migration state on already-migrated device"
+ "Signed out; stopping upgrade eligibility monitoring and clearing per-account state"
+ "fileRemover"
+ "migrateAppDataFromBundleIdentifier:toBundleIdentifier:completionHandler:"
+ "migrateAppDataFromBundleIdentifier:toBundleIdentifier:persistenceController:completionHandler:"
```
