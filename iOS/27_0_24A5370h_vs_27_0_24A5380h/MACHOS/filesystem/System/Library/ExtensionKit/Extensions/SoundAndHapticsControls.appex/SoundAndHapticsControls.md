## SoundAndHapticsControls

> `/System/Library/ExtensionKit/Extensions/SoundAndHapticsControls.appex/SoundAndHapticsControls`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1db2` | `0x20a2` | **`+0x2f0`** |
| `__TEXT.__text` | `0x10984` | `0x10b1c` | **`+0x198`** |
| `__TEXT.__swift5_reflstr` | `0x487` | `0x4c7` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x821` | `0x859` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x310` | `0x328` | **`+0x18`** |
| `__TEXT.__const` | `0x2404` | `0x23f4` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x1d0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
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

-1129.0.0.0.0
+2027.0.1.100.0

-  CStrings:  132
+  CStrings:  139
Functions:
~ sub_10000c1ec : 712 -> 788
~ sub_10000c4b4 -> sub_10000c500 : 96 -> 104
~ sub_10000d024 -> sub_10000d078 : 7412 -> 7712
~ sub_10000ed18 -> sub_10000ee98 : 96 -> 104
~ sub_1000106f0 -> sub_100010878 : 96 -> 104
~ sub_100010bcc -> sub_100010d5c : 96 -> 104
CStrings:
+ "#ALARM_TIMER_GROUP"
+ "#ALERT_NOTIFICATION_GROUP"
+ "#CHANGE_WITH_BUTTONS"
+ "#LOCK_SOUND_SWITCH"
+ "#MATCH_ALARM_RINGTONE_VOLUME"
+ "#MATCH_RINGTONE_VOLUME"
+ "#RING_VOLUME_SLIDER"
+ "#SHOW_IN_STATUS_BAR"
+ "#SILENT_MODE"
+ "#SYSTEM_HAPTICS"
+ "Alarms and Timers"
+ "Alerts and System Sounds"
+ "Match Ringtone Volume"
+ "Sounds & Haptics → Alarms and Timers"
+ "Sounds & Haptics → Alerts and System Sounds"
+ "The 'Haptics' setting is located within the 'Sounds & Haptics' in the iPhone iOS Settings app. This setting allows for changing when haptics play for alarms, timers, alerts, and when iPhone rings."
+ "The 'Match Ringtone Volume' setting in 'Alarms and Timers' is located within the 'Sounds & Haptics' in the iPhone iOS Settings app. When enabled, the alarm and timer volume matches the ringtone volume instead of using its own slider."
+ "The 'Match Ringtone Volume' setting in 'Alerts and System Sounds' is located within the 'Sounds & Haptics' in the iPhone iOS Settings app. When enabled, the alert and system-sounds volume matches the ringtone volume instead of using its own slider."
+ "The 'Ringtone Volume' setting is located within the 'Sounds & Haptics' in the iPhone iOS Settings app. This setting allows for changing the ringtone and alert volume."
+ "haptics for alarms, timers, and alerts"
+ "vibration patterns"
- "ALARM_VOLUME_SLIDER"
- "ALERT_VOLUME_SLIDER"
- "Alarms & Timers Volume"
- "Alerts and System Sounds Volume"
- "CHANGE_WITH_BUTTONS"
- "LOCK_SOUND_SWITCH"
- "RINGER_AND_ALERT_GROUP"
- "SHOW_IN_STATUS_BAR"
- "SILENT_MODE"
- "SYSTEM_HAPTICS"
- "The 'Haptics' setting is located within the 'Sounds & Haptics' in the iPhone iOS Settings app. This setting allows for changing when haptics play during ringtones and alerts"
- "The 'Ringtone' setting is located within the 'Sounds & Haptics' in the iPhone iOS Settings app. This setting allows for changing the ringtone and alert volume."
- "notification volume"
- "sounds and vibration patterns"
```
