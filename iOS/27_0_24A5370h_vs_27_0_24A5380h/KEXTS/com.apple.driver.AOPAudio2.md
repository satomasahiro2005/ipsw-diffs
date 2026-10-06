## com.apple.driver.AOPAudio2

> `com.apple.driver.AOPAudio2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__kalloc_var` | `—` | `0x280` | **`+0x280`** |
| `__TEXT.__cstring` | `0xac1` | `0xaf9` | **`+0x38`** |
| `__TEXT_EXEC.__auth_stubs` | `0x1d0` | `0x1f0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xe8` | `0xf8` | **`+0x10`** |
| `__TEXT_EXEC.__text` | `0x2bd4` | `0x2bd8` | **`+0x4`** |

### Other Changes

```diff

-400.11.0.0.0
-  Functions: 118
+400.12.0.0.0
+  Functions: 120

-  CStrings:  53
+  CStrings:  55
CStrings:
+ "site.Packet.uint8_t"
+ "site.RegisterAccess::Packet.uint8_t"
```
