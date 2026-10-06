## libMobileGestalt.dylib

> `/usr/lib/libMobileGestalt.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__const` | `0x22800` | `0x26268` | **`+0x3a68`** |
| `__TEXT.__text` | `0x6b748` | `0x6c1e8` | **`+0xaa0`** |
| `__TEXT.__unwind_info` | `0x2328` | `0x22e0` | **`-0x48`** |
| `__AUTH_CONST.__cfstring` | `0x13380` | `0x133c0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1790d` | `0x1794d` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x190` | `0x158` | **`-0x38`** |
| `__AUTH_CONST.__auth_got` | `0xa38` | `0xa68` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x44` | `0x24` | **`-0x20`** |
| `__DATA.__bss` | `0xe00` | `0xdf0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1d8` | **`+0x10`** |
| `__TEXT.__const` | `0xa788` | `0xa798` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1e18` | `0x1e20` | **`+0x8`** |

### Other Changes

```diff

-1622.0.5.0.0
+1622.40.10.0.0

-  Functions: 3617
-  Symbols:   1510
-  CStrings:  3872
+  Functions: 3620
+  Symbols:   1512
+  CStrings:  3874
Symbols:
+ _MobileGestalt_get_deviceShowsBatteryModelInformationLegacyHW
+ _swift_deallocClassInstance
+ _swift_release
- _objc_enumerationMutation
CStrings:
+ "8AF94169-7706-452F-BFF5-73C1912CF133"
+ "DeviceShowsBatteryModelInformationLegacyHW"
+ "Rq0MF/w+gXM66Ii4fkWOzg"
+ "show-legacy-battery-model-info"
+ "special-regions-count"
- "2067C7B1-457D-4028-AD86-5F02D952C264"
- "Class getNFHardwareManagerClass(void)_block_invoke"
- "NFHardwareManager"
```
