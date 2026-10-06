## cameraispd

> `/usr/libexec/cameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x3aede0` | `0x3bdde0` | **`+0xf000`** |
| `__TEXT.__text` | `0x7cd44` | `0x7ce40` | **`+0xfc`** |
| `__TEXT.__cstring` | `0x7754` | `0x77aa` | **`+0x56`** |
| `__TEXT.__oslogstring` | `0x5f8f` | `0x5fd3` | **`+0x44`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-20.57.3.0.0
+20.62.0.0.0

-  Functions: 1560
+  Functions: 1561

-  CStrings:  1841
+  CStrings:  1844
CStrings:
+ "/usr/local/share/firmware/isp/0227_01XX.dat"
+ "/usr/local/share/firmware/isp/2226_01XX.dat"
+ "20.62"
+ "ISP still in use by another session; keeping shared interface open\n"
- "20.57.3"
```
