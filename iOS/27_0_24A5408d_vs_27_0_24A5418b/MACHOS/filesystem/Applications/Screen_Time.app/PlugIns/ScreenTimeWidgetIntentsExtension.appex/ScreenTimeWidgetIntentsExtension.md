## ScreenTimeWidgetIntentsExtension

> `/Applications/Screen Time.app/PlugIns/ScreenTimeWidgetIntentsExtension.appex/ScreenTimeWidgetIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x614c` | `0xaaf8` | **`+0x49ac`** |
| `__TEXT.__eh_frame` | `—` | `0x418` | **`+0x418`** |
| `__TEXT.__auth_stubs` | `0x740` | `0xa00` | **`+0x2c0`** |
| `__TEXT.__objc_stubs` | `0x4a0` | `0x620` | **`+0x180`** |
| `__DATA_CONST.__auth_got` | `0x3a8` | `0x508` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x314` | `0x424` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x218` | `0x318` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x348` | `0x438` | **`+0xf0`** |
| `__TEXT.__const` | `0x578` | `0x628` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x2fc` | `0x38e` | **`+0x92`** |
| `__TEXT.__objc_methname` | `0x8d5` | `0x965` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0x260` | `0x2c0` | **`+0x60`** |
| `__DATA_CONST.__got` | `0xd8` | `0x138` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x68` | `0xc8` | **`+0x60`** |
| `__DATA.__data` | `0x778` | `0x7b8` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `—` | `0x2c` | **`+0x2c`** |
| `__TEXT.__swift_as_ret` | `—` | `0x24` | **`+0x24`** |
| `__TEXT.__objc_methtype` | `0x31a` | `0x33a` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `—` | `0x1c` | **`+0x1c`** |
| `__DATA_CONST.__auth_ptr` | `0xd8` | `0xf0` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x564` | `0x574` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-655.0.101.0.0
+655.0.106.0.0
+  - /System/Library/Frameworks/Accounts.framework/Accounts

+  - /System/Library/PrivateFrameworks/FamilyCircle.framework/FamilyCircle

+  - /System/Library/PrivateFrameworks/ScreenTimeSettingsServices.framework/ScreenTimeSettingsServices

-  Functions: 172
-  Symbols:   150
-  CStrings:  165
+  Functions: 222
+  Symbols:   173
+  CStrings:  183
Symbols:
+ _OBJC_CLASS_$_ACAccountStore
+ _OBJC_CLASS_$_FAFetchFamilyCircleRequest
+ _objc_release_x9
+ _objc_retain_x25
+ _objc_retain_x26
+ _objc_retain_x27
+ _swift_allocError
+ _swift_bridgeObjectRetain_n
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_continuation_throwingResume
+ _swift_continuation_throwingResumeWithError
+ _swift_initStackObject
+ _swift_release_x24
+ _swift_release_x27
+ _swift_release_x28
+ _swift_retain_x21
+ _swift_retain_x24
+ _swift_retain_x25
+ _swift_retain_x28
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _swift_unknownObjectRelease
- _swift_endAccess
- _swift_retain_x22
CStrings:
+ "Failed to fetch ScreenTimeSettings for family member: %{public}@"
+ "Failed to fetch family"
+ "Failed to fetch family member DSID or altDSID"
+ "Failed to fetch local user"
+ "Failed to initialize ScreenTimeSettings for current user: %{public}@"
+ "No local user found."
+ "aa_firstName"
+ "aa_lastName"
+ "aa_personID"
+ "aa_primaryAppleAccount"
+ "altDSID"
+ "defaultStore"
+ "firstName"
+ "isGuardian"
+ "lastName"
+ "longLongValue"
+ "me"
+ "startRequestWithCompletionHandler:"
+ "v24@?0@\"FAFamilyCircle\"8@\"NSError\"16"
- "couldn't fetch local user"
```
