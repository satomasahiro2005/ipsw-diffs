## com.apple.HealthKit.HealthKitTCCNotificationExtension

> `/System/Library/Frameworks/HealthKit.framework/PlugIns/com.apple.HealthKit.HealthKitTCCNotificationExtension.appex/com.apple.HealthKit.HealthKitTCCNotificationExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7a68` | `0xb2a4` | **`+0x383c`** |
| `__TEXT.__cstring` | `0xd6` | `0x2a6` | **`+0x1d0`** |
| `__DATA.__bss` | `0x348` | `0x4d8` | **`+0x190`** |
| `__TEXT.__eh_frame` | `—` | `0x188` | **`+0x188`** |
| `__TEXT.__auth_stubs` | `0xb20` | `0xc40` | **`+0x120`** |
| `__TEXT.__const` | `0x40a` | `0x4f2` | **`+0xe8`** |
| `__TEXT.__objc_stubs` | `0x420` | `0x500` | **`+0xe0`** |
| `__DATA.__data` | `0x420` | `0x4f0` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x1e0` | `0x2a8` | **`+0xc8`** |
| `__DATA_CONST.__const` | `0x3c0` | `0x468` | **`+0xa8`** |
| `__DATA_CONST.__auth_got` | `0x598` | `0x628` | **`+0x90`** |
| `__TEXT.__objc_methname` | `0x568` | `0x5f3` | **`+0x8b`** |
| `__DATA_CONST.__got` | `0x2f0` | `0x358` | **`+0x68`** |
| `__TEXT.__constg_swiftt` | `0x1c8` | `0x220` | **`+0x58`** |
| `__DATA.__objc_data` | `0x138` | `0x178` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x27d` | `0x2bb` | **`+0x3e`** |
| `__DATA.__objc_selrefs` | `0x1e0` | `0x218` | **`+0x38`** |
| `__DATA.__objc_const` | `0x200` | `0x220` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x60` | `0x78` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0xd4` | `0xec` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x190` | `0x1a0` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x18` | `0x24` | **`+0xc`** |
| `__TEXT.__swift5_reflstr` | `0x6d` | `0x78` | **`+0xb`** |
| `__TEXT.__swift5_capture` | `0x64` | `0x68` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x18` | `0x1c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-7027.0.67.2.1
+7027.0.72.2.5

-  Functions: 183
-  Symbols:   126
-  CStrings:  98
+  Functions: 239
+  Symbols:   134
+  CStrings:  112
Symbols:
+ _OBJC_CLASS_$_HKDisplayType
+ _OBJC_CLASS_$_NSBundle
+ _OBJC_CLASS_$_NSListFormatter
+ __swiftEmptyDictionarySingleton
+ _objc_release_x27
+ _objc_retain_x22
+ _objc_retain_x26
+ _objc_retain_x27
+ _swift_getExistentialTypeMetadata
+ _swift_release_n
+ _swift_release_x25
+ _swift_retain_x20
+ _swift_retain_x21
+ _swift_retain_x22
+ _swift_retain_x25
- _objc_retain_x23
- _swift_release_x23
- _swift_release_x26
- _swift_release_x27
- _swift_retain_x23
- _swift_retain_x27
- _swift_retain_x28
CStrings:
+ "Can access your data for: %@."
+ "ClientDisplayName"
+ "Final item in a truncated list of Health data types, e.g. 'Steps, Flights Climbed, and more'"
+ "Reminder body listing the Health topics an app can access when the app name is unavailable. %@ is the topic list."
+ "Reminder body listing the Health topics an app can access. First %@ is the app name, second %@ is the topic list."
+ "allDisplayTypes"
+ "categoryIdentifier"
+ "displayName"
+ "displayTypeIdentifier"
+ "localization"
+ "localizedStringByJoiningStrings:"
+ "mainBundle"
+ "topicsText"
+ "“%@” can access your data for: %@."
```
