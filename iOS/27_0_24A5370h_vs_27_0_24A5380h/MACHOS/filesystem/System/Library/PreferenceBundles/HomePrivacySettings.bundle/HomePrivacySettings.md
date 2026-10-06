## HomePrivacySettings

> `/System/Library/PreferenceBundles/HomePrivacySettings.bundle/HomePrivacySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc1ec` | `0xd4b4` | **`+0x12c8`** |
| `__TEXT.__swift5_typeref` | `0xac7` | `0x94f` | **`-0x178`** |
| `__TEXT.__eh_frame` | `0x52c` | `0x624` | **`+0xf8`** |
| `__TEXT.__auth_stubs` | `0xcf0` | `0xd90` | **`+0xa0`** |
| `__TEXT.__const` | `0x7d0` | `0x848` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x3a0` | `0x3f8` | **`+0x58`** |
| `__DATA_CONST.__auth_got` | `0x680` | `0x6d0` | **`+0x50`** |
| `__DATA.__data` | `0x818` | `0x860` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x454` | `0x49c` | **`+0x48`** |
| `__TEXT.__oslogstring` | `—` | `0x47` | **`+0x47`** |
| `__TEXT.__cstring` | `0x7fc` | `0x7d8` | **`-0x24`** |
| `__DATA.__objc_const` | `0x340` | `0x360` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x10c` | `0x12c` | **`+0x20`** |
| `__DATA.__common` | `0xc8` | `0xe0` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x1c` | `0x34` | **`+0x18`** |
| `__DATA.__bss` | `0x508` | `0x518` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x1a2` | `0x1b2` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x10` | `0x20` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x178` | `0x184` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x18` | `0x24` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x278` | `0x280` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x468` | `0x470` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x210` | `0x218` | **`+0x8`** |
| `__TEXT.__objc_classname` | `0xd7` | `0xdd` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1227.0.0.0.1
+1232.3.0.0.0

+  - /System/Library/PrivateFrameworks/EnergyKitFoundation.framework/EnergyKitFoundation

-  Functions: 271
-  Symbols:   147
-  CStrings:  64
+  Functions: 298
+  Symbols:   152
+  CStrings:  66
Symbols:
+ __os_log_impl
+ __swift_stdlib_bridgeErrorToNSError
+ _objc_retain_x19
+ _os_log_type_enabled
+ _swift_errorRetain
+ _swift_slowAlloc
+ _swift_slowDealloc
- _objc_release_x22
- _swift_getErrorValue
CStrings:
+ "Delete data failed: %@"
+ "Failure checking energy data status: %@"
+ "_canDeleteEnergyData"
- "Delete data failed: "
```
