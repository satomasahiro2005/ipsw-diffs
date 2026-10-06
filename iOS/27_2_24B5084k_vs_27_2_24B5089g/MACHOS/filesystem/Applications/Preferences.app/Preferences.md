## Preferences

> `/Applications/Preferences.app/Preferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x129714` | `0x12a998` | **`+0x1284`** |
| `__TEXT.__eh_frame` | `0x6dec` | `0x6f74` | **`+0x188`** |
| `__TEXT.__const` | `0xadf4` | `0xaee4` | **`+0xf0`** |
| `__DATA.__data` | `0x7748` | `0x7820` | **`+0xd8`** |
| `__DATA.__objc_const` | `0x7518` | `0x75c8` | **`+0xb0`** |
| `__DATA.__bss` | `0x8368` | `0x83e8` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x5948` | `0x59c0` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x39b8` | `0x3a28` | **`+0x70`** |
| `__DATA.__objc_data` | `0x1598` | `0x15e8` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x26e8` | `0x2730` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x4c50` | `0x4c90` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x3af6` | `0x3b36` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x16a4` | `0x16d8` | **`+0x34`** |
| `__TEXT.__swift5_fieldmd` | `0x2ab4` | `0x2ae8` | **`+0x34`** |
| `__TEXT.__objc_classname` | `0xfbb` | `0xfeb` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x99ea` | `0x9a18` | **`+0x2e`** |
| `__DATA_CONST.__auth_got` | `0x2630` | `0x2650` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0xb98` | `0xbb8` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x5dc` | `0x5f4` | **`+0x18`** |
| `__TEXT.__cstring` | `0x6276` | `0x6266` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x2b0` | `0x2bc` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x2a0` | `0x2ac` | **`+0xc`** |
| `__DATA.__common` | `0x390` | `0x398` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x460` | `0x464` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x2b0` | `0x2b4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-2027.1.4.0.0
+2027.1.6.0.0

-  - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels

+  - /System/Library/PrivateFrameworks/SiriSetup.framework/SiriSetup

-  Functions: 4409
-  Symbols:   2301
-  CStrings:  1574
+  Functions: 4430
+  Symbols:   2305
+  CStrings:  1575
Symbols:
+ _$s9SiriSetup0A18SettingsAppearanceV14iconIdentifierSSvg
+ _$s9SiriSetup0A18SettingsAppearanceV21didChangeNotificationSo18NSNotificationNameavgZ
+ _$s9SiriSetup0A18SettingsAppearanceV5titleSSvg
+ _$s9SiriSetup0A18SettingsAppearanceV7currentACvgZ
+ _$s9SiriSetup0A18SettingsAppearanceVMa
- _$s16GenerativeModels0aB12AvailabilityV13shouldBeShown19inSettingsReturningSbSpySo20GMAvailabilityStatusVG_tFZ
CStrings:
+ "Siri appearance changed"
+ "_TtC11SettingsApp20SiriListItemProvider"
+ "com.apple.graphic-icon.apps-on-current-device"
- "com.apple.graphic-icon.apps-on-ipad"
- "com.apple.graphic-icon.apps-on-iphone"
```
