## Bridge

> `/private/var/staged_system_apps/Bridge.app/Bridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2460e0` | `0x246484` | **`+0x3a4`** |
| `__TEXT.__oslogstring` | `0x15f0a` | `0x15f9a` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x229e0` | `0x22a60` | **`+0x80`** |
| `__TEXT.__cstring` | `0x182be` | `0x1831e` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x3d9e5` | `0x3da45` | **`+0x60`** |
| `__DATA.__objc_const` | `0x23fe8` | `0x24008` | **`+0x20`** |
| `__DATA.__objc_data` | `0x86f8` | `0x8718` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xd4f0` | `0xd510` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x11f20` | `0x11f40` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x2a54` | `0x2a74` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x16b84` | `0x16ba4` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x4410` | `0x4428` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x5dd0` | `0x5de0` | **`+0x10`** |
| `__TEXT.__const` | `0x29206` | `0x29216` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2fe9` | `0x2ff9` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2a58` | `0x2a64` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x2f00` | `0x2f08` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x85a0` | `0x85a8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x3c0` | `0x3c4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_nlclslist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1370.0.0.0.0
+1372.0.0.0.0

-  Functions: 12631
-  Symbols:   3322
-  CStrings:  15638
+  Functions: 12634
+  Symbols:   3323
+  CStrings:  15647
Symbols:
+ _CGSizeEqualToSize
CStrings:
+ "545ac5a6-e886-4466-b1b1-6621157fe0d6"
+ "Application not active: deferring hello animation until the app becomes active."
+ "View is not visible: deferring hello animation until it becomes visible"
+ "configuredSize"
+ "deviceRequiresUpdateInstallChoice:"
+ "https://support.apple.com/128132"
+ "isAnimating"
+ "isViewLoaded"
+ "startWatchAnimationIfNeeded"
```
