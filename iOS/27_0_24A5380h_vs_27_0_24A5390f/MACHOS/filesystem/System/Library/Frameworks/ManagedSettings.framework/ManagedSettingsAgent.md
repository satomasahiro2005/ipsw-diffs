## ManagedSettingsAgent

> `/System/Library/Frameworks/ManagedSettings.framework/ManagedSettingsAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70910` | `0x72f28` | **`+0x2618`** |
| `__TEXT.__oslogstring` | `0x2e42` | `0x2ee2` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x1cc8` | `0x1d38` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x1c30` | `0x1be0` | **`-0x50`** |
| `__DATA.__data` | `0x1ed0` | `0x1f18` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x1000` | `0x1038` | **`+0x38`** |
| `__DATA.__objc_const` | `0x1e58` | `0x1e78` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1f40` | `0x1f60` | **`+0x20`** |
| `__TEXT.__cstring` | `0x7c5` | `0x7e5` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xc78` | `0xc98` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xfa8` | `0xfb8` | **`+0x10`** |
| `__TEXT.__const` | `0x1c4c` | `0x1c3c` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0xb85` | `0xb95` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x9e8` | `0x9f4` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-302.0.0.0.0
+304.0.0.0.0

-  Functions: 1064
-  Symbols:   748
-  CStrings:  547
+  Functions: 1063
+  Symbols:   750
+  CStrings:  551
Symbols:
+ _$s19DeviceConfiguration5StoreV09valuesForB2IDSDySSSDySSs8Sendable_pGGvg
+ _$s19DeviceConfiguration8ProviderP23getStoreIdentifiersSync3forSayAA0E10IdentifierCGSS_tKFZTj
CStrings:
+ ".tokenized.plist"
+ "Failed to purge DC store. Error: %@"
+ "Failed to update store in DC. Error: %@"
+ "Unable to check tokenized.plist for store with name %{public}s."
+ "Unable to delete %{public}s: Path doesn't exist."
+ "deleted now-empty store %{public}s"
+ "no DC store for %{public}s, skipping property update"
- "Failed to update store in DC. Erro: %@"
- "Unable to delete %{public}s: Path doesn't exist!"
- "Unable to settings files for store with name %{public}s."
```
