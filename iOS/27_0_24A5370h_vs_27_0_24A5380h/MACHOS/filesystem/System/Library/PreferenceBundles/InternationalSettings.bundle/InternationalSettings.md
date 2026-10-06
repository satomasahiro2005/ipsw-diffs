## InternationalSettings

> `/System/Library/PreferenceBundles/InternationalSettings.bundle/InternationalSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20050` | `0x207e4` | **`+0x794`** |
| `__TEXT.__objc_stubs` | `0x46c0` | `0x47e0` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x593e` | `0x5a55` | **`+0x117`** |
| `__DATA.__objc_data` | `0xb48` | `0xc00` | **`+0xb8`** |
| `__DATA.__objc_const` | `0x25c8` | `0x2678` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x1601` | `0x1691` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0xe40` | `0xec0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x18e8` | `0x1960` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0x1788` | `0x17e8` | **`+0x60`** |
| `__TEXT.__const` | `0x5d0` | `0x620` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x36c` | `0x325` | **`-0x47`** |
| `__DATA_CONST.__auth_got` | `0x730` | `0x770` | **`+0x40`** |
| `__DATA.__data` | `0x648` | `0x680` | **`+0x38`** |
| `__TEXT.__objc_classname` | `0x5c7` | `0x5f7` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x290` | `0x2bc` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x4e0` | `0x508` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0xec` | `0x114` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x9b8` | `0x998` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0xf1` | `0x109` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x190` | `0x17c` | **`-0x14`** |
| `__TEXT.__swift5_typeref` | `0x3bb` | `0x3c5` | **`+0xa`** |
| `__DATA.__common` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x218` | `0x220` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x100` | `0x108` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0xd8` | `0xe0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x740` | `0x748` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x18` | `0x1c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-295.3.0.0.0
+297.0.0.0.0

-  Functions: 609
-  Symbols:   393
-  CStrings:  1280
+  Functions: 622
+  Symbols:   398
+  CStrings:  1296
Symbols:
+ _OBJC_CLASS_$_NSMutableSet
+ __os_log_error_impl
+ _objc_retain_x28
+ _swift_getObjectType
+ _swift_once
CStrings:
+ "Deep link activated but IPLanguageDiscoveryPostedLanguages is nil or empty: %{private}@"
+ "IPLanguageDiscoveryPostedLanguages"
+ "LanguageDiscoveryDeepLinkActivated"
+ "LanguageDiscoveryDeepLinkTrigger"
+ "T@\"NSString\",N,R"
+ "TB,N,Vpending"
+ "clearLanguageDiscoveryFollowUp"
+ "fire"
+ "handleLanguageDiscoveryDeepLink:"
+ "isViewLoaded"
+ "minusSet:"
+ "notificationNameString"
+ "pending"
+ "persistRejectedLanguage:"
+ "postNotificationName:object:"
+ "setPending:"
+ "specifierPropertyKey"
+ "window"
- "Deep link activated but language %{public}@ filtered out (already in use or previously confirmed)"
- "Deep link activated but no primary discovered language found"
```
