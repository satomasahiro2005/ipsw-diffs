## newsd

> `/System/Library/PrivateFrameworks/NewsDaemon.framework/newsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x54860` | `0x545e0` | **`-0x280`** |
| `__TEXT.__objc_methname` | `0x5f95` | `0x5fd5` | **`+0x40`** |
| `__DATA.__objc_const` | `0x3c90` | `0x3ca8` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x1bf7` | `0x1c07` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x15f8` | `0x1600` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1a40` | `0x1a48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5960.0.0.0.0
+5962.0.0.0.0

-  Functions: 1483
+  Functions: 1482

-  CStrings:  1532
+  CStrings:  1535
Symbols:
+ _$s8NewsCore16FeedItemDatabaseC013feedIDsForTagG0ySaySSGAEKF
- _$s8NewsCore16FeedItemDatabaseC20feedContextForTagIDsySDyS2S_So06FCFeedG0CtGSaySSGKF
Functions:
~ sub_100050764 : 7664 -> 7292
- sub_1000534d0
CStrings:
+ "@\"NSDictionary\"16@0:8"
+ "T@\"NSDictionary\",R,N"
+ "dislikeDatesByArticleID"
```
