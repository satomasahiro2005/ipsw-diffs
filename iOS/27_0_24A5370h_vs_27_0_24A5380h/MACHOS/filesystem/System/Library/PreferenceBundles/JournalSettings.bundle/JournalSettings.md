## JournalSettings

> `/System/Library/PreferenceBundles/JournalSettings.bundle/JournalSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76ba4` | `0x772ec` | **`+0x748`** |
| `__TEXT.__auth_stubs` | `0x3310` | `0x3370` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x1990` | `0x19c0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x1145` | `0x1175` | **`+0x30`** |
| `__DATA.__objc_const` | `0x3098` | `0x30b8` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2440` | `0x2420` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x14aa` | `0x14ca` | **`+0x20`** |
| `__DATA.__objc_data` | `0x6d10` | `0x6d28` | **`+0x18`** |
| `__TEXT.__const` | `0x4644` | `0x4654` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x2f44` | `0x2f54` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x2ad6` | `0x2ae6` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1834` | `0x1840` | **`+0xc`** |
| `__DATA.__common` | `0x440` | `0x448` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xba8` | `0xba0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xe08` | `0xe10` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-84.0.0.0.0
+89.0.0.0.0

-  Functions: 1819
+  Functions: 1821

-  CStrings:  966
+  CStrings:  967
CStrings:
+ "Found an unhandled text attachment: %s"
+ "hasPendingMarkup"
- "textAttachment"
```
