## dmd

> `/usr/libexec/dmd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x812dc` | `0x81558` | **`+0x27c`** |
| `__TEXT.__oslogstring` | `0xb22e` | `0xb2a0` | **`+0x72`** |
| `__TEXT.__objc_methname` | `0x11846` | `0x1186f` | **`+0x29`** |
| `__TEXT.__cstring` | `0x5489` | `0x54ae` | **`+0x25`** |
| `__DATA_CONST.__cfstring` | `0x57e0` | `0x5800` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xe960` | `0xe980` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xef0` | `0xf00` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x4198` | `0x41a0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x788` | `0x790` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x2740` | `0x2748` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2210` | `0x2218` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-259.0.0.0.0
+260.0.0.0.0

-  Functions: 3218
-  Symbols:   918
-  CStrings:  4519
+  Functions: 3220
+  Symbols:   919
+  CStrings:  4522
Symbols:
+ _xpc_dictionary_get_data
CStrings:
+ "Received xpc stream event (trusted distributed notification matching) with name: %{public}@ user info: %{public}@"
+ "com.apple.distnoted.matching.trusted"
+ "dataWithBytesNoCopy:length:freeWhenDone:"
```
