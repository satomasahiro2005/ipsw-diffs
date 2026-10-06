## NewsTag

> `/private/var/staged_system_apps/News.app/PlugIns/NewsTag.appex/NewsTag`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x96170` | `0x978b8` | **`+0x1748`** |
| `__TEXT.__swift5_typeref` | `0x6b5c` | `0x72ae` | **`+0x752`** |
| `__TEXT.__const` | `0x6aa4` | `0x6b34` | **`+0x90`** |
| `__DATA.__data` | `0x4f28` | `0x4fa8` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x4e20` | `0x4de0` | **`-0x40`** |
| `__TEXT.__swift5_reflstr` | `0x1518` | `0x1548` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x3230` | `0x3250` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x7b07` | `0x7ae7` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x1a88` | `0x1a78` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1930` | `0x1940` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xc38` | `0xc48` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1fc0` | `0x1fd0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1bd8` | `0x1be4` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0xaf8` | `0xaf0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

-  Functions: 2865
+  Functions: 2878

-  CStrings:  1908
+  CStrings:  1906
Symbols:
+ _swift_retain_x9
- _OBJC_CLASS_$_FCNewsArticleEmbeddingsConfiguration
CStrings:
+ "secondarySystemFillColor"
- "articleEmbeddingsConfiguration"
- "articleEmbeddingsScoringEnabled"
- "newsPersonalizationConfiguration"
```
