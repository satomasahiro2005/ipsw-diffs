## BookEPUB

> `/private/var/staged_system_apps/Books.app/Frameworks/BookEPUB.framework/BookEPUB`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27fa18` | `0x27fcb4` | **`+0x29c`** |
| `__TEXT.__oslogstring` | `0xc7d3` | `0xc873` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x14508` | `0x14578` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x1f58` | `0x1fb0` | **`+0x58`** |
| `__DATA.__objc_const` | `0x10ce8` | `0x10d08` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xa940` | `0xa960` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x4260` | `0x4278` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x5890` | `0x58a8` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-6647.0.0.0.0
+6655.0.0.0.0

-  CStrings:  5818
+  CStrings:  5823
Functions:
~ __Z48_BEURLHandlerImageDataForiBooksURLUsingCacheItemP5NSURLP19BEProtocolCacheItem : 452 -> 616
~ sub_25e10 -> sub_25eb4 : 5808 -> 5948
~ sub_27928 -> sub_27a58 : 980 -> 1100
~ sub_29074 -> sub_2921c : 2160 -> 2288
~ sub_29cd0 -> sub_29ef8 : 2264 -> 2392
~ sub_49054 -> sub_492fc : 1060 -> 1032
~ sub_4a244 -> sub_4a4d0 : 1444 -> 1436
~ sub_63300 -> sub_63584 : 1760 -> 1736
~ sub_1cdaf4 -> sub_1cdd60 : 1936 -> 1960
~ sub_1d0808 -> sub_1d0a8c : 544 -> 568
CStrings:
+ "[DRMTrace][read] keybag refetch triggered during content serving; path=%@"
+ "[DRMTrace][read] keybag refetch triggered during content serving; path=%@ underlying=%@"
+ "disableGenmojiCreationSuggestions"
+ "setDisableGenmojiCreationSuggestions:"
+ "setSemanticContentAttribute:"
```
