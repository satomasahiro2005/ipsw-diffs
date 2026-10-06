## SystemIntents

> `/System/Library/CoreServices/SystemIntents.app/SystemIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8ec8` | `0x8f9c` | **`+0xd4`** |
| `__TEXT.__eh_frame` | `0x5f0` | `0x578` | **`-0x78`** |
| `__TEXT.__auth_stubs` | `0x7e0` | `0x830` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x3f8` | `0x420` | **`+0x28`** |
| `__TEXT.__const` | `0x7b4` | `0x7d4` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x360` | `0x348` | **`-0x18`** |
| `__DATA.__data` | `0x220` | `0x228` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x108` | `0x110` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x232` | `0x23a` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x80` | `0x78` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-17.0.0.0.0
+18.0.0.0.0

-  Functions: 217
-  Symbols:   236
+  Functions: 214
+  Symbols:   243
Symbols:
+ _$s10AppIntents12UserIdentityV23personaUniqueIdentifierSSvg
+ _$s10AppIntents12UserIdentityVMa
+ _$s10AppIntents12UserIdentityVMn
+ _$s10AppIntents19IntentSystemContextV12userIdentityAA04UserG0VSgvg
+ _FBSOpenApplicationOptionKeyPersona
+ _objc_release_x27
+ _objc_release_x28
```
