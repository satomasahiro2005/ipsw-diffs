## ndoagent

> `/System/Library/PrivateFrameworks/NewDeviceOutreach.framework/ndoagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70d60` | `0x736dc` | **`+0x297c`** |
| `__DATA.__bss` | `0xbf38` | `0xb540` | **`-0x9f8`** |
| `__DATA.__data` | `0x1878` | `0x1fa8` | **`+0x730`** |
| `__DATA.__objc_const` | `0x28b0` | `0x2c08` | **`+0x358`** |
| `__DATA_CONST.__const` | `0x3fc8` | `0x3d50` | **`-0x278`** |
| `__TEXT.__const` | `0x8598` | `0x83d8` | **`-0x1c0`** |
| `__TEXT.__constg_swiftt` | `0x10c8` | `0xf48` | **`-0x180`** |
| `__TEXT.__unwind_info` | `0x1d60` | `0x1c10` | **`-0x150`** |
| `__TEXT.__auth_stubs` | `0x2d60` | `0x2c40` | **`-0x120`** |
| `__TEXT.__eh_frame` | `0x1f70` | `0x2048` | **`+0xd8`** |
| `__TEXT.__objc_methname` | `0x2883` | `0x291f` | **`+0x9c`** |
| `__DATA_CONST.__auth_got` | `0x16c0` | `0x1630` | **`-0x90`** |
| `__TEXT.__swift5_typeref` | `0x1750` | `0x16c6` | **`-0x8a`** |
| `__DATA_CONST.__got` | `0xac0` | `0xb48` | **`+0x88`** |
| `__TEXT.__swift5_capture` | `0x7a0` | `0x800` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x28a6` | `0x28fb` | **`+0x55`** |
| `__TEXT.__swift5_fieldmd` | `0x129c` | `0x125c` | **`-0x40`** |
| `__DATA_CONST.__auth_ptr` | `0x8f0` | `0x8c0` | **`-0x30`** |
| `__TEXT.__objc_methtype` | `0x8c2` | `0x8e2` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x84` | `0x68` | **`-0x1c`** |
| `__TEXT.__swift_as_ret` | `0x94` | `0x78` | **`-0x1c`** |
| `__TEXT.__swift5_types` | `0x198` | `0x184` | **`-0x14`** |
| `__TEXT.__cstring` | `0x1a71` | `0x1a80` | **`+0xf`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-602.0.0.0.0
+616.0.0.0.0

-  Functions: 2539
-  Symbols:   1208
-  CStrings:  919
+  Functions: 2426
+  Symbols:   1202
+  CStrings:  920
Symbols:
+ _swift_retain_x9
- _$s6NDOAPI15NDOConfigLoaderCMn
- _$s6NDOAPI17NDOConfigMemCacheMp
- _$s6NDOAPI9NDOLoaderMp
- _objc_retain_x27
- _swift_getOpaqueTypeConformance2
- _swift_isaMask
- _swift_release_x9
CStrings:
+ "%s Profile list changed but development flag is set. No action needed."
```
