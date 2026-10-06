## PhotosPosterProvider

> `/System/Library/ExtensionKit/Extensions/PhotosPosterProvider.appex/PhotosPosterProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27cac` | `0x28558` | **`+0x8ac`** |
| `__TEXT.__objc_methname` | `0x2f21` | `0x2fc1` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xa86` | `0xad6` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x1418` | `0x1468` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x14a0` | `0x14e0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x1040` | `0x1078` | **`+0x38`** |
| `__DATA.__data` | `0xa58` | `0xa88` | **`+0x30`** |
| `__DATA.__objc_const` | `0x1240` | `0x1258` | **`+0x18`** |
| `__DATA.__objc_data` | `0x500` | `0x518` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x538` | `0x550` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x880` | `0x898` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xaa8` | `0xab8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1180` | `0x1190` | **`+0x10`** |
| `__TEXT.__const` | `0x984` | `0x994` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x7f2` | `0x7fc` | **`+0xa`** |
| `__DATA_CONST.__auth_got` | `0x8c8` | `0x8d0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xbf0` | `0xbf8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-910.33.102.0.0
+912.0.111.0.0

-  Functions: 1062
+  Functions: 1077

-  CStrings:  709
+  CStrings:  715
CStrings:
+ "Dropping poster descriptor '%s': known-broken segmentation version %ld"
+ "TB,R,N,Gpx_isEmbeddedDisplay"
+ "Version gate dropped all descriptors, falling back to cold start"
+ "loadSegmentationItemFromWallpaperURL:error:"
+ "px_embeddedDisplay"
+ "px_isEmbeddedDisplay"
```
