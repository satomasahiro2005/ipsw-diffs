## restorecameraispd

> `/usr/libexec/restorecameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x3bdc00` | `0x571c88` | **`+0x1b4088`** |
| `__TEXT.__text` | `0x1d010` | `0x1d5c4` | **`+0x5b4`** |
| `__TEXT.__cstring` | `0x32fe` | `0x345f` | **`+0x161`** |
| `__TEXT.__oslogstring` | `0x22c4` | `0x2350` | **`+0x8c`** |
| `__TEXT.__const` | `0x16d0` | `0x16e0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x568` | `0x570` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-20.77.1.0.0
+20.104.4.0.0

-  Functions: 420
+  Functions: 425

-  CStrings:  634
+  CStrings:  644
CStrings:
+ "/usr/local/share/firmware/isp/2727_01XX.dat"
+ "/usr/local/share/firmware/isp/3527_02XX.dat"
+ "/usr/local/share/firmware/isp/3527_03XX.dat"
+ "/usr/local/share/firmware/isp/4227_01XX.dat"
+ "/usr/local/share/firmware/isp/4427_01XX.dat"
+ "/usr/local/share/firmware/isp/7127_02XX.dat"
+ "/usr/local/share/firmware/isp/7327_01XX.dat"
+ "/usr/local/share/firmware/isp/7327_02XX.dat"
+ "20.104.4"
+ "Unexpected client Get data length=%zu expected=%zu (pid %{private}d)\n"
+ "Unexpected client Set data length=%zu expected=%zu (pid %{private}d)\n"
- "20.77.1"
```
