## com.apple.iokit.IOMobileGraphicsFamily-DCP

> `com.apple.iokit.IOMobileGraphicsFamily-DCP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x6082` | `0x63cb` | **`+0x349`** |
| `__TEXT_EXEC.__text` | `0x2ae10` | `0x2af30` | **`+0x120`** |

### Other Changes

```diff

-700.50.104.1.0
+700.50.108.0.0

-  CStrings:  500
+  CStrings:  512
Functions:
~ sub_fffffff00a218f58 -> sub_fffffff00a19f018 : 704 -> 896
~ sub_fffffff00a2193d4 -> sub_fffffff00a19f554 : 524 -> 564
~ sub_fffffff00a2302a4 -> sub_fffffff00a1b644c : 140 -> 152
~ sub_fffffff00a231e10 -> sub_fffffff00a1b7fc4 : 304 -> 348
CStrings:
+ "AppleDCPLinkService: endpoint power-down entered with driver_power set, this wait cannot complete: this=%p power2=%d"
+ "AppleDCPLinkService: hibernate-resume re-start of link service failed"
+ "map_block_buf: pbt=%u allocateBufferWithOptions failed user_size=%u\n"
+ "map_block_buf: pbt=%u block_size=%zu too small for addr_offs=%u size_offs=%u"
+ "map_block_buf: pbt=%u buf->map failed, buf_flags=0x%x\n"
+ "map_block_buf: pbt=%u buf->prepare failed ret=0x%x, buf_flags=0x%x\n"
+ "map_block_buf: pbt=%u set_kernel_power_assert failed ret=0x%x\n"
+ "map_block_buf: pbt=%u temp_buf->map failed\n"
+ "map_block_buf: pbt=%u temp_buf->prepare failed ret=0x%x"
+ "map_block_buf: pbt=%u withAddressRange failed user_addr=0x%llx, user_size=%u, buf_flags=0x%x\n"
+ "set_block: map_block_buf failed, pbt=%u, block=%p, block_size=%zu, ret=0x%x\n"
+ "set_block: pbt=%u rejected, DCP reset in progress\n"
```
