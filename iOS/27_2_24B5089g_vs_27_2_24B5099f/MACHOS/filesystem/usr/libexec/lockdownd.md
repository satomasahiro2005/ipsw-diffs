## lockdownd

> `/usr/libexec/lockdownd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91fe0` | `0x92008` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x15c0` | `0x15e0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x180` | `0x190` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xc38` | `0xc48` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x3f7` | `0x405` | **`+0xe`** |
| `__DATA.__objc_selrefs` | `0x5a8` | `0x5b0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xaf0` | `0xaf8` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0xf22` | `0xf28` | **`+0x6`** |
| `__TEXT.__cstring` | `0xee5e` | `0xee5f` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-1378.40.2.0.0
+1378.40.3.0.0

-  Functions: 882
+  Functions: 883

-  CStrings:  2521
+  CStrings:  2522
CStrings:
+ "-[LockdownWiFiMonitor start]"
+ "Tried to start WiFi monitor with no interface; this is a no-op"
+ "start"
- "-[LockdownWiFiMonitor init]"
- "Failed to create initial state WiFiMonitor block"
```
