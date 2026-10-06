## nanoregistryd

> `/usr/libexec/nanoregistryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x1609d` | `0x16191` | **`+0xf4`** |
| `__TEXT.__text` | `0x1003d0` | `0x10047c` | **`+0xac`** |
| `__DATA.__objc_const` | `0x1a360` | `0x1a380` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0xbfc0` | `0xbfe0` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x4baf` | `0x4bc9` | **`+0x1a`** |
| `__DATA_CONST.__objc_intobj` | `0xe10` | `0xe28` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x1c595` | `0x1c5ad` | **`+0x18`** |
| `__TEXT.__cstring` | `0xe041` | `0xe058` | **`+0x17`** |
| `__TEXT.__unwind_info` | `0x3a68` | `0x3a58` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x11dc` | `0x11e0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1070.0.0.0.0
+1075.0.0.0.0

-  Functions: 5823
+  Functions: 5826

-  CStrings:  8644
+  CStrings:  8647
CStrings:
+ "18"
+ "NanoRegistry-1075"
+ "[obliterateGizmo] watch received DeviceWillUnpairRequest: advertisedName=%{public}@ shouldObliterate=%{BOOL}d shouldBrick=%{BOOL}d shouldPreserveESim=%{BOOL}d shouldOverwriteStorage=%{BOOL}d pairingFailureCode=%{public}@ abortReason=%{public}@"
+ "_shouldOverwriteStorage"
+ "shouldOverwriteStorage"
+ "{?=\"pairingFailureCode\"b1\"shouldBrick\"b1\"shouldObliterate\"b1\"shouldOverwriteStorage\"b1\"shouldPreserveESim\"b1}"
- "31"
- "NanoRegistry-1070"
- "{?=\"pairingFailureCode\"b1\"shouldBrick\"b1\"shouldObliterate\"b1\"shouldPreserveESim\"b1}"
```
