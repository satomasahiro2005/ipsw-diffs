## Diagnostics

> `/Applications/Diagnostics.app/Diagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c1874` | `0x1c1c98` | **`+0x424`** |
| `__TEXT.__gcc_except_tab` | `0xbe0` | `0xc88` | **`+0xa8`** |
| `__TEXT.__objc_methname` | `0x131b5` | `0x13255` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x5010` | `0x5070` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x73c4` | `0x7414` | **`+0x50`** |
| `__DATA.__objc_const` | `0x272a8` | `0x272e8` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x44a9` | `0x44e9` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x6300` | `0x6340` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x1518` | `0x1540` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x3d58` | `0x3d78` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x2e1b` | `0x2e3b` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x4ef0` | `0x4ee0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x2788` | `0x2780` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x3b8` | `0x3bc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_acfuncs`
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

-  Functions: 9543
-  Symbols:   2319
-  CStrings:  5198
+  Functions: 9546
+  Symbols:   2318
+  CStrings:  5207
Symbols:
- _swift_willThrowTypedImpl
CStrings:
+ "@\"NSObject\""
+ "Accessory still disconnected on DK-initiated clear; keeping session alive to deliver test result."
+ "Diagnostics3"
+ "_stateLock"
+ "changeMakoLayerType:"
+ "clearMakoTexture"
+ "displayMakoTexture:backgroundTexture:depth:"
+ "endIgnoringDisconnectsEndingSessionIfStillDisconnected:"
+ "v40@0:8@\"IOSurface\"16@\"IOSurface\"24@\"NSNumber\"32"
```
