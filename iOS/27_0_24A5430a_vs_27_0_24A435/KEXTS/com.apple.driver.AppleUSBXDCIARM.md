## com.apple.driver.AppleUSBXDCIARM

> `com.apple.driver.AppleUSBXDCIARM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x3c23c` | `0x4c654` | **`+0x10418`** |
| `__TEXT.__os_log` | `0x7754` | `0x9bce` | **`+0x247a`** |
| `__DATA_CONST.__const` | `0x6da0` | `0x8180` | **`+0x13e0`** |
| `__TEXT.__cstring` | `0x43e2` | `0x4614` | **`+0x232`** |
| `__DATA_CONST.__kalloc_type` | `0x2c0` | `0x340` | **`+0x80`** |
| `__DATA.__common` | `0x1f0` | `0x240` | **`+0x50`** |
| `__DATA_CONST.__mod_init_func` | `0x58` | `0x68` | **`+0x10`** |
| `__DATA_CONST.__mod_term_func` | `0x58` | `0x68` | **`+0x10`** |

### Other Changes

```diff

-  Functions: 395
+  Functions: 465

-  CStrings:  245
+  CStrings:  257
CStrings:
+ "%s@%s: %s::%s: ATC_USB31DRD_CFG_BLK_ISOCTHROTTLE_CTL.ISOCTHROTTLE_RD_LIMIT = 0x%x\n"
+ "%s@%s: %s::%s: ATC_USB31DRD_CFG_BLK_ISOCTHROTTLE_CTL.ISOCTHROTTLE_WR_LIMIT = 0x%x\n"
+ "%s@%s: %s::%s: _atcusbClkCfgRegister 0x%x\n"
+ "%s@%s: %s::%s: _atcusbPipeClkCfgRegister 0x%x\n"
+ "%s@%s: %s::%s: timed out waiting for ISOCTHROTTLE_CTL.ISOCTHROTTLE_OUTSTANDING_RD = 0x%x\n"
+ "%s@%s: %s::%s: timed out waiting for ISOCTHROTTLE_CTL.ISOCTHROTTLE_OUTSTANDING_WR = 0x%x\n"
+ "AppleT8152USBXDCI"
+ "AppleT8152USBXDCI.cpp"
+ "AppleT8160USBXDCI"
+ "AppleT8160USBXDCI.cpp"
+ "site.AppleT8152USBXDCI"
+ "site.AppleT8160USBXDCI"
```
