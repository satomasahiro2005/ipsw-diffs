## libiconv.2.dylib

> `/usr/lib/libiconv.2.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__data` | `—` | `0x58` | **`+0x58`** |
| `__DATA_DIRTY.__data` | `0x2b0` | `0x258` | **`-0x58`** |
| `__TEXT.__text` | `0x62e4` | `0x62a4` | **`-0x40`** |

### Other Changes

```text
Functions:
~ __citrus_bcs_strtol : 732 -> 708
~ __citrus_bcs_strtoul : 640 -> 608
~ __citrus_bcs_convert_to_lower : 48 -> 40
~ __citrus_bcs_convert_to_upper : 52 -> 44
~ __citrus_db_factory_serialize : 852 -> 844
~ __citrus_prop_parse_variable : 908 -> 924
```
