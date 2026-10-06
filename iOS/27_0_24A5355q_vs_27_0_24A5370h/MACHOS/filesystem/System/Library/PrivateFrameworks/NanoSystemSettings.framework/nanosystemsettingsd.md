## nanosystemsettingsd

> `/System/Library/PrivateFrameworks/NanoSystemSettings.framework/nanosystemsettingsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x25e0` | `0x2677` | **`+0x97`** |
| `__TEXT.__text` | `0x1d468` | `0x1d470` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-374.0.0.0.0
+375.0.0.0.0

-  CStrings:  1536
+  CStrings:  1538
Functions:
~ sub_100003ef4 : 7012 -> 6864
~ sub_100006794 -> sub_100006700 : 304 -> 300
~ sub_10000b6c8 -> sub_10000b630 : 1016 -> 1112
~ sub_10000bac0 -> sub_10000ba88 : 200 -> 280
~ sub_10000c454 -> sub_10000c46c : 1344 -> 1340
~ sub_10000c994 -> sub_10000c9a8 : 336 -> 332
~ sub_10000df14 -> sub_10000df24 : 1824 -> 1820
~ sub_10000e634 -> sub_10000e640 : 1716 -> 1712
~ sub_10000fff0 -> sub_10000fff8 : 2296 -> 2288
~ sub_100013ef4 : 404 -> 400
~ sub_100014110 -> sub_10001410c : 404 -> 400
~ sub_10001869c -> sub_100018694 : 372 -> 368
~ sub_10001e58c -> sub_10001e580 : 984 -> 980
~ sub_10001ea9c -> sub_10001ea8c : 1260 -> 1284
CStrings:
+ "Launching; \"NanoSystemSettingsDaemon-375\" \"146\""
+ "[obliterateGizmo] NanoRegistry unpair operationHasBegun, error=%@"
+ "[obliterateGizmo] handing off to NanoRegistry unpairWithDevice: options=%@ device=%@"
- "Launching; \"NanoSystemSettingsDaemon-374\" \"400\""
```
