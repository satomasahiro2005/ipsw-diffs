## newfs_apfs

> `/System/Library/Filesystems/apfs.fs/newfs_apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x51390` | `0x516fc` | **`+0x36c`** |
| `__TEXT.__cstring` | `0xf7d9` | `0xf937` | **`+0x15e`** |

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

-  CStrings:  1308
+  CStrings:  1314
Functions:
~ sub_10000482c : 160 -> 168
~ sub_10000ddfc -> sub_10000de04 : 316 -> 332
~ sub_10000df38 -> sub_10000df50 : 128 -> 164
~ sub_10001167c -> sub_1000116b8 : 572 -> 576
~ sub_100014d30 -> sub_100014d70 : 5164 -> 5204
~ sub_100027ef8 -> sub_100027f60 : 1208 -> 1364
~ sub_100035aec -> sub_100035bf0 : 340 -> 304
~ sub_100038058 -> sub_100038138 : 1572 -> 1592
~ sub_10003a7d0 -> sub_10003a8c4 : 2548 -> 2556
~ sub_10003b2c4 -> sub_10003b3c0 : 988 -> 1204
~ sub_10003f20c -> sub_10003f3e0 : 128 -> 136
~ sub_10003fa4c -> sub_10003fc28 : 5264 -> 5380
~ sub_1000444a8 -> sub_1000446f8 : 292 -> 308
~ sub_100049a78 -> sub_100049cd8 : 3380 -> 3604
~ sub_10004fcd0 -> sub_100050010 : 168 -> 176
~ sub_10004ff90 -> sub_1000502d8 : 616 -> 628
~ sub_10005025c -> sub_1000505b0 : 244 -> 252
~ sub_100050b04 -> sub_100050e60 : 408 -> 424
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
- "%s:%d: %s failed to create bitmap object %lld: %d\n"
- "%s:%d: %s failed to free internal pool block %lld: %d\n"
- "3283"
```
