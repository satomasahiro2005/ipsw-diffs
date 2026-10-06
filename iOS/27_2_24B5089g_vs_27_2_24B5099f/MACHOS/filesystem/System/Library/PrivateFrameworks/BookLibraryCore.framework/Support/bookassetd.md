## bookassetd

> `/System/Library/PrivateFrameworks/BookLibraryCore.framework/Support/bookassetd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe27c4` | `0xe2978` | **`+0x1b4`** |
| `__TEXT.__oslogstring` | `0xc63b` | `0xc6ae` | **`+0x73`** |
| `__TEXT.__cstring` | `0x3ae1` | `0x3b0a` | **`+0x29`** |
| `__DATA_CONST.__const` | `0x7ea0` | `0x7ec0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xdb0` | `0xdc0` | **`+0x10`** |
| `__DATA.__bss` | `0x160` | `0x168` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x6f0` | `0x6f8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1a30` | `0x1a38` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2353.0.0.0.0
+2354.0.0.0.0

-  Functions: 2440
-  Symbols:   589
-  CStrings:  4626
+  Functions: 2442
+  Symbols:   590
+  CStrings:  4631
Symbols:
+ _sysctlbyname
Functions:
~ sub_1000c39ac : 240 -> 412
+ sub_1000c3b80
+ sub_1000e42b8
CStrings:
+ "FairPlay decrypt failed: %d (sample size %u)"
+ "FairPlay decrypt path: %{public}s (kern.hv_vmm_present=%d, status=%d)"
+ "chunks"
+ "kern.hv_vmm_present"
+ "single-sample"
```
