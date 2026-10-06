## FindMyAppCore

> `/private/var/staged_system_apps/FindMy.app/Frameworks/FindMyAppCore.framework/FindMyAppCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xea458` | `0xea010` | **`-0x448`** |
| `__TEXT.__const` | `0xb514` | `0xb3c4` | **`-0x150`** |
| `__DATA_CONST.__const` | `0x6e90` | `0x6d80` | **`-0x110`** |
| `__DATA.__bss` | `0x93b8` | `0x92b8` | **`-0x100`** |
| `__TEXT.__swift5_reflstr` | `0x3106` | `0x3086` | **`-0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x2954` | `0x28e0` | **`-0x74`** |
| `__TEXT.__auth_stubs` | `0x2e50` | `0x2ec0` | **`+0x70`** |
| `__TEXT.__cstring` | `0x4578` | `0x4508` | **`-0x70`** |
| `__TEXT.__swift5_typeref` | `0xa91a` | `0xa8de` | **`-0x3c`** |
| `__DATA_CONST.__auth_got` | `0x1730` | `0x1768` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x271c` | `0x26e4` | **`-0x38`** |
| `__DATA.__common` | `0x178` | `0x1a0` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x4204` | `0x41dc` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x3730` | `0x3710` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xc68` | `0xc78` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0xf20` | `0xf18` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x450` | `0x448` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x30c` | `0x304` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-470.30.6.14.34
+470.31.6.16.26

-  Functions: 4837
-  Symbols:   1809
-  CStrings:  783
+  Functions: 4819
+  Symbols:   1802
+  CStrings:  781
Symbols:
+ _get_enum_tag_for_layout_string 13FindMyAppCore0B21LocationSharingDeviceV0fG0OSg
+ _symbolic _____Sg 10FindMyCore22LocationSharingDevicesV
+ _symbolic _____Sg 10FindMyCore22LocationSharingDevicesV0feD0V
+ _symbolic _____Sg 12FindMyLocate12ClientTargetV
+ _symbolic _____Sg 13FindMyAppCore0B21LocationSharingDeviceV0fG0O
+ _symbolic _____Sg_ABt 10FindMyCore22LocationSharingDevicesV
- ___swift_memcpy34_8
- ___swift_memcpy56_8
- _get_enum_tag_for_layout_string 13FindMyAppCore0B21LocationSharingDeviceV0fG0O
- _symbolic Say_____G 13FindMyAppCore22LocationSharingDevicesV6DeviceV
- _symbolic _____ 13FindMyAppCore22LocationSharingDevicesV
- _symbolic _____ 13FindMyAppCore22LocationSharingDevicesV6DeviceV
- _symbolic _____Sg 13FindMyAppCore22LocationSharingDevicesV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 13FindMyAppCore22LocationSharingDevicesV6DeviceV
- _symbolic _____y_____SaySSGG 10Foundation15ListFormatStyleV AA06StringD0V
- _symbolic _____y_____SaySSG_G 10Foundation15ListFormatStyleV0B4TypeO AA06StringD0V
- _symbolic _____y_____SaySSG_G 10Foundation15ListFormatStyleV5WidthO AA06StringD0V
- _type_layout_string 13FindMyAppCore22LocationSharingDevicesV
- _type_layout_string 13FindMyAppCore22LocationSharingDevicesV6DeviceV
CStrings:
+ "LOCATION_SHARING_INFO_SHEET_LOCATION_SERVICES_OFF_"
- "LOCATION_SHARING_INFO_SHEET_DETAIL_%@"
- "LOCATION_SHARING_INFO_SHEET_DETAIL_WITH_WATCHES_%@"
- "LOCATION_SHARING_INFO_SHEET_LOCATION_SERVICES_OFF"
```
