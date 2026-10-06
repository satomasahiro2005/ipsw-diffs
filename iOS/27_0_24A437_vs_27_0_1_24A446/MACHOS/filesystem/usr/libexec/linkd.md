## linkd

> `/usr/libexec/linkd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__eh_frame` | `0x1569c` | `0x15674` | **`-0x28`** |
| `__TEXT.__oslogstring` | `0x658f` | `0x659f` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7838` | `0x7830` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-301.0.51.1.104
+301.0.51.1.105
Symbols:
+ _$s15AppIntentsIndex08MetadataC0V23appShortcutsUnprocessed3forSbSS_tKF
- _$s15AppIntentsIndex08MetadataC0V21appShortcutsProcessedySbSSKF
Functions:
~ sub_10000c0b0 : 12 -> 32
~ sub_100011cfc -> sub_100011d10 : 16 -> 12
~ sub_100011d0c -> sub_100011d1c : 12 -> 20
~ sub_100011d18 -> sub_100011d30 : 20 -> 12
~ sub_100014810 -> sub_100014820 : 36 -> 16
~ sub_100014834 -> sub_100014830 : 32 -> 36
~ sub_100022ad4 : 28 -> 24
~ sub_100161f7c -> sub_100161f78 : 896 -> 900
~ sub_10016255c : 108 -> 104
~ sub_100170f98 -> sub_100170f94 : 24 -> 28
CStrings:
+ "AppShortcuts for %{public}s does not need processing, unblocking"
- "AppShortcuts for %{public}s appear processed, unblocking"
```
