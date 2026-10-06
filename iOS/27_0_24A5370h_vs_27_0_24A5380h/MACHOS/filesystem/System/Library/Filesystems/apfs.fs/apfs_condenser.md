## apfs_condenser

> `/System/Library/Filesystems/apfs.fs/apfs_condenser`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c9d4` | `0x4cd30` | **`+0x35c`** |
| `__TEXT.__cstring` | `0xf5a5` | `0xf6c8` | **`+0x123`** |

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

-  CStrings:  1256
+  CStrings:  1261
Functions:
~ sub_10000f75c : 408 -> 424
~ sub_1000106c0 -> sub_1000106d0 : 316 -> 332
~ sub_1000107fc -> sub_10001081c : 128 -> 164
~ sub_100015cbc -> sub_100015d00 : 5164 -> 5204
~ sub_10002c0e8 -> sub_10002c154 : 1208 -> 1364
~ sub_100030398 -> sub_1000304a0 : 332 -> 300
~ sub_1000304e4 -> sub_1000305cc : 284 -> 276
~ sub_100035b9c -> sub_100035c7c : 1572 -> 1592
~ sub_100038314 -> sub_100038408 : 2548 -> 2556
~ sub_100038e08 -> sub_100038f04 : 988 -> 1204
~ sub_10003cda0 -> sub_10003cf74 : 128 -> 136
~ sub_10003d600 -> sub_10003d7dc : 5264 -> 5380
~ sub_100040e54 -> sub_1000410a4 : 292 -> 308
~ sub_1000466dc -> sub_10004693c : 3380 -> 3604
~ sub_10004c55c -> sub_10004c89c : 168 -> 176
~ sub_10004c754 -> sub_10004ca9c : 616 -> 628
~ sub_10004ca20 -> sub_10004cd74 : 244 -> 252
CStrings:
+ "%s:%d: %s oid 0x%llx flags 0x%llx type 0x%x/0x%x error freeing new location %d\n"
+ "%s:%d: %s op %d error getting cab %d @ %lld: %d\n"
+ "%s:%d: %s op %d error getting cib %d @ %lld: %d\n"
+ "%s:%d: %s op %d error getting cib %d bitmap %d @ %lld: %d\n"
+ "%s:%d: %s op %d failed to allocate block from internal pool: %d\n"
+ "%s:%d: %s op %d failed to create bitmap object %lld: %d\n"
+ "%s:%d: %s op %d failed to free internal pool block %lld: %d\n"
+ "3283.0.9.502.1"
+ "nx-tree-node-compact-lock"
- "%s:%d: %s failed to allocate block from internal pool: %d\n"
- "%s:%d: %s failed to create bitmap object %lld: %d\n"
- "%s:%d: %s failed to free internal pool block %lld: %d\n"
- "3283"
```
