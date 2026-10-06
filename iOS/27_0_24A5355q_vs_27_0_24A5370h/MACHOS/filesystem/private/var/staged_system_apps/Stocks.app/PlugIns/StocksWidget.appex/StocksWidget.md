## StocksWidget

> `/private/var/staged_system_apps/Stocks.app/PlugIns/StocksWidget.appex/StocksWidget`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xda9e4` | `0xdb888` | **`+0xea4`** |
| `__TEXT.__const` | `0x9914` | `0x9a14` | **`+0x100`** |
| `__DATA.__data` | `0x7ab0` | `0x7b88` | **`+0xd8`** |
| `__DATA.__bss` | `0xd3b0` | `0xd440` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x287c` | `0x28cc` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x3420` | `0x3458` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x235c` | `0x2390` | **`+0x34`** |
| `__TEXT.__auth_stubs` | `0x46e0` | `0x4710` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x2f1a` | `0x2f4a` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1f0f` | `0x1f2f` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x2378` | `0x2390` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0xa78` | `0xa90` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x1488` | `0x1490` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x698` | `0x69c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x2c0` | `0x2c4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2016.0.0.0.0
+2018.0.0.0.0

-  Functions: 4604
+  Functions: 4624
Symbols:
+ _objc_retain_x9
- _OBJC_CLASS_$_FCNewsArticleEmbeddingsConfiguration
CStrings:
+ "Fetched quoteDetail, clientRefreshedAt=%s, id=%s"
+ "Sparkline model for %{public}s with date range %{public}s not considered valid for quote (exchangeStatus: %{public}s, serverCreatedAt: %{public}s, clientRefreshedAt: %{public}s)"
- "Fetched quoteDetail, dateLastRefreshed=%s, id=%s"
- "Sparkline model for %{public}s with date range %{public}s not considered valid for quote (exchangeStatus: %{public}s, serverCreatedAt: %{public}s, dateLastRefreshed: %{public}s)"
```
