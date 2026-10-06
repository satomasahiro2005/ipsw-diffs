## FindMyAppCore

> `/private/var/staged_system_apps/FindMy.app/Frameworks/FindMyAppCore.framework/FindMyAppCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe3cb0` | `0xe53b8` | **`+0x1708`** |
| `__DATA.__bss` | `0x9228` | `0x9318` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0x6af0` | `0x6bd0` | **`+0xe0`** |
| `__TEXT.__const` | `0xb1a4` | `0xb264` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x2f76` | `0x3016` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x2830` | `0x28bc` | **`+0x8c`** |
| `__TEXT.__cstring` | `0x43b8` | `0x4438` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x2bf0` | `0x2c50` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x3628` | `0x3668` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xc70` | `0xc38` | **`-0x38`** |
| `__TEXT.__constg_swiftt` | `0x2690` | `0x26c8` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x1600` | `0x1630` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0xa356` | `0xa386` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x1594` | `0x1570` | **`-0x24`** |
| `__DATA.__objc_const` | `0x2bd8` | `0x2bf8` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1a12` | `0x1a32` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x40a8` | `0x4094` | **`-0x14`** |
| `__DATA.__data` | `0x6518` | `0x6528` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0xd34` | `0xd44` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0xee8` | `0xef0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x444` | `0x44c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2fc` | `0x304` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x2ac` | `0x2a4` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-470.30.6.14.10
+470.30.6.14.19

+  - /usr/lib/swift/libswiftAppleArchive.dylib
+  - /usr/lib/swift/libswiftCallKit.dylib

+  - /usr/lib/swift/libswiftCoreAudio_Private.dylib

-  Functions: 4734
-  Symbols:   1763
-  CStrings:  768
+  Functions: 4763
+  Symbols:   1777
+  CStrings:  772
Symbols:
+ ___swift_memcpy34_8
+ ___swift_memcpy56_8
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftAppleArchive_$_FindMyAppCore
+ __swift_FORCE_LOAD_$_swiftCallKit
+ __swift_FORCE_LOAD_$_swiftCallKit_$_FindMyAppCore
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private_$_FindMyAppCore
+ _swift_getTupleTypeMetadata2
+ _symbolic Say_____G 13FindMyAppCore22LocationSharingDevicesV6DeviceV
+ _symbolic _____ 13FindMyAppCore22LocationSharingDevicesV
+ _symbolic _____ 13FindMyAppCore22LocationSharingDevicesV6DeviceV
+ _symbolic _____Sg 13FindMyAppCore22LocationSharingDevicesV
+ _symbolic ___________Sg14sharingEndDatet 13FindMyAppCore21LocationSharingStatusO13PauseDurationO 10Foundation4DateV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 13FindMyAppCore22LocationSharingDevicesV6DeviceV
+ _type_layout_string 13FindMyAppCore22LocationSharingDevicesV
+ _type_layout_string 13FindMyAppCore22LocationSharingDevicesV6DeviceV
+ keypath_set.7Tm
- _swift_release_x12
- _swift_setDeallocating
- _symbolic _____y_____G s11_SetStorageC 12FindMyLocate6DeviceV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 12FindMyLocate6DeviceV
CStrings:
+ " sharingEndDate "
+ "Cannot display Shared From sheet: locationSharingDevices not yet available"
+ "LOCATION_SHARING_FOOTER_RESTRICTED"
+ "LOCATION_SHARING_PAUSE_ALERT_MESSAGE_GENERIC_"
+ "LOCATION_SHARING_RESUME_TODAY_"
+ "LOCATION_SHARING_RESUME_TOMORROW_"
+ "PEOPLE_MANAGEMENT_FOOTER_RESTRICTED"
+ "_locationSharingDevices"
- "LOCATION_SHARING_PAUSE_ALERT_MESSAGE_GENERIC"
- "LOCATION_SHARING_RESUME_TODAY"
- "LOCATION_SHARING_RESUME_TOMORROW"
- "Not able to retrieve sharing devices from FindMyLocate: %@"
```
