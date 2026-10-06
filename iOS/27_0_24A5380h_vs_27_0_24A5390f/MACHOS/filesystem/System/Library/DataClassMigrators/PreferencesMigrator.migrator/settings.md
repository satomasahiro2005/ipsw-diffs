## settings

> `/System/Library/DataClassMigrators/PreferencesMigrator.migrator/settings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x154d8` | `0x17524` | **`+0x204c`** |
| `__DATA.__bss` | `0x3580` | `0x3a00` | **`+0x480`** |
| `__TEXT.__const` | `0x1d20` | `0x1f70` | **`+0x250`** |
| `__TEXT.__cstring` | `0x1344` | `0x1524` | **`+0x1e0`** |
| `__TEXT.__eh_frame` | `0x864` | `0x94c` | **`+0xe8`** |
| `__DATA.__data` | `0xa60` | `0xb40` | **`+0xe0`** |
| `__TEXT.__swift5_reflstr` | `0x499` | `0x569` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0xaa0` | `0xb30` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x6a0` | `0x728` | **`+0x88`** |
| `__TEXT.__swift5_fieldmd` | `0x3d4` | `0x448` | **`+0x74`** |
| `__TEXT.__swift5_typeref` | `0x604` | `0x65c` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x3a0` | `0x3ec` | **`+0x4c`** |
| `__TEXT.__auth_stubs` | `0xcf0` | `0xd30` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x1ac` | `0x1d0` | **`+0x24`** |
| `__DATA_CONST.__auth_got` | `0x680` | `0x6a0` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x318` | `0x328` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x298` | `0x2a0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x68` | `0x70` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x3c` | `0x44` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x34` | `0x3c` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x48` | `0x4c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-2027.0.3.100.0
+2027.0.6.101.0

+  - /System/Library/PrivateFrameworks/SettingsServices.framework/SettingsServices

-  Functions: 489
-  Symbols:   403
-  CStrings:  107
+  Functions: 529
+  Symbols:   409
+  CStrings:  110
Symbols:
+ _$s16SettingsServices0A19SearchIndexerClientC14requestReindex3forySayAC0G13DomainRequestVG_tYaKFZ
+ _$s16SettingsServices0A19SearchIndexerClientC14requestReindex3forySayAC0G13DomainRequestVG_tYaKFZTu
+ _$s16SettingsServices0A19SearchIndexerClientC20ReindexDomainRequestV20openIntentIdentifier08appValueK0017attributionBundleK004hostoK0AESS_S3StcfC
+ _$s16SettingsServices0A19SearchIndexerClientC20ReindexDomainRequestVMa
+ _$s16SettingsServices0A19SearchIndexerClientC20ReindexDomainRequestVMn
+ _$s16SettingsServices0A19SearchIndexerClientCMa
CStrings:
+ "No value provided for `-attribution-bundle-identifiers`."
+ "Request a reindex of a specific `OpenIntent`/target domain via the `SettingsSearchIndexerClient` API in `SettingsServices`."
+ "Unlike `reindex`, which performs the indexing operation directly via `SettingsHost`, this command calls into `SettingsServices` to *request* that the host Settings application reindex the specified domain(s). One request is issued per provided attribution bundle identifier."
```
