## ScreenTimeWidgetExtension

> `/Applications/Screen Time.app/PlugIns/ScreenTimeWidgetExtension.appex/ScreenTimeWidgetExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41704` | `0x4a1f8` | **`+0x8af4`** |
| `__TEXT.__eh_frame` | `0x928` | `0x1058` | **`+0x730`** |
| `__TEXT.__oslogstring` | `0xf25` | `0x11d5` | **`+0x2b0`** |
| `__TEXT.__objc_stubs` | `0xc40` | `0xe00` | **`+0x1c0`** |
| `__TEXT.__auth_stubs` | `0x1e60` | `0x1fe0` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0xa08` | `0xb70` | **`+0x168`** |
| `__DATA_CONST.__const` | `0x1438` | `0x1550` | **`+0x118`** |
| `__TEXT.__objc_methname` | `0xd35` | `0xe15` | **`+0xe0`** |
| `__TEXT.__const` | `0x20c8` | `0x2198` | **`+0xd0`** |
| `__DATA_CONST.__auth_got` | `0xf38` | `0xff8` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x3cb8` | `0x3d4e` | **`+0x96`** |
| `__DATA.__objc_selrefs` | `0x448` | `0x4b8` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x638` | `0x6a0` | **`+0x68`** |
| `__TEXT.__swift_as_cont` | `0x40` | `0xa4` | **`+0x64`** |
| `__TEXT.__swift5_capture` | `0x428` | `0x478` | **`+0x50`** |
| `__DATA.__data` | `0x1970` | `0x19b0` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x35a` | `0x39a` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x30` | `0x6c` | **`+0x3c`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x4c` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0xbec` | `0xbfc` | **`+0x10`** |
| `__TEXT.__cstring` | `0x4d3` | `0x4c3` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x5f8` | `0x600` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-655.0.101.0.0
+655.0.106.0.0
+  - /System/Library/Frameworks/Accounts.framework/Accounts

-  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags
+  - /System/Library/PrivateFrameworks/FamilyCircle.framework/FamilyCircle

+  - /System/Library/PrivateFrameworks/ScreenTimeSettingsServices.framework/ScreenTimeSettingsServices

-  Functions: 912
-  Symbols:   231
-  CStrings:  300
+  Functions: 978
+  Symbols:   237
+  CStrings:  328
Symbols:
+ _OBJC_CLASS_$_ACAccountStore
+ _OBJC_CLASS_$_FAFetchFamilyCircleRequest
+ _STShouldHideBundleIdentifierFromUI
+ _objc_release_x9
+ _swift_continuation_throwingResume
+ _swift_continuation_throwingResumeWithError
+ _swift_setDeallocating
- _swift_allocBox
CStrings:
+ "Current user is migrated to new Screen Time, always using Device Activity."
+ "Failed to create ScreenTimeSettings for remote user: %{public}@"
+ "Failed to fetch ScreenTimeSettings for family member: %{public}@"
+ "Failed to fetch family"
+ "Failed to fetch family member DSID or altDSID"
+ "Failed to fetch family: %{public}@"
+ "Failed to fetch local user"
+ "Failed to find family member with dsid: %{private}s"
+ "Failed to initialize ScreenTimeSettings for current user: %{public}@"
+ "Failed to load ScreenTimeSettings for me: %{public}@"
+ "Family member missing altDSID."
+ "No local user found."
+ "No local user settings provided. Returning nil user."
+ "aa_altDSID"
+ "aa_firstName"
+ "aa_lastName"
+ "aa_personID"
+ "aa_primaryAppleAccount"
+ "aa_primaryAppleAccountWithCompletion:"
+ "aa_primaryEmail"
+ "defaultStore"
+ "firstName"
+ "isGuardian"
+ "lastName"
+ "longLongValue"
+ "me"
+ "startRequestWithCompletionHandler:"
+ "v24@?0@\"ACAccount\"8@\"NSError\"16"
+ "v24@?0@\"FAFamilyCircle\"8@\"NSError\"16"
- "couldn't fetch local user"
```
