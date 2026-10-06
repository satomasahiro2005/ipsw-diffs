## wifivelocityd

> `/usr/libexec/wifivelocityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9a8f8` | `0x99894` | **`-0x1064`** |
| `__DATA_CONST.__cfstring` | `0xaf40` | `0xaea0` | **`-0xa0`** |
| `__TEXT.__objc_methname` | `0xddbb` | `0xdd46` | **`-0x75`** |
| `__TEXT.__cstring` | `0xc5a6` | `0xc533` | **`-0x73`** |
| `__DATA.__objc_const` | `0x8ba0` | `0x8b30` | **`-0x70`** |
| `__TEXT.__objc_stubs` | `0xd1c0` | `0xd160` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0x1b88` | `0x1b38` | **`-0x50`** |
| `__DATA_CONST.__objc_arrayobj` | `0x1500` | `0x14d0` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x53e4` | `0x53c4` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x3aa8` | `0x3a90` | **`-0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x23b0` | `0x23a0` | **`-0x10`** |
| `__TEXT.__const` | `0x3b0` | `0x3c0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x6e4` | `0x6d8` | **`-0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-  Functions: 2367
+  Functions: 2346

-  CStrings:  5281
+  CStrings:  5269
CStrings:
- "-dbg=print_nan_avail"
- "-nan"
- "-nan_peers"
- "Filtered known networks for customer install without MegaWiFi profile\n"
- "T@\"W5WiFiInterface\",R,&,V_nan"
- "__startNANPerfLogging"
- "__startNANQueryTimer"
- "_nan"
- "_nanQueryFileHandle"
- "_nanQueryTimer"
- "nan"
- "nan_%@"
```
