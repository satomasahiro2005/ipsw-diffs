## userfsd

> `/System/Library/PrivateFrameworks/UserFS.framework/userfsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34c4` | `0x3600` | **`+0x13c`** |
| `__TEXT.__oslogstring` | `0x6d7` | `0x726` | **`+0x4f`** |
| `__TEXT.__gcc_except_tab` | `0x1c0` | `0x1f8` | **`+0x38`** |
| `__TEXT.__objc_stubs` | `0x760` | `0x780` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x3f0` | `0x400` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0xa00` | `0xa0b` | **`+0xb`** |
| `__DATA.__objc_selrefs` | `0x338` | `0x340` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x208` | `0x210` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-762.0.0.0.0
+764.0.0.0.0

-  Symbols:   88
-  CStrings:  270
+  Symbols:   89
+  CStrings:  272
Symbols:
+ _objc_retain_x28
Functions:
~ sub_100001008 : 1528 -> 1520
~ sub_100002434 -> sub_10000242c : 1880 -> 2208
~ sub_100003440 -> sub_100003580 : 1152 -> 1148
CStrings:
+ "invalidate"
+ "liveFSService:delegate:addDisk:%@:collision:restoring previous UVFSService[%d]"
```
