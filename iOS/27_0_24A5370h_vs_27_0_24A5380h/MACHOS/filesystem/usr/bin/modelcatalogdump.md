## modelcatalogdump

> `/usr/bin/modelcatalogdump`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16048` | `0x18694` | **`+0x264c`** |
| `__TEXT.__cstring` | `0x5c6` | `0x922` | **`+0x35c`** |
| `__TEXT.__auth_stubs` | `0x1090` | `0x11e0` | **`+0x150`** |
| `__DATA_CONST.__auth_got` | `0x850` | `0x8f8` | **`+0xa8`** |
| `__TEXT.__eh_frame` | `0xe98` | `0xef8` | **`+0x60`** |
| `__DATA.__data` | `0x330` | `0x378` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x78` | `0xc0` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0x2d` | `0x70` | **`+0x43`** |
| `__TEXT.__unwind_info` | `0x4e8` | `0x528` | **`+0x40`** |
| `__TEXT.__const` | `0x59c` | `0x5d4` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x3a1` | `0x3d1` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x208` | `0x220` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x188` | `0x198` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-295.0.1.0.0
+298.3.0.0.0

-  Functions: 448
-  Symbols:   119
-  CStrings:  43
+  Functions: 520
+  Symbols:   124
+  CStrings:  53
Symbols:
+ _objc_retain_x26
+ _swift_allocError
+ _swift_arrayDestroy
+ _swift_deallocClassInstance
+ _swift_release_x28
+ _swift_setDeallocating
+ _swift_willThrow
- _objc_retain_x25
- _swift_willThrowTypedImpl
CStrings:
+ " found, but no backing resources are present in the catalog"
+ " found, but none of its resources are present in the catalog"
+ "--resource, --resource-bundle, and --use-case are mutually exclusive"
+ "No resource bundle found with identifier: "
+ "No resource found with identifier: "
+ "Resource bundle "
+ "The identifier of the resource bundle. When provided, only the statuses of resources in this bundle are printed (skips device, use-case, and coherence sections)."
+ "The identifier of the resource. When provided, only this resource's status is printed (skips device, use-case, and coherence sections)."
+ "The identifier of the use case. When provided, only the statuses of resources backing this use case are printed (skips device, use-case, and coherence sections)."
+ "Unknown use case identifier: "
```
