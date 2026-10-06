## remotemanagementd

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/remotemanagementd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8a298` | `0x8b2b8` | **`+0x1020`** |
| `__DATA.__objc_const` | `0x8598` | `0x86a8` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0xc217` | `0xc31b` | **`+0x104`** |
| `__DATA_CONST.__got` | `0x930` | `0x9f8` | **`+0xc8`** |
| `__TEXT.__ustring` | `0x246` | `0x2ec` | **`+0xa6`** |
| `__DATA_CONST.__cfstring` | `0x33e0` | `0x3460` | **`+0x80`** |
| `__TEXT.__cstring` | `0x2fac` | `0x3019` | **`+0x6d`** |
| `__DATA.__objc_data` | `0x1d60` | `0x1db0` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0xf0ac` | `0xf0f9` | **`+0x4d`** |
| `__TEXT.__objc_methlist` | `0x49e8` | `0x4a28` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0xc320` | `0xc360` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0xff8` | `0x1032` | **`+0x3a`** |
| `__DATA_CONST.__const` | `0x2740` | `0x2760` | **`+0x20`** |
| `__DATA.__bss` | `0x590` | `0x5a0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x3508` | `0x3518` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x2f0` | `0x2f8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2098` | `0x20a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-624.0.3.0.0
+624.0.8.0.0

-  Functions: 2553
+  Functions: 2566

-  CStrings:  3869
+  CStrings:  3880
CStrings:
+ "%@ has unpublished predicate status items, leaving state unchanged"
+ "%@ predicate references errored status items: %{public}@"
+ "Activation’s (%@:%@) predicate (%@) references status items in an error state: %@."
+ "Error.PredicateStatusItemsError"
+ "ErroredStatusItems"
+ "Failed to remove old directory: %{public}@"
+ "Ignoring migration: not system scoped"
+ "Ignoring migration: old database does not exist"
+ "New database exists, removing old directory"
+ "RMMigrationProtectedContainer"
+ "Starting migration from %{public}@ to %{public}@"
+ "createMissingStatusValueErrorWithKeyPath:"
+ "isEqualToArray:"
+ "migrationProtectedContainer"
+ "predicateStatusItemsError:forActivation:"
- "Not OK to migrate: new database exists"
- "Not OK to migrate: old database does not exist"
- "_directoryExistsAtURL:"
- "_okToMigrateFromURL:toURL:"
```
