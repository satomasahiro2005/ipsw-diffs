## diagnosticscheckupd

> `/usr/libexec/diagnosticscheckupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48e00` | `0x49198` | **`+0x398`** |
| `__TEXT.__objc_methname` | `0x816e` | `0x8251` | **`+0xe3`** |
| `__TEXT.__gcc_except_tab` | `0xadc` | `0xb84` | **`+0xa8`** |
| `__DATA.__objc_const` | `0xe1f0` | `0xe290` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x12f0` | `0x1338` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x37cc` | `0x380c` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x267b` | `0x26bb` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0xbb2` | `0xbe2` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x640` | `0x668` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x1de0` | `0x1df8` | **`+0x18`** |
| `__DATA.__data` | `0x27e0` | `0x27d0` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x2d0` | `0x2d4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1369.0.0.0.0
+1374.0.5.0.0

-  Functions: 1830
+  Functions: 1833

-  CStrings:  2371
+  CStrings:  2378
CStrings:
+ "@\"NSObject\""
+ "_stateLock"
+ "changeMakoLayerType:"
+ "clearMakoTexture"
+ "diagnosticscheckupd3"
+ "displayMakoTexture:backgroundTexture:depth:"
+ "v40@0:8@\"IOSurface\"16@\"IOSurface\"24@\"NSNumber\"32"
```
