## com.apple.driver.DiskImages.KernelBacked

> `com.apple.driver.DiskImages.KernelBacked`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x2c0` | `0x2d0` | **`+0x10`** |
| `__TEXT_EXEC.__text` | `0x433c` | `0x4348` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x160` | `0x168` | **`+0x8`** |

### Other Changes

```diff

-696.0.0.0.0
+698.0.0.0.0
Functions:
~ __ZN21IOHDIXHDDriveInKernel14processCommandER13IOHDIXCommandR12BounceBuffer : 1240 -> 1252
```
