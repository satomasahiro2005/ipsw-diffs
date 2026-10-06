## apfs_iosd

> `/System/Library/Filesystems/apfs.fs/apfs_iosd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x339a4` | `0x33cf0` | **`+0x34c`** |
| `__TEXT.__cstring` | `0x6684` | `0x679d` | **`+0x119`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3283.0.0.0.0
+3283.0.9.502.1

-  CStrings:  746
+  CStrings:  751
Functions:
~ sub_100006124 : 324 -> 332
~ sub_1000159f8 -> sub_100015a00 : 1208 -> 1364
~ sub_100017304 -> sub_1000173a8 : 508 -> 520
~ sub_100017f34 -> sub_100017fe4 : 240 -> 256
~ sub_10001b8f8 -> sub_10001b9b8 : 316 -> 332
~ sub_10001ba34 -> sub_10001bb04 : 128 -> 164
~ sub_10001d118 -> sub_10001d20c : 1728 -> 1756
~ sub_10001f944 -> sub_10001fa54 : 2548 -> 2556
~ sub_100020438 -> sub_100020550 : 988 -> 1204
~ sub_100023828 -> sub_100023a18 : 128 -> 136
~ sub_1000247dc -> sub_1000249d4 : 5264 -> 5380
~ sub_100027c54 -> sub_100027ec0 : 292 -> 308
~ sub_10002c744 -> sub_10002c9c0 : 3380 -> 3604
~ sub_1000327c0 -> sub_100032b1c : 296 -> 280
CStrings:
+ "%s:%d: %s oid 0x%llx flags 0x%llx type 0x%x/0x%x error freeing new location %d\n"
+ "%s:%d: %s op %d error getting cab %d @ %lld: %d\n"
+ "%s:%d: %s op %d error getting cib %d @ %lld: %d\n"
+ "%s:%d: %s op %d error getting cib %d bitmap %d @ %lld: %d\n"
+ "%s:%d: %s op %d failed to allocate block from internal pool: %d\n"
+ "%s:%d: %s op %d failed to create bitmap object %lld: %d\n"
+ "%s:%d: %s op %d failed to free internal pool block %lld: %d\n"
+ "nx-tree-node-compact-lock"
- "%s:%d: %s failed to allocate block from internal pool: %d\n"
- "%s:%d: %s failed to create bitmap object %lld: %d\n"
- "%s:%d: %s failed to free internal pool block %lld: %d\n"
```
