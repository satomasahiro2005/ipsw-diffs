## com.apple.driver.AppleDisplayCrossbar

> `com.apple.driver.AppleDisplayCrossbar`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x630` | **`+0x630`** |
| `__TEXT_EXEC.__text` | `0x3f3c4` | `0x3f208` | **`-0x1bc`** |
| `__TEXT.__cstring` | `0x4d62` | `0x4cf4` | **`-0x6e`** |
| `__TEXT.__os_log` | `0x6c22` | `0x6bc7` | **`-0x5b`** |
| `__DATA_CONST.__const` | `0x112c0` | `0x11308` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0x310` | `0x318` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x100` | `0xf8` | **`-0x8`** |

### Other Changes

```diff

-414.0.0.0.2
-  Functions: 2200
+417.0.1.0.0
+  Functions: 2204

-  CStrings:  820
+  CStrings:  816
CStrings:
+ "12222222222222222222222"
+ "IOAV[%d] %s<0x%llx>::%s: dfp(0x%llx): Domain%u, atc%u,%u (atc%u-%s): Bogus tile assignment detected (%d/%d/%d), revisit DFP display pipe assignment\n"
+ "IOAV[%d] %s<0x%llx>::%s: dfp(0x%llx): reallocate for newly available ext pipes\n"
+ "dfp(0x%llx): Domain%u, atc%u,%u (atc%u-%s): Bogus tile assignment detected (%d/%d/%d), revisit DFP display pipe assignment\n"
+ "dfp(0x%llx): reallocate for newly available ext pipes\n"
+ "role"
- "122222222222222222222"
- "IOAV[%d] %s<0x%llx>::%s: dfp(0x%llx): Domain%u, atc%u,%u (atc%u-%s): Bogus tile assignment detected, revisit DFP display pipe assignment\n"
- "IOAV[%d] %s<0x%llx>::%s: dfp(0x%llx): revisit DFP display pipe assignment for Dual cable display\n"
- "IOAV[%d] %s<0x%llx>::%s: dfp(0x%llx): revisit DFP display pipe assignment for HDMI\n"
- "allows-dual-pipe"
- "dfp(0x%llx): Domain%u, atc%u,%u (atc%u-%s): Bogus tile assignment detected, revisit DFP display pipe assignment\n"
- "dfp(0x%llx): revisit DFP display pipe assignment for Dual cable display\n"
- "dfp(0x%llx): revisit DFP display pipe assignment for HDMI\n"
- "dpxbar-dual-pipe"
- "supportsDualPipe"
```
