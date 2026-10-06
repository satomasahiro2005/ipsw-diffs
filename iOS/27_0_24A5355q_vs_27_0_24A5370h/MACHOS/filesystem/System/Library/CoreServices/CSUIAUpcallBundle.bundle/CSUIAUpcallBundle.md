## CSUIAUpcallBundle

> `/System/Library/CoreServices/CSUIAUpcallBundle.bundle/CSUIAUpcallBundle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9c2c` | `0x9cc8` | **`+0x9c`** |
| `__TEXT.__auth_stubs` | `0xa00` | `0x9f0` | **`-0x10`** |
| `__TEXT.__cstring` | `0x1c9` | `0x1b9` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x144` | `0x138` | **`-0xc`** |
| `__TEXT.__swift5_typeref` | `0x2be` | `0x2b2` | **`-0xc`** |
| `__DATA_CONST.__auth_got` | `0x508` | `0x500` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x608` | `0x600` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-465.0.0.0.0
+468.0.0.0.0

-  Symbols:   177
+  Symbols:   176
Symbols:
- _objc_retain_x27
Functions:
~ sub_268c : 256 -> 276
~ sub_278c -> sub_27a0 : 256 -> 264
~ sub_5348 -> sub_5364 : 788 -> 852
~ sub_6628 -> sub_6684 : 916 -> 864
~ sub_6a8c -> sub_6ab4 : 304 -> 388
~ sub_6bbc -> sub_6c38 : 268 -> 300
~ sub_6cc8 -> sub_6d64 : 28 -> 108
~ sub_6d4c -> sub_6e38 : 116 -> 128
~ sub_6e38 -> sub_6f30 : 444 -> 404
~ sub_762c -> sub_76fc : 716 -> 708
~ sub_97b8 -> sub_9880 : 280 -> 276
~ sub_a5a8 -> sub_a66c : 80 -> 64
~ sub_a5f8 -> sub_a6ac : 212 -> 180
~ sub_a7d0 -> sub_a864 : 140 -> 148
CStrings:
+ "presentAlertAndWaitForResult()"
- "presentAlertAndWaitForResult(for:on:)"
```
