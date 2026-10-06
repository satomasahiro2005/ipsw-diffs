## Health

> `/private/var/staged_system_apps/Health.app/Health`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcc18c` | `0xcca64` | **`+0x8d8`** |
| `__DATA.__data` | `0x57d8` | `0x5818` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x5cc0` | `0x5ce8` | **`+0x28`** |
| `__TEXT.__cstring` | `0x545e` | `0x547e` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x35c0` | `0x35e0` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x13dc` | `0x13f4` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x26e8` | `0x2700` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x55a0` | `0x55b0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x577d` | `0x578d` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x13b0` | `0x13b8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x2ad8` | `0x2ae0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  Functions: 3641
-  Symbols:   2401
-  CStrings:  1694
+  Functions: 3649
+  Symbols:   2402
+  CStrings:  1696
Symbols:
+ _$s18HealthExperienceUI024PinnedContentDataLoggingF6SourceC06pinnedE7Manager7contextAC0A8Platform0dE8Managing_p_So22NSManagedObjectContextCtcfc
+ _$s2os6LoggerV15HealthUtilitiesE15healthSubsystemSSvgZ
+ _$sSo13HKHealthStoreC14HealthPlatformE13sourceProfileAC06SourceF0Ovg
- _$s2os6LoggerV14HealthPlatformE15healthSubsystemSSvgZ
- _swift_willThrowTypedImpl
CStrings:
+ "Quick log title text"
+ "simplifiedLogging"
```
