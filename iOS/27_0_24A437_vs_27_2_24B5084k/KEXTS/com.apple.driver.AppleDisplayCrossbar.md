## com.apple.driver.AppleDisplayCrossbar

> `com.apple.driver.AppleDisplayCrossbar`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x414ac` | `0x44890` | **`+0x33e4`** |
| `__DATA_CONST.__const` | `0x11838` | `0x124a0` | **`+0xc68`** |
| `__TEXT.__os_log` | `0x69e8` | `0x6c8a` | **`+0x2a2`** |
| `__TEXT.__cstring` | `0x515c` | `0x532f` | **`+0x1d3`** |
| `__DATA_CONST.__kalloc_type` | `0x800` | `0x840` | **`+0x40`** |
| `__DATA.__common` | `0x510` | `0x538` | **`+0x28`** |
| `__TEXT.__const` | `0x2b0` | `0x2d0` | **`+0x20`** |
| `__DATA_CONST.__mod_init_func` | `0xf8` | `0x100` | **`+0x8`** |
| `__DATA_CONST.__mod_term_func` | `0xf8` | `0x100` | **`+0x8`** |

### Other Changes

```diff

-417.0.4.0.0
-  Functions: 2263
+417.40.5.0.2
+  Functions: 2369

-  CStrings:  855
+  CStrings:  882
CStrings:
+ "1211111212221212111112222211111111111122222222222222222222222222222222222222222222222222222222222222222211111112121221"
+ "AppleT8132DPTXPort"
+ "AppleT8132DPTXPort.cpp"
+ "DCDADJ"
+ "DCDADJ = %x\n"
+ "DCOCFG"
+ "DCOCFG = %x RODCO_ENCAP_EFUSE = %x RODCO_BIASADJ_EFUSE = %x\n"
+ "DLFCFG"
+ "DLFCFG = %x\n"
+ "DTCCAL"
+ "DTCCAL = %x\n"
+ "DTCVREG"
+ "DTCVREG = %x\n"
+ "IOAV[%d] %s<0x%llx>::%s: DCDADJ = %x\n"
+ "IOAV[%d] %s<0x%llx>::%s: DCOCFG = %x RODCO_ENCAP_EFUSE = %x RODCO_BIASADJ_EFUSE = %x\n"
+ "IOAV[%d] %s<0x%llx>::%s: DLFCFG = %x\n"
+ "IOAV[%d] %s<0x%llx>::%s: DTCCAL = %x\n"
+ "IOAV[%d] %s<0x%llx>::%s: DTCVREG = %x\n"
+ "IOAV[%d] %s<0x%llx>::%s: RODCOROLEAKCOMP = %x\n"
+ "IOAV[%d] %s<0x%llx>::%s: ret=0x%08x"
+ "RODCOROLEAKCOMP"
+ "RODCOROLEAKCOMP = %x\n"
+ "didChangeLinkConfiguration"
+ "handleSetPllCoreCfgTunables"
+ "ret=0x%08x"
+ "site.AppleT8132DPTXPort"
+ "willChangeLinkConfiguration"
```
