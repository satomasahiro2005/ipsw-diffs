## matd

> `/System/Library/PrivateFrameworks/WelcomeKit.framework/matd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ad8` | `0x2b50` | **`+0x78`** |
| `__TEXT.__objc_methname` | `0xa7f` | `0xae5` | **`+0x66`** |
| `__TEXT.__cstring` | `0x5fb` | `0x647` | **`+0x4c`** |
| `__TEXT.__objc_methtype` | `0x3fd` | `0x42c` | **`+0x2f`** |
| `__DATA_CONST.__cfstring` | `0x2a0` | `0x2c0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xb20` | `0xb40` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x42c` | `0x444` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x400` | `0x410` | **`+0x10`** |
| `__DATA.__objc_const` | `0x4b0` | `0x4b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x160` | `0x168` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`

### Other Changes

```diff

-1439.0.0.0.0
+1441.40.1.0.0

-  Functions: 64
+  Functions: 65

-  CStrings:  234
+  CStrings:  239
Functions:
~ sub_100003514 : 92 -> 120
+ sub_10000358c
CStrings:
+ "%@ will update item count. completed_item_count=%lld, total_item_count=%lld"
+ "daemon:didUpdateCompletedItemCount:totalItemCount:"
+ "server:didUpdateCompletedItemCount:totalItemCount:"
+ "v40@0:8@\"MKAPIServer\"16Q24Q32"
+ "v40@0:8@16Q24Q32"
```
