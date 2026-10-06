## JournalShared

> `/System/Library/PrivateFrameworks/JournalShared.framework/JournalShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10021c` | `0x100ba4` | **`+0x988`** |
| `__TEXT.__cstring` | `0x1b82` | `0x1c32` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x248d` | `0x250d` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x1d27` | `0x1d47` | **`+0x20`** |
| `__DATA.__data` | `0x2680` | `0x2690` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x2658` | `0x2648` | **`-0x10`** |
| `__TEXT.__const` | `0xd830` | `0xd840` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2dbc` | `0x2dc8` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0xad8` | `0xae0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3ba8` | `0x3bb0` | **`+0x8`** |

### Other Changes

```diff

-94.0.0.0.0
+99.2.1.0.0

-  Functions: 5314
+  Functions: 5313

-  CStrings:  386
+  CStrings:  389
Symbols:
+ _ACDAccountStoreDidChangeNotification
- _CKAccountChangedNotification
CStrings:
+ "%K != nil AND (%K == YES OR %K == nil)"
+ "Account isn't authenticated"
+ "Remote %{public}s record is newer for id %{public}s; overwriting local asset fields."
+ "SUBQUERY(%K, $asset, ($asset.%K == NO OR $asset.%K == nil) AND ($asset.%K == NO OR $asset.%K == nil) AND ($asset.%K == NO OR $asset.%K == nil)).@count > 0"
- "ANY %K.%K != true"
```
