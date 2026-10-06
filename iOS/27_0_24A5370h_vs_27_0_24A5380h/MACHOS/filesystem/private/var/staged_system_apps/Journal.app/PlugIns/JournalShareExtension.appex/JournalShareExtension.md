## JournalShareExtension

> `/private/var/staged_system_apps/Journal.app/PlugIns/JournalShareExtension.appex/JournalShareExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf85d8` | `0xf8f78` | **`+0x9a0`** |
| `__DATA_CONST.__const` | `0x4f10` | `0x4e98` | **`-0x78`** |
| `__TEXT.__auth_stubs` | `0x3fe0` | `0x4050` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x2ae4` | `0x2b2c` | **`+0x48`** |
| `__TEXT.__const` | `0x61d4` | `0x6214` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x1ff8` | `0x2030` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x4c30` | `0x4c68` | **`+0x38`** |
| `__DATA.__data` | `0x5d90` | `0x5dc0` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0xf6c` | `0xf3c` | **`-0x30`** |
| `__DATA.__objc_const` | `0x4788` | `0x47a8` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x4dc0` | `0x4da0` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1a01` | `0x1a21` | **`+0x20`** |
| `__DATA.__objc_data` | `0x7f70` | `0x7f88` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2800` | `0x2818` | **`+0x18`** |
| `__DATA.__bss` | `0x66e0` | `0x66f0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x3d5c` | `0x3d6c` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x694d` | `0x695d` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x24cd` | `0x24bd` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1e80` | `0x1e8c` | **`+0xc`** |
| `__DATA.__common` | `0x648` | `0x650` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x1a88` | `0x1a80` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xe20` | `0xe28` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x12d8` | `0x12e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-84.0.0.0.0
+89.0.0.0.0

-  Functions: 3155
+  Functions: 3152

-  CStrings:  1715
+  CStrings:  1716
CStrings:
+ "Found an unhandled text attachment: %s"
+ "Manually adding %{public}s asset with id %{public}s. AllAssets: %{public}s"
+ "Will allow reloading of drawing asset with id %{public}s"
+ "hasChanges"
+ "hasPendingMarkup"
- "Asset already exists in allAssets. Won't add %{public}s asset with id %{public}s. AllAssets: %{public}s"
- "EntryViewModel: reducing textLength stored property value of (%ld) to Int16.max (%hd)"
- "setTextLength:"
- "textAttachment"
```
