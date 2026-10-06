## caraccessoryd

> `/usr/libexec/caraccessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43428` | `0x437b4` | **`+0x38c`** |
| `__TEXT.__oslogstring` | `0x4b72` | `0x4bf2` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x468` | `0x4a0` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x1600` | `0x15f0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xcb8` | `0xcc8` | **`+0x10`** |
| `__DATA.__objc_data` | `0x13e0` | `0x13e8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xb10` | `0xb08` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x950` | `0x958` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-534.3.0.0.0
+537.3.0.0.0

-  Functions: 1339
-  Symbols:   3295
-  CStrings:  1403
+  Functions: 1341
+  Symbols:   3296
+  CStrings:  1405
Symbols:
+ _$s13caraccessoryd19CAFDNowPlayingAgentC18formattedFrequency33_FF809742895DEAA2EB5774A1CBC6B439LL3forSSSgSo14CAFMediaSourceCSg_tFTf4nd_n
+ _$sSTsE5first5where7ElementQzSgSbADKXE_tKFSaySo12CAFMediaItemCG_Tg5098$s13caraccessoryd19CAFDNowPlayingAgentC09updateNowC033_FF809742895DEAA2EB5774A1CBC6B439LLyyFSbSo12dE6CXEfU_SSTf1cn_n
- _$s10Foundation4DataV5countSivg
CStrings:
+ "Media item does not have a name, falling back to frequency"
+ "Media item does not have a name, source frequency unavailable"
```
