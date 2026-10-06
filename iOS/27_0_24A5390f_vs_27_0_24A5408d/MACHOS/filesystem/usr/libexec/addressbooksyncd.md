## addressbooksyncd

> `/usr/libexec/addressbooksyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3bf0c` | `0x3c090` | **`+0x184`** |
| `__TEXT.__oslogstring` | `0x25f2` | `0x263e` | **`+0x4c`** |
| `__DATA_CONST.__cfstring` | `0x3300` | `0x3340` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2d76` | `0x2dac` | **`+0x36`** |
| `__TEXT.__unwind_info` | `0xd18` | `0xd20` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-307.0.0.0.0
+308.0.0.0.0

-  CStrings:  2700
+  CStrings:  2704
Functions:
~ sub_100025fb8 : 100 -> 300
~ sub_100032a40 -> sub_100032b08 : 564 -> 752
CStrings:
+ "== Started AddressBookSync-308"
+ "Forcing census alert via %@ override"
+ "Forcing favorites sync via %@ override"
+ "internal_forceCensusAlert"
+ "internal_forceFavoritesSync"
- "== Started AddressBookSync-307"
```
