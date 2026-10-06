## com.apple.driver.DiskImages

> `com.apple.driver.DiskImages`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x470` | **`+0x470`** |
| `__TEXT_EXEC.__text` | `0x937c` | `0x93f0` | **`+0x74`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-691.0.0.0.0
+696.0.0.0.0
Functions:
~ sub_fffffff009ffcd24 -> sub_fffffff00a07e144 : 272 -> 304
~ sub_fffffff00a003b2c -> sub_fffffff00a084f6c : 3356 -> 3456
~ sub_fffffff00a004c00 -> sub_fffffff00a0860a4 : 292 -> 272
~ sub_fffffff00a004d74 -> sub_fffffff00a086204 : 136 -> 140
CStrings:
+ "696"
- "691"
```
