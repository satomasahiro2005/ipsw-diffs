## BackupAgent2

> `/usr/libexec/BackupAgent2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x90610` | `0x907ec` | **`+0x1dc`** |
| `__DATA_CONST.__got` | `0x4e0` | `0x588` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x18eab` | `0x18eed` | **`+0x42`** |
| `__TEXT.__objc_stubs` | `0xc960` | `0xc9a0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0xde9d` | `0xdeda` | **`+0x3d`** |
| `__TEXT.__objc_methname` | `0xe7ac` | `0xe7e3` | **`+0x37`** |
| `__TEXT.__gcc_except_tab` | `0x2118` | `0x2100` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x5fe4` | `0x5ffc` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x3c98` | `0x3ca8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1940` | `0x1948` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-3036.0.0.0.0
+3038.0.0.0.0

-  Functions: 2450
+  Functions: 2452

-  CStrings:  5756
+  CStrings:  5759
Functions:
~ sub_100042450 : 512 -> 552
- sub_1000457d0
+ sub_100045ae4
+ sub_10006cf40
+ sub_10006e300
CStrings:
+ "=pqldb= Unexpected open success when creating empty DB at %@"
+ "Failed to create SQLite database"
+ "_isSQLiteCannotOpenError"
+ "mb_openAtURL:withFlags:error:"
- "Can't find the database: %@"
```
