## GeneralSettingsIntents

> `/System/Library/ExtensionKit/Extensions/GeneralSettingsIntents.appex/GeneralSettingsIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd698` | `0xdeec` | **`+0x854`** |
| `__TEXT.__cstring` | `0x29a1` | `0x2e91` | **`+0x4f0`** |
| `__TEXT.__swift5_reflstr` | `0x430` | `0x4c0` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x6b0` | `0x730` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x2b0` | `0x2ec` | **`+0x3c`** |
| `__TEXT.__auth_stubs` | `0xb20` | `0xb10` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x598` | `0x590` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1a8` | `0x1a0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1259.0.0.0.0
+2027.0.2.0.0

-  Symbols:   123
-  CStrings:  219
+  Symbols:   122
+  CStrings:  234
Symbols:
- _swift_willThrowTypedImpl
Functions:
~ sub_100001b28 : 904 -> 992
~ sub_100001eb0 -> sub_100001f08 : 128 -> 148
~ sub_100002b28 -> sub_100002b94 : 14392 -> 16288
~ sub_100006360 -> sub_100006b34 : 128 -> 148
~ sub_100007f90 -> sub_100008778 : 1044 -> 1108
~ sub_100008430 -> sub_100008c58 : 1040 -> 1104
~ sub_10000967c -> sub_100009ee4 : 596 -> 576
CStrings:
+ "AM PM status bar"
+ "DATE_AND_TIME#24_HOUR_TIME"
+ "DATE_AND_TIME#SET_TIMEZONE_AUTOMATICALLY"
+ "DATE_AND_TIME#SET_TIME_AUTOMATICALLY"
+ "DATE_AND_TIME#SHOW_AMPM_IN_STATUS_BAR"
+ "DATE_AND_TIME#SHOW_DATE_IN_STATUS_BAR"
+ "DATE_AND_TIME#TIME_ZONE"
+ "Set Time Zone Automatically"
+ "Show AM/PM in Status Bar"
+ "Show Date in Status Bar"
+ "The “Set Time Zone Automatically” setting is in the iOS Settings app under the “General” and “Date & Time” panes. This setting allows users to change whether the time zone is synced automatically or set manually."
+ "The “Show AM/PM in Status Bar” setting is in the iOS Settings app under the “General” and “Date & Time” panes. This setting controls whether AM/PM indicator appears in the iPad status bar."
+ "The “Show Date in Status Bar” setting is in the iOS Settings app under the “General” and “Date & Time” panes. This setting controls whether the date appears in the iPad status bar."
+ "The “Time Zone” setting is in the iOS Settings app under the “General” and “Date & Time” panes. This setting allows users to view or change their current time zone."
+ "automatic time zone"
+ "change time zone"
- "DATE_AND_TIME#SET_AUTOMATICALLY"
```
