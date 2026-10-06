## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/AppleMCTF`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x87bb0` | `0x87c38` | **`+0x88`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Functions:
~ sub_e314 : 6988 -> 7004
~ sub_3544c -> sub_3545c : 500 -> 536
~ sub_3bcb0 -> sub_3bce4 : 7396 -> 7384
~ sub_53a74 -> sub_53a9c : 428 -> 404
~ sub_696e8 -> sub_696f8 : 244 -> 248
~ sub_6a054 -> sub_6a068 : 256 -> 260
~ sub_6a264 -> sub_6a27c : 256 -> 260
~ sub_76c60 -> sub_76c7c : 1204 -> 1212
~ sub_8423c -> sub_84260 : 204 -> 208
~ sub_84308 -> sub_84330 : 204 -> 208
~ sub_84d70 -> sub_84d9c : 1468 -> 1472
~ sub_8532c -> sub_8535c : 4068 -> 4108
~ sub_87244 -> sub_8729c : 1880 -> 1920
~ sub_8799c -> sub_87a1c : 304 -> 312
CStrings:
+ "21:36:11"
- "22:23:40"
```
