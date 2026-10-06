## AboutSettings

> `/System/Library/PreferenceBundles/AboutSettings.bundle/AboutSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1277c` | `0x13a54` | **`+0x12d8`** |
| `__TEXT.__auth_stubs` | `0xb40` | `0xcb0` | **`+0x170`** |
| `__DATA_CONST.__auth_got` | `0x5b0` | `0x668` | **`+0xb8`** |
| `__DATA_CONST.__got` | `0x4f0` | `0x530` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x841` | `0x879` | **`+0x38`** |
| `__DATA.__data` | `0x418` | `0x448` | **`+0x30`** |
| `__TEXT.__cstring` | `0x1414` | `0x1444` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0xb1` | `0xe1` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x1840` | `0x1820` | **`-0x20`** |
| `__TEXT.__const` | `0x272` | `0x292` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x3970` | `0x3951` | **`-0x1f`** |
| `__TEXT.__oslogstring` | `0x44b` | `0x42f` | **`-0x1c`** |
| `__DATA_CONST.__objc_arrayobj` | `0x90` | `0x78` | **`-0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xd0` | `0xe0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x450` | `0x460` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x12d0` | `0x12c8` | **`-0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0xa8` | `0xa0` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0xf18` | `0xf10` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-1257.0.0.0.0
+1259.0.0.0.0

-  Functions: 350
-  Symbols:   350
+  Functions: 361
+  Symbols:   358
Symbols:
+ _OBJC_CLASS_$_SystemHealthViewController
+ __swiftEmptyDictionarySingleton
+ _swift_dynamicCast
+ _swift_dynamicCastClass
+ _swift_release_x21
+ _swift_release_x23
+ _swift_retain_x21
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
- _objc_retain_x28
CStrings:
+ "%{public}s: p&sh specifiers did load"
+ "-[PSGAboutController viewDidLoad]_block_invoke"
- "%{public}s: handling deferred url after p&sh specifiers did load"
- "shouldDeferPushForSpecifierID:"
```
