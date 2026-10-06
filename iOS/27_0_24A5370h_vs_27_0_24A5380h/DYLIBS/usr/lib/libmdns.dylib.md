## libmdns.dylib

> `/usr/lib/libmdns.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x140` | `0xfa0` | **`+0xe60`** |
| `__DATA_DIRTY.__objc_data` | `0xeb0` | `0x50` | **`-0xe60`** |
| `__DATA_CONST.__got` | `0x0` | `0x2f0` | **`+0x2f0`** |
| `__TEXT.__text` | `0x310e8` | `0x310b4` | **`-0x34`** |

### Other Changes

```diff

-3085.0.0.0.1
+3089.0.0.0.1
Functions:
~ _DomainNameAppendString : 348 -> 352
~ __DNSRecordDataToStringEx2 : 5188 -> 5136
~ __mdns_siphash_with_key_ex : 980 -> 972
~ _mdns_string_builder_append_escaped_ascii_string : 304 -> 308
```
