## nanoregistryd

> `/usr/libexec/nanoregistryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10047c` | `0x100628` | **`+0x1ac`** |
| `__DATA_CONST.__cfstring` | `0xbfe0` | `0xc040` | **`+0x60`** |
| `__TEXT.__cstring` | `0xe058` | `0xe0aa` | **`+0x52`** |
| `__TEXT.__objc_methname` | `0x1c5ad` | `0x1c5ee` | **`+0x41`** |
| `__DATA.__objc_selrefs` | `0x5e80` | `0x5e88` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xdacc` | `0xdad4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3a58` | `0x3a60` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
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

-1075.0.0.0.0
+1075.1.0.0.0

-  Functions: 5826
+  Functions: 5827

-  CStrings:  8647
+  CStrings:  8651
Functions:
~ sub_100022a6c : 724 -> 856
+ sub_100070ac0
CStrings:
+ "55"
+ "NanoRegistry-1075.1"
+ "com.apple.nanoregistry.watch-migration-start"
+ "companionConnected"
+ "companionNearby"
+ "reportWatchMigrationBeginWithCompanionNearby:companionConnected:"
- "18"
- "NanoRegistry-1075"
```
