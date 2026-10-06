## com.apple.kext.AppleMatch

> `com.apple.kext.AppleMatch`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x24dc` | `0x25b0` | **`+0xd4`** |
| `__TEXT_EXEC.__auth_stubs` | `0xc0` | `0xb0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x60` | `0x58` | **`-0x8`** |

### Other Changes

```diff

-49.0.0.0.0
+50.0.1.0.0
Functions:
~ sub_fffffff0091ef4fc -> sub_fffffff0091f677c : 4748 -> 4680
~ sub_fffffff0091f09b0 -> sub_fffffff0091f7bec : 212 -> 308
~ sub_fffffff0091f0a84 -> sub_fffffff0091f7d20 : 272 -> 456
```
