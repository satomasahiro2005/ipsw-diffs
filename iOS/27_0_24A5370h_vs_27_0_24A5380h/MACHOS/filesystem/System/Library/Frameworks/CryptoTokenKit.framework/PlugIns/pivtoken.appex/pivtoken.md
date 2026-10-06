## pivtoken

> `/System/Library/Frameworks/CryptoTokenKit.framework/PlugIns/pivtoken.appex/pivtoken`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3318` | `0x33d4` | **`+0xbc`** |
| `__TEXT.__oslogstring` | `0x2ac` | `0x2f1` | **`+0x45`** |
| `__TEXT.__objc_stubs` | `0xce0` | `0xcc0` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x434` | `0x424` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x120` | `0x130` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0xec` | `0xe2` | **`-0xa`** |
| `__TEXT.__objc_methname` | `0xbaa` | `0xba0` | **`-0xa`** |
| `__DATA.__objc_selrefs` | `0x460` | `0x458` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`

### Other Changes

```diff

-878.0.3.0.0
+878.0.8.0.0
CStrings:
+ "skipping %{public}@: unsupported PIV key (type %{public}@, %ld bits)"
- "hexString"
```
