## slurpAPFSMeta

> `/System/Library/Filesystems/apfs.fs/slurpAPFSMeta`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x378f0` | `0x37c14` | **`+0x324`** |
| `__TEXT.__cstring` | `0x8f26` | `0x903f` | **`+0x119`** |

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

-  CStrings:  769
+  CStrings:  774
Functions:
~ sub_100008f10 : 296 -> 280
~ sub_1000091c4 -> sub_1000091b4 : 572 -> 576
~ sub_100015aa0 -> sub_100015a94 : 1208 -> 1364
~ sub_100018da0 -> sub_100018e30 : 408 -> 424
~ sub_100019d44 -> sub_100019de4 : 5264 -> 5380
~ sub_10001edc0 -> sub_10001eed4 : 292 -> 308
~ sub_100023ab8 -> sub_100023bdc : 3380 -> 3604
~ sub_100026540 -> sub_100026744 : 176 -> 172
~ sub_10002b6a0 -> sub_10002b8a0 : 2548 -> 2556
~ sub_10002c194 -> sub_10002c39c : 988 -> 1204
~ sub_10002fa88 -> sub_10002fd68 : 128 -> 136
~ sub_100031cac -> sub_100031f94 : 316 -> 332
~ sub_100031de8 -> sub_1000320e0 : 128 -> 164
~ sub_100035338 -> sub_100035654 : 1884 -> 1892
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
