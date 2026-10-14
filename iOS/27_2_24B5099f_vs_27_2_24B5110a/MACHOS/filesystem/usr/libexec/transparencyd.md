## transparencyd

> `/usr/libexec/transparencyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x356244` | `0x356ca4` | **`+0xa60`** |
| `__TEXT.__cstring` | `0x151f0` | `0x152f0` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x152ca` | `0x153aa` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x26c92` | `0x26d42` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x317e` | `0x31ce` | **`+0x50`** |
| `__DATA.__objc_const` | `0x33dd0` | `0x33e18` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `0x1ea20` | `0x1ea60` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1f2d8` | `0x1f2f8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x16310` | `0x16330` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x8a41` | `0x8a61` | **`+0x20`** |
| `__DATA.__objc_data` | `0xab60` | `0xab78` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x4628` | `0x4640` | **`+0x18`** |
| `__DATA.__data` | `0xe5e8` | `0xe5d8` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x8d28` | `0x8d38` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x5120` | `0x5128` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd688` | `0xd690` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
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
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1766.40.56.0.0
+1766.40.58.0.0

-  Functions: 20639
+  Functions: 20647

-  CStrings:  12101
+  CStrings:  12109
CStrings:
+ "@56@0:8@16@24@32@40d48"
+ "How much older than the IDS answer the KT answer IDS supplies must be before a peer lookup queries KT again because the two disagree. A younger answer is what a query now would return. 0 queries on every disagreement."
+ "KTSuppliedLeafRefreshMinimumAge"
+ "hasSignedClientData"
+ "initWithContextStore:queryManager:ktLogClient:database:suppliedLeafRefreshMinimumAge:"
+ "suppliedLeafContradictionReason: %lu IDS device(s) without signed client data left out of the leaf check for %{mask.hash}@"
+ "suppliedLeafRefreshMinimumAge"
+ "suppliedLeafRefreshMinimumAgeConfig"
+ "validateURI: %s supplied leaf is %.*fs older than the IDS answer, under %fs, not checking it"
- "initWithContextStore:queryManager:ktLogClient:database:"
```
