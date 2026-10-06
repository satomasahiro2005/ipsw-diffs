## restorecameraispd

> `/usr/libexec/restorecameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x571c88` | `0x5acc88` | **`+0x3b000`** |
| `__TEXT.__text` | `0x1d5c4` | `0x1d92c` | **`+0x368`** |
| `__TEXT.__cstring` | `0x345f` | `0x350c` | **`+0xad`** |
| `__DATA_CONST.__cfstring` | `0x15e0` | `0x1620` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x2350` | `0x237c` | **`+0x2c`** |
| `__TEXT.__auth_stubs` | `0xf90` | `0xfb0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x7d8` | `0x7e8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x570` | `0x578` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x4b8` | `0x4b4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__const`

### Other Changes

```diff

-20.105.6.0.0
+20.106.4.0.0

-  Functions: 425
-  Symbols:   301
-  CStrings:  644
+  Functions: 430
+  Symbols:   303
+  CStrings:  653
Symbols:
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
CStrings:
+ "%s - Error reading kernel config cache - chan: %d, res: 0x%08X\n"
+ "%s - channel configs not valid - exiting\n"
+ "%s - kernel config count %d != firmware %d - chan: %d\n"
+ "/usr/local/share/firmware/isp/2027_01XX.dat"
+ "/usr/local/share/firmware/isp/2327_01XX.dat"
+ "/usr/local/share/firmware/isp/2327_02XX.dat"
+ "20.106.4"
+ "CacheChannelConfigs"
+ "Could not find %s as %s (errno: %d)"
+ "Found %s at %s."
+ "Will use ISP references"
+ "Will use SEP references"
+ "sparse reference plist"
+ "sparseLP reference plist"
- "%s - Error getting LSC polynomial - chan: %d, res: 0x%08X\n"
- "%s - Error getting camera config - chan: %d, res: 0x%08X\n"
- "20.105.6"
- "Could not find reference plist at %s (errno: %d). Will use ISP references"
- "Found reference plist at %s. Will use SEP references"
```
