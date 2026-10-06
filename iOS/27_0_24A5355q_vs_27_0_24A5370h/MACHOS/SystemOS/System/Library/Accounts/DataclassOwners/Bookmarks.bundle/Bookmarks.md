## Bookmarks

> `/System/Library/Accounts/DataclassOwners/Bookmarks.bundle/Bookmarks`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15cc` | `0x14a0` | **`-0x12c`** |
| `__TEXT.__oslogstring` | `0x12d` | `0xe3` | **`-0x4a`** |
| `__DATA_CONST.__const` | `0x150` | `0x198` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x300` | `0x2e0` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x640` | `0x620` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x190` | `0x180` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x7df` | `0x7e8` | **`+0x9`** |
| `__DATA.__objc_selrefs` | `0x288` | `0x280` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xa0` | `0x98` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x44` | `0x40` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.1.18.10.4
+7625.1.20.10.3

-  Symbols:   76
-  CStrings:  139
+  Symbols:   73
+  CStrings:  136
Symbols:
- _OBJC_CLASS_$_NSFileManager
- _WBSafariContainerPath
- _WBSafariDirectoryPath
CStrings:
+ "Failed to delete Safari's container data via sync agent %{public}@"
+ "deleteSafariContainerDataWithCompletionHandler:"
- "Failed to delete Safari's Library data %{public}@"
- "Failed to delete Safari's container data %{public}@"
- "Safari's Library data has been deleted"
- "defaultManager"
- "removeItemAtPath:error:"
```
