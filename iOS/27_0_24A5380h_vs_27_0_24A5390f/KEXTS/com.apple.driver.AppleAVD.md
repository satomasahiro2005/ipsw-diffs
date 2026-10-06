## com.apple.driver.AppleAVD

> `com.apple.driver.AppleAVD`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x5fd98` | `0x5ff10` | **`+0x178`** |
| `__TEXT.__os_log` | `0x1b0ed` | `0x1b1cb` | **`+0xde`** |
| `__TEXT.__cstring` | `0x7cfb` | `0x7d1b` | **`+0x20`** |
| `__TEXT_EXEC.__auth_stubs` | `0x700` | `0x6f0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x380` | `0x378` | **`-0x8`** |

### Other Changes

```diff

-989.1.0.0.0
-  Functions: 2163
+991.0.0.0.0
+  Functions: 2162

-  CStrings:  1770
+  CStrings:  1771
CStrings:
+ "AppleAVD: %s(): active_mcc_bit_vector_val is 0x%x\n"
+ "AppleAVD: ERROR: %s(): [Core %u] AVD Reset Function handle is NULL! Check the EDT\n"
+ "AppleAVD: INFO: %s(): Unexpected active-mcc-bit-vector value. Assume tunablesIdx is 1.\n"
+ "AppleAVD: INFO: %s(): [Core %u] AVD reset function returned %d\n"
+ "AppleAVD: INFO: %s(): [Core %u] resetPsdService(0, %u) returned %d\n"
- "AppleAVD: ERROR: %s(): AVD Reset Function handle is NULL! Check the EDT\n"
- "AppleAVD: INFO: %s(): AVD reset function returned %d\n"
- "AppleAVD: INFO: %s(): resetPsdService(0) returned %d\n"
- "setEventEntryFloat"
```
