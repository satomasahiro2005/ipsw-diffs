## dasd

> `/usr/libexec/dasd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1779b8` | `0x178114` | **`+0x75c`** |
| `__TEXT.__objc_methname` | `0x2e49d` | `0x2e5bd` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0x1af80` | `0x1b040` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x16be9` | `0x16c79` | **`+0x90`** |
| `__DATA_CONST.__cfstring` | `0x118e0` | `0x11940` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x131b4` | `0x131f4` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x41c1` | `0x4201` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x9cc0` | `0x9cf0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x10566` | `0x10586` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x5050` | `0x5068` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
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
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2467.2.1.0.0
+2467.2.2.0.0

-  Functions: 8343
+  Functions: 8349

-  CStrings:  12437
+  CStrings:  12452
CStrings:
+ "%@|v"
+ "%@|v%ld"
+ "@32@0:8@16q24"
+ "FastPass %{public}@ v%d consumed %.1fs this run, %.1fs cumulative"
+ "FastPass %{public}@ v%d has consumed %.1fs of its %.1fs budget, %.1fs remaining"
+ "FastPassConsumedRuntime"
+ "accrueFastPassRuntimeForActivity:"
+ "addConsumedRuntime:forFastPass:semanticVersion:"
+ "clearConsumedRuntimeForFastPass:resetAll:"
+ "consumedRuntimeForFastPass:semanticVersion:"
+ "consumedRuntimeKeyForFastPass:semanticVersion:"
+ "d32@0:8@16q24"
+ "d40@0:8@16q24d32"
+ "remainingRuntimeForFastPass:semanticVersion:budget:"
+ "v40@0:8d16@24q32"
```
