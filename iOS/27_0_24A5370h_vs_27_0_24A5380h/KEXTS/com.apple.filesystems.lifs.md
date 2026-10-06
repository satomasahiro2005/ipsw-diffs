## com.apple.filesystems.lifs

> `com.apple.filesystems.lifs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x20214` | `0x20244` | **`+0x30`** |

### Other Changes

```diff

-974.0.1.0.2
+974.0.7.0.0
Functions:
~ _lifs_vnop_readdir : 1740 -> 1764
~ _lifs_vnop_getattrlistbulk : 1292 -> 1300
~ sub_fffffff00aacddcc -> sub_fffffff00aac910c : 788 -> 792
~ sub_fffffff00aace1e0 -> sub_fffffff00aac9524 : 740 -> 752
```
