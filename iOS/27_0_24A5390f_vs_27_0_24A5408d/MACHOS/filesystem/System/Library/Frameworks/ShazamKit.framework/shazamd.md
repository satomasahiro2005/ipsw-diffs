## shazamd

> `/System/Library/Frameworks/ShazamKit.framework/shazamd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f7cc` | `0x4f9a0` | **`+0x1d4`** |
| `__TEXT.__oslogstring` | `0x4d55` | `0x4da8` | **`+0x53`** |
| `__TEXT.__objc_stubs` | `0xd1a0` | `0xd1c0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x10d4e` | `0x10d62` | **`+0x14`** |
| `__DATA.__objc_const` | `0xccf0` | `0xcd00` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x6164` | `0x6174` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x3b38` | `0x3b40` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x918` | `0x920` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x14e0` | `0x14e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-427.0.44.0.0
+427.0.48.0.0

-  Functions: 1885
-  Symbols:   446
-  CStrings:  3921
+  Functions: 1886
+  Symbols:   447
+  CStrings:  3923
Symbols:
+ _AVAudioSessionPortCarAudio
CStrings:
+ "Overriding the signature recording source to external due to active Carplay route."
+ "isUsingCarPlayRoute"
```
