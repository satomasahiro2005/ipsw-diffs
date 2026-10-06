## WeatherPoster

> `/private/var/staged_system_apps/WeatherPosterApp.app/Extensions/WeatherPoster.appex/WeatherPoster`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4fc34` | `0x4eef4` | **`-0xd40`** |
| `__TEXT.__oslogstring` | `0x30f5` | `0x3005` | **`-0xf0`** |
| `__DATA_CONST.__const` | `0x3240` | `0x31d0` | **`-0x70`** |
| `__TEXT.__eh_frame` | `0x968` | `0x9c8` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x1800` | `0x17c0` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x3dfd` | `0x3dcd` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0xce4` | `0xcb4` | **`-0x30`** |
| `__TEXT.__auth_stubs` | `0x2260` | `0x2240` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x1074` | `0x105c` | **`-0x18`** |
| `__DATA_CONST.__auth_got` | `0x1138` | `0x1128` | **`-0x10`** |
| `__TEXT.__cstring` | `0xa20` | `0xa10` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x1397` | `0x1387` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0xcf0` | `0xce8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x578` | `0x570` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0xd4c` | `0xd54` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1138` | `0x1130` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1470.0.0.0.0
+1474.0.0.0.0

-  Functions: 1904
-  Symbols:   306
-  CStrings:  990
+  Functions: 1898
+  Symbols:   304
+  CStrings:  985
Symbols:
- _OBJC_CLASS_$_NSFileCoordinator
- _objc_release_x1
CStrings:
+ "Failed to create JPEG data when saving snapshot to disk for kind=%{public}s"
- "Failed to create snapshot because URL could not be created for kind=%{public}s"
- "Failed to encode snapshot for kind=%{public}s"
- "File coordination failed for kind=%{public}s; error=%{public}s. Falling back to uncoordinated render."
- "Snapshot for kind=%{public}s already rendered by concurrent process; reusing"
- "coordinateWritingItemAtURL:options:error:byAccessor:"
- "v16@?0@\"NSURL\"8"
```
