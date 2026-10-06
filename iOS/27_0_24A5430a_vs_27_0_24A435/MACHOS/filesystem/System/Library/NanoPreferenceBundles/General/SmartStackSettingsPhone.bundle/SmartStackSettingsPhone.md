## SmartStackSettingsPhone

> `/System/Library/NanoPreferenceBundles/General/SmartStackSettingsPhone.bundle/SmartStackSettingsPhone`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4bb0` | `0x5c20` | **`+0x1070`** |
| `__TEXT.__objc_methname` | `0x429` | `0x589` | **`+0x160`** |
| `__TEXT.__objc_stubs` | `0x280` | `0x3e0` | **`+0x160`** |
| `__TEXT.__auth_stubs` | `0x660` | `0x770` | **`+0x110`** |
| `__DATA.__data` | `0x3f8` | `0x488` | **`+0x90`** |
| `__DATA_CONST.__auth_got` | `0x338` | `0x3c0` | **`+0x88`** |
| `__DATA.__objc_selrefs` | `0x180` | `0x1f8` | **`+0x78`** |
| `__TEXT.__oslogstring` | `—` | `0x73` | **`+0x73`** |
| `__TEXT.__cstring` | `0x371` | `0x3d1` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x170` | `0x1d0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x1bc` | `0x214` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x1f8` | `0x240` | **`+0x48`** |
| `__TEXT.__const` | `0x354` | `0x394` | **`+0x40`** |
| `__DATA.__objc_const` | `0x360` | `0x390` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x197` | `0x1c7` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x178` | `0x1a0` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x292` | `0x2b4` | **`+0x22`** |
| `__DATA_CONST.__got` | `0xa8` | `0xc8` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x26c` | `0x28c` | **`+0x20`** |
| `__DATA.__objc_data` | `0x368` | `0x380` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x54` | `0x68` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x100` | `0x110` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x30` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xda` | `0xe8` | **`+0xe`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x4` | `0x8` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x8` | `0xc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 120
-  Symbols:   105
-  CStrings:  98
+  Functions: 139
+  Symbols:   118
+  CStrings:  121
Symbols:
+ _OBJC_CLASS_$_NHSSPrivacyDefaults
+ _OBJC_CLASS_$_NSNumber
+ _PSFooterTextGroupKey
+ __os_log_impl
+ _objc_release_x26
+ _objc_retain_x22
+ _objc_retain_x23
+ _objc_retain_x8
+ _os_log_type_enabled
+ _swift_arrayInitWithCopy
+ _swift_dynamicCast
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _swift_slowDealloc
CStrings:
+ "MUSIC_DETECTION_GROUP_ID"
+ "MUSIC_DETECTION_SWITCH_ID"
+ "Music Detection: failed to create group specifier"
+ "Music Detection: failed to create switch specifier"
+ "NHSSPrivacyDefaultsObserver"
+ "SmartStackSettingsPhone"
+ "boolValue"
+ "com.apple.NanoSmartStack"
+ "getMusicDetectionEnabled:"
+ "groupSpecifierWithID:"
+ "initWithBool:"
+ "localizedMicrophonePermissionSwitchFootnote"
+ "localizedMicrophonePermissionSwitchName"
+ "microphonePermission"
+ "preferenceSpecifierNamed:target:set:get:detail:cell:edit:"
+ "privacyDefaultsDidChange"
+ "reloadSpecifiers"
+ "setIdentifier:"
+ "setMicrophonePermission:"
+ "setMusicDetectionEnabled:for:"
+ "setProperty:forKey:"
+ "v32@0:8@16@24"
+ "viewDidDisappear:"
```
