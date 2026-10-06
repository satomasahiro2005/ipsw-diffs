## WebBookmarks

> `/System/Library/PrivateFrameworks/WebBookmarks.framework/WebBookmarks`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf1258` | `0xf171c` | **`+0x4c4`** |
| `__TEXT.__cstring` | `0x10160` | `0x10210` | **`+0xb0`** |
| `__TEXT.__gcc_except_tab` | `0xc370` | `0xc3e0` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x6500` | `0x6540` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x8b80` | `0x8bb0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x5980` | `0x59a0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x5130` | `0x5140` | **`+0x10`** |

### Other Changes

```diff

-625.1.29.10.29
+625.2.4.1.0

-  Functions: 4938
-  Symbols:   6597
-  CStrings:  2188
+  Functions: 4943
+  Symbols:   6604
+  CStrings:  2190
Symbols:
+ -[WBTabCollection localTabGroupWithUUID:]
+ -[WBTabGroupManager localTabGroupWithUUID:]
+ -[WBWindowState initWithUUID:localTabGroup:sceneID:]
+ -[WebBookmarkTabCollection _localTabGroupWithUUID:]
+ GCC_except_table136
+ GCC_except_table276
+ ___41-[WBTabCollection localTabGroupWithUUID:]_block_invoke
CStrings:
+ "Failed to check whether tab group %d is claimed by an open window"
+ "SELECT 1 FROM windows WHERE date_closed IS NULL AND (local_tab_group_id = %d OR private_tab_group_id = %d)"
```
