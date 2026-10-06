## HSTouchHIDService

> `/System/Library/HIDPlugins/ServicePlugins/HSTouchHIDService.plugin/HSTouchHIDService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcfc38` | `0xcfca0` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x4c64` | `0x4caa` | **`+0x46`** |
| `__DATA_CONST.__cfstring` | `0x7720` | `0x7760` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1e18` | `0x1dd8` | **`-0x40`** |
| `__TEXT.__objc_stubs` | `0x7ae0` | `0x7b20` | **`+0x40`** |
| `__DATA_CONST.__objc_dictobj` | `0x258` | `0x230` | **`-0x28`** |
| `__TEXT.__objc_methname` | `0x908a` | `0x90a9` | **`+0x1f`** |
| `__DATA_CONST.__objc_intobj` | `0x6c0` | `0x6a8` | **`-0x18`** |
| `__TEXT.__cstring` | `0xc1d9` | `0xc1f1` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x2430` | `0x2440` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x518` | `0x508` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0xead0` | `0xead8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4908` | `0x4900` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-10100.44.0.0.0
+10110.3.0.0.0

-  Functions: 5286
+  Functions: 5285

-  CStrings:  4199
+  CStrings:  4203
Symbols:
+ _objc_msgSend$boolForKey:
+ _objc_msgSend$initWithSuiteName:
- ___48+[HSTouchHIDService matchService:options:score:]_block_invoke_2
- ___block_descriptor_32_e19_"NSDictionary"8?0l
Functions:
~ +[HSTouchHIDService matchService:options:score:] : 972 -> 944
- ___48+[HSTouchHIDService matchService:options:score:]_block_invoke_2
~ -[HSTSensingAlgs createUserDevice:platformId:] : 744 -> 888
CStrings:
+ "10110.3"
+ "MTDisableDebugUserDevice"
+ "MTDisableDebugUserDevice set; skipping debug HID user device creation"
+ "boolForKey:"
+ "initWithSuiteName:"
- "10100.44"
```
