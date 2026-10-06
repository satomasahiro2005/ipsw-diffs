## MediaRemoteUI

> `/Applications/MediaRemoteUI.app/MediaRemoteUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ee68` | `0x3f4a8` | **`+0x640`** |
| `__TEXT.__oslogstring` | `0x13e1` | `0x14b1` | **`+0xd0`** |
| `__TEXT.__objc_methname` | `0x5d1d` | `0x5d7d` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x2c20` | `0x2c60` | **`+0x40`** |
| `__DATA.__objc_data` | `0x3b40` | `0x3b68` | **`+0x28`** |
| `__DATA.__objc_const` | `0xad88` | `0xada8` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x23fc` | `0x241c` | **`+0x20`** |
| `__DATA.__data` | `0x29b0` | `0x29a0` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x1238` | `0x1248` | **`+0x10`** |
| `__TEXT.__const` | `0x2004` | `0x2014` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1c90` | `0x1ca0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1923` | `0x1933` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x12d6` | `0x12e6` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1120` | `0x112c` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x1038` | `0x1040` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.110.75.1.0
+4026.100.79.0.0

-  Functions: 1479
+  Functions: 1483

-  CStrings:  1284
+  CStrings:  1289
CStrings:
+ "LockScreenCoordinator isValidGeometryForExpandedLayout - pad -> true"
+ "LockScreenCoordinator isValidGeometryForExpandedLayout - phone screenBounds=%fx%f o=%ld h=%f -> %{bool}d"
+ "[CoverSheetBackgroundView] staticArtworkInsets base: %f contentInsets: %f/%f sheet: %f/%f reserved: %f/%f sizeClass: %ld/%ld"
+ "activeInterfaceOrientation"
+ "platterScene"
+ "setPlatterScene:"
- "[CoverSheetBackgroundView] staticArtworkInsets base: %f contentInsets: %f/%f sheet: %f/%f sizeClass: %ld/%ld"
```
