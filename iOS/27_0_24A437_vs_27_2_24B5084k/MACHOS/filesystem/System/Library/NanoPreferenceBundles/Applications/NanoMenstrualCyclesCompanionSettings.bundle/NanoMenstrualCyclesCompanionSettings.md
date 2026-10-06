## NanoMenstrualCyclesCompanionSettings

> `/System/Library/NanoPreferenceBundles/Applications/NanoMenstrualCyclesCompanionSettings.bundle/NanoMenstrualCyclesCompanionSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7498` | `0x6a30` | **`-0xa68`** |
| `__DATA.__bss` | `0x390` | `0x88` | **`-0x308`** |
| `__TEXT.__const` | `0x394` | `0x1c4` | **`-0x1d0`** |
| `__DATA_CONST.__auth_ptr` | `0x110` | `0x60` | **`-0xb0`** |
| `__TEXT.__auth_stubs` | `0xad0` | `0xa20` | **`-0xb0`** |
| `__DATA_CONST.__auth_got` | `0x570` | `0x518` | **`-0x58`** |
| `__TEXT.__swift5_typeref` | `0x1b0` | `0x15e` | **`-0x52`** |
| `__DATA.__data` | `0x388` | `0x350` | **`-0x38`** |
| `__TEXT.__constg_swiftt` | `0x1d0` | `0x198` | **`-0x38`** |
| `__TEXT.__unwind_info` | `0x230` | `0x1f8` | **`-0x38`** |
| `__TEXT.__swift5_assocty` | `0x48` | `0x18` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x270` | `0x248` | **`-0x28`** |
| `__TEXT.__swift5_reflstr` | `0x121` | `0xfe` | **`-0x23`** |
| `__TEXT.__objc_methname` | `0x4db` | `0x4bb` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xd0` | `0xb4` | **`-0x1c`** |
| `__DATA_CONST.__got` | `0x220` | `0x208` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x1c` | `0x4` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `—` | **`-0x14`** |
| `__TEXT.__swift5_types` | `0x10` | `0xc` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

+  - /System/Library/PrivateFrameworks/HealthAppServices.framework/HealthAppServices

-  Functions: 134
-  Symbols:   157
+  Functions: 115
+  Symbols:   155
Symbols:
+ _OBJC_CLASS_$_LSApplicationWorkspace
- _OBJC_CLASS_$_UIApplication
- __swiftEmptyDictionarySingleton
- _swift_getForeignTypeMetadata
CStrings:
+ "defaultWorkspace"
+ "hk_asyncOpenURL:"
+ "initWithFeatureAvailabilityProviding:healthDataSource:"
- "initWithFeatureAvailabilityProviding:healthDataSource:currentCountryCode:"
- "openURL:options:completionHandler:"
- "sharedApplication"
```
