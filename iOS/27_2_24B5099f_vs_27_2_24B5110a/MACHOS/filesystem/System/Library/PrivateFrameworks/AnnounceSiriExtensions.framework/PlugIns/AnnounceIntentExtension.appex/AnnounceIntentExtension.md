## AnnounceIntentExtension

> `/System/Library/PrivateFrameworks/AnnounceSiriExtensions.framework/PlugIns/AnnounceIntentExtension.appex/AnnounceIntentExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x143d8` | `0x14a04` | **`+0x62c`** |
| `__TEXT.__oslogstring` | `0xc4c` | `0xcbc` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0xa20` | `0xa40` | **`+0x20`** |
| `__DATA.__data` | `0x760` | `0x778` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1a8` | `0x1b8` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0xd0d` | `0xd1d` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x3e8` | `0x3f0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1a0` | `0x198` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x450` | `0x458` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Symbols:   181
-  CStrings:  262
+  Symbols:   182
+  CStrings:  265
Symbols:
+ _ANDefaultDisableSiriKitIntentHandlersOnHomeAccessory
+ _OBJC_CLASS_$_ANDevice
+ _swift_retain_x24
- _swift_deletedAsyncMethodErrorTu
- _swift_retain_x23
CStrings:
+ "Intent Handler is disabled: %{public}@"
+ "Not sending playback command on HomeAccessory: %{public}@"
+ "isHomeAccessory"
```
