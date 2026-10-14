## wifid

> `/usr/sbin/wifid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x1c900` | `0x1c920` | **`+0x20`** |
| `__TEXT.__text` | `0x1c4388` | `0x1c43a8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x75e30` | `0x75e3e` | **`+0xe`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  17387
+  CStrings:  17388
Functions:
~ sub_1000b6294 : 208 -> 228
~ sub_1000d0274 -> sub_1000d0288 : 3800 -> 3812
CStrings:
+ "HomeAccessory"
+ "WiFiManager-2029.9 Oct  4 2026 02:16:18"
+ "WiFiManager-2029.9 Oct  4 2026 02:17:11"
- "WiFiManager-2029.9 Sep 27 2026 23:38:55"
- "WiFiManager-2029.9 Sep 27 2026 23:40:00"
```
