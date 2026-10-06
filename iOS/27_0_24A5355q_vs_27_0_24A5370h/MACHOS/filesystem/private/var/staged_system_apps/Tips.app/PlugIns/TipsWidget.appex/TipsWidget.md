## TipsWidget

> `/private/var/staged_system_apps/Tips.app/PlugIns/TipsWidget.appex/TipsWidget`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16304` | `0x165a0` | **`+0x29c`** |
| `__TEXT.__cstring` | `0x4a6` | `0x456` | **`-0x50`** |
| `__TEXT.__objc_methname` | `0x109` | `0x14f` | **`+0x46`** |
| `__TEXT.__objc_stubs` | `0x200` | `0x240` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x2e2` | `0x312` | **`+0x30`** |
| `__TEXT.__const` | `0x14d4` | `0x14f4` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x638` | `0x650` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x80` | `0x90` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x11b0` | `0x11c0` | **`+0x10`** |
| `__DATA.__data` | `0xf78` | `0xf80` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x8e0` | `0x8e8` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x2d4` | `0x2dc` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1cb8` | `0x1cb0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-850.0.0.0.0
+853.0.0.0.0

-  Functions: 513
-  Symbols:   149
+  Functions: 514
+  Symbols:   150
Symbols:
+ _OBJC_CLASS_$_TPSImageAssetController
+ _swift_bridgeObjectRetain_n
+ _swift_retain_x24
- _objc_release_x27
- _objc_release_x28
CStrings:
+ "ImageView: no cached image for identifier: %@"
+ "ImageView: using cached image for identifier: %@"
+ "cacheIdentifierForDocument:userInterfaceStyle:"
+ "getImageForIdentifier:"
- "large size: getting image from entry"
- "large size: no image available in entry"
- "large size: using dark image from entry"
- "large size: using light image from entry"
```
