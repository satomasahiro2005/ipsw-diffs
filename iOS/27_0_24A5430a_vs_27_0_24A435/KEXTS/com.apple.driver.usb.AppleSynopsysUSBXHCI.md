## com.apple.driver.usb.AppleSynopsysUSBXHCI

> `com.apple.driver.usb.AppleSynopsysUSBXHCI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x415a0` | `0x52ac0` | **`+0x11520`** |
| `__TEXT.__os_log` | `0x6a7a` | `0x8b8a` | **`+0x2110`** |
| `__DATA_CONST.__const` | `0x8718` | `0x9288` | **`+0xb70`** |
| `__TEXT.__cstring` | `0x43d2` | `0x44cd` | **`+0xfb`** |
| `__DATA_CONST.__kalloc_type` | `0x600` | `0x680` | **`+0x80`** |
| `__DATA.__common` | `0x2b8` | `0x2e0` | **`+0x28`** |
| `__TEXT_EXEC.__auth_stubs` | `0x5d0` | `0x5e0` | **`+0x10`** |
| `__DATA.__bss` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x2e8` | `0x2f0` | **`+0x8`** |
| `__DATA_CONST.__mod_init_func` | `0x88` | `0x90` | **`+0x8`** |
| `__DATA_CONST.__mod_term_func` | `0x88` | `0x90` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 591
+  Functions: 644

-  CStrings:  277
+  CStrings:  285
CStrings:
+ "%s@%s: %s::%s: copyMapperForDevice() failed\n"
+ "%s@%s: %s::%s: failed to create AppleTypeCPhy session\n"
+ "%s@%s: %s::%s: failed to enable USB2 phy\n"
+ "%s@%s: %s::%s: failed to enable USB3 phy\n"
+ "112"
+ "AppleT8160USBXHCI"
+ "AppleT8160USBXHCI.cpp"
+ "site.AppleT8160USBXHCI"
```
