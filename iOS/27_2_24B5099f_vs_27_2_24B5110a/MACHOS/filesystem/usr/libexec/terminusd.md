## terminusd

> `/usr/libexec/terminusd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x201da4` | `0x202030` | **`+0x28c`** |
| `__TEXT.__cstring` | `0x52bd6` | `0x52bcf` | **`-0x7`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-914.40.26.502.1
+914.42.1.0.0
Functions:
~ sub_100013f48 : 1252 -> 1356
~ sub_10001ecb4 -> sub_10001ed1c : 6724 -> 6992
~ sub_10002e96c -> sub_10002eae0 : 1040 -> 1144
~ sub_1000aa048 -> sub_1000aa224 : 1320 -> 1424
~ sub_10011ce60 -> sub_10011d0a4 : 2220 -> 2292
CStrings:
+ "01:19:43"
+ "914.42.1"
+ "Oct 10 2026"
- "19:31:07"
- "914.40.26.502.1"
- "Oct  2 2026"
```
