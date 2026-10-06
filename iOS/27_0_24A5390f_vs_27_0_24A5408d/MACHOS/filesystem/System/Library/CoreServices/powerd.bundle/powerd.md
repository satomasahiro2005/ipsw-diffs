## powerd

> `/System/Library/CoreServices/powerd.bundle/powerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77d44` | `0x77f30` | **`+0x1ec`** |
| `__TEXT.__oslogstring` | `0xe24a` | `0xe213` | **`-0x37`** |
| `__DATA_CONST.__cfstring` | `0x76a0` | `0x76c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x6e93` | `0x6ead` | **`+0x1a`** |
| `__DATA_CONST.__objc_intobj` | `0x3f0` | `0x408` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1690` | `0x1698` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-2043.0.31.0.0
+2043.0.45.502.1

-  Functions: 2648
+  Functions: 2649
CStrings:
+ "3.3"
+ "@24@0:8^{?=IIb1b1b1b1b1iiiiiiQiiiiiiQIiiQiii@@@qi@@I^{?}}16"
+ "Permanent Battery Failure"
+ "i32@0:8@\"NSDictionary\"16^{?=IIb1b1b1b1b1iiiiiiQiiiiiiQIiiQiii@@@qi@@I^{?}}24"
+ "i32@0:8@16^{?=IIb1b1b1b1b1iiiiiiQiiiiiiQIiiQiii@@@qi@@I^{?}}24"
+ "i32@0:8^{?=IIb1b1b1b1b1iiiiiiQiiiiiiQIiiQiii@@@qi@@I^{?}}16^@24"
- "3.2"
- "@24@0:8^{?=IIb1b1b1b1b1iiiiiiIiiiiiiQIiiQiii@@@qi@@I^{?}}16"
- "Invalid tlcCounter, skip battery charging state update"
- "i32@0:8@\"NSDictionary\"16^{?=IIb1b1b1b1b1iiiiiiIiiiiiiQIiiQiii@@@qi@@I^{?}}24"
- "i32@0:8@16^{?=IIb1b1b1b1b1iiiiiiIiiiiiiQIiiQiii@@@qi@@I^{?}}24"
- "i32@0:8^{?=IIb1b1b1b1b1iiiiiiIiiiiiiQIiiQiii@@@qi@@I^{?}}16^@24"
```
