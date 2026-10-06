## libSystemDetermination.dylib

> `/System/Library/Frameworks/CoreTelephony.framework/Support/libSystemDetermination.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f654` | `0x6faa0` | **`+0x44c`** |
| `__TEXT.__oslogstring` | `0x9d41` | `0x9e3c` | **`+0xfb`** |
| `__TEXT.__cstring` | `0x36a3` | `0x36c4` | **`+0x21`** |
| `__TEXT.__gcc_except_tab` | `0x597c` | `0x5988` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x2418` | `0x2420` | **`+0x8`** |

### Other Changes

```diff

-13478.3.1.3.0
+13482.1.0.0.0

-  CStrings:  1453
+  CStrings:  1458
CStrings:
+ "424 Bad Location received on WiFi. Suppressing WiFi PCSCF and retrying on cellular."
+ "No cellular PCSCF available after 424 Bad Location. Giving up."
+ "RCSRegRefreshTimer: already registered, re-arming timer."
+ "RCSRegistrationEvent-NoCellPcscf"
+ "Skipping WiFi PCSCF %s due to 424 Bad Location"
```
