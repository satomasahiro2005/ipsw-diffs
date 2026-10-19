## wifid

> `/usr/sbin/wifid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x1c920` | `0x1c960` | **`+0x40`** |
| `__TEXT.__text` | `0x1c43a8` | `0x1c4374` | **`-0x34`** |
| `__TEXT.__objc_stubs` | `0x150a0` | `0x15080` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x1b455` | `0x1b437` | **`-0x1e`** |
| `__TEXT.__cstring` | `0x75e3e` | `0x75e50` | **`+0x12`** |
| `__DATA.__common` | `0x60` | `0x68` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x63d0` | `0x63c8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1408` | `0x1400` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   1356
-  CStrings:  17388
+  Symbols:   1355
+  CStrings:  17389
Symbols:
- _kWAMessageKeyPrivateMacHomeNetwork
CStrings:
+ "WiFiManager-2029.9 Oct  8 2026 01:03:56"
+ "WiFiManager-2029.9 Oct  8 2026 01:05:20"
+ "iPad12,1"
+ "iPad12,2"
- "WiFiManager-2029.9 Oct  4 2026 02:16:18"
- "WiFiManager-2029.9 Oct  4 2026 02:17:11"
- "setPrivateMacNetworkTypeHome:"
```
