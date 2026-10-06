## com.apple.driver.AppleDisplayCrossbar

> `com.apple.driver.AppleDisplayCrossbar`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x3d704` | `0x414ac` | **`+0x3da8`** |
| `__DATA_CONST.__const` | `0x10bc8` | `0x11838` | **`+0xc70`** |
| `__TEXT.__cstring` | `0x4de0` | `0x515c` | **`+0x37c`** |
| `__TEXT.__os_log` | `0x689b` | `0x69e8` | **`+0x14d`** |
| `__TEXT.__const` | `0x1a4` | `0x2b0` | **`+0x10c`** |
| `__DATA_CONST.__kalloc_type` | `0x7c0` | `0x800` | **`+0x40`** |
| `__DATA.__common` | `0x4e8` | `0x510` | **`+0x28`** |
| `__TEXT_EXEC.__auth_stubs` | `0x630` | `0x640` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x318` | `0x320` | **`+0x8`** |
| `__DATA_CONST.__mod_init_func` | `0xf0` | `0xf8` | **`+0x8`** |
| `__DATA_CONST.__mod_term_func` | `0xf0` | `0xf8` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 2160
+  Functions: 2263

-  CStrings:  821
+  CStrings:  855
CStrings:
+ "\"%s::%s(): \" \"RCAL impedance failed\" @%s:%d"
+ "\"%s::%s(): \" \"no ACK to POWER DOWN command after 16us\" @%s:%d"
+ "\"%s::%s(): \" \"no ACK to POWER UP command after 16us\" @%s:%d"
+ "\"%s::%s(): \" \"pll failed to lock\" @%s:%d"
+ "%s::%s(): RCAL impedance failed"
+ "%s::%s(): no ACK to POWER DOWN command after 16us"
+ "%s::%s(): no ACK to POWER UP command after 16us"
+ "%s::%s(): pll failed to lock"
+ "AppleT8152DPTXPort"
+ "AppleT8152DPTXPort.cpp"
+ "IOAV[%d] %s<0x%llx>::%s: %s::%s(): RCAL impedance failed"
+ "IOAV[%d] %s<0x%llx>::%s: %s::%s(): no ACK to POWER DOWN command after 16us"
+ "IOAV[%d] %s<0x%llx>::%s: %s::%s(): no ACK to POWER UP command after 16us"
+ "IOAV[%d] %s<0x%llx>::%s: %s::%s(): pll failed to lock"
+ "IOAV[%d] %s<0x%llx>::%s: requested zero laneCount with wake=%d, exiting.."
+ "asdc-aux-shm-tunables"
+ "asdc-cmn-tunables"
+ "asdc-dppll-core-tunables"
+ "asdc-dppll-top-tunables"
+ "asdc-txd-cfg-0-tunables"
+ "asdc-txd-cfg-1-tunables"
+ "asdc-txd-cfg-2-tunables"
+ "asdc-txd-cfg-3-tunables"
+ "asdc-txspl-cfg-0-tunables"
+ "asdc-txspl-cfg-1-tunables"
+ "asdc-txspl-cfg-2-tunables"
+ "asdc-txspl-cfg-3-tunables"
+ "lane-shm-regs-0-tunables"
+ "lane-shm-regs-1-tunables"
+ "lane-shm-regs-2-tunables"
+ "lane-shm-regs-3-tunables"
+ "phySetActiveLaneCount"
+ "requested zero laneCount with wake=%d, exiting.."
+ "site.AppleT8152DPTXPort"
```
