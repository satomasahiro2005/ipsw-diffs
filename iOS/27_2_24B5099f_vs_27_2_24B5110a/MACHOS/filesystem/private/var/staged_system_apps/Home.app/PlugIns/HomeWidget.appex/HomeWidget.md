## HomeWidget

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeWidget.appex/HomeWidget`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__swift5_typeref` | `0x74ee` | `0x780e` | **`+0x320`** |
| `__TEXT.__text` | `0x9cd30` | `0x9ca74` | **`-0x2bc`** |
| `__TEXT.__auth_stubs` | `0x3030` | `0x3120` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x203d` | `0x211d` | **`+0xe0`** |
| `__DATA.__data` | `0x2bd8` | `0x2c88` | **`+0xb0`** |
| `__DATA_CONST.__got` | `0xb98` | `0xc20` | **`+0x88`** |
| `__DATA_CONST.__auth_got` | `0x1820` | `0x1898` | **`+0x78`** |
| `__TEXT.__const` | `0x4788` | `0x47d8` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0xec0` | `0xee0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xe0e` | `0xe2e` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1870` | `0x1888` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0xe00` | `0xe0c` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1269.2.3.0.1
+1269.2.5.1.4

+  - /System/Library/PrivateFrameworks/HomeAppIntents.framework/HomeAppIntents

-  Functions: 1827
+  Functions: 1843

-  CStrings:  477
+  CStrings:  482
CStrings:
+ "HFCharacteristicValueDoorStateDoorOpen"
+ "HFCharacteristicValueDoorStateForcedOpen"
+ "door.left.hand.open"
+ "lock.open.trianglebadge.exclamationmark.fill"
+ "lock.trianglebadge.exclamationmark.fill"
```
