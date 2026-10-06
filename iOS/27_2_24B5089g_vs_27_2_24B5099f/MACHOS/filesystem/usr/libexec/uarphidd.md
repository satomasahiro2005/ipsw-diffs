## uarphidd

> `/usr/libexec/uarphidd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x58d0` | `0x5bb0` | **`+0x2e0`** |
| `__TEXT.__gcc_except_tab` | `—` | `0x9c` | **`+0x9c`** |
| `__TEXT.__oslogstring` | `0x8f9` | `0x96c` | **`+0x73`** |
| `__TEXT.__auth_stubs` | `0x580` | `0x5d0` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x2c8` | `0x2f8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x178` | `0x1a0` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0xd80` | `0xda0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xeea` | `0xf00` | **`+0x16`** |
| `__DATA.__objc_selrefs` | `0x418` | `0x420` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xc8` | `0xc0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x198` | `0x1a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1587.40.28.0.0
+1587.40.33.0.0

-  Functions: 155
-  Symbols:   120
-  CStrings:  388
+  Functions: 157
+  Symbols:   126
+  CStrings:  392
Symbols:
+ __Unwind_Resume
+ ___objc_personality_v0
+ _objc_copyWeak
+ _objc_destroyWeak
+ _objc_initWeak
+ _objc_loadWeakRetained
CStrings:
+ "%s: Allow VID=0x%04x PID=0x%04x"
+ "%s: Ignore VID=0x%04x PID=0x%04x"
+ "%s: VID=0x%04x PID=0x%04x has no serial number is ioreg ?!?"
+ "%s: entry has nil serial number ?! %@"
+ "%s: known entry matching dict %@"
+ "removeObjectsInArray:"
+ "weak self was nil"
- "%s: Allow PID=0x%04x PID=0x%04x"
- "%s: Ignore PID=0x%04x PID=0x%04x"
- "%s: known entrey matching dict %@"
```
