## MessagesCloudSync

> `/System/Library/PrivateFrameworks/MessagesCloudSync.framework/MessagesCloudSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1038c8` | `0x104564` | **`+0xc9c`** |
| `__DATA.__bss` | `0x7f80` | `0x8200` | **`+0x280`** |
| `__TEXT.__const` | `0x99b0` | `0x9bc0` | **`+0x210`** |
| `__TEXT.__oslogstring` | `0x5a33` | `0x5b63` | **`+0x130`** |
| `__TEXT.__swift5_typeref` | `0x2868` | `0x28de` | **`+0x76`** |
| `__TEXT.__swift5_assocty` | `0x5b8` | `0x618` | **`+0x60`** |
| `__DATA.__data` | `0xf98` | `0xfd8` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x307a` | `0x30aa` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x2c34` | `0x2c60` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0x8e51` | `0x8e79` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1020` | `0x1048` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x33bc` | `0x33d8` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0x140` | `0x154` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x75c` | `0x770` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x1158` | `0x1168` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x27d0` | `0x27c0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x38d8` | `0x38e0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2dc` | `0x2e0` | **`+0x4`** |

### Other Changes

```diff

-1491.200.73.0.0
+1491.200.95.0.0

-  Functions: 3896
+  Functions: 3926

-  CStrings:  870
+  CStrings:  872
CStrings:
+ "Transfer %s: could not size the record's asset at %s; not adopting the cloud copy"
+ "Transfer %s: could not size the record's asset at %s; not preferring the local copy"
+ "Transfer %s: incoming has unknown pgen state, but local is valid. Incoming stored pgen state %ld, resolved %ld, attributionInfo %s. Existing stored pgen state %ld, resolved %ld, attributionInfo %s"
+ "Transfer %s: local data newer than cloud; marking fieldsToSync %s to update server"
- "Transfer %s: incoming has unknown pgen state, but local progressed past that, it is newer than cloud"
- "Transfer %s: local data newer than cloud; marking dirty to update server"
```
