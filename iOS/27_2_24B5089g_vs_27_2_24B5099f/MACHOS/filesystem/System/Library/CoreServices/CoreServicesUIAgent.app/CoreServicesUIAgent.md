## CoreServicesUIAgent

> `/System/Library/CoreServices/CoreServicesUIAgent.app/CoreServicesUIAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17d24` | `0x183d8` | **`+0x6b4`** |
| `__TEXT.__oslogstring` | `0xa7f` | `0xb2f` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x990` | `0x9e0` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x2eb6` | `0x2f06` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x662` | `0x6aa` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0xe30` | `0xe70` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1020` | `0x1060` | **`+0x40`** |
| `__DATA.__common` | `0xb0` | `0x90` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x720` | `0x740` | **`+0x20`** |
| `__TEXT.__const` | `0xb34` | `0xb54` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x124` | `0x144` | **`+0x20`** |
| `__DATA.__objc_const` | `0x1208` | `0x1220` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x268` | `0x280` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xa68` | `0xa78` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1143` | `0x1153` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5e0` | `0x5f0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x240` | `0x248` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xd60` | `0xd68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
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

-469.1.7.0.0
+469.1.10.0.0

-  Functions: 450
-  Symbols:   403
-  CStrings:  687
+  Functions: 456
+  Symbols:   411
+  CStrings:  695
Symbols:
+ _$s7SwiftUI15ModifiedContentVyxq_GAA4ViewA2aERzAA0E8ModifierR_rlMc
+ _$s7SwiftUI31AccessibilityAttachmentModifierVAA04ViewE0AAMc
+ _$s7SwiftUI31AccessibilityAttachmentModifierVMa
+ _$s7SwiftUI31AccessibilityAttachmentModifierVMn
+ _$s7SwiftUI4ViewPAAE19accessibilityHiddenyAA15ModifiedContentVyxAA31AccessibilityAttachmentModifierVGSbF
+ _$ss26DefaultStringInterpolationV06appendC0yyxlF
+ _OBJC_CLASS_$_OBHeaderAccessoryButton
+ _swift_release_x25
+ _swift_retain_x1
- _swift_release_x23
CStrings:
+ "Explanatory text about what app replacement does, shown in alert detail"
+ "MigrationContext("
+ "Move Existing App Data and Settings to New App"
+ "T@\"NSString\",N,R"
+ "The app developer recommends moving your existing “%1$@” app data and settings to the new “%2$@” app.\n\nYour device can do this for you now, before you start using the new app. Afterwards, the old app will be deleted from this device. You won't have another opportunity to move your existing app data and settings to the new app."
+ "The existing “%1$@” app is being restored from backup. Try again later."
+ "The existing “%1$@” app is busy. Try again later."
+ "The existing “%1$@” app is installing. Try again later."
+ "The existing “%1$@” app is updating. Try again later."
+ "Unable to Move App Data and Settings"
+ "Will present migration flow view controller for migration: %@"
+ "Your device was unable to move your existing “%1$@” app data and settings to the new “%2$@” app."
+ "accessoryButton"
+ "addAccessoryButton:"
+ "after unexpected error, declining migration"
+ "generic exposition on failure for app migration interpolating app names"
+ "https://support.apple.com/148930"
+ "migration source for %@ is %@"
+ "will offer migration to %@"
- "Are you sure you don’t want to move app data and settings?"
- "Could Not Move App Data and Settings from “%1$@”"
- "Move Existing App Data and Settings to This App"
- "Some data and settings failed to transfer. %@"
- "The developer recommends moving your existing “%1$@” app data and settings to the new “%2$@” app.\n\nYour device can do this for you now, before you start using your new app. Afterwards, the old app will be deleted from this device."
- "The existing “%1$@” is being restored from backup. Try again later."
- "The existing “%1$@” is busy. Try again later."
- "The existing “%1$@” is installing. Try again later."
- "The existing “%1$@” is updating. Try again later."
- "You’ll be able to use this app right away, but you may be asked to set up your preferences again for settings like notifications, location access, and more.\n\nYour device can take care of this for you automatically."
- "generic exposition on failure for app migration. Error's localized description is interpolated"
```
