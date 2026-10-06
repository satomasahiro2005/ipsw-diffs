## apfs_checkseal

> `/System/Library/Filesystems/apfs.fs/apfs_checkseal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f80c` | `0x4fb80` | **`+0x374`** |
| `__TEXT.__cstring` | `0xfefd` | `0x10016` | **`+0x119`** |

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

-  CStrings:  1285
+  CStrings:  1290
Functions:
~ sub_1000168b8 : 1208 -> 1364
~ sub_10001d12c -> sub_10001d1c8 : 516 -> 520
~ sub_10001e190 -> sub_10001e230 : 408 -> 424
~ sub_100021970 -> sub_100021a20 : 5164 -> 5204
~ sub_100029984 -> sub_100029a5c : 316 -> 332
~ sub_100029ac0 -> sub_100029ba8 : 128 -> 164
~ sub_1000331a4 -> sub_1000332b0 : 332 -> 300
~ sub_100034bf4 -> sub_100034ce0 : 1572 -> 1592
~ sub_10003736c -> sub_10003746c : 2548 -> 2556
~ sub_100037e60 -> sub_100037f68 : 988 -> 1204
~ sub_10003bdf8 -> sub_10003bfd8 : 128 -> 136
~ sub_10003c748 -> sub_10003c930 : 5264 -> 5380
~ sub_1000402fc -> sub_100040558 : 292 -> 308
~ sub_1000458cc -> sub_100045b38 : 3380 -> 3604
~ sub_10004f4b4 -> sub_10004f800 : 168 -> 176
~ sub_10004f6ac -> sub_10004fa00 : 616 -> 628
~ sub_10004f978 -> sub_10004fcd8 : 244 -> 252
~ sub_10004fa6c -> sub_10004fdd4 : 136 -> 148
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
