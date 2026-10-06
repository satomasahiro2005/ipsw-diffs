## com.apple.driver.usb.AppleSynopsysUSB40XHCI

> `com.apple.driver.usb.AppleSynopsysUSB40XHCI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x63c3c` | `0x796a4` | **`+0x15a68`** |
| `__TEXT.__os_log` | `0xc733` | `0xf1b4` | **`+0x2a81`** |
| `__DATA_CONST.__const` | `0x58a0` | `0x65f8` | **`+0xd58`** |
| `__DATA_CONST.__kalloc_type` | `0x480` | `0x540` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x2e01` | `0x2eb0` | **`+0xaf`** |
| `__DATA.__common` | `0x218` | `0x268` | **`+0x50`** |
| `__DATA_CONST.__mod_init_func` | `0x68` | `0x78` | **`+0x10`** |
| `__DATA_CONST.__mod_term_func` | `0x68` | `0x78` | **`+0x10`** |
| `__TEXT_EXEC.__auth_stubs` | `0x2e0` | `0x2f0` | **`+0x10`** |
| `__DATA.__bss` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x170` | `0x178` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 465
+  Functions: 545

-  CStrings:  180
+  CStrings:  187
CStrings:
+ "%s@%s: %s::%s: copyMapperForDevice() failed\n"
+ "112"
+ "AppleT8152USBXHCI"
+ "AppleT8152USBXHCI.cpp"
+ "AppleT8152USBXHCICommandRing"
+ "site.AppleT8152USBXHCI"
+ "site.AppleT8152USBXHCICommandRing"
```
