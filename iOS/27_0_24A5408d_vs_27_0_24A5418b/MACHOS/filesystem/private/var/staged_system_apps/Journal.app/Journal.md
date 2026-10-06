## Journal

> `/private/var/staged_system_apps/Journal.app/Journal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x92401c` | `0x924e9c` | **`+0xe80`** |
| `__TEXT.__oslogstring` | `0x114d0` | `0x11570` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x32504` | `0x3254c` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x5158` | `0x5188` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x19f78` | `0x19f88` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-99.2.1.0.0
+99.2.2.0.0

-  Functions: 33637
-  Symbols:   8108
-  CStrings:  10088
+  Functions: 33640
+  Symbols:   8114
+  CStrings:  10091
Symbols:
+ _$s16GenerativeModels0aB12AvailabilityV0C0O14RestrictedInfoV0D6ReasonO11descriptionSSvg
+ _$s16GenerativeModels0aB12AvailabilityV0C0O14RestrictedInfoV0D6ReasonO21mdmAndParentalControlyA2ImFWC
+ _$s16GenerativeModels0aB12AvailabilityV0C0O15UnavailableInfoV0D6ReasonO11descriptionSSvg
+ _$s16GenerativeModels0aB12AvailabilityV0C0O15UnavailableInfoV0D6ReasonO19parentalRestrictionyA2ImFWC
+ _$s16GenerativeModels0aB12AvailabilityV0C0O15UnavailableInfoV0D6ReasonO21mdmAndParentalControlyA2ImFWC
+ _$s16GenerativeModels0aB12AvailabilityV0C0Os23CustomStringConvertibleAAMc
CStrings:
+ "FUP-AVAIL journaling.FollowUpPrompts availability=%{public}s"
+ "FUP-AVAIL restricted reasons=[%{public}s]"
+ "FUP-AVAIL unavailable reasons=[%{public}s]"
```
