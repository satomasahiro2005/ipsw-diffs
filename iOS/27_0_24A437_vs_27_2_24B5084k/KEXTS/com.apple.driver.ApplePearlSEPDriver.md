## com.apple.driver.ApplePearlSEPDriver

> `com.apple.driver.ApplePearlSEPDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x40b64` | `0x40e14` | **`+0x2b0`** |
| `__TEXT.__os_log` | `0x4e19` | `0x4e57` | **`+0x3e`** |
| `__TEXT.__cstring` | `0xb369` | `0xb357` | **`-0x12`** |
| `__TEXT_EXEC.__auth_stubs` | `0xba0` | `0xbb0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x5d0` | `0x5d8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x25a8` | `0x25b0` | **`+0x8`** |

### Other Changes

```diff

-980.0.26.0.0
-  Functions: 751
+980.40.11.0.0
+  Functions: 755

-  CStrings:  1743
+  CStrings:  1742
CStrings:
+ "%s: Unpacked raw frames ENABLED\n"
- "%s: Unpacked raw frames %s\n"
- "camPearlPackedRaw"
```
