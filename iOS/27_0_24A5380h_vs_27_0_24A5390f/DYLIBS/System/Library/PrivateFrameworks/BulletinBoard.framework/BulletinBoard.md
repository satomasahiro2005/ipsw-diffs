## BulletinBoard

> `/System/Library/PrivateFrameworks/BulletinBoard.framework/BulletinBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x748c0` | `0x786f4` | **`+0x3e34`** |
| `__TEXT.__oslogstring` | `0x5eea` | `0x65ef` | **`+0x705`** |
| `__AUTH_CONST.__cfstring` | `0x6960` | `0x6be0` | **`+0x280`** |
| `__AUTH.__objc_data` | `0x190` | `—` | **`-0x190`** |
| `__DATA_DIRTY.__objc_data` | `0x1720` | `0x18b0` | **`+0x190`** |
| `__TEXT.__cstring` | `0x62a4` | `0x6426` | **`+0x182`** |
| `__DATA_CONST.__const` | `0x1f90` | `0x2038` | **`+0xa8`** |
| `__TEXT.__const` | `0x170` | `0x190` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x860c` | `0x862c` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x20a0` | `0x20b8` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x107a8` | `0x107b8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3fb8` | `0x3fc0` | **`+0x8`** |

### Other Changes

```diff

-952.0.0.0.0
+953.100.0.0.0

-  Functions: 3355
-  Symbols:   5162
-  CStrings:  1378
+  Functions: 3365
+  Symbols:   5172
+  CStrings:  1431
Symbols:
+ -[BBBiometricResource isPasscodeSet]
+ -[BBSectionInfo changedPropertiesComparedTo:]
+ -[BBSectionInfoSettings changedPropertiesComparedTo:]
+ _BBStringFromBBAlertType
+ _BBStringFromBBAuthorizationStatus
+ _BBStringFromBBBulletinGroupingSetting
+ _BBStringFromBBSectionAnnounceSetting
+ _BBStringFromBBSectionCategory
+ _BBStringFromBBSectionInfoSetting
+ _BBStringFromBBSectionType
CStrings:
+ "%s: %@"
+ "%s: %@ -> %@"
+ "%{public}@: Read %lu BBSectionInfo entries from persistence"
+ "%{public}@: Read section info (version=%{public}@, encoded count=%lu)"
+ "%{public}@: Reading BBSectionInfo from persistence at %{public}@"
+ "%{public}@: Reading cleared sections from persistence"
+ "%{public}@: initialized"
+ "%{public}@: setSectionInfoByID count=%lu"
+ "(new) "
+ "BBPersistentStoreMigrator: decoded %lu section infos for migration"
+ "BBPersistentStoreMigrator: no migration needed (on-disk version already %lu)"
+ "BBPersistentStoreMigrator: on-disk version=%lu, target=%lu, encoded section count=%lu"
+ "BBPersistentStoreMigrator: running section ID migration"
+ "BBPersistentStoreMigrator: starting section info migration (target version %lu)"
+ "BBPersistentStoreMigrator: upgrading to version 1 (remove vestigial sections + content preview migration)"
+ "BBPersistentStoreMigrator: upgrading to version 2 (sanitize push settings)"
+ "BBPersistentStoreMigrator: v3 migration complete (locked=%lu, healed=%lu)"
+ "BBPersistentStoreMigrator: will migrate (needsSectionIDMigration=%{BOOL}d, versionBump=%{BOOL}d)"
+ "BBPersistentStoreMigrator: writing migrated section info (count=%lu) at version %lu"
+ "BBServer startup: loaded %lu section infos from persistent store"
+ "BBServer startup: loading data providers"
+ "BBServer startup: loading data providers and settings"
+ "BBServer startup: resuming XPC listeners"
+ "Effective content preview setting: %{public}@, raw: %{public}@, globalSetting: %{public}@, isLocked: %@"
+ "Protection state changed for %{public}@: wasLocked:%d isLocked=%d contentPreviewSetting=%ld"
+ "Writing section info with reason: '%{public}@'"
+ "[%{public}@] \tNew = %{public}@"
+ "[%{public}@] \tOld = %{public}@"
+ "[%{public}@] %{public}@: changed: {%{public}@}"
+ "[%{public}@] %{public}@: read from disk: %{public}@"
+ "[%{public}@] %{public}@: setSectionInfo changed: {%{public}@}"
+ "[%{public}@] Got effective contentPreviewSetting for lockedApp: %{public}@"
+ "[%{public}@] Saving updated section info changed: {%{public}@}"
+ "[%{public}@] loaded: %{public}@"
+ "[%{public}@] v3 migration: resetting content preview setting from ShowNever to Default for locked app"
+ "[%{public}@] v3 migration: setIsLocked=YES, contentPreviewSetting=%ld"
+ "announcePriorityNotificationsSetting"
+ "authorized"
+ "bulletins"
+ "denied"
+ "directMessagesSetting"
+ "enabledAll"
+ "enabledTimeSensitive"
+ "hasUserConfiguredDirectMessagesSetting"
+ "hasUserConfiguredTimeSensitiveSetting"
+ "invalid"
+ "managedSectionInfoSettings: {%@}"
+ "modal"
+ "none"
+ "notDetermined"
+ "notSupported"
+ "off"
+ "parentSection"
+ "provisional"
+ "sectionInfoSettings: {%@}"
+ "subsection"
+ "temporary"
+ "weeApp"
- "Protection state changed for %{public}@: isLocked=%d contentPreviewSetting=%ld"
- "Reading BBSectionInfo from persistence"
- "Reading cleared sections from persistence"
- "Resetting content preview setting from ShowNever to Default for locked app \"%{public}@\""
- "Saving updated section info for: %{public}@\n\tOld = %{public}@\n\tNew = %{public}@"
```
