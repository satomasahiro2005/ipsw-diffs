## ManagedSettingsAgent

> `/System/Library/Frameworks/ManagedSettings.framework/ManagedSettingsAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72f28` | `0x72a04` | **`-0x524`** |
| `__DATA_CONST.__const` | `0x1be0` | `0x1eb0` | **`+0x2d0`** |
| `__TEXT.__oslogstring` | `0x2ee2` | `0x2fb2` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0x3a0` | `0x430` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x608` | `0x680` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0xc98` | `0xd00` | **`+0x68`** |
| `__DATA.__data` | `0x1f18` | `0x1f58` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x1038` | `0x1068` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xb95` | `0xb65` | **`-0x30`** |
| `__TEXT.__const` | `0x1c3c` | `0x1c5c` | **`+0x20`** |
| `__DATA.__objc_const` | `0x1e78` | `0x1e68` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x1f60` | `0x1f70` | **`+0x10`** |
| `__TEXT.__cstring` | `0x7e5` | `0x7d5` | **`-0x10`** |
| `__TEXT.__objc_classname` | `0x77c` | `0x76c` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0xba2` | `0xb92` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x9f4` | `0x9e8` | **`-0xc`** |
| `__DATA.__objc_data` | `0x2c0` | `0x2b8` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0xfb8` | `0xfc0` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1031` | `0x102f` | **`-0x2`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-304.0.0.0.0
+304.2.6.0.0

-  Functions: 1063
-  Symbols:   750
-  CStrings:  551
+  Functions: 1110
+  Symbols:   751
+  CStrings:  554
Symbols:
+ _$s15ManagedSettings23SettingMetadataProtocolP11invertForDCSbSgvgTj
CStrings:
+ "Failed to initialize web domain token with persisted value: %{public}@"
+ "Failed to persist refreshed web domain token: %{public}s"
+ "persistable value not convertible to Bool for %{public}s"
+ "shieldExtension"
+ "tokenExpiryNotifier"
- "$__lazy_storage_$_shieldExtension"
- "tokenEncodingNotifier"
```
