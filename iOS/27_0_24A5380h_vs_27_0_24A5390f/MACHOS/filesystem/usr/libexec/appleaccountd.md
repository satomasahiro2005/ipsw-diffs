## appleaccountd

> `/usr/libexec/appleaccountd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3edc54` | `0x3ef6b0` | **`+0x1a5c`** |
| `__DATA.__bss` | `0x13a00` | `0x13b80` | **`+0x180`** |
| `__TEXT.__const` | `0x13230` | `0x133b0` | **`+0x180`** |
| `__TEXT.__eh_frame` | `0x1464c` | `0x147c4` | **`+0x178`** |
| `__TEXT.__oslogstring` | `0x2081d` | `0x2095d` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x13d28` | `0x13e40` | **`+0x118`** |
| `__DATA.__objc_const` | `0x1dd08` | `0x1dde0` | **`+0xd8`** |
| `__DATA.__data` | `0x14200` | `0x142c0` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x7705` | `0x7795` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x7893` | `0x7921` | **`+0x8e`** |
| `__TEXT.__constg_swiftt` | `0xc4f8` | `0xc578` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x8480` | `0x84f0` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x65b8` | `0x660c` | **`+0x54`** |
| `__TEXT.__objc_stubs` | `0x4cc0` | `0x4d00` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x2e6d` | `0x2e9d` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x6685` | `0x66b5` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x6520` | `0x654c` | **`+0x2c`** |
| `__TEXT.__cstring` | `0x4579` | `0x4599` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x11b4` | `0x11d0` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x86c` | `0x884` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1700` | `0x1710` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x2014` | `0x2024` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xc6c` | `0xc7c` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x664` | `0x674` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x1668` | `0x1670` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x5f8` | `0x600` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x630` | `0x638` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x220` | `0x224` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-1063.1.0.0.0
+1064.0.0.0.0

-  Functions: 10200
+  Functions: 10230

-  CStrings:  4152
+  CStrings:  4164
CStrings:
+ "Cache invalidated for account: %{private,mask.hash}s"
+ "Caller-initiated force refresh, bypassing cache reads (writes %s)"
+ "Device list cache enabled via internal override"
+ "Device list cache verdict from URL bag: %{bool}d"
+ "Failed to deserialize account data: account or identifier is nil"
+ "Feature flag disabled, bypassing cache"
+ "Skipping cache write — kill switch engaged"
+ "_TtC13appleaccountd26DeviceListCacheFeatureFlag"
+ "deviceListCacheEnabledWithCompletion:"
+ "featureFlag"
+ "isDeviceListCacheEnabled"
+ "provideDeviceList rejected account with nil identifier"
+ "provideDeviceList-cacheMiss"
+ "provideDeviceList-flagDisabled"
+ "resolvedVerdict"
+ "v12@?0B8"
- "Cache invalidated for account: %{private,mask.hash}@"
- "Failed to deserialize account data: account is nil"
- "Force refresh requested, bypassing cache"
- "provideDeviceList-cached"
```
