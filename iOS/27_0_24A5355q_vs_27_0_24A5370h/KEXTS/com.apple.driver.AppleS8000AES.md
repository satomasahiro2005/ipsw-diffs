## com.apple.driver.AppleS8000AES

> `com.apple.driver.AppleS8000AES`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x200` | **`+0x200`** |
| `__TEXT_EXEC.__text` | `0x4090` | `0x412c` | **`+0x9c`** |
| `__TEXT.__cstring` | `0x1393` | `0x13a4` | **`+0x11`** |

### Other Changes

```diff

-138.0.0.0.0
+139.0.0.0.0
Functions:
~ __ZN24AppleS8000AESAccelerator10_enableAESEb : 704 -> 784
~ sub_fffffff00943c610 -> __ZN24AppleS8000AESAccelerator16_distribute_dkeyEv : 132 -> 164
~ __ZN24AppleS8000AESAccelerator12_completeAESEv : 888 -> 920
~ __ZN24AppleS8000AESAccelerator13_push_commandEPvj : 252 -> 256
~ sub_fffffff00943df28 -> __ZN24AppleS8000AESAccelerator16_distribute_dkeyEv.cold.1 : 44 -> 52
CStrings:
+ "\"AppleS8000AESAccelerator::_distribute_dkey: DKey distribution failure (aes-version=%u)\" @%s:%d"
- "\"AppleS8000AESAccelerator::_distribute_dkey: DKey distribution failure\" @%s:%d"
```
