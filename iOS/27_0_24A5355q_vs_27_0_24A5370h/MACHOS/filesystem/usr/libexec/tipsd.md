## tipsd

> `/usr/libexec/tipsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18a34` | `0x18a7c` | **`+0x48`** |
| `__TEXT.__objc_methtype` | `0x1149` | `0x1189` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x3794` | `0x379f` | **`+0xb`** |
| `__DATA_CONST.__got` | `0x3f8` | `0x400` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6f8` | `0x700` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x1705` | `0x1706` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-850.0.0.0.0
+853.0.0.0.0

+  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry

-  Symbols:   401
-  CStrings:  915
+  Symbols:   402
+  CStrings:  918
Symbols:
+ _OBJC_CLASS_$_NRPairedDeviceRegistry
Functions:
~ sub_10000380c -> sub_100003874 : 1244 -> 1264
~ sub_100007dcc -> sub_100007e48 : 2148 -> 2136
~ sub_10000b908 -> sub_10000b978 : 660 -> 656
~ sub_10000c5b4 -> sub_10000c620 : 1148 -> 1144
~ sub_10000ca30 -> sub_10000ca98 : 676 -> 668
~ sub_10000e324 -> sub_10000e384 : 168 -> 188
~ sub_10000e3cc -> sub_10000e440 : 208 -> 236
~ sub_1000176bc -> sub_10001774c : 360 -> 352
~ sub_100017824 -> sub_1000178ac : 328 -> 332
~ sub_100018444 -> sub_1000184d0 : 244 -> 268
~ sub_100019990 -> sub_100019a34 : 268 -> 272
~ sub_100019c90 -> sub_100019d38 : 124 -> 132
CStrings:
+ "reindex all searchableItems request from extension (scope %ld)"
+ "reindexAllSearchableItemsForScope:completionHandler:"
+ "reindexSearchableItemsWithIdentifiers request: %lu (scope %ld)"
+ "reindexSearchableItemsWithIdentifiers:scope:completionHandler:"
+ "v32@0:8q16@?24"
+ "v32@0:8q16@?<v@?@\"NSError\">24"
+ "v40@0:8@\"NSArray\"16q24@?<v@?@\"NSError\">32"
+ "v40@0:8@16q24@?32"
- "reindex all searchableItems request from extension"
- "reindex reindexSearchableItemsWithIdentifiers request from extension: %lu"
- "reindexAllSearchableItemsWithCompletionHandler:"
- "reindexSearchableItemsWithIdentifiers:completionHandler:"
- "v32@0:8@\"NSArray\"16@?<v@?@\"NSError\">24"
```
