## Diagnostics

> `/Applications/Diagnostics.app/Diagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c4738` | `0x1c5174` | **`+0xa3c`** |
| `__TEXT.__objc_stubs` | `0xb100` | `0xb200` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x128f1` | `0x129b1` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x5490` | `0x5550` | **`+0xc0`** |
| `__DATA_CONST.__objc_intobj` | `0xa68` | `0xaf8` | **`+0x90`** |
| `__TEXT.__objc_methname` | `0x13535` | `0x135b5` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x1e20` | `0x1e80` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x5b5c` | `0x5b14` | **`-0x48`** |
| `__DATA.__objc_selrefs` | `0x3da8` | `0x3de8` | **`+0x40`** |
| `__DATA_CONST.__objc_arraydata` | `0x2c0` | `0x2f0` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x4e50` | `0x4e80` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x43a4` | `0x43c8` | **`+0x24`** |
| `__DATA.__objc_data` | `0xc2a0` | `0xc2b8` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x2738` | `0x2750` | **`+0x18`** |
| `__DATA.__data` | `0xb440` | `0xb450` | **`+0x10`** |
| `__TEXT.__const` | `0xf074` | `0xf084` | **`+0x10`** |
| `__TEXT.__cstring` | `0xae88` | `0xae98` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x744c` | `0x745c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6420` | `0x6430` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xac14` | `0xac22` | **`+0xe`** |
| `__DATA_CONST.__auth_ptr` | `0x19f8` | `0x1a00` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1528` | `0x1530` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x9770` | `0x9778` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 9588
-  Symbols:   2304
-  CStrings:  5241
+  Functions: 9598
+  Symbols:   2308
+  CStrings:  5255
Symbols:
+ _$s20MobileGestaltPrivate30MGGetLogicalDeviceDisplayCountSiyF
+ _MobileGestalt_copy_productType_obj
+ _OBJC_CLASS_$_CADisplay
+ _objc_retain_x12
CStrings:
+ "BPCC"
+ "Failed to write btp0 for shelf life mode. Aborting shutdown."
+ "Failed to write btp1 for shelf life mode. Aborting shutdown."
+ "Multipack system detected. Using btp0/btp1 for shelf life mode."
+ "_navigationBarSafeAreaAdjustment"
+ "_setNavigationBarSafeAreaAdjustment:"
+ "btp0"
+ "btp1"
+ "currentMode"
+ "displays"
+ "height"
+ "nativeBounds"
+ "screen"
+ "width"
```
