## AccountsDaemon

> `/System/Library/PrivateFrameworks/AccountsDaemon.framework/AccountsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x904a` | `0x90ca` | **`+0x80`** |
| `__TEXT.__text` | `0x83788` | `0x83730` | **`-0x58`** |
| `__DATA_CONST.__const` | `0x1778` | `0x1750` | **`-0x28`** |
| `__DATA_CONST.__got` | `0xd90` | `0xd80` | **`-0x10`** |

### Other Changes

```diff

-1119.0.0.0.0
+1122.0.0.0.0

-  Functions: 2424
-  Symbols:   3215
-  CStrings:  1186
+  Functions: 2423
+  Symbols:   3212
+  CStrings:  1187
Symbols:
+ _NSManagedObjectContextDidSaveObjectIDsNotification
- _NSDeletedObjectsKey
- _NSInsertedObjectsKey
- _NSManagedObjectContextDidSaveNotification
- ___block_descriptor_49_e8_32s40s_e5_v8?0ls32l8s40l8
CStrings:
+ "%{public}@ %{public}@ account: %{private}@ [%{private}@], changes: %{private}@"
+ "Posting ACDAccountStoreDidChangeNotification: %{public}@ %{public}@ account: %{private}@ [%{private}@], notifying:%{bool}d"
- "%{public}@ %{public}@ account: %{private}@, changes: %{private}@"
```
