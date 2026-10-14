## AskToViewExtension

> `/System/Library/ExtensionKit/Extensions/AskToViewExtension.appex/AskToViewExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18860` | `0x1e1c0` | **`+0x5960`** |
| `__TEXT.__eh_frame` | `0x9b4` | `0xc24` | **`+0x270`** |
| `__TEXT.__swift5_typeref` | `0x86a` | `0xa50` | **`+0x1e6`** |
| `__DATA_CONST.__const` | `0xba8` | `0xd10` | **`+0x168`** |
| `__TEXT.__auth_stubs` | `0xf90` | `0x10e0` | **`+0x150`** |
| `__TEXT.__const` | `0xa08` | `0xb58` | **`+0x150`** |
| `__DATA_CONST.__got` | `0x2c8` | `0x398` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x530` | `0x5e8` | **`+0xb8`** |
| `__DATA_CONST.__auth_got` | `0x7d0` | `0x878` | **`+0xa8`** |
| `__TEXT.__swift5_capture` | `0x4a4` | `0x544` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x447` | `0x4c7` | **`+0x80`** |
| `__DATA.__data` | `0x6d0` | `0x748` | **`+0x78`** |
| `__TEXT.__swift5_reflstr` | `0x32f` | `0x36e` | **`+0x3f`** |
| `__TEXT.__swift_as_cont` | `0x74` | `0xa4` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x258` | `0x27c` | **`+0x24`** |
| `__DATA_CONST.__auth_ptr` | `0x2d8` | `0x2f0` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x48` | `0x5c` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x48` | `0x54` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-97.125.7.0.0
+97.125.8.0.0

-  Functions: 347
-  Symbols:   167
-  CStrings:  131
+  Functions: 406
+  Symbols:   168
+  CStrings:  135
Symbols:
+ _OBJC_CLASS_$_NSError
+ _objc_retain_x28
+ _os_variant_has_internal_ui
+ _swift_willThrow
- _objc_retain_x25
- _swift_release_x28
- _swift_retain_x22
CStrings:
+ "An unknown error occurred."
+ "Can’t Send Request"
+ "[Internal Only] "
+ "com.apple.AskTo"
```
