## Pasteboard

> `/System/Library/PrivateFrameworks/Pasteboard.framework/Pasteboard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x2d0` | `0x140` | **`-0x190`** |
| `__DATA_DIRTY.__objc_data` | `0x5a0` | `0x730` | **`+0x190`** |

### Other Changes

```diff

-9127.1.3.0.0
+9127.1.12.0.0
Symbols:
+ -[PBItemCollection authoredBootSession]
+ -[PBItemCollection itemQueue_authoredBootSession]
+ -[PBItemCollection setAuthoredBootSession:]
+ -[PBItemCollection setItemQueue_authoredBootSession:]
+ _OBJC_IVAR_$_PBItemCollection._itemQueue_authoredBootSession
+ ___39-[PBItemCollection authoredBootSession]_block_invoke
+ ___43-[PBItemCollection setAuthoredBootSession:]_block_invoke
- -[PBItemCollection itemQueue_saveBootSession]
- -[PBItemCollection saveBootSession]
- -[PBItemCollection setItemQueue_saveBootSession:]
- -[PBItemCollection setSaveBootSession:]
- _OBJC_IVAR_$_PBItemCollection._itemQueue_saveBootSession
- ___35-[PBItemCollection saveBootSession]_block_invoke
- ___39-[PBItemCollection setSaveBootSession:]_block_invoke
```
